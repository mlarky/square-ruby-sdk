## Submit Evidence Response

Defines fields in a SubmitEvidence response.

### Structure

`SubmitEvidenceResponse`

### Fields

| Name | Type | Tags | Description |
|  --- | --- | --- | --- |
| `errors` | [`Array<Error Hash>`](/doc/models/error.md) | Optional | Information on errors encountered during the request. |
| `dispute` | [`Dispute Hash`](/doc/models/dispute.md) | Optional | Represents a dispute a cardholder initiated with their bank. |

### Example (as JSON)

```json
{
  "errors": null,
  "dispute": null
}
```

