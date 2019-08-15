## Card

Represents the payment details of a card to be used for payments. These
details are determined by the `card_nonce` generated by `SqPaymentForm`.

### Structure

`Card`

### Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `id` | `String` | Optional | Unique ID for this card. Generated by Square. |
| `card_brand` | [`String (Card Brand)`](/doc/models/card-brand.md) | Optional | Indicates a card's brand, such as `VISA` or `MASTERCARD`. |
| `last_4` | `String` | Optional | The last 4 digits of the card number. |
| `exp_month` | `Long` | Optional | The expiration month of the associated card as an integer between 1 and 12. |
| `exp_year` | `Long` | Optional | The four-digit year of the card's expiration date. |
| `cardholder_name` | `String` | Optional | The name of the cardholder. |
| `billing_address` | [`Address Hash`](/doc/models/address.md) | Optional | Represents a physical address. |
| `fingerprint` | `String` | Optional | A unique, Square-assigned ID that identifies the card across multiple<br>locations and applications for a single Square account. |

### Example (as JSON)

```json
{
  "id": null,
  "card_brand": null,
  "last_4": null,
  "exp_month": null,
  "exp_year": null,
  "cardholder_name": null,
  "billing_address": null,
  "fingerprint": null
}
```
