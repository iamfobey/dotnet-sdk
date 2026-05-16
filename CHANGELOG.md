# Changelog

## [0.1.0] - 2026-05-11

### Added
- Initial release of `Stendly` NuGet package
- `StendlyClient` implementing `IStendlyClient` with configurable `HttpClient`
- Payment Intents: `CreateAsync`, `RetrieveAsync`
- Terminals: `CreateAsync`, `ListAsync`
- Webhooks: `UpdateAsync`, `ConstructEvent`
- Merchant: `GetProfileAsync`, `GetStatsAsync`
- Typed exceptions: `StendlyException`, `StendlyAuthenticationException`, `StendlyValidationException`, `StendlyRateLimitException`, `StendlyApiConnectionException`, `StendlySignatureVerificationException`
- Data models: `PaymentIntent`, `Terminal`, `MerchantProfile`, `MerchantStats`, `DailyStats`, `WebhookEvent`, `WebhookData`
- Automatic API key prefix validation (`st_live_`)
- Environment auto-detection from API key
- XML documentation file generation