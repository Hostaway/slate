## Reservation webhook log object

```json
{
    "id": 2,
    "accountId": 10450,
    "listingMapId": "40160",
    "reservationId": "1234",
    "reservationWebhookId": 89,
    "currentReservationStatus": "new",
    "previousReservationStatus": null,
    "url": "https://webhook.site/6e73ba6d-789e-ds4d64-9f68-a2e1134d1c6f3",
    "responseStatus": "200",
    "responseBody": "200"
}
```

Property | Required | Type | Description
-------- | -------- | ---- | ----------- 
`id` | yes | int | Identifier of reservationWebhookLog object
`accountId` | yes | int | Identifier of account object
`listingMapId` | yes | int | Identifier of listing object
`reservationId` | yes | int | Identifier of reservation object
`reservationWebhookId` | yes | int | Identifier of Reservation Webhook
`currentReservationStatus` | yes | string | Reservation status
`previousReservationStatus` | no | string | Previous reservation status
`url` | yes | string | URL
`responseStatus` | yes | int | Response status
`responseBody` | no | int | Response body