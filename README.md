# DHL Tracking API & Webhooks

Use Track123 to track DHL shipments through one unified shipment tracking API.

Track123 lets your application register DHL tracking numbers, retrieve tracking updates, and receive delivery events through webhooks.

- DHL carrier code: `dhl`

- [Track DHL packages on Track123](https://www.track123.com/carriers/dhl)

- [DHL API integration page](https://www.track123.com/carriers/dhl/api)

- [Track123 API documentation](https://docs.track123.com)

> This repository explains how to track DHL shipments with Track123. It is not official DHL API documentation.

## DHL tracking API integration

When your application already knows that a shipment is handled by DHL, set `courierCode` to `dhl` when registering the tracking number.

Use [Carrier Detection](https://docs.track123.com/reference/detection-courier) when your application does not have an approved carrier code.

Use your own tracking number in the registration request. Track123 does not provide public test tracking numbers in this repository.

## Integration guides

- [DHL tracking webhook](webhook.md)
- [DHL tracking statuses](tracking-status.md)
- [DHL API errors and rate limits](errors-and-rate-limits.md)

## DHL tracking API resources

- [Register package trackings](https://docs.track123.com/reference/register-package-trackings)
- [Get package trackings](https://docs.track123.com/reference/get-package-trackings)
- [Carrier detection](https://docs.track123.com/reference/detection-courier)

## Track DHL packages and view FAQs

For shipment lookup, carrier contact information, and customer-facing FAQs, visit [DHL tracking on Track123](https://www.track123.com/carriers/dhl).

## More Track123 resources

- [All supported carriers](https://www.track123.com/carriers)
- [Track123 developer documentation](https://docs.track123.com)

Carrier names and websites are used only to identify compatible carriers. Track123 is not affiliated with or endorsed by DHL unless explicitly stated.
