<!--lint disable awesome-list-item-->
<div align="center">
  <p align="center">
    <img alt="Commercetools" src="https://avatars.githubusercontent.com/u/1084585?s=150&v=4" width="150" />
  </p>
<h1>Awesome Commercetools</h1>
<p>A curated list of awesome resources and tools for working with Commercetools, a flexible, cloud-native eCommerce platform</p>

<a href="#integrations">Integrations</a>
&nbsp;&nbsp;&nbsp;
<a href="CONTRIBUTING.md">Contribution guide</a>
&nbsp;&nbsp;&nbsp;
<a href="https://docs.commercetools.com/docs/">Official documentation</a>

  <a href="https://awesome.re">
    <img src="https://awesome.re/badge.svg" alt="Awesome">
  </a>
</div>

## Integrations

### Payment
- [Braintree](https://github.com/mediaopt/braintree-commercetools-connector): This is a connect application to integrate Braintree into Commercetools. It follows the folder structure to ensure certification & deployment from commercetools connect team.
- [Adyen](https://github.com/Adyen/adyen-commercetools): Provides an integration between the commercetools and Adyen payment service provider based on the concept of Adyen Web Components.
- [Gr4vy](https://github.com/gr4vy/gr4vy-commercetools): Gr4vy commercetools integration.
- [Cybersource](https://github.com/CyberSource/cybersource-plugins-commercetools): This repository contains the source code for the CyberSource CommerceTools plugin.
- [Worldpay](https://github.com/Worldpay/Worldpay-CommerceTools-CG): The module provides integration between commercetools and Worldpay Worldwide Payment Gateway (WPG).
- [Planet (Datatrans)](https://github.com/weareplanet/commercetools-planet-integration): Online payments made easy with Planet's commercetools connector. Link dozens of payment methods, acquirers, and currencies to your commercetools projects and offer your customers a state-of-the-art user experience for online payments.
- [Mollie](https://github.com/mollie/commercetools): This project provides a Hosted checkout based integration between the commercetools and Mollie PSP.
- [Paypal Plus](https://github.com/commercetools/commercetools-paypal-plus-integration) **!DEPRECATED**: Integration between commercetools API and PayPal Plus API.
- [Payone](https://github.com/commercetools/commercetools-payone-integration) **!DEPRECATED**: This software provides an integration between the commercetools eCommerce platform API and the PAYONE payment service provider.

### Authentication
- [Auth0](https://github.com/gradientedge/commercetools-auth0): Facilitates the customer account synchronisation between auth0 and commercetools.

### Discount
- [Talon.One](https://github.com/talon-one/commercetools-talonone-accelerator): The Talon.One's commercetools accelerator allows you to integrate the Talon.One Promotion Engine with your commercetools Commerce Platform.

### Notification
- [Klaviyo](https://github.com/klaviyo/commercetools-klaviyo): The Klaviyo plugin for commercetools is a Node.js application that provides the ability to sync commercetools data into Klaviyo.
- [Sendgrid](https://github.com/Devgurusio/aws-sendgrid-commercetools-connector): The sendgrid commercetools serverless connector for AWS, allows you to quickly deploy a cloud service to manage your emails in Sendgrid based on commercetools messaging and subscriptions.

### Search
- [Algolia](https://www.algolia.com/developers/code-exchange/backend-tools/integrate-commercetools-with-algolia/): Connect your commercetools store with Algolia in a few clicks. Index your products and keep your product data in sync with Algolia without writing code. The Algolia commercetools integration handles the data connection between your commercetools store and Algolia.
- [Constructor](https://github.com/commercetools/commercetools-constructorio-connector): This connector contains code to connect commercetools to constructor.io.

### File storage and management
- [Cloudinary](https://github.com/cloudinary/cloudinary_commercetools_mach): This repo contains the microservices needed to host the functions that drive the Cloudinary commercetools extension. See the individual Readme.md for the platform of your choosing (AWS/Azure/GCP).
- [Filerobot](https://github.com/scaleflex/commercetools-filerobot-plugin): Filerobot is a scalable and performance-oriented Digital Asset Management platform with integrated image and video optimizers to store, organize, optimize and deliver your media assets such as images, videos, PDFs and many other brand assets fast all around the world to all device types.

### Loader
- [Marketplacer](https://github.com/marketplacer/ChangeCX-Commercetools-Marketplacer-Accelerator): Marketplacer offers a webhook feature that enables connection to any external endpoint, allowing for the real-time sharing of information such as products, product variant(adverts), and seller updates.
- [Enterspeed](https://github.com/enterspeedhq/enterspeed-source-commercetools): A ready to use integration service for connecting Commercetools as an Enterspeed data-source by importing products, variants and categories.

### CMS
- [Blueprint](https://github.com/craftercms/commercetools-blueprint): This is a fully functional ecommerce blueprint with editorial content weaved in. Commerce is done via integration with commercetools and you'll need to create an account with commercetools to get started.
- [Kontent.ai](https://github.com/hermanviking/integration-commercetools): This custom element extension for Kontent.ai allows users to search and link selected products from commercetools into their structured content.

## Storefront
- [Vuestorefront](https://github.com/vuestorefront/vue-storefront): The open-source frontend for Commercetools. Built with a PWA and headless approach, using a modern JS stack.
- [Commercetools Frontend](https://docs.commercetools.com/frontend-getting-started/overview): Commercetools native frontend (commercetools Studio) formerly known as [frontastic](https://www.frontastic.cloud/)

## Tools
- [Commercetools Anonymizer](https://github.com/mmularski/commercetools-utils): CLI Tool for some Commercetools useful actions like: Personal data erasure, Personal data anonymization, and Generating some mock data.
- [Category Exporter](https://commercetools.github.io/nodejs/cli/category-exporter.html): A package which exports commercetools categories in JSON format from the commercetools platform.
- [CSV Parser Discount Code](https://commercetools.github.io/nodejs/cli/category-exporter.html): Convert commercetools discount codes CSV data to JSON. See example below for CSV format, sample response and usage.
- [CSV Parser Price](https://commercetools.github.io/nodejs/cli/csv-parser-price.html): Convert commercetools price CSV data to JSON. See example below for CSV format and sample response.
- [CSV Parser Orders](https://commercetools.github.io/nodejs/cli/csv-parser-orders.html): Convert commercetools order CSV data to JSON. See examples below for supported CSV format and sample responses.
- [CSV Parser State](https://commercetools.github.io/nodejs/cli/csv-parser-state.html): Convert commercetools states CSV data to JSON. See example below for CSV format, sample response and usage.
- [Custom Objects Exporter](https://commercetools.github.io/nodejs/cli/custom-objects-exporter.html): A package which exports commercetools custom objects in JSON format from the commercetools platform.
- [Custom Objects Importer](https://commercetools.github.io/nodejs/cli/custom-objects-importer.html): This package helps with importing commercetools custom objects in JSON format to the commercetools platform. The package is built to be used in conjunction with sphere-node-cli.
- [Customer Groups Exporter](https://commercetools.github.io/nodejs/cli/customer-groups-exporter.html): A package which exports commercetools customer groups in JSON format from the commercetools platform.
- [Personal Data Erasure](https://commercetools.github.io/nodejs/cli/personal-data-erasure.html): A package which deletes or exports commercetools personal data in JSON format from the commercetools platform.
- [Discount Code Generator](https://commercetools.github.io/nodejs/cli/discount-code-generator.html): Generate unique discount codes to be imported to the commercetools platform.
- [Discount Code Exporter](https://commercetools.github.io/nodejs/cli/discount-code-exporter.html): A package that helps with exporting commercetools discount codes in JSON or CSV format from the commercetools platform.
- [Discount Code Importer](https://commercetools.github.io/nodejs/cli/discount-code-importer.html): A package that helps with importing commercetools discount codes in JSON format to the commercetools platform. This package is built to be used in conjunction with sphere-node-cli.
- [Inventories Exporter](https://commercetools.github.io/nodejs/cli/inventories-exporter.html): This package helps in exporting inventories from the commercetools platform in csv and json format.
- [Price Exporter](https://commercetools.github.io/nodejs/cli/price-exporter.html): A package that helps with exporting commercetools price in JSON or CSV format from the commercetools platform.
- [Product Exporter](https://commercetools.github.io/nodejs/cli/product-exporter.html): A package that helps with exporting commercetools products from the commercetools platform. The products can be exported in JSON format, or as chunks that can be piped to a parser for more export formats.
- [Product JSON to CSV Parser](https://commercetools.github.io/nodejs/cli/product-json-to-csv.html): A package that parses commercetools products JSON data to CSV. The products to be parsed can either be read from a .json file or directly piped in from the product exporter.
- [Product JSON to XLSX Parser](https://commercetools.github.io/nodejs/cli/product-json-to-xlsx.html): A package that parses commercetools products JSON data to XLSX. The products to be parsed can either be read from a .json file or directly piped in from the product exporter.
- [Resource Deleter](https://commercetools.github.io/nodejs/cli/resource-deleter.html): A package which deletes resources from the commercetools platform.
- [State Importer](https://commercetools.github.io/nodejs/cli/state-importer.html): A package that helps with importing commercetools states in JSON format to the commercetools platform. This package is built to be used in conjunction with sphere-node-cli.

## SDK
- [Commercetools JAVA SDK](https://github.com/commercetools/commercetools-sdk-java-v2): The e-commerce SDK from commercetools for Java.
- [Commercetools PHP SDK](https://github.com/commercetools/commercetools-sdk-php-v2): The e-commerce SDK from commercetools for PHP.
- [Commercetools .NET SDK](https://github.com/commercetools/commercetools-dotnet-core-sdk-v2): The e-commerce SDK from commercetools for .NET.
- [Commercetools Typescript SDK](https://github.com/commercetools/commercetools-sdk-typescript): The e-commerce SDK from commercetools for JavaScript written in TypeScript.
- [Commercetools GO SDK](https://github.com/labd/commercetools-go-sdk): The Commercetools Go SDK is automatically generated based on the official API specifications of Commercetools.
- [Commercetools Python SDK](https://github.com/labd/commercetools-python-sdk): This is an unofficial Python SDK for the Commercetools platform. It only supports Python 3.6+ and uses type annotation for an improved development experience.
- [Commercetools Swift SDK](https://github.com/commercetools/commercetools-ios-sdk): The e-commerce iOS SDK from commercetools.

## Other
- [Commercetools Messages](https://github.com/composable-software/commercetools-messages): This library mocks the Commercetools messages to ease testing of your typescript codebases.
- [Commercetools Postman Collections](https://github.com/commercetools/commercetools-postman-collection): Postman provides a REST client that helps you executing API requests without any development effort. API requests can be organized into collections that you can import into Postman.
- [Commercetools Terraform Provider](https://github.com/labd/terraform-provider-commercetools): The Terraform commercetools provider allows you to configure your commercetools project with infrastructure-as-code principles.
- [Commercetools Mocking library for Node](https://github.com/labd/commercetools-node-mock): This library mocks the Commercetools rest api to ease testing of your typescript codebases interacting with the commercetools api.
- [Commercetools Mock Server](https://github.com/labd/commercetools-mock-server): Docker image which offers mocks for the commercetools api.
- [Commercetools Entities Schemas](https://github.com/Devgurusio/commercetools-entities-schemas): Reusable commercetools entities schemas definitions.
- [Commercetools OMS Connector](https://github.com/Harshca/ct-oms-connector) Generic connector to connect commerceTools with any OMS

## Contribute

Contributions are welcome! If you have any additional resources or tools related to Commercetools that you'd like to add, feel free to submit a pull request. Read the [contribution guidelines](CONTRIBUTING.md) first.

## License

This awesome list is licensed under the [CC0-1.0 License](https://creativecommons.org/publicdomain/zero/1.0/), meaning you can copy, modify, and distribute the content without asking for permission.
