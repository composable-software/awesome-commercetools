<!--lint disable awesome-list-item-->
<div align="center">
  <p align="center">
    <img alt="commercetools" src="https://avatars.githubusercontent.com/u/1084585?s=150&v=4" width="150" />
  </p>
<h1>Awesome commercetools</h1>
<p>A curated list of integrations, SDKs, and developer tools for commercetools, a composable commerce platform.</p>

<a href="#integrations">Integrations</a>
&nbsp;&nbsp;&nbsp;
<a href="CONTRIBUTING.md">Contribution guide</a>
&nbsp;&nbsp;&nbsp;
<a href="https://docs.commercetools.com/">Official documentation</a>

  <a href="https://awesome.re">
    <img src="https://awesome.re/badge.svg" alt="Awesome">
  </a>
</div>

For hosted integrations, consult the official [Connect marketplace directory](https://docs.commercetools.com/merchant-center/connect).

## Integrations

### Payments

- [Braintree](https://github.com/mediaopt/braintree-commercetools-connector) - Connect integration for Braintree payments.
- [Adyen](https://github.com/Adyen/adyen-commercetools) - Integrates Adyen Web Components with commercetools payments and notifications.
- [PayPal](https://github.com/mediaopt/paypal-commercetools-connector) - Connect integration for PayPal payments, with frontend components and payment notifications.
- [Ecommpay](https://github.com/ITECOMMPAY/ecommpay-commercetools-integration) - Integrates Ecommpay's hosted payment page and payment notifications.
- [Cybersource](https://github.com/CyberSource/cybersource-plugins-commercetools) - Payment integration using commercetools API extensions and Cybersource services.
- [Worldpay](https://github.com/Worldpay/Worldpay-CommerceTools-CG) - Integrates the Worldpay Worldwide Payment Gateway (WPG).
- [Mollie](https://github.com/mollie/commercetools-connector) - Connect integration for Mollie hosted checkout and payment notifications; replaces the deprecated `mollie/commercetools` repository.
- [Stripe for Checkout](https://github.com/stripe/stripe-commercetools-checkout-app) - Stripe Payment Element integration for commercetools Checkout.
- [Stripe for Composable Commerce](https://github.com/stripe/stripe-commercetools-connect-app) - Stripe payment integration for custom checkout experiences, deployed through Connect.
- [Briqpay](https://github.com/Briqpay-Extensions/connect-payment-integration-briqpay) - Connect integration with an embedded payment widget and webhook-driven payment updates.

### Authentication

- [Auth0](https://github.com/gradientedge/commercetools-auth0) - Customer account synchronization between Auth0 and commercetools. Last repository push: July 2023; review compatibility before adopting.

### Promotions and loyalty

- [Talon.One](https://github.com/talon-one/commercetools-talonone-accelerator) - AWS/GCP accelerator connecting Talon.One promotions with commercetools.
- [Voucherify](https://github.com/voucherifyio/commerce-tools-integration) - Integrates coupons, gift cards, referral campaigns, and loyalty programs through API extensions.
- [Voucherify Gift Cards for Checkout](https://github.com/commercetools/connect-giftcard-integration-voucherify) - Connect integration for Voucherify gift cards with frontend and payment-processing modules.

### Tax

- [Avalara](https://github.com/mediaopt/avalara-commercetools-connector) - Connect integration for AvaTax calculations, address validation, and invoice filing.

### Email and marketing

- [Klaviyo](https://github.com/klaviyo/commercetools-klaviyo) - Synchronizes commercetools data with Klaviyo, with self-hosted and Connect deployment options.
- [Connect Email Integration Template](https://github.com/commercetools/connect-email-integration-template) - Starter template for building email notifications with an external provider; requires implementation and configuration.

### Search and discovery

- [Algolia](https://www.algolia.com/search-solutions/commercetools) - Provider overview of search integration options and implementation services for commercetools.
- [Constructor](https://docs.constructor.com/docs/integrating-with-constructor-platform-connectors-catalog-connectors-commercetools-connector) - Managed catalog connector for products, variants, categories, and custom attributes; setup requires contacting Constructor.
- [Relewise](https://github.com/Relewise/relewise-integrations-commercetools-connect) - Synchronizes the product catalog with Relewise for search and recommendations through Connect.

### Digital asset management

- [Cloudinary](https://github.com/cloudinary/cloudinary_commercetools_mach) - Microservices for a Cloudinary integration, with AWS, Azure, and Google Cloud deployment examples.
- [Scaleflex DAM (formerly Filerobot)](https://github.com/scaleflex/commercetools-scaleflex-dam-plugin) - Integrates Scaleflex digital asset management with commercetools.

### Marketplace and data integration

- [Marketplacer](https://github.com/marketplacer/ChangeCX-Commercetools-Marketplacer-Accelerator) - Accelerator for synchronizing Marketplacer products, variants, and sellers using webhooks.
- [Enterspeed](https://github.com/enterspeedhq/enterspeed-source-commercetools) - Imports products, variants, and categories into Enterspeed. Last repository push: February 2023; review compatibility before adopting.

### Order management and fulfillment

- [fulfillmenttools](https://github.com/fulfillmenttools/commercetools-connector) - Official fulfillmenttools integration applications for commercetools Connect.
- [OMS Connector](https://github.com/Harshca/ct-oms-connector) - Community starting point for connecting an order management system; requires adaptation to the target OMS.

### Content management

- [Kontent.ai](https://github.com/hermanviking/integration-commercetools) - Community custom element for selecting and referencing products. Last repository push: November 2022; review compatibility before adopting.
- [Strapi](https://github.com/JonssonWorkwear/strapi-plugin-commercetools-integration) - Custom field for searching and referencing commercetools products in Strapi; check supported Strapi versions.
- [Storyblok](https://github.com/labd/storyblok-plugins) - Community plugins including a commercetools category selector.
- [Contentful](https://www.contentful.com/marketplace/commercetools/) - Contentful app for browsing and linking commercetools products and categories in content entries.

## Storefront

- [Alokai (formerly Vue Storefront)](https://docs.alokai.com/integrations/commercetools) - commercetools integration maintained by Alokai and available through its Enterprise offering.
- [commercetools Frontend](https://docs.commercetools.com/frontend-development/overview) - Managed frontend development platform with a visual editing environment, formerly Frontastic.

## Tools

- [commercetools Anonymizer](https://github.com/mmularski/commercetools-utils) - Community CLI for personal data erasure, anonymization, and mock data generation. Last repository push: July 2023; review compatibility before adopting.
- [Postman Collections](https://github.com/commercetools/commercetools-postman-collection) - API request examples for exploring and testing commercetools APIs in Postman.
- [Terraform Provider](https://github.com/labd/terraform-provider-commercetools) - Community provider for managing commercetools resources as infrastructure as code.

## SDKs

### Official

- [Java](https://github.com/commercetools/commercetools-sdk-java-v2) - Official Java SDK.
- [PHP](https://github.com/commercetools/commercetools-sdk-php-v2) - Official PHP SDK.
- [.NET](https://github.com/commercetools/commercetools-dotnet-core-sdk-v2) - Official .NET SDK.
- [TypeScript](https://github.com/commercetools/commercetools-sdk-typescript) - Official SDK for TypeScript and JavaScript.

### Community

- [Go](https://github.com/labd/commercetools-go-sdk) - Community Go SDK generated from the commercetools API specifications.
- [Python](https://github.com/labd/commercetools-python-sdk) - Community Python SDK with type annotations.

## Testing and schemas

- [Messages](https://github.com/composable-software/commercetools-messages) - Message mocks for TypeScript tests. Last repository push: October 2022; review coverage before adopting.
- [Node Mock](https://github.com/labd/commercetools-node-mock) - Mocks commercetools REST APIs using Mock Service Worker; also maintains the Docker mock-server image.
- [Entity Schemas](https://github.com/Devgurusio/commercetools-entities-schemas) - Reusable schemas for commercetools HTTP API entities.
- [Test Data](https://github.com/commercetools/test-data) - Builders for REST and GraphQL test data in JavaScript and TypeScript.

## Historical resources

These resources are retained for existing implementations and reference. Archived repositories are read-only; a long period without pushes alone does not establish that a project is unusable.

- [SendGrid on AWS](https://github.com/Devgurusio/aws-sendgrid-commercetools-connector) - Serverless email connector with no repository pushes since November 2018; compatibility is unverified.
- [CrafterCMS Blueprint](https://github.com/craftercms/commercetools-blueprint) - Archived ecommerce and editorial-content blueprint.
- [Swift / iOS SDK](https://github.com/commercetools/commercetools-ios-sdk) - Archived official iOS SDK.
- [Node.js CLI tools](https://github.com/commercetools/nodejs#cli-tools) - Deprecated since March 31, 2025. Previously listed exporters, importers, CSV converters, discount-code utilities, personal-data erasure, and resource deletion tools belong to this retired toolset.

## Contribute

Contributions are welcome! Read the [contribution guidelines](CONTRIBUTING.md) before submitting a resource or an update.

## License

This awesome list is licensed under the [CC0-1.0 License](https://creativecommons.org/publicdomain/zero/1.0/), meaning you can copy, modify, and distribute the content without asking for permission.
