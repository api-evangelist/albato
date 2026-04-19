# Albato (albato)
Albato is a no-code automation platform and embedded iPaaS that enables businesses to automate workflows by connecting 1,000+ apps without writing code. Supports multi-step automations with triggers, actions, conditions, and delays. Albato Embedded allows SaaS companies to offer white-label native integrations to their customers.

**URL:** [https://albato.com](https://albato.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - No-Code Automation, Workflow Automation, Embedded iPaaS, App Integration, Integrations, Webhooks, White-Label

## Timestamps

- **Created:** 2025-06-06
- **Modified:** 2026-04-19

## APIs

### Albato Automations API
REST API for managing multi-step automation workflows in Albato. Supports creating, enabling, disabling, and monitoring automation executions across 1,000+ connected apps.

**Human URL:** [https://albato.com](https://albato.com)

#### Tags:

 - Automation, Workflow, No-Code, Executions

#### Properties

- [Documentation](https://albato.com)
- [OpenAPI](openapi/albato-automations-openapi.yaml)
- [JSONSchema](json-schema/albato-albato-automations-automation-schema.json)
- [JSONSchema](json-schema/albato-albato-automations-automation-step-schema.json)
- [JSONSchema](json-schema/albato-albato-automations-execution-schema.json)

### Albato Embedded API
REST API for Albato Embedded iPaaS enabling SaaS companies to manage customer teams, app connectors, and automation templates for white-label integration delivery.

**Human URL:** [https://albato.com/embedded](https://albato.com/embedded)

#### Tags:

 - Embedded iPaaS, White-Label, Teams, Connectors, Templates

#### Properties

- [Documentation](https://albato.com/embedded)
- [OpenAPI](openapi/albato-embedded-openapi.yaml)
- [JSONSchema](json-schema/albato-albato-embedded-team-schema.json)
- [JSONSchema](json-schema/albato-albato-embedded-user-schema.json)
- [JSONSchema](json-schema/albato-albato-embedded-connector-schema.json)
- [JSONSchema](json-schema/albato-albato-embedded-template-schema.json)

## Common Properties

- [Website](https://albato.com)
- [Documentation](https://wiki.albato.com/en)
- [GettingStarted - Albato Embedded iPaaS](https://albato.com/embedded)
- [Pricing](https://albato.com/pricing)
- [Integrations - 1,000+ App Integrations](https://albato.com/apps/all-integrations)

## Features

| Name | Description |
|------|-------------|
| No-Code Automation Builder | Visual automation builder for creating multi-step workflows connecting 1,000+ apps without writing code, with conditions, delays, and data transformations. |
| 1,000+ App Integrations | Pre-built connectors for CRM, marketing, e-commerce, communication, and productivity apps including HubSpot, Salesforce, Google Workspace, Slack, Shopify, and more. |
| Albato Embedded iPaaS | White-label integration platform for SaaS companies to embed Albato's automation capabilities natively in their products with full branding control. |
| Multi-Step Workflows | Support for complex automations with sequential and conditional steps, delays, loops, and data transformations without coding. |
| Real-Time and Scheduled Triggers | Webhook-based real-time triggers for instant event processing and scheduled polling triggers for API-based app integrations. |
| Custom App Integrator | Build custom API connectors from any REST API using the App Integrator without development handoff, supporting all major auth methods. |
| Execution Monitoring | Detailed execution history with step-level logging, success/error rates, real-time notifications, and dashboard insights. |
| Data Transformation | Built-in data mapping, field transformation, and JavaScript code steps for processing data between connected apps. |

## Use Cases

| Name | Description |
|------|-------------|
| CRM and Marketing Automation | Sync leads between CRM and marketing tools, automate email campaigns, and route prospects based on behavioral conditions. |
| E-Commerce Order Processing | Automate order notifications, inventory updates, fulfillment triggers, and customer communication across e-commerce platforms. |
| SaaS Native Integration Delivery | Use Albato Embedded to offer customers white-labeled integrations in your SaaS product without in-house iPaaS development. |
| Customer Support Automation | Route tickets, trigger alerts, and sync customer data between helpdesk, CRM, and communication platforms automatically. |
| Data Synchronization | Keep data consistent across business systems with bidirectional syncs, scheduled automations, and event-driven updates. |

## Integrations

| Name | Description |
|------|-------------|
| HubSpot | CRM and marketing automation for contact and deal management. |
| Salesforce | Enterprise CRM for sales pipeline and opportunity workflows. |
| Google Workspace | Google Sheets, Gmail, Drive, Calendar, and Forms integrations. |
| Slack | Team messaging integration for workflow notifications and alerts. |
| Shopify | E-commerce integration for order, product, and customer automation. |
| Stripe | Payment processing integration for subscription and payment workflows. |
| Notion | Workspace integration for task and project data synchronization. |
| Airtable | Database integration for spreadsheet and grid data workflows. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Albato Automations API](openapi/albato-automations-openapi.yaml)
- [Albato Embedded API](openapi/albato-embedded-openapi.yaml)

### JSON Schema

- [albato-albato-automations-automation-schema.json](json-schema/albato-albato-automations-automation-schema.json)
- [albato-albato-automations-automation-step-schema.json](json-schema/albato-albato-automations-automation-step-schema.json)
- [albato-albato-automations-execution-schema.json](json-schema/albato-albato-automations-execution-schema.json)
- [albato-albato-embedded-team-schema.json](json-schema/albato-albato-embedded-team-schema.json)
- [albato-albato-embedded-user-schema.json](json-schema/albato-albato-embedded-user-schema.json)
- [albato-albato-embedded-connector-schema.json](json-schema/albato-albato-embedded-connector-schema.json)
- [albato-albato-embedded-template-schema.json](json-schema/albato-albato-embedded-template-schema.json)

### JSON Structure

- [albato-albato-automations-automation-structure.json](json-structure/albato-albato-automations-automation-structure.json)
- [albato-albato-automations-automation-step-structure.json](json-structure/albato-albato-automations-automation-step-structure.json)
- [albato-albato-automations-execution-structure.json](json-structure/albato-albato-automations-execution-structure.json)
- [albato-albato-embedded-team-structure.json](json-structure/albato-albato-embedded-team-structure.json)
- [albato-albato-embedded-user-structure.json](json-structure/albato-albato-embedded-user-structure.json)
- [albato-albato-embedded-connector-structure.json](json-structure/albato-albato-embedded-connector-structure.json)
- [albato-albato-embedded-template-structure.json](json-structure/albato-albato-embedded-template-structure.json)

### JSON-LD

- [albato-albato-context.jsonld](json-ld/albato-albato-context.jsonld)

### Examples

- [albato-albato-automations-automation-example.json](examples/albato-albato-automations-automation-example.json)
- [albato-albato-automations-automation-step-example.json](examples/albato-albato-automations-automation-step-example.json)
- [albato-albato-automations-execution-example.json](examples/albato-albato-automations-execution-example.json)
- [albato-albato-embedded-team-example.json](examples/albato-albato-embedded-team-example.json)
- [albato-albato-embedded-user-example.json](examples/albato-albato-embedded-user-example.json)
- [albato-albato-embedded-connector-example.json](examples/albato-albato-embedded-connector-example.json)
- [albato-albato-embedded-template-example.json](examples/albato-albato-embedded-template-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Albato Automations API](capabilities/shared/automations-api.yaml) — 6 operations for automation management
- [Albato Embedded API](capabilities/shared/embedded-api.yaml) — 5 operations for embedded team and connector management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [iPaaS Automation](capabilities/ipaas-automation.yaml) | albato-automations, albato-embedded | 6 | Automation Builder, SaaS Developer, Operations Manager |

## Vocabulary

- [Albato Vocabulary](vocabulary/albato-vocabulary.yaml) — Unified taxonomy mapping 6 resources, 7 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Albato Spectral Rules](rules/albato-spectral-rules.yml) — 25 rules across 8 categories enforcing Albato API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
