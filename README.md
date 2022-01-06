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

·Speed to Market

