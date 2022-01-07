# Google Cloud

Google Cloud Platform is the suite of infrastructures and services that Google uses internally and is also available to any company or user, in such a way that it is applicable to a multitude of business processes.

Google Cloud Platform offers us tools that we can divide into 3 groups, according to the type of service:

·Infrastructure as a service (IaaS)

·Platform as a service (PaaS)

·Software as a Service (SaaS)

## Cloud computing features:

·Self-service and on-demand computation.

·Connected to the network (you can access from anywhere).

·Economies of scale (The provider shares resources among all customers).

·Elasticity (the client can obtain resources or decrease them as required very quickly).

·Metered service (you pay what you consume).

# Data centers

Info: https://cloud.withgoogle.com/infrastructure/explore/step-1

## Parts of data center

Networking Room: Here the Jupiter clusters are connected with the rest of Google Cloud through the Google backbone network.

Jupiter Network Equipment: Equipment (software and hardware) developed by Google, to connect all the servers in the data centers, so that they are almost one.

Maglev Load Balancers: They are Global Load Balancers. They balance the load to Google Compute Engine, so that it can serve a million requests per second without pre-warming.

### Custom Chips:

#### Titan: Low-power, secure microcontroller designed with Google's hardware security requirements and scenarios in mind.
#### Cloud TPUs: Chip designed to accelerate machine learning workloads with TensorFlow.

### Water Pipes: 
Cold water that runs from the cooling plant to the data center, where it is used to extract heat from inside the hot huts. The warm water is then returned to the cooling plant where residual heat is removed and the water returns to the data center.

### HotHut: 
Custom cooling systems for Google server racks. They serve as temporary homes for the hot air that comes out of our servers, isolating it from the rest of the data center floor.

### Cooling Plant: 
In Google's data centers, the “free cooling” provided by the climate through a water system is used. That is, the cooling plant receives hot water from the data center and cold water from the cooling towers, the heat is transferred from hot water to cold water. The chilled water returns to the data center floor to extract more heat from the equipment there, and the hot water flows into the cooling towers to be cooled.

## The transformational cloud:

### First part

·The cleanest cloud/Sustainability.

·Saves you money.

·Easy to use and self-optimizing.

·Custom industry solutions.

### Second part

·Era of virtual machines (VM): The cloud begins, startups realize that it is not necessary to buy all the infrastructure, which until then was necessary and that they could take advantage of the "cloud"

·Age of Cloud Infrastructure: Many Traditional Businesses Realize the Potential of the Cloud.


## Architectures on GCP

### Computing options

#### Compute Engine

·Virtual Machines

·Bear Metal (full servers by special licensing tea)

#### GKE

·Kubernetes Engine

·How to orchestrate different types of containers

#### App Engine (Serverless Platform)

To run web applications

Zero server administration

#### Cloud run

Serverless containers

#### Cloud Function

·Serverless function

#### Firebase

·Front-end PaaS and mobile development

·It is known as Back-end as a Service

### Serverless computing

Info: https://cloud.google.com/serverless

Develop, deploy and scale applications quickly and safely in a fully managed environment

·Auto-scaling

·Fully managed

·Speed to Market.


## Aggressive Global Rollout

### It is a private network with a fairly large dimension and scope.

### How to build submarine cables.

### Landing of a submarine cable.

### Submarine cable ties.

  ·They are repeaters for the amplification of optical signals
  
  ·It is quite particular and quite safe
  
  ·This allows a global reach


## Google network

