# AZ-304 Crash Course Outline

## SESSION 1

### Identity and Security Design

* Authentication
    * Azure AD B2C
    * App registrations
    * Managed Identity
        * Instance Metadata Service
    * Hybrid identity
        * IdFix
        * Azure AD Connect Health
        * AAD DS
    * Conditional Access
        * Trusted Locations
* Authorization
    * Custom RBAC roles
    * Azure AD PIM
        * Access reviews
    * Key Vault


### Storage Data Design

* Raw data migration
    * Data Box
    * AzCopy
* Storage accounts
    * Replication options
    * SAS tokens
    * Tiers
    * Legal hold access policy
    * Azure File Sync
    * Table and queue services
* Virtual machines
    * Disk caching options
    * Premium vs standard options/SLA
* Azure SQL Database
    * Types
        * Managed Instance
        * Virtual Machine
        * SSIS Integration Runtime
        * Always Encrypted w/ determ vs non-determ encryption
    * Query Store/Performance Insight
    * Database auditing
    * SQLInsights
    * SQL Analytics
    * Elastic pools
    * Long-term backup retention
    * Always Encrypted


## #Monitoring Design

* Enable diagnostics collection
* Activity log
* Log Analytics
* Resource Graph
* App Insights
    * Service Map
* Cost Management
    * Reservations
    * HUB
    * Budgets
    * Advisor
* Alerts
    * Rules and Action Groups
    * Function app notifications



## DAY 2


### Business Continuity Design

* High availability
    * VMs
        * VMSS auto-scale
        * Fault, update domains
        * ASR in the Recovery Services vault
        * Backup and recovery in the RS vault
    * Networks
        * CDN
        * App Gateway
        * Traffic Manager
* Database migration
    * DMA, DMS


### Infrastructure Design

* Blueprints
    * Scoping (Management Groups)
* Policy and exclusions
* APIM
    * Authorization levels
    * Policies
* VNet integration
    * Service endpoints
* Networking
    * App Gateway with WAF
    * IPv4 subnetting
    * ExpressRoute / S2S VPN
* Data pipelines
    * ADF
    * Event Grid
    * Event Hub
    * Service Bus
    * Service Fabric
    * Azure Redis Cache
* Containers
    * AKR
        * SKU differences
    * ACI
    * AKS
* VMS
    * SKU differences
* Azure Batch
* Functions
    * Pricing options
