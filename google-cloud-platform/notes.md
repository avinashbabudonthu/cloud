# Notes

# Overview of Google Cloud Platform - GCP 
* GCP has
	* 20 Regions
	* 61 zones
	* 134 network edge locations
	* available in 200+ countries and territories
	* Still expanding
	* For most recent updates on regions, locations etc refer [https://cloud.google.com/about/locations](https://cloud.google.com/about/locations)
	* 1537 (approximately) services
* Zone
	* Data center
	* High availability, reliability, redundancy
	* When application is launched we generally make it available in multiple zones to make application highly available
* Region
	* Collection of multiple data centers
	* 1 Region will have atleast 2 zones
* Network edge locations
	* Delivers static content to enhance user experience
	
# Building blocks of GCP
* Core
	* Compute
	* Storage
	* Network
		* Enables communication across multiple applications and services offered by google
* Databases
	* Sql
	* NoSql
* Data & Analytics
	* Business Intelligence and Data warehouse
* AI & Machine Learning
* Hybrid & Multi-cloud
* API Management
* Migration
	* To migrate work loads from on premises to cloud
* Security
* Devops Tools
* Management Tools
	* Services through which customers can interact and manage their deployments
![picture](pictures/building-blocks.jpg)

# Key GCP services
* Compute
	* Compute Engine - also called as `GCE(Google Compute Engine)`
		* IaaS - Infrastructure as a Service
		* Similar to AWS EC2
	* App Engine
		* PaaS
	* Kubernetes Engine. Also called `GKE - Google Kubernetes Engine`
		* CaaS - Container as a Services
	* Container Registry
		* Manages docker container images
	* Cloud Functions
		* Similar to AWS Lambda
* Storage and databases
	* Cloud storage
	* Cloud Bigtable
	* Cloud datastore
	* Cloud Sql
	* Cloud spanner
	* Persistent disk
* Network
	* Cloud virtual network
		* Hybrid and isolated network capabilities within the public cloud
	* Cloud load balancing
		* Routes the traffic across multiple instance of the application
	* Cloud CDN
	* Cloud interconnect
	* Cloud DNS
* Security & Identity
	* Cloud IAM
	* Cloud resource manager
	* Cloud security scanner
	* Cloud platform security
* AI & Machine Learning
	* Cloud machine learning
	* Vision API
	* Speech API
	* Natural language API
	* Translation API
	* Jobs API
* Devops tools - provides automation capabilities
	* Cloud SDK
	* Deployment manager
	* Cloud source repositories
	* Cloud tools for android studio
	* Cloud tools fo IntelliJ
	* Powershell cloud tools
	* Virtual studio cloud tools
	* Plugin for eclipse
	* Cloud test lab
* Management tools - provides insights to existing deployments
	* Stackdriver
	* Monitoring
	* Logging
	* Error reporting
	* Trace
	* Debuggger
	* Deployment manager
	* Cloud endpoints
	* Cloud console
	* Cloud shell
	* Cloud machine app
	* Billing app
	* Cloud APIs

# Other GCP services
* API analytics
* IOT core
* VPN
* AutoML
* Transfer appliance
* Beyond corp
* File store
* Memory store

# Get started with GCP
* Open url - [https://cloud.google.com/free](https://cloud.google.com/free)
* Click on `Get started for free` button
* We need to give credit card information for signup
* Google charges minimal amount on credit card and that will be refunded
* Once signup, we will be naviated to `Google cloud platform console`

# Set an alert on billing
* Click on menu icon on top left
* Click `Billing` link
* Click on `Budgets & alerts` link in left menu
* Click on `CREATE BUDGET` link
* Follow the instruction to create alert

# GCP platform resources
* Anything we lauch is creation of resource like
	* GCE VMs
	* Cloud pub/sub topics
	* cloud storage buckets
	* etc
* Reources belong to project
* In GCP project directly represents the billable unit. Any resource we launch is associated with project. Every resource under project is directly billed
* Projects may be organized into folders
	* We can have multiple projects under Dev, Test, Prod
* Each project can be associated with different credit card
* Folder may belong to one and only one organization. This is optional
* Organization is top level entity in GCP hierarchy
* Organization will be available only if we have `GSuite` account
* GCP resources hierarchy
![picture](pictures/gcp-resources-hierarchy.jpg)

# Interactive with GCP
* Web console
	* Front end GUI
* Cloud shell, cloud SDK
	* For devops engineers
	* comes with `CLI`
	* Cloud SDK can be installed in windows, linux, mac machines
	* Cloud shell is terminal built into the browser. Without installing anything we can quickly interact with GCP
* Mobile App
* REST API
![picture](pictures/interacting-with-gcp.jpg)

# Accesing GCP
* Interactive shell environment for GCP
* Accessible from web browser
* Comes preloaded with `IDE, gcloud SDK` and other tools
* Backed by GCE VM comes with 5 GB of disk storage