# Introduction

The Azure DocumentDB Migration extension for Visual Studio Code helps you assess and migrate your MongoDB workloads to Azure DocumentDB seamlessly. It offers two key capabilities:

## 1. Comprehensive Assessment

Quickly identify the actions needed for a smooth migration. The extension generates a detailed report at the account, database, and collection levels, categorizing findings as Critical, Warning, or Informational to help you prioritize. Key highlights include:

- **Unsupported Features and Syntax**: Detects unsupported MongoDB features, commands, query syntax, and index types, along with usage frequency for prioritization.

- **Resource-Specific Recommendations**: Provides actionable guidance for each affected resource, including technical details for remediation.

- **Environment Overview**: Summarizes essential details of your MongoDB environment version, license, instance type, and database/collection statistics.

- **Compatibility and Platform Constraints**: Highlights Azure DocumentDB specific quotas, and limits.

## 2. Online & Offline Migration

Accelerate your modernization journey with zero-cost migration in both online and offline modes. Migration jobs run entirely on Azure-managed resources, maintained by the Azure DocumentDB team, no infrastructure setup required.

- **Secure and Flexible**: Initiate and monitor migrations without staying connected, ideal for large-scale or secure scenarios. Supports private endpoint-enabled targets for enterprise-grade security.

- **Broad Source Support**: Migrate from self-hosted MongoDB, MongoDB Atlas, or other compatible sources all within a unified, intuitive VS Code experience.

Enjoy improved performance, reduced operational overhead, and a streamlined path to Azure DocumentDB without additional migration costs.

## Telemetry

VS Code collects usage data and sends it to Microsoft to help improve our products and services. Read our [privacy statement](https://go.microsoft.com/fwlink/?LinkId=521839) to learn more. If you don’t wish to send usage data to Microsoft, you can set the `telemetry.enableTelemetry` setting to `false`. Learn more in our [FAQ](https://code.visualstudio.com/docs/supporting/faq#_how-to-disable-telemetry-reporting).

## Privacy Statement

To learn more about our Privacy Statement visit [this link](https://go.microsoft.com/fwlink/?LinkId=521839).

## License

Copyright (c) Microsoft Corporation. All rights reserved.
This extension is licensed under the [EULA](https://github.com/Azure/ads-extension-mongo-migration-assets/blob/main/migrationextension_license.md).