![image](https://user-images.githubusercontent.com/78567418/148380946-992baeac-4aa6-4517-ba43-a74ef44e6c1c.png)

### Global network

  ·Reduces configuration load

  ·Global reach
  
### Live migration

  ·Network resistance

  ·High availability

  ·Managed Updates and Maintenance

### Scale and Performance

  ·Horizontal scaling

  ·Better application performance

  ·No choke point

## Cloud DNS

### Low latency global DNS

  ·Integrates with Global Anycast IP Load Balancing
  
  ·Simple and scalable records management
  
  ·DNSSEC to verify the integrity of the DNS record

## Content Delivery Networks

### A proven global CDN

  ·A content distribution network created to reach users around the world

  ·Large object support for media and games

## Network Tiers

  ·Premium network to reach your users quickly

  ·Standard network for cost-sensitive applications
  
  ![image](https://user-images.githubusercontent.com/78567418/148381601-e8bb8f1a-a794-4437-ae9e-95857570fac2.png)

## VPC Service Controls

  ·Mitigate the risks of data breaches

  ·Extend the limits of security in cloud environments

  ·Enforce context-aware access

  ·Centralized management of security policies
  
![image](https://user-images.githubusercontent.com/78567418/148381064-2b310cd0-0a42-4d58-8326-0379b958a1b0.png)
  
## Cloud armor

### Defense against DDoS and web attacks

  ·DDoS defense built at scale

  ·Defense against Top 10 OWASP

  ·Integrated with a rich ecosystem of security partners

  ·"Absorbing the largest attacks requires the bandwidth necessary to watch half a million YouTube videos at the same time, in HD"
  
![image](https://user-images.githubusercontent.com/78567418/148381518-39a4455c-3697-4f66-a97a-c53ae9831224.png)

## Regions and zones in GCP

·The region is a geographical area where there are several areas separated by a certain distance, in which each of these areas has data centers inside.

![image](https://user-images.githubusercontent.com/78567418/148382183-7e3802bf-2620-45a9-88dc-cc325e2722f9.png)

·Many times we will require that our application or software be in several zones and / or regions due to high availability and latency, to prevent a natural or human catastrophe from altering our services.


·The points of presence are data centers of the local internet service providers with which Google has contracts and / or agreements

## BigQuery: patterns in the cloud

How BigQuery leverages the cloud infrastructure to work in parallel and deliver results.

1. We send query in SQL.
2. Point of presence: enter the Google network.
3. Get to the closest DataCenter, traveling through Google's private fiber network.
4. The query is routed to a cluster within the data center. We can have very powerful bandwidths like 1 petabyte per second of data.
5. An executing node turns our query into an executing plan; that is, it divides our query into bits to process them in parallel.
6. Escogen máquinas que ejecutarán nuestros pedacitos de query de forma paralela.
7. El resultado se junta y se regresa al usuario.

## Hybrid and multi-cloud

Because workloads, infrastructure, and processes are unique to each business, each hybrid strategy must be tailored to specific needs. The result is that the terms hybrid cloud and multiple clouds are sometimes used inconsistently.

In the context of Google Cloud, the term hybrid cloud describes a configuration in which common or interconnected workloads are deployed across multiple computing environments, one based on the public cloud and at least one private.

The term multiple clouds describes configurations that combine at least two public cloud service providers.

## Google Cloud benefits

1. Inteligent

  ·Convert data into insights in real time using AI

  ·Agile decision making

2. Open and flexible:

  ·Choice and flexibility with open source, hybrid and multi-cloud solutions

  ·Protect your business from seller lock-in

3. Collaboration and productivity

  ·Google worspace provides all the digital tools you need to help your business prosper today and tomorrow

  ·Teams collaborate, frontline workers stay connected, and companies create new experiences for customers

  ·Flexible Workspace solutions make working from anywhere a reality

4. Secure

  ·Your data is stored, processed and protected in the same infrastructure used for Google's own operations.

  ·Only Google Cloud encrypts data at rest and in transit by default

  ·With the Google network, your data is not transferred over public networks, which increases performance and security.

5. Sustainable

  ·Google Cloud is the only major cloud provider purchasing enough renewable energy to cover all of our operations

  ·Net operational emissions from your use of the cloud are zero and the electricity used corresponds to 100% renewable energy

6. Save costs

  ·Google Cloud helps increase operational efficiency and optimize IT spending

  ·Google Cloud application migration can save up to 32% (compared to on-prem)

  ·Invoice versus project provide visibility into ROI of specific initiatives

7. Easy to use

  ·Google Cloud is easy to use and self-optimizing

  ·Designed to easily deploy large-scale cloud services

8. Industry solutions

  ·Improve efficiency and agility, reduce costs, and capture new market opportunities.

  ·From next-generation retail telehealth, Google Cloud creates customized solutions to address your biggest challenges.

  ·Companies like Netflix, P&G, and Target rely on our unique, industry-pioneering solutions, expertise, and partner network.
  
## Multi-Layer Security

For security we need know what is the type of service that we use.

  ·On-Premises: 100% responsibility for safety
  
  ·IaaS: Responsibility of the provider all the security of the hardware and its connectivity.
  
  ·PaaS: Responsibility of the provider all the security of users, accesses, authorizations.
  
  ·SaaS: The user is solely responsible for the access policies and content.
  
![image](https://user-images.githubusercontent.com/78567418/148403298-9f354b78-c649-4872-accd-9632fe0da68e.png)

### End-to-end security

  ·Images Bases Security
  
  ·Vulnerability Analysis (Of the dependencies that we have in the images)
  
  ·Binary authorization
  
  ·Shielded Containers
  
  ·Container Sandbox
  
  ·Container threat detection
  
  ·Standards, regulations and certifications

![image](https://user-images.githubusercontent.com/78567418/148403955-3436a41f-d554-4aff-8f63-bcc435b04932.png)

### Cryptographically secure identities

  ·User identity
  
  ·Device Identity
  
  ·Machine identity
  
  ·Service Identity
  
  ·Code identity
  
### Regulations and certifications

  ·Google Cloud contracts for financial institutions in Mexico address the requirements of the CNBV frameworks

  ·Google Cloud contracts for financial institutions in Argentina address the requirements of BCRA Communication A 6375.

  ·Google Cloud regularly undergoes several independent third-party audits for security, privacy, and compliance controls.
  
![image](https://user-images.githubusercontent.com/78567418/148404024-45950fe3-19b9-4944-bbbf-c24721c61644.png)

## Information encryption

1. All information on the hard drive is encrypted
2. Each hard disk only contains parts of the information of a message and never the complete original image

### Data Encryption keys

Keys generated to encrypt each individual part of an original message

### Key encryption Keys

Keys that can be generated by Google or by the owner of the information (in case of wanting to further increase security independently of google) and that they are used to encrypt the keys that encrypt the information.

### Flow of information

1. You send a file from your computer.
2. It reaches a point of presence, and no one can enter inside. All data is encrypted.
3. Arrives at the regional DC. Each hardware verifies that each request has an authentic identity.
4. Divide the file into multiple pieces. It is saved on different discs. That is why having a single disk is useless for having only fragments of the information.
5. Keys are generated to encrypt the files (Data Encryptions Keys).
6. Another key is created to encrypt the keys that encrypt the files. This can be created by Google or by the user.
7. To get the data, we need your IDs. The pieces are decrypted with their keys, joined and returned to the user.

## Billing accounts

They are the means of payment for expenses in GCP. They come in two varieties:

1.- You can have a self-service in which you pay for what you use without the need for a contract
2.- A contract is signed as a traditional service and payment requests are generated

_Payment Profile: _Here the credit card is stored and it is the one that it manages.

![image](https://user-images.githubusercontent.com/78567418/148462325-06f22629-41bb-4e28-8b94-4e478a3074fb.png)

Establish good practices:

1. Set the means of payment in the payment profile
2. Generate a billing account and link it to the organization
3. Export all data to big query

## Resources hierarchy

Map the organizational structure.
Manage at scale.
Separation.
Policy inheritance.

### Organization
It is the root of the resource hierarchy. This has several things assigned directly to the organization:

·The Billing Account is assigned to it.
·Administrator groups can operate on this node.
·The permissions that the entire organization must have can be assigned here, and inherited to the nodes below.

If we use Google Workspace, Google's SaaS (Software as a Service), identities are a way to authenticate users who belong to your organization and have access to your Google Cloud.

### Cloud identity

Cloud Identity allows us to generate users for Google Cloud without the need for Google Workspace. It gives us 50 identities at no cost.

A domain is linked to the organization to identify it.

![image](https://user-images.githubusercontent.com/78567418/148462696-c5241b01-00c0-4b8a-be15-4eff4fb3d8aa.png)

### Folders

Models the organizational structure with GCP (be it departments, teams, applications, workloads, life cycle, billing and security isolation).

Folders can contain projects and folders.

Being able to group the structures in folders allows us to:

·Limit access, create groups and give them permissions in a specific space.
·Discriminate costs, know how much a specific node costs me.

### Projects

They contain the computational resources. A project is a grouper of resources.

It is important to develop a project with a need in mind.

For example:

·CI / CD project
·Project of a Micro service
·Project for marketing site

#### Advantages of small projects:

·Easy maintenance
·More security
·Ease of Evolution

## Identity and access managment

Who is the member?

·A person.
·A subsystem (eg Application): this is known as a service account.

### Zero Trust / Zero Trust

We do not trust what is within our security perimeter automatically.

·Communications within the security perimeter are encrypted and come with permissions.
·We establish which applications can talk to which applications.
·We determine the type of resources that applications can generate.

### What can you do?

There is a very large taxonomy of related resources that you can do.

Resources have certain permissions assigned. In addition, the permissions allow actions to be taken on a resource:

·Generate a new one
·Modify it
·Delete it
·Make it update

### In which resource?

Security policies are assigned to each of the resources. In a policy we can establish the role of the members.

### Roles

Roles are a collection of detailed permissions that we assign to groups or user, frequently is better only make groups with permissions.

We can generate our own roles, but there are already several existing ones.

### Organization-level groups

![image](https://user-images.githubusercontent.com/78567418/148468411-759a00c9-b6e0-4251-962e-c41e8930118f.png)

#### Super Administrators

·Equal to Linux 

·Super user is a user with a lot of powers

#### Org. Admins

·Define IAM policies

·Determine the structure of the resource hierarchy

·Create projects until the organization is mature

![image](https://user-images.githubusercontent.com/78567418/148468640-fc92d02c-3581-4113-8d6f-9b2782c05e83.png)

#### Network Admins

·Create networks, subnets, network devices (cloud routers, cloud VPN, and cloud load balancers)

·Maintains firewall rules, unless maintained by security administrator

![image](https://user-images.githubusercontent.com/78567418/148468675-faf604f0-4254-4c19-bc78-6692c1a1374e.png)

#### Security Admins

·Set policies and restrictions for the entire organization, folders, and projects

·Set IAM roles for projects

·Maintains visibility of logs and resources

#### Billing Admins

·Set up a billing account

·Monitor resource usage

### Policy allocation and inheritance

It can be assigned at various levels: we can assign policies at the org level. folder, project and resource.
In addition to that they inherit the policy of the superior nodes.

### Structure

The structure is assigned to someone user and a folder.

`{
	"bindings": [                                                                                                                          
 		{  
 		"role": "roles/storage.objectAdmin",  
  		"members": [  
			"user:alice@acme.com",  
			"serviceAccount:my-other-app@appspot.gserviceaccount.com",      
			"group:admins@acme.com",      
			"domain:acme.com" ]
		},
		{
		"role": "roles/storage.objectViewer",	# rol
		"members": ["user:bob@acme.com"]	# who we assign role }
		]
}`

## GCP interacts through API

You can interact with GCP through 3 methods:

1. The web App
2. The mobile App
3. The CLI for the terminal

### Interact with CLI

In order to interact with the CLI from your local computer, you must install the GCloud application, which you can find here[here](https://cloud.google.com/sdk/docs/install), the steps are:

GCloud: https://cloud.google.com/sdk/docs/install

1. Select your operating system in which you are going to use it.
2. Download the version of your system, keep in mind that for Windows it is better to use the PowerShell option and download it directly by command line, Google provides the command.
3. After installing it, they initialize it with the command:
`gcloud init`

## Market place

Advantages

·Easy installation, save time.

·A single invoice is received from Google, even if the services are from third parties.

### It's an AppStore

·Is specialized in business software

·Shopping platform

### Marketplace Advantages

·It is easy to install

·One single invoice from Google

### How the MarketPlace works

·Has a large selection of software

·It is quoted through the list price or private negotiations (the client's price and its confidentiality are respected)
