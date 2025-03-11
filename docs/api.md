# API Reference

## Get Trip Details

### Endpoint

`GET /api/trips/{tripId}`

### Request

* `tripId`: The ID of the trip.

### Response

```json
{
  "tripId": 123,
  "destination": "Paris",
  "startDate": "2024-07-01",
  "endDate": "2024-07-07"
}