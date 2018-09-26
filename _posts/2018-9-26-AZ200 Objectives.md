---
layout: post
title: AZ-200 Exam Objectives 
---

After digesting the recently published Azure certification changes, I've decided that I'll gain more benefit from pursuing the [Azure Developer Associate](https://www.microsoft.com/en-us/learning/azure-developer.aspx) track than upgrading to [Azure Administrator via AZ-102](https://www.microsoft.com/en-us/learning/exam-AZ-102.aspx).  

As Azure is such a moving target, I've found that instructional videos or pdfs tend to becomes obsolete far too quickly to be a reliable source of study.  The best thing to do is simply take a list of the published exam objectives, go through each one in turn and find the current Azure documention that's applicable to each.

With that in mind, here's a list of all current (beta) objectives for both exams that make up the Azure Developer track. Once I begin studying, I'll start to hunt down the current docs and training for each objective and start adding hyperlinks to the list.

For now, I've still got quite a bit of work ahead progressing through some of [Bob Tabor's .Net series](https://www.devu.com/curriculum)!

# **[AZ-200: Objectives](https://www.microsoft.com/en-us/learning/exam-AZ-200.aspx)**

# *1. Select the appropriate cloud technology solution (15-20%)*

### Select an appropriate compute solution

* leverage appropriate design patterns
* select appropriate network connectivity options
* design for hybrid topologies

### Select an appropriate integration solution

* address computational bottlenecks, state management, and OS requirements
* provide for web hosting if applicable
* evaluate minimum number of nodes

### Select an appropriate storage solution

* validate data storage technology capacity limitations
* address durability of data
* provide for appropriate throughput of data access
* evaluate structure of data storage
* provide for data archiving, retention, and compliance

# *2. Develop for cloud storage (30-35%)*

### Develop solutions that use storage tables

* connect to storage
* design and implement policies to tables
* query a table storage by using code

### Develop solutions that use Cosmos DB storage

* choose a consistency level
* choose appropriate API for Cosmos DB Storage
* create, read, update, and delete tables in Cosmos storage by using code
* manage documents and collections in Cosmos DB Storage

### Develop solutions that use file storage

* implement quotas for File Shares in storage account
* move items in file shares between containers asynchronously
* set file storage container properties in metadata

### Develop solutions that use a relational database

* create, read, update, and delete database tables by using code
* implement dynamic data masking

### Develop solutions that use blob storage

* create a shared access signature for a blob
* move items in blob storage between containers asynchronously
* set blob storage container properties in metadata

### Developing for caching and content delivery solutions

* develop for Azure Redis cache, storage on Content Delivery Networks (CDNs)
* develop code to address session state and cache invalidation

# *3. Create Platform as a Service (PaaS) Solutions (35-40%)*

### Create web applications by using PaaS

* create an Azure app service web app by using Azure CLI, PowerShell, and other tools
* create documentation for the API by using open source and other tools
* create an App Service Web App for containers
* create an App Service background task by using WebJobs

### Create mobile apps using PaaS

* add push notifications for mobile app
* enable offline sync for mobile app
* implement a remote instrumentation strategy for mobile devices

### Create an app service Logic App

* create a custom connector for Logic Apps, a custom template for a Logic App
* create a Logic App
* package an Azure App Service Logic App

### Create app or service that runs on Service Fabric

* develop a stateful Reliable Service and a stateless Reliable Service
* develop an actor-based Reliable Service
* write code to consume Reliable Collections in your service

### Create serverless functions

* implement the bindings for the function (input and output)
* implement the function trigger by using a data operation, timer, webhook, or other tools
* develop an Azure Function app for containers by using Azure Portal, CLI, and other tools
* develop an Azure Service Fabric Mesh App

### Schedule bulk operations

* define the batch output and conditions by using Batch Service API
* write code to run a batch job
* run a batch job by using Azure CLI, Azure Portal, and other tools

### Create solutions that use Azure Kubernetes Service

* configure diagnostic settings on resources
* create a container image by using a Docker file
* create an Azure Container Service (ACS/AKS) cluster by using the Azure CLI and Azure Portal
* publish an image to the Azure Container Registry
* implement an application that runs on an Azure Container Instance
* implement container instances by using Azure Container Service (ACS/AKS), Azure Service Fabric, and other tools
* manage container settings by using code

### Design and develop applications that use media services

* implement an application using Video Indexer, Video API, Preview, and other media related services
* implement file-based encoding and Azure Media Analytics
* develop media solutions that use AI services (e.g., content moderation, optical character recognition, video summarization, face detection, etc.)

# *4. Secure cloud solutions (15-20%)*

### Implement authentication

* implement authentication by using certificates, forms-based authentication, tokens, Windows-integrated authentication
* implement multi-factor authentication by using Azure AD options

### Implement access control

* implement Claims-Based Access Control (CBAC) and Role-Based Access Control (RBAC) authorization

### Implement secure data solutions

* encrypt and decrypt data at rest
* encrypt data with Always Encrypted
* implement Azure Confidential Compute and SSL/TLS communications
* manage cryptographic keys in the Azure Key Vaullt
# ***[AZ-201 Objectives](https://www.microsoft.com/en-us/learning/exam-AZ-201.aspx)***

# *1. Develop for an Azure cloud model (50-55%)*

### Develop for asynchronous processing

* implement parallelism, multithreading, processing, durable functions, Azure logic apps, interfaces with storage, interfaces to data access, and appropriate asynchronous compute models

### Develop for autoscaling

* implement autoscaling rules and patterns (schedule, operational/system metrics, code that addresses singleton application instances, and code that addresses transient state

### Develop long-running tasks

* implement large-scale, parallel, and high-performance apps by using batches
* implement resilient apps by using queues
* implement code to address application events by using web hooks
* address continuous processing tasks by using web jobs

### Implement distributed transactions

* identify tools to implement distributed transactions (e.g., ADO.NET, elastic transactions, multi-database transactions)
* manage transaction scope
* manage transactions across multiple databases and servers

### Enable search of textual content

* create an Azure Search index by using code, Azure Portal, etc.
* import searchable data by using code, Azure Portal, etc.
* query the Azure Search index by using code

### Instrument an app or service and implement logging

* configure instrumentation in an app or service by using Application Insights and other tools
* configure logging service by using Application Insights, Azure Alerts, Azure Dashboards, Metrics Explorer, and other tools (e.g., ELK)

# *2. Implement cloud integration solutions (25-30%)*

### Manage APIs by using API Management (APIM)

* analyze recommendations on security center
* create an APIM instance
* configure authentication for APIs
* create an API gateway
* define policies for APIs

### Configure a message-based integration architecture

* configure an app or service to send emails, Event Grid, and the Azure Relay Service
* create and configure a Notification Hub, an Event Hub, and a Service Bus
* configure queries across multiple products
* configure an app or service with Microsoft Graph

### Develop an application message model

* create a message schema and a message exchange
* create and configure a Notification Hub, an Event Hub, and a Service Bus
* create an event model
* create topics and subscriptions

# *3. Develop Azure Cognitive Services, Bot, and IoT solutions (20-25%)*

### Integrate Azure Cognitive Services in an application

* develop solutions by using intelligent algorithms that identify items from images and videos
* develop solutions by using intelligent algorithms related to speech, natural language processing, Bing Search, and recommendations and decision making

### Create and integrate bots

* create a bot by using the Bot Framework
* create a natural language conversation flow
* manage bots by using the Azure Portal
* register a bot by using the Bot Framework

### Create and implement IoT solutions

* configure Azure Time Series Insights
* configure Stream Analytics service for inputs and outputs
* establish bidirectional communication with IoT devices by using IoT Hub
* register devices with IoT Hub Device