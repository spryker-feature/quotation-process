# Spryker Feature: Quotation Process

Request for Quote is an Yves functionality that allows an Agent to check quotes, have a list of them, create notification after a Request for Quote was created. In Request for Quote, Agent can change prices, add discount for a specific products or for the whole RfQ.

[Learn more](https://docs.spryker.com/docs/scos/user/features/202108.0/quotation-process-feature-overview.html)

## Installation

```
composer require spryker-feature/quotation-process
```

## Recommended feature dependencies
- [spryker-feature/agent-assist](https://github.com/spryker-feature/agent-assist)
- [spryker-feature/cart](https://github.com/spryker-feature/cart)
- [spryker-feature/company-account](https://github.com/spryker-feature/company-account)
- [spryker-feature/customer-account-management](https://github.com/spryker-feature/customer-account-management)
- [spryker-feature/prices](https://github.com/spryker-feature/prices)
- [spryker-feature/spryker-core](https://github.com/spryker-feature/spryker-core)

If you don't include the feature dependencies, make sure you use the respective modules instead.

## Optional modules
- [Shop.QuoteRequestAgentPageExtension ^1.0.0](https://github.com/spryker-shop/quote-request-agent-page-extension) (Extension)
- [QuoteRequestAgentsRestApi ^0.3.0](https://github.com/spryker/quote-request-agents-rest-api) (Legacy Glue)
- [QuoteRequestExtension ^1.2.0](https://github.com/spryker/quote-request-extension) (Extension)
- [Shop.QuoteRequestPageExtension ^1.0.0](https://github.com/spryker-shop/quote-request-page-extension) (Extension)
- [QuoteRequestsRestApi ^0.1.0](https://github.com/spryker/quote-requests-rest-api) (Legacy Glue)
- [QuoteRequestsRestApiExtension ^1.0.0](https://github.com/spryker/quote-requests-rest-api-extension) (Extension)
- [SalesQuoteRequestConnector ^1.0.0](https://github.com/spryker/sales-quote-request-connector) (Connector)
