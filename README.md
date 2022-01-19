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

# Google Cloud Storage

It is an object storage service, an object is an immutable piece of data identified by an object name.
A bucket is a container for objects.

Calculator: https://cloud.google.com/products/calculator 

### Main features

·Unified experience
·Consistent carbonated listing
·Geo - redundant
·Scalable to exabytes

## Cloud Storage uses

·Content storage and delivery: Images or videos.
·Computing, analytics and ML: Large volumes of information and using the Cloud
Dataproc to analyze that information.
·Backups and archiving: Backups of databases, virtual machines, information systems, etc.

## Typical structure

Objects are associated with Buckets. Buckets are related to projects and projects are associated with an Organization.

## Security

·We can manage access to objects within Cloud Storage.
·100% of the objects in Cloud Storage are encrypted all the time; both at rest and in motion.
·Retention capacity; the amount of time we guarantee storing an object.
·Version control, like git, we can "rewrite" the objects with the new version of them and keep the history of each change.

## Encryption

Flexible control when encrypting data.

·Default: Google manages the keys transparently.
·Customer-managed (CMEK): You manage your keys in Google Cloud KMS.
·Customer-supplied (CSEK): Store your keys outside of Google Cloud.

## Use Cloud Storage

We can develop our tools to interact with Cloud Storage.

·From our programs.
·Build our libraries.
·Refuse the libraries that Google offers us.

### Tools that already exist to use Cloud Storage:

·Cloud Console
·gsutil

## Create a bucket

with gsutil:

It is suggested to put the Bucket that is associated with the project, so that it is easy to locate. The name of the Bucket must be unique.

·Create a Bucket(`make Bucket`)
`gsutil mb gs://my-project-bucket-01`

·See my busckets
`gsutil ls`

·See objects in a bucket
`gsutil ls gs://my-project-bucket-01`

·Copy objects to a Bucket
`gsutil cp ./file.txt gs://my-project-bucket-01`

·Copy objects of a Bucket to other site
`gsutil cp gs://my-project-bucket-01/file.txt`

·Activate control version in objects of a Bucket
`gsutil versioning set on gs://my-project-bucket-01`

·Deactivate control version in objects of a Bucket
`gsutil versioning set off gs://my-project-bucket-01`

## Cloud Storage storage classes

When creating a Bucket we must define the location and class.

### Location

Define where our data will reside.

#### Location types

1. Regional: The data is replicated in the zones of a single region. For frequently accessed data within a region.
2. Dual-regional: The data is replicated in nearby regions. For availability of frequently accessed data in a specific area.
3. Multi-regional: The data is replicated in different regions (continents). For the highest availability of frequently accessed data.

## Classes

They refer to the frequency with which we access and the availability we want on the objects within the bucket. Besides the price.

1. Standards: Objects that we access frequently (more expensive).
2. Nearline: Access to objects once a month.
3. Coldline: Access to objects once a quarter.
4. Archive: Access to objects once a year.

## Classes vs. Location

We can combine classes with different locations, according to our needs.

## Create a bucket

1. Select the Cloud Storage option from the hamburger menu.
2. Click on "Create Bucket".
3. Give a unique name to the "bucket" (you can prefix the name of the project) and Continue.
4. Select where it will be stored (Multi-Region, Dual Region or Region) and Continue.
5. Select the storage class (Standard, Nearline, Coldline, Archive) and Continue.
6. Select access control (Uniform, Fine-grained) and Continue.
7. Choose the Advanced Configuration you need (Encryption, retention policy, etc.).
8. Click on the CREATE button.

### Create a bucket Standar on console

We created a Standard Multi-region Bucket in the US. Access to the public was provided and uniform access was chosen. Finally we select a retention of 10 years. This in gsutil would look like this:

`gsutil mb -c standard -l us --pap enforced -b on --retention 10y gs://gemb-platzi-storage-bucket-01`

Where:

-c is the class

-l is the type of location we want

--pap specifies public access

-b is to enable uniform access

Advanced:

--retention is the retention period of the resource.

## Google Cloud Bigtable

Cloud Bigtable is Google's NoSQL Big Data database service, fully managed at the patabyte scale for use cases where low-latency random data access, scalability, and reliability are critical.

