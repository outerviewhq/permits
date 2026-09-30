# Data dictionary

Public permit records use only the following fields:

| Field | Type | Nullable | Description |
|---|---|---:|---|
| date | date or datetime | yes | Reported permit date |
| year | integer | yes | Calendar year derived from the permit date |
| description | string | yes | Public project or work description |
| metadescription | string | yes | Human-readable summary of the permit |
| address | string | yes | Permit location |
| geometry | geometry | yes | Permit location geometry when available |

Country publications may have different coverage, but they must not expose
additional public record fields without updating this contract first.
