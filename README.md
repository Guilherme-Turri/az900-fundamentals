# ☁☁ AZ-900 Fundamentals ☁☁
## About
Study case for AZ-900 certification.

## ☁☁ 1  🔸 Primary types of cloud:

### `Public`
- No capital expenses for vertical scaling.
- An app can be provisioned and deprovisioned quickly.
- The organization only pays for what it uses.

### `Private`
- Initial hardware must be acquired for setup and maintenance.
- The organization has full control over resources and security.
- The organization is responsible for all scales, such as security, architecture, authentication, and maintenance.

### `Hybrid`
- Offers greater flexibility
- Organization determines where to run its applications, e.g., Public cloud for security, private for hardware.

## 🔸 Cloud benefits:
### `High availability`
- SLA (Service Level Agreement) High availability time.

### `Scalability`
- vertical (up) vs. horizontal(out ) (energy x clusters).
### Vertical:
  - Also known as "scaling up."
  - Involves increasing the capacity of a single resource, such as adding more processing power, memory, or storage to a server.
  - Often occurs within a virtual machine or dedicated server.
  - It's more suitable for workloads that require higher resource capacity, but it can have physical limits and be more expensive compared to horizontal scalability.

### Horizontal:
  - Also known as "scaling out."
  - Involves adding more identical instances of a resource, such as virtual machines or servers, to distribute the load.
  - Can be done more efficiently and elastically in terms of resources as more instances are added according to demand.
  - It's highly suitable for scenarios where demand varies and maintaining consistent performance is crucial, potentially being more cost-effective as you only pay for what you use.
###  `Elasticity`
- Ability to increase power, for example during holidays when demand for a service will be higher.

### `Global reach`
- Providing a server for multiple countries.

### `Customer latency capability`
  - Ability to measure and improve latency.

### `Considerations about predictive cost`
- If a standard is maintained, it's easy to predict expenses/costs.

### `Disaster recovery`
- Swift movement in case of any issue (disaster), with the global reach help.

### `Security`
- Effective and certified security policy.

### `Failure Tolerance`
- Low failure rate

## 🔸CAPEX x OPEX
### `Capex`
- Company expenditure (such as infrastructure, etc.) all at once.

### `OPEX`
- Spending as needed
- Spending in installments
 ### Consumption-based mode
 - You spend -> You pay.
 - Not spent -> Not paid.
 - Better cost prediction. Billing based on actual usage.

## 🔸Cloud Services: IaaS | PaaS | Saas

### `IaaS (Infrastructure as a Service):`

Provides cloud-virtualized IT infrastructure such as virtual machines, storage, and networking.
Users have full control over the operating system and applications installed on virtual machines.
Suited for developers and system administrators who want more control over configuration and management of the environment.
Examples: Amazon EC2, Azure Virtual Machines, Google Compute Engine.

### `PaaS (Platform as a Service):`

Offers a complete platform for application development and execution, including infrastructure, programming languages, libraries, and tools.
Developers can focus on application code without worrying about underlying infrastructure.
Ideal for developers aiming to build and deploy applications rapidly without managing infrastructure.
Examples: Azure App Service, Google App Engine, Heroku.

### `SaaS (Software as a Service):` 
Provides ready-to-use software applications over the internet, where users can access and use the software directly without installation or maintenance.
Users don't need to concern themselves with infrastructure, maintenance, or software updates.
Suitable for businesses and users seeking immediate software solutions without the complexity of maintenance.
Examples: Microsoft 365, Google Workspace.

