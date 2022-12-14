[Back to Syllabus](./README.md#course-syllabus)

## Learning Objectives
- Describe the features, benefits, and use cases for the __3 main cloud service models—IaaS, PaaS, and SaaS__
- Describe the features, benefits, and use cases for the __3 main cloud deployment models—Public, Private, and Hybrid__
<br>

##  Overview of Cloud Service Models
- __SaaS__: Anyone, Youtube-user / easiest to use
- __PaaS__: Dev _(Jane)_
- __IaaS__: System-Admin / most complex<p><img src="https://user-images.githubusercontent.com/60066472/85106613-73983b00-b247-11ea-819d-431d8e0694ab.PNG" width="450"></p>
<br>

##  IaaS
- __Infrastructure-as-a-Service__
    - delivers fundamental compute, network, and storage resources to consumers on-demand
    - customers can create or provision virtual machines in their choice of Region and Zone available from the Cloud Provider.<p><img src="https://user-images.githubusercontent.com/60066472/85106993-27012f80-b248-11ea-8a34-e31a4b6d435a.PNG" width="400"></p>
- __Key Components__
    - Physical Data Centers: end experience it as a service provided to them.
    - Compute: auto-scaling and load balancing
    - Network
    - Storage: object, file, block
- __Concerns__: lack of transparency, dependency on a third party
- __Use Cases__
    - for Test and Development
    - for Business Continuity and Disaster REcovery
    - for Faster Depoloyments and Scaling
    - for High Performance Computing
    - for Big Data Anlaysis
<br>

##  PaaS
- __Platform-as-a-Service__
    - provides customers a complete platform—hardware, software, and infrastructure—to develop, deploy, manage, and run applications created by them or acquired from a third-party.
    - hosts everything—servers, networks, storage, operating system, application runtimes, APIs, middleware, databases, and other tools—at their data center.
    - leaves the user responsible for only the application code and its maintenance.
- __5 Key Characteristics__
    - High level of Abstraction
    - Supprt Services and APIs
    - Run-time Environments
    - Rapid Deployment Mechanism
    - Middleware Capabilities
- __Advantages__: Scalability, Faster time to market, Greater agility and innovation
- __Concerns__: Information security threats, Dependency on service provider's infrastructure.
- __Use Cases__
    - for API Developments and Management
    - for IoT
    - for Business Analytics/Intelligence
    - for Business Process Management
    - for Master Data Management
- __Available Offerings__
    - Cloud Foundry, IBM Cloud Paks, AWS Elastic Beanstalk, Windows Azure, RedHat OpenShift, Magento Commerce
Cloud, Force.com, and Apache Stratos.
<br>

##  Saas
- __Software as a Service__
    - provides users with access to a service provider’s cloud-based software.
- __6 Key Characteristics__
    - Multi-tenant Architecture
    - Manage Privilleges and Monitor Data
    - Security, Compliance, Maintenance
    - Customize Applications
    - Subscription Model
    - Scalable Resources
- __Advantages__: Reduce the time from decision to value, Increase workforce productivity, Spread out software costs
- __Drivers for Moving to SaaS__
    - To reduce on-premises IT infrastructure and capital expenditure
    - To avoid ongoing upgrades, maintenance, and patching
    - To run applications with minimal input
    - To manage websites, marketing, sales, and operations
    - To gain resilience and business continuity of the cloud provider
- __Concerns__: Data ownership and data safety, needs good internet connection
- __Use Cases__
    - for Email and Collaboration: MS Office 365, Gmail
    - for CRM services: NetSuite CRM and Salesforce
    - for HRM services: Workday and SAP SuccessFactors,
    - for Financial Management

<br>

##  Public Cloud
- __Deplyment models indicate ...__
    - where the infrastructure resides
    - who owns and manages it
    - how cloud resources and services are made available to users<p><img src="https://user-images.githubusercontent.com/60066472/85112325-6b90c900-b250-11ea-9697-3173f1492ea1.PNG" width="300"></p>
- __Public Cloud__
    - resources are distributed on an as-needed basis offered through a variety of subscription and pay-as-you-go models.
    - resources are NOT dedicated for use by a single tenant or organization.
    - user does not have any control over the computing environment
    - provider bears all the capital, operational, and maintenance expenses<p><img src="https://user-images.githubusercontent.com/60066472/85112904-59fbf100-b251-11ea-825d-35fdd925ab07.PNG" width="400"></p>
- __Public Colud Providers__
    - IBM Cloud, Microsoft Azure, Google Cloud Platform, and Alibaba Cloud.
    - offers a wide spectrum of niche services with varied payment options.
- __Advantages__: On-demand resources, Economies of scale, High Reliability
- __Concerns__: Security, Data Sovereignty Compliance
- __Use Cases__
    - for Building and testing applications, and reducing time-to market
    - for Business with fluctuating capacity and resourcing needs
    - for Building secondary infrastructures for disaster recovery
    - for Greater accessibility and easy distribution
    - for Outsourcing the management of standardized business platform
<br>

##  Private Cloud
- __Private Cloud__
    - NIST's definition
        - cloud infrastructure provisioned for exclusive use by a single organization comprising multiple consumers, such as the business units within the organization.
- __Internal Private Cloud__ _(on-premises)_
    - owned and managed by organization
- __External Private Cloud__ _(off-premises)_
    - owned, managed by service provider
    - __VPC__ _(Virtual Private Cloud)_
        - let an organization establish its own cloud-like computing environment in a logically isolated part of a shared public cloud.
        - offered by most Public Cloud providers such as IBM and Amazon.<p><img src="https://user-images.githubusercontent.com/60066472/85114432-253d6900-b254-11ea-8a95-4863d7cde92f.PNG" width="500"></p>
- __Advantages__: Public Cloud Benefits + Control
- __Use Cases__
    - To modernize and integrate in-house & legacy applications or services
    - To build applications anywhere
    - To fully control over critical security issues
<br>

##  Hybrid Cloud
- __Hybrid Cloud__
    - mix of public and private cloud
    - connects an organization’s on-premise private cloud and third-party public cloud into a single, flexible infrastructure for running the organization’s applications and workloads.
- __3 Tenets__: Interoperable, Scalable, Portable
- __3 Types__
    - Hybrid Mono-cloud
        - hybrid cloud with one cloud provider
    - Hybrid Multi-cloud
        - an open standards-based stack that can be deployed on any public cloud infrastructure.
        - offers organizations to move workloads and environments from one vendor to another.
    - Composite Multi-cloud
        - Greater flexibilty
        - distributes single applications across multiple providers, allowing to move application components across cloud services and vendors.
- __Advantages__: Security, Scalibility, Resource optimization, Cost saving
- __Use Cases__
    - SaaS integration
    - Data and AI integration
    - Enhancing legacy apps
    - VMware migration
<br>


## Module Summary
- Cloud computing allows us to utilize technology as a service, leveraging remote resources on-demand, on a pay-as-you-model. There are three main service models available on the cloud—Infrastructure-as-a-Service, Platform-as-a-Service (PaaS), and Software-as-a-Service (SaaS).
    - IaaS provides the fundamental compute, network, and storage resources for customers on-demand.
    - PaaS provides customers the hardware, software, and infrastructure to develop, deploy, manage, and run applications created by them or acquired from a third-party.
    - SaaS provides access to users to a service provider’s cloud-based software. Users simply access the applications on Cloud while the Cloud provider maintains the infrastructure, platform, data, application code, security, availability, and performance of the application.
- Deployment models indicate where the infrastructure resides, who owns and manages it, and how cloud resources and services are made available to users. There are three main deployment models available on the cloud—Public, Private, and Hybrid.
    - In the Public cloud model, the service provider owns, manages, provisions, and maintains the physical infrastructure such as data centers, servers, networking equipment, and storage, with users accessing virtualized compute, networking, and storage resources as services.
    - In the Private cloud model, the provider provisions the cloud infrastructure for exclusive use by a single organization. The private cloud infrastructure can be internal to the organization and run or on-premises. Or, it can be on a public cloud, as in the case of Virtual Private Clouds (VPC) and be owned, managed, and operated by the cloud provider.
    - In the Hybrid cloud model, an organization’s on-premise private cloud and third-party, public cloud is connected as a single, flexible infrastructure leveraging the features and benefits of both Public and Private clouds.
<br>


[Go to Next Module](./4_Components.md)
