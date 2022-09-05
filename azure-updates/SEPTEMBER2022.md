# Azure Updates 09/2022 - Highlights

### Microsoft DevBox

##### :boom: Preview

Microsoft Dev Box is now in public preview. Microsoft Dev Box provides self-service access for developers to high-performance, 
cloud-based workstations preconfigured and ready-to-code for specific projects—all while maintaining security and corporate governance.

With Microsoft Dev Box, organizations can:
- Maximize dev productivity with ready-to-code, self-service Dev Boxes.
- Centralize governance of workstations running anywhere to maintain greater security, compliance, and cost efficiency.
- Customize dev boxes with everything developers need for their current projects.

[Documentation](https://azure.microsoft.com/blog/announcing-microsoft-dev-box-preview)

---

### API Management
##### :dizzy: GA 

Azure API Management support for the MSAL authorization library is now generally available.
You can provide a more secure OAuth 2.0 authorization code flow using PKCE when implementing user sign-in and sign-up actions 
in the developer portal through Azure Active Directory and Azure Active Directory B2C.

[Documentation](https://docs.microsoft.com/azure/api-management/api-management-howto-aad?WT.mc_id=wwc-aces#migrate-to-msal)

---

### App Service

##### :boom: Preview

Azure App Configuration now supports replicating your configuration data in the configuration store to replicas in other Azure regions. 
Available to standard tier subscribers, any updates or additions to key/values in the configuration store or in a replica will be automatically synchronized,
using an eventual consistency model.

This delivers benefits including:
 - Increased resiliency:
   Replication across regions means that your configuration data will still be accessible should a service outage impact your store or 
   any one of the replicas.
 - Minimize latency – Now your applications can consume the data locally rather than issuing cross-region requests.
 - Optimize request distribution – Replicas and the configuration store have unique applicable request limits,
   enabling you to distribute requests efficiently to avoid exhausting the request limits on either the replicas or the configuration store.

[Documentation](https://docs.microsoft.com/azure/azure-app-configuration/concept-geo-replication?WT.mc_id=wwc-aces)

---

### Container Apps

##### :flight_arrival: Updated Features

Azure Container Apps (ACA) support for Dapr release 1.8.3 is now generally available.
All Container App Environments have been automatically upgraded to consume 1.8.3

[Dapr v1.8 release notes](https://github.com/dapr/dapr/releases/tag/v1.8.0)

[Documentation](https://docs.microsoft.com/azure/container-apps/dapr-overview?tabs=bicep1%2Cyaml?WT.mc_id=wwc-aces)

---

### Data Explorer

##### :dizzy: GA

Azure Data Explorer (ADX) now supports ingesting data from S3 natively.

[Documentation](https://techcommunity.microsoft.com/t5/azure-data-explorer-blog/azure-data-explorer-supports-native-ingestion-from-amazon-s3/ba-p/3606746)

---

### Azure Regions

##### :earth_africa: Region Updates

- 3 Availability Zones in UAE North
- New region: Qatar (with AZs)
              
[Documentation](https://news.microsoft.com/en-xm/2022/08/23/microsoft-launches-azure-availability-zones-to-heighten-competitiveness-of-uae-organizations)

[Azure Regions](https://azure.microsoft.com/global-infrastructure/geographies/#geographies)

---
