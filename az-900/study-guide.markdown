# AZ-900: Microsoft Azure Fundamentals

## Describe cloud concepts

### Describe cloud computing

Using someone else's computer

#### Define cloud computing

Cloud computing is the delivery of computing services over the internet. Computing services include common IT infrastructure such as virtual machines, storage, databases, and networking. Cloud services also expand the traditional IT offerings to include things like Internet of Things (IoT), maching learning (ML), and artificial intelligence(AI).

#### [Describe the shared responsibility model](https://learn.microsoft.com/en-us/training/modules/describe-cloud-compute/4-describe-shared-responsibility-model)

In a traditional corporate datacenter, the datacenter was responsible for maintaining the physical spcae, ensuring security, and maintaining or replacing the servers if anything happens. The IT department was responsible for maintaining all the infrastructure and software needed to keep the datacenter up and running. They're also likely to be responsible for keeping all systems patched and on the correct version.

With the shared responsibility model, these responsibilities get shared between the cloud provider and the consumer. Phyical security, power, cooling, and network connectivity are the responsibility of the cloud provider. The consumer isn't collocated with the datacenter, so it wouldn't make sense for the consumer to have any of those responsibilities.

At the same time, the consumer is responsible for the data and information stored in the cloud. (You wouldn't want the cloud provider to be able to read your information.) The consumer is also responsible for access security, meaning you only give access to those who need it.

Then, for some things, the responsibility depends on the situation. If you're using a cloud SQL datbase, the cloud provider would be responsible for maintaining the actual database. However, you're still responsible for the data that gets ingested into the database. If you deployed a virtual machine and installed an SQL database on it, you'd be responsible for database patches and updates, as well as maintaining the data and information stored in the database.

With an on-premises datacenter, you're responsible for everything. With cloud computing, those responsibilities shift. The shares responsibility model is heavily tied into the cloud services types: IaaS, PaaS, and SaaS. IaaS places the most responsibility on the consumer, with the cloud provider being responsible for the basics of physical security, power, and connectivity. On the other end of the spectrum, SaaS places the most responsibility with the cloud provider. PaaS, being the middle ground between IaaS and SaaS, rests somewhere in the middle and evenly distributes responsibility between the cloud provider and the consumer.

The consumer will always be responsible for:

- The information and data stored in the cloud
- Devices that are allowed to connect to you cloud (cell phones, computers, and so on)
- The accounts and identities of the people, services, and devices within your organization

The cloud provider will always be responsible for:

- The physical datacenter
- The physical network
- The physical hosts

The consumer's service model will determine responsibility for things like:

- Operating systems
- Network controls
- Applications
- Identity and infrastructure

#### Define cloud models, including public, private, and hybrid

Public cloud: service provided by a third-party provider, hardware can be shared amongst multiple clients.

Private cloud: hardware is only used by a single company, which often owns the hardware and datacenter.

Hybrid cloud: Combination of public and private cloud with automation and orchestration between the two.

Community Cloud: Infrastructure is shared between several orgs from a specific community with common concerns (security, compliance, jurisdiction, etc.).

#### Identify appropriate use cases for each cloud model

Public cloud:

Private cloud:

Hybrid cloud:

#### Describe the consumption-based model

#### Compare cloud pricing models

### Describe the benefits of using cloud services

#### Describe the benefits of high availability and scalability in the cloud

#### Describe the benefits of reliability and predictability in the cloud

#### Describe the benefits of security and governance in the cloud

#### Describe the benefits of manageability in the cloud

### Describe the cloud service types

#### Describe infrastructure as a service (IaaS)

#### Describe platform as a service (PaaS)

#### Describe software as a service (SaaS)

#### Identify appropriate use cases for each cloud service (IaaS, PaaS, SaaS)