When to use SQL: When you already know the number of users you are going to have and you are not going to have accelerated growth, you plan to grow.

When to use NoSQL: When the database is very large, the peaks are very high and the growth is very accelerated.

Cloud Bigtable is a NoSQL database service that advances to Petabytes if necessary

### Features

·High processing

·Low latency processing

·Very large amounts of data

·Resize without downtime

·Flexible and automated replication

·Google Search, Maps and other Google products

### How do we interact with the Cloud Big Table?

·Application api: We can read and write data through a service layer called network Hbase, which is an open code manager that helps us expose the point provided by these operations of writing, reading, updating and deleting and this is normally used to send data to applications or dashboards

·Streaming / Transmission: Datflow Streaming, Saprk Streaming and Apache Storm

·Batch Processing: Data can be read and written to Big Table in batch form (large quantities) this can be done through hadoop, Datflow, Apache Spark.

### Google Cloud Bigtable in action

In this class we create a Bigtable instance with the name `quick-start-instance`, id `quick-start-instance` and cluster `id quickstart-instance-c1`. The drive type was single node SSD. Finally the region was `us-east1` and the zone `us-east1-c`.

From the CLI we can create our instance using the `cbt` tool, the command to create the instance of this class would look like this: 

`cbt createinstance quick-start-instance "quick-start-instance" quickstart-instance-c1 us-east1-c 1 SSD`

Where:

·`quick-start-instance` it´s id
·`"quick-start-instance"` ït´s name
·`quickstart-instance-c1` it´s id of cluster
·`us-east1-c` it´s region
·`1` number of nodes
·`SSD` type of disk

### Steps of Google Cloud Bigtable

Commands steps: 

o We associate our instance to my cloud Shell profile to send command and to which database
• `Echo Project = 'gcloud config get-value project'> ~ / .cbtrc`
• `Echo instance = instancename >> ~ / .cbtrc`

o We create a table
• `Cbt createtable my-table`

o We authorize the Shell to interact with the api
• `Cbt ls`

o Let's add a column family or add columns
• `Cbt createfamily my-table cf1 // family name1`
• `Cbt ls my-table`

o We enter data in the table
• `cbt set my-table r1 cf1: c1 = test-value`
• `cbt read my-table`

## Cloud SQL

This is the managed Relational Database service. It can be MySQL, PosgreSQL and SLQ Server.

If you need more performance, it can be scaled vertically (a more powerful machine).
If more availability is required, a two-zone architecture can be chosen.

### Features

· Fully managed

· An integrated solution: They can be accessed from anywhere.

· Reliable: It is easy to configure replicas, backups and activate the Failover process (replace an instance when it fails).

· Easy Migrations to CloudSQL: Database Migration Service helps to migrate DBs on premise to the Cloud easily.

In this type of database we carry out transactions and they must comply with ACID principles.

·Atomicity: Ensures that all operations carried out in a transaction, and otherwise that it is possible to return to the previous state (rollback).

·Consistency: Ensures that all transactions are successful, the data must make sense.

·Isolation: It dictates that the operations are isolated and transparent, that is, multiple operations occur independently and without being affected.

·Durabilty: It ensures that the result of an operation remains even when there was an error.

## Cloud spanner in action

### Features.

·Relational database designed for any scale

·Availability five 9 (99.999%)

·Automatic fragmentation.

### Create instance from gcloud CLI

In this class we create a Cloud Spanner instance named `example-db`, regional and in central US. Besides that we occupy only 1 node.

To create said instance using `gcloud` we use the following command:

`gcloud spanner instances create example-db --config=regional-us-central1 --nodes=1`

### Create database from gcloud CLI

To create a database called `example-db-db` in our `example-db` instance we use the command:

`gcloud spanner databases create example-db-db --instance=example-db`

### Create a schema from gcloud CLI

`cloud spanner databases ddl update example-db-db \
--instance=example-db \ 
		--ddl='CREATE TABLE Singers ( 
				SingerId INT64 NOT NULL, 
				FirstName STRING(1024), 
				LastName STRING(1024), 
				SingerInfo BYTES(MAX) 
				) PRIMARY KEY (SingerId)'`
				
