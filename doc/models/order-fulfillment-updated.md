## Order Fulfillment Updated

### Structure

`OrderFulfillmentUpdated`

### Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `order_id` | `String` | Optional | The order's unique ID. |
| `version` | `Integer` | Optional | Version number which is incremented each time an update is committed to the order.<br>Orders that were not created through the API will not include a version and<br>thus cannot be updated.<br><br>[Read more about working with versions](https://developer.squareup.com/docs/docs/orders-api/manage-orders#update-orders) |
| `location_id` | `String` | Optional | The ID of the merchant location this order is associated with. |
| `state` | [`String (Order State)`](/doc/models/order-state.md) | Optional | The state of the order. |
| `created_at` | `String` | Optional | Timestamp for when the order was created in RFC 3339 format. |
| `updated_at` | `String` | Optional | Timestamp for when the order was last updated in RFC 3339 format. |
| `fulfillment_update` | [`Array<Order Fulfillment Updated Update Hash>`](/doc/models/order-fulfillment-updated-update.md) | Optional | The fulfillments that were updated with this version change. |

### Example (as JSON)

```json
{
  "order_id": null,
  "version": null,
  "location_id": null,
  "state": null,
  "created_at": null,
  "updated_at": null,
  "fulfillment_update": null
}
```

