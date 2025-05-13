---
sidebar_position: 2
title: Zygote vs Public Clouds
---

> Properties and those inherit, are a decoration for an accessible life style. But the enduring and sound works are preferred at your sovereign for more reward and for hope."

The following table compares Azure services with Zygote features. It is not a complete list of Azure services! The goal is to show how Zygote is an alternative to public clouds by being efficient, cost-effective, and easy to use while respecting your sovereign. Actually adding more items to the list doesn't really change the conclusion. Zygote is a super strategy for the long term and also short term! The same conclusion could be with other cloud providers like AWS, GCP, and many others.

| Azure Service/Category | What is that? | What Zygote Offers instead? |
|-----------------------|-----------------------------|-------|
| Azure Virtual Machines | Like a computer you can use on the internet. | Use your laptop, and rent VMs/Metal from your local provider and your friends. SSH is the only thing needed for integration. |
| Azure Virtual Desktop | A desk and apps you can use on any computer. | Buy a laptop! Set it up with `z x`! Linux/MacOS and Windows (with WSL2) are supported on your Laptop. |
| Azure DevOps | Helps people work together to make apps. | Use `z y` to run repo pipelines locally and/or remotely. Z Yacht runs your local pipeline in Github Actions, for free!|
| Azure SQL | A place to store and organize lots of information. | Use `z q` for SQL IO. |
| Azure AI Services | Makes computers smart to understand things. | Package your ML functions in a container and deploy using `z_pod`. Use `z q` and/or `z c` for IO|
| Azure AI Foundry | A tool to build smart computer programs. | Use Python/Poetry to develop and test AI apps on your laptop and deploy using `z_pod` role and `Yacht` |
| Azure AI Content Safety | Keeps bad stuff away from apps and games. | Content is not safe! Unless produced by yourself and your network! Otherwise you only keep the most essential stuff away! |
| Azure Kubernetes Service (AKS) | Manages lots of app pieces working together. | Use `z_pod` over SSH |
| Azure Arc | Connects different computers to work as one. | Zygote is one. `zcore` runs anywhere! |
| Azure Local | Runs internet tools on your own computer. | `zcore` runs locally and/or remotely! |
| Azure Blob Storage | A big box to store pictures, videos, and files. | Use `z q` and`z c` for IO |
| Azure Active Directory (Azure AD) | Checks who you are to keep apps safe. | Use `z cert` to generate certs for client and servers|
| Azure Cosmos DB | A super-fast place to save and find app data. | `z q`, Add a new shard by incrementing `z_num_shards` |
| Azure Backup | Saves your stuff so you don’t lose it. | You can clone a node by having a copy of `z_backup_dir` after triggering a snapshot. `z q` and `z c`  |
| Azure Machine Learning | Teaches computers to learn like people. | Use Python/Poetry in your laptop and package in a Container. Deploy using `z_pod` |
| Azure AI Model Catalog | A library of smart tools for computers. | Use Python/Poetry in your laptop and package in a Container. Deploy using `z_pod`|
| Azure OpenAI Service | Makes computers understand and talk better. | Use any APIs |
| Azure AI Language | Helps computers understand words and sentences. | Use Open Source libraries or make one and don't limit your app to any API |
| Azure AI Vision | Helps computers see and understand pictures. | Find a proper ML library or be one |
| Azure AI Search | Finds things super fast on the internet. | Use APIs or create one |
| Azure Databricks | Helps look at big piles of information. | Run stuff using `podman` in your laptop. Develop your function then deploy using `z_pod`. Use `z q` and `z c` for IO. |
| Microsoft Copilot in Azure | A helper for making apps and solving problems. | Use through APIs. Don't limit yourself to a tool for solving a problem, make one if nothing is good enough. |
| Azure Cognitive Services | Gives apps brains to see, hear, and talk. | Use Python/Poetry in your laptop, handle the rest using `z` and `z_pod` |
| Azure Bot Service | Makes chatty robots for apps and websites. | Make it a container deploy using `z_pod`, use `z c` and `z q` for IO |
| Azure Anomaly Detector | Spots weird things in data to fix problems. | Find a Python library for this or make one |
| Linux Virtual Machines in Azure | Computers on the internet using Linux. | Don't limit yourself to a single source for computers, `zcore` runs anywhere using `ssh` |
| SQL Server on Azure Virtual Machines | A special computer for organizing information. | `z q`|
| Windows Server | Computers on the internet using Windows. | Build for the web! `z_core` and `blueprint` support Windows through WSL2. Add an NVMe to your machine and install Windows to play video games while you work on your next `z` project.|
| Azure Functions | Small app pieces that do one job at a time. | Being Boilerplateles is also "Serverless". Make a container out of your codebase using `z_container`, then deploy using `z_pod`.  |
| Azure Virtual Machine Scale Sets | Lots of computers working together when needed. | Use `z_node` to borrow nodes from various providers. |
| Azure Spot Virtual Machines | Cheap computers you use when available. | Any node running `z_core` is part of a zygote deployment. Doesn't matter where is the machine, when starts and when stops. |
| Azure Container Apps | Runs apps in small, easy-to-move packages. | Any app run by `Docker/Podman` could be deployed using `z_pod` |
| Azure Compute Fleet | Manages many computers at once. | It does! `zcore` is a cooperative system kernel for web! |
| Azure Batch | Runs big jobs on lots of computers at once. | Make a container for your function! Call it multiple times. Each time gets a chunk of work done. Use `z p` for pub/sub. |
| Azure CycleCloud | Organizes supercomputers for big tasks. | Use `z_pod` to deploy on specific hosts in case your function requires special devices |
| Azure App Service | A place to put your apps so everyone can use them. | `z_pod` your container |
| Azure Container Instances | Runs one app package at a time. | Use `z_container` to publish in Github packages. |
| Azure Spring Apps | Helps run special apps for businesses. | Make containers working with HTTP, use `z_pod` |
| Azure Red Hat OpenShift | Manages app packages with extra tools. | Use `podman` to package apps. |
| Azure Kubernetes Fleet Manager | Organizes many app groups working together. | Zygote apps find each other by trusting to the same CA. |
| Azure Container Registry | A storage place for app packages. | Github packages or such. |
| App Configuration | Sets up apps to work just right. | Use `z c` for app configs and keep a local copy in a container volume. |
| Azure Service Fabric | Builds big apps that work super well. | `z p` and `channels` |
| Azure Database for PostgreSQL | A special place to store app information. | Use `z q` |
| Microsoft Defender for Cloud | Protects computers from bad things. | Upgrade nodes regularly by adding one an removing an existing. Repeat this until all nodes are updated. |
| Azure IoT Edge | Connects smart devices to the internet. | Use `channels` |
| Azure Monitor | Watches computers to make sure they’re okay. | Deploy Prometheus exporters using `z_pod`. Use `tap` for explore.|
| Microsoft Sentinel | Looks for dangers to keep computers safe. | use `z log` |
| Azure Stack | Runs Azure tools on your own computers. | It is already run in your laptop and in your local datacenter! |
| Azure ExpressRoute | A super-fast internet connection for Azure. | Everyting is IP in Zygote |
| Azure VPN Gateway | A safe tunnel to connect your computers to Azure. | Use SSH with hardware token |
| Azure Database for MySQL | Another place to store app information. | `z q`|
| Azure Database for MariaDB | A special storage for app data. | `z q`|
| Azure Synapse Analytics | Looks at tons of information to find answers. | Use D3.js and `z q` to visualize time series. Deploy your React (or like) functions using `z_pod`. |
| Azure Databricks | Helps look at big piles of information. | Deploy a function to perform map/reduce over `z q`. Control using `z p`. Use pandas/numpy etc. |
| Microsoft Purview | Keeps track of information and keeps it safe. | Use `z vault` backed by security token. Setup using `x` |
| Azure Data Factory | Moves and organizes big amounts of data. | Use `z q` and Python in your laptop. Then deploy your notebooks in a container using `z_pod`|
| Microsoft Fabric | A tool to work with lots of information easily. | It is Zygote! |
| HDInsight | Looks at huge piles of data to find patterns. | Export everything to `z q`. Use Python. Deploy using `z_pod`. Split the work into chunks using `z p` |
| Azure Data Explorer | Finds answers in data really fast. | `z q` (SQL) and Python |
| Azure Data Lake Storage | A giant storage place for all kinds of data. | Query `z q` and `z c`! |
| Azure Operator Insights | Helps businesses understand their data better. | Export stuff to Prometheus. Use `tap` or your own visualizer to chart Prometheus-ed metrics |
| Azure Stream Analytics | Looks at data as it comes in, like a live show. | Deploy your notebooks using `z_pod` |
| Azure Event Hubs | Catches lots of messages for apps to use. | `z p` |
| Azure Virtual Network (VNet) | A private internet space for your apps. | Use `iptables` |
| Azure Load Balancer | Shares work between computers so they’re not too busy. | Use DNS for load balancing otherwise `zcore`'s reverse proxy. |
| Azure Application Gateway | Makes sure web apps work fast and safe. |`zcore` includes a reverse proxy and hits all incoming requests|
| Azure Front Door | Speeds up apps by sending them from nearby places. | Deploy front nodes where needed |
| Azure Content Delivery Network (CDN) | Makes videos and pictures load super fast. | `z q` to track files, where they are and should be. Deploy function using `z_pod` to backfill hosts. |
| Azure Traffic Manager | Sends people to the closest app server. | Zygote uses sql router to hit the closes. And use DNS routing with multiple front nodes. |
| Azure DNS | Helps people find your apps on the internet. | Deploy bind using `z_pod` or use third party|
| Azure Files | A shared folder for your apps to use. | `z q` and `z c` |
| Azure Queue Storage | Holds messages for apps to pick up later. | `z p` |
| Azure Table Storage | A simple place to store small bits of data. | `z q` |
| Azure Disk Storage | Hard drives for your internet computers. | `z q`|
| Azure Archive Storage | A cheap place to keep old files you don’t need often. | `z q` to track backups |
| Azure Pipelines | Automatically builds and sends out app updates. | Handle Github events in your container |
| Azure Repos | A place to save and share your app code. | Github etc. |
| Azure Boards | Helps teams plan and track their work. | Github projects |
| Azure Test Plans | Tests apps to make sure they work right. | Test in your laptop. Both your container and `yacht` plays |
| Azure Artifacts | Shares app pieces with your team. | `z_release` and `z_container` |
| Azure SignalR Service | Makes apps talk to users in real time. | Use Websocket and `channels`|
| Azure Key Vault | A safe to lock up passwords and secrets. | `z vault` and `z q` |
| Azure Security Center | Watches for dangers and keeps apps safe. | Upgrade frequently or keep going with specific version |
| Azure DDoS Protection | Stops bad guys from slowing down your apps. | `iptables` and DDoS protection at network level |
| Azure Bastion | A safe way to connect to your computers. | Use `z_nodes` to make a bastion and configure using `iptables`|
| Azure Logic Apps | Connects apps to work together smoothly. | They are! |
| Azure Service Bus | Sends messages between apps safely. | `channels` or `z p` |
| Azure Event Grid | Tells apps when something important happens. | `channels` or `z p` |
| Azure API Management | Controls and protects app connections. | Use Open API spec |