### Insert data to our DB from gcloud CLI

To insert a single record:

`gcloud spanner rows insert --database=example-db-db \  
--instance=example-db \
--table=Singers \  
--data=SingerId=1,FirstName=Marc,LastName=Richards`

### Update data in our DB with gcloud CLI

To update a single record:

`gcloud spanner rows update --table=Singers --database=example-db-db --instance=example-db \ 
--data=SingerId=1,SingerName=Will`

### Delete data in our DB with gcloud CLI

To delete a single record: 

`gcloud spanner rows delete --table=Singers --database=example-db-db \ 
--instance=example-db --keys=1`

### Reed data from SQL

To query our records:

`gcloud spanner databases execute-sql example-db-db \ 
--instance=example-db \
--sql='SELECT * FROM Singers'`

![image](https://user-images.githubusercontent.com/78567418/149233133-f1b6419f-c278-4ccd-a4ae-dc133d361d17.png)

## Firestore

BigTable is a NoSQL Database of type Key-Value (key-value), while Cloud Firestore is a NoSQL Database of documents

** Document ** = Set of data associated with the same concept
Example: Product, Note, Player.

Collection: Set of documents.

### Cloud Firestore

·Serverless

·Real time

·Offline support

#### Characteristics:

·Scalable

·Trustworthy

·Flexible

·Available

·Transactional

#### Some use cases can be:

·User profile management

·Real time inventories

·State changes

·Data synchronization

## Firestore in action

In this class we create an instance of Firestore in Native Mode, located in us-east4.

Using the following command we can create a Google Cloud Firestore Native database:

`gcloud firestore databases create --region=us-east4`

To create a document csv:

`node TestDocument 5`

Where:

·node: references to document

·TesteDocument: references to name's document

·5: references number of document for create

To use document:

`node importTestDocument "name of csv created"`

When we import document this apper on Firestore Data.

## Comparative of different types of storage

![image](https://user-images.githubusercontent.com/78567418/149354427-d0d0d487-c03b-476e-a04a-efac8ba88ffd.png)

## Google belives

Google believes that in the future all companies regardless of their size or sector will differentiate themselves from their competitors through technology, mostly in the form of software. And the best software is all about data. Thus, each one will become a data company, if it is not already.

# Project Google Photos

Our Google Photos Clone project will have the 3 essential functionalities of this famous app:

1. Store the photographs so that they are safeguarded.
2. Recognize what is inside a photo.
3. Being able to find photos through natural language searches.

What I want to tell you with this is that if you take photos of anything with your cell phone, that photo will be saved in the cloud. And to find it, you just have to write in a search engine some word (s) that describe what is in the photo.

To create this you will not need to code the application. The code, written in Python with Flask, I will share it with you within the classes in a GitHub repository. What we will do in this series of courses is to create the base infrastructure to run this app from the cloud with the essential characteristics mentioned.

![image](https://user-images.githubusercontent.com/78567418/149415740-0c5fafb7-c687-4700-8aef-e03801f988a0.png)

You can upload photos and save them in the cloud, so that later you can search for them with a single word in English using cloud storage technologies and artificial intelligence such as computer vision and natural language processing.

![source](https://user-images.githubusercontent.com/78567418/149415908-5c70ca42-7334-4868-9dcb-a51f1c8c4fa7.gif)

## First steps

1. Go Console.
2. Search Manager Resources.
3. Create a project.
4. Select Project.
5. Go home.

## Cloud storage

1. Search Cloud Storage.
2. Select Create bucket.
3. In storage class select Standard.
4. Go browser storage.
5. Select bucket created.
6. Go permissions.
7. Delete public access.
8. Create a user like all-user.
9. Define to all-user permission to only read/view.

# Virtual Private Cloud(VPC)

It is a way of establishing connectivity between the resources we have in the cloud.

Virtual, isolated and private network environment that is based on the concept of a software-defined network.

There is a private global network (has global reach). In other words, it allows us to connect all our resources to the VPC regardless of the region they are in.

## Subnets

VPCs are made up of subnets. A VPC must have at least one subnet.

Subnets are regional in scope. That is, we can connect resources that are in different zones of a region using the subnet.

Subnets have associated IP ranges, they are used to assign private IPs to the resources that are associated with the subnet.

## VPC types

·Default: Create a subnet in all GCP regions, create some firewalls

·Auto Mode: Similar to the previous one but it is expandable to /16.

·Custom Mode: Does not create subnets by default, you have full control of the IPs. Expandable to any size RFC 1918

## Ilustration

![image](https://user-images.githubusercontent.com/78567418/150156945-548fbeeb-2e20-4750-88cf-78ebfd05bd3b.png)

## Subnet ranges

When a subnet is created, its main range of IP addresses must be defined.

The main internal addresses for resources (VM instances, internal load balancers, and internal protocol forwarding) are from the main range of the subnet.

### Limitations

·The main IP range of the subnet can be expanded, but not replaced or reduced, after the subnet has been created.

·You can remove and replace a subnet's secondary IP address range only if no instances are using that range.

·The minimum size of the primary or secondary range is eight IP addresses. Which means, the longest subnet mask you can use is /29.

·Valid ranges can be found here.

## VPC in action

Recomendation: VPC default is not recommended in production because we have less control when the IP range is generated, which means we have less control over some of the traffic that is sent to endpoints with the same reference IP

## Capacities 

![image](https://user-images.githubusercontent.com/78567418/150158950-0b974f70-1805-48b6-928a-e04cfe2ccfc5.png)


## About Cloud NAT

It is a software-defined distributed managed service. It does not rely on proxy devices or virtual machines.

Cloud NAT configures the Andromeda software that powers our VPC to provide source network address translation (source NAT, or SNAT) for virtual machines without external IP addresses. It also provides Destination Network Address Translation (Destination NAT or DNAT) for established incoming response packets.

### Profits

·Security: You can reduce the need for individual virtual machines so that each one has external IP addresses. Subject to outbound firewall rules, VMs without external IP addresses can access destinations on the Internet. For example, you might have virtual machines that only need Internet access to download updates or complete provisioning.

·Availability: Cloud NAT is a software-defined distributed managed service. It is not dependent on any virtual machines in your project or a single physical gateway device. Configures a NAT gateway on a Cloud Router, which provides the control plane for NAT and contains configuration parameters that you specify. Google Cloud runs and maintains processes on the physical machines running your Google Cloud VMs.

·Scalability: Cloud NAT can be configured to automatically scale the number of NAT IP addresses you use, and supports VMs that belong to managed instance groups, including those with autoscaling enabled.

·Rendimiento: Cloud NAT no reduce el ancho de banda de la red por VM. Cloud NAT es implementado por la red definida por software Andromeda de Google.

## Net services

![image](https://user-images.githubusercontent.com/78567418/150170871-dfc18ca9-1b8c-4a42-a74a-cf144ffdf5fe.png)

## VPC peering 

![image](https://user-images.githubusercontent.com/78567418/150173002-dcd2eb04-c238-4a52-9905-f55dbc6bde0f.png)

## Shared VPC

Centrelaize communicxation and simplify system

![image](https://user-images.githubusercontent.com/78567418/150173178-3ff03929-c2c9-4a94-8eff-15b97ca3d60e.png)

## Rules Firewall

![image](https://user-images.githubusercontent.com/78567418/150173451-88117f69-e4c4-41ad-bdd5-aee4802f3d6b.png)

### Rules implicite

![image](https://user-images.githubusercontent.com/78567418/150173985-54982763-f32f-40f4-9bb1-ffac91c01e88.png)

## Cloud Computing

·Cloud computing services must be a service on demand / self-service, be able to enter a browser to the provider's page and consume the resources that are needed.

·All access to cloud services must be through a network, usually the internet.

·The cloud provider's physical services are shared among its customers.

·The elasticity, to increase the computing capacity of the applications, is fast.

·Payment is only for what is used.

### Compute Engine (Infrastructure as a Service)

·General purpose and optimized Virtual Machines (VMs).

·Preemptible VMs (virtual machine on maximum 24 hours, can be turned off earlier, the advantage is that they generate significant cost savings).

·Pay per second / Sustained usage discounts.

·Live Migration.

·Sizing Recommendations.

·Predefined and customizable machine types.