## 🔸Shared Responsibility Model
![Types Of](https://github.com/Guilherme-Turri/az900-fundamentals/blob/main/900img/Shared%20Responsibility%20Model.png)

## ☁☁ 2  🔸 Main Azure's Services:
### `Architecture components`
- Regions and availability zones.
- Region pairs (mirroring)
 - Automatic replication for certain resources. Preserve data resilience with comprehensive compliance
- Resource Group and subscriptions.
  
### `Main resources`
- Computing
- NetWork
- Storage
- DataBase

## 🔸Resources Group
It is a container for managing resources as a single unit (logical grouping).
1 Resource can exist in only 1 Group
1 resource can exist in different regions
Apps can use multiple resource groups
### `Azure Resource Manager ARM`
- It provides a management layer that allows you to create, update, and delete resources in your Azure subscription.
![Shared Responsibility Model](https://github.com/Guilherme-Turri/az900-fundamentals/blob/main/900img/ARM.png)

### `Azure subscription`
 - Distribution of responsibility
   - Provides authorized and authenticated access to Azure accounts.
 - Billing limit 
   - invoices and billing reports for each subscription.
 - Access Control Limit 
   - Manage and control access to resources that users provision with specific subscriptions
## 🔸Management groups:
- Division of subscription boundaries
- Alternative for managing governance across subscriptions

## 🔸Azure Services:
### `Virtual Machine`
 - IaaS service
 - Choose SO
 - Choose Network
 - Choose Memory
 - etc

### `App Service`
 - PaaS service
 - Managed platform for quickly creating, deploying, and scaling web apps/APIs.
 - Work with .Net .NetCore Node, Java Python PHP
 - No need to worry about the infrastructure, just focus on the application, data, security, and access.
 - Could be used with Docker IMG, or, with code, dockerhub, etc

 ### `Container Service`
  -Virtualized environment
  - Kubernets AKS

 ### `Network Service` 
 - Virtual Network: Enables services to communicate with each other (VNET)
 - VPN
 - ExpressRoute: Extends on-premises network to Azure through a private connection
 - 
## 🔸Storage access layer
- Hot \ Frequent
  - Used for frequent access data storage
- Intermittent
  - Used for infrequent storage with a minimum retention of 30 days
- Archive
  -  Used for rarely accessed data

 ## 🔸DB Servies
  ### `Azure COSMODB`
  NOSQL Scale elastically
  ### `AZURE DB`
 (DaaS) Relational SQL server based
 ### `AZURE Postgress`
  PostGress based
   ## Azure Managed SQL Instance
   Managed SQL Instance is designed for customers looking to migrate multiple applications from an on-premises or self-built IaaS environment, or provided by an ISV, to a fully managed PaaS cloud environment with the least migration effort possible. "LIFT AND SHIFT"
 ## ☁☁ 3 🔸Azure Solutions
 ### `Azure IoT`
 - SaaS, like 365, Plataform that Monitors and manages actions
 ### `IoT Hub`
   - Managed cloud service that acts as a central hub for bidirectional messaging between IoT apps and the devices it manages.
### `Azure Sphere`
- Physical device that sends information to Azure Hub, for example, connects to a coffee maker
 ## 🔸Big Data and Analytics
   ### `Azure Synapse Analytics`
   - Data WareHouse cloud based - Structured Data -
### `Azure HD Insights`
- Big Data based on Hadoop- Analytcs Service
### `Azure Data Bricks`
- Servico de análise baseado no Apache Spark
 ## 🔸IA/ML
### `Azure Machine Learning`
- Cloud Solution for devleper, trainning, ML Models
### `Azure Cognitives Services`
- Enable applications to see, listen, speak, comprehend, and interpret user needs.

### `Azure Bot Services`
 - Develop intelligent, enterprise-level bots.
 ## 🔸SERVERLESS
 ### `Azure Functions`
- Event-based code, e.g. HTTP messages, messages arriving in a queue, etc., triggering an action.
### `Azure Logic Apps`
- Like azure functions in a workflow, Automates and orchestrates tasks.
### `Azure Devops`
  - Cloud-based development collaboration tool, including pipelines, Kanban cards, and automated testing.
### `Azure Github Actions`
  - Automate the workflow for creating, testing, and deploying. Uses GitHub.
 ### `AzureDevTest Labs`
- Pre-configured template (like ARM) to quickly create Azure environments, minimizing expenses and cost overruns.

### `Azure Assistant`
- personalized cloud consultant that helps you follow best practices to optimize your Azure deployments. Continuously monitors.
  -Reliability, security, performance, cost, operational excellence.
### `Azure Monitor`
  - Colects Logs, msgs. Creates error alerts. Ex: if theres 4 500's Errors, send an email.
    - Application Insigts, Logs Analysis, Smarts Alerts, Automation, Custom dashboards.
 ## ☁☁ 4 🔸Azure Security
 ### `Defender for Cloud`
 - Monitoring Service
    - Provide Protection
    - Detect and Block Malwares
    - Analyze and Identify Possible Attacks
    - "Just in Time" Access Control for Ports
 ### `Azure Sentinel`
 - Security Information and Event Management (SIEM) and Security Orchestration, Automation, and Response (SOAR) Solution
  ![Azure Sentinel](https://github.com/Guilherme-Turri/az900-fundamentals/blob/main/900img/SENTINEL.png)

### `Azure Key Vault`
- Stores app secrets/certificates in a centralized cloud location to securely control permissions and log access.
    - Secret Management
    - Key Management
    - Certificate Management
    - Stores secrets per Hardware Security Modules (HSMs) security modules.
      - First, a KeyVault is created, and then a password is created within the key vault.
### `Dedicated Host`
- Provides physical servers that host one or more dedicated Azure VMs for the workload of a single organization.
- Benefits:
  - Hardware isolation at the server level
  - Control over maintenance event timing
  - Aligned with Azure Hybrid Usage benefits
  - 
## 🔸Connectivity and Secure Network
Complete Protection

- a layered approach to safeguard the system
- Provides several levels of protection
- Attacks against one layer are isolated from the subsequent layers

### layers
- Physical Security
  - Access Identity
    - Perimeter
      - Network
        - Computing
          - Application
            - Data

### NOTE: Always deny, trust 0

## 🔸 Shared Responsability:
  ![Shared Responsability](https://github.com/Guilherme-Turri/az900-fundamentals/blob/main/900img/shared-responsibility.png)

 ## 🔸 Network Security Group:
### `Traffic Control`
- What, Where and When!!
- Filters network traffic to and from Azure resources within Azure virtual networks.
- Define inbound and outbound rules to filter by source and destination IP address, port, and protocol.
- Add rules as needed within the subscription limit.
- Azure applies default baseline security rules to new NSGs (Network Security Groups).
- Replace default rules with new, higher-priority rules.
 ## 🔸 Azure Firewall:
 ### `FaaS`
- Grants/denies access to the server based on the source IP address to protect network resources.
- Applies filtering rules for inbound and outbound traffic.
- Integrated high availability.
- Unrestricted cloud scalability
- Uses Azure Monitor's log registry
- 
 ## 🔸 DDoS Protection Azure:
- ex of  "Distributed Denial-of-Service (DDoS) attack": Overloading and depleting network resources, causing slowness and unresponsiveness. Thousands of requests per second.
- When there are many 'strange' requests, Azure DDoS protection would block repeated calls.

 ## ☁☁ 4 🔸Identity, governance, privacy, and compliance
 ### `Authentication x Authorization`
 #### Authentication:
  - Identifies person or service
  - Requests credentials
  - Foundation for establishing identity principles and secure access control
 #### Authorization:
  - Determines the level of authenticated access or service
  - Defines which data or service can be accessed or what actions can be taken
Azure Auth MultiFactor
 ## 🔸 Azure Active Diretory (AAD):
 Access and Identity Service cloud based 
 ### `Access and Identity Management Service`
- Employee authentication/credentials for resource access
- Single Sign-On (SSO)
- App management
- Business-to-Business (B2B)
- Business-to-Consumer Identity Service (B2C)
- Device management
 ### `Conditional Access`
 Policy that gathers signals, makes decisions, and enforces organizational policies. Example: where (location) the login is performed.
- User or group association
- IP location
- Device
- Application
- Risk detection
  
