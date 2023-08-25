# ☁☁ AZ-900 Fundamentals ☁☁
## About
Study case for AZ-900 certification.

 ## 🔸 Primary types of cloud:

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
