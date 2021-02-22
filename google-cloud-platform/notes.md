# Notes

# Overview of Google Cloud Platform - GCP 
* GCP has
	* 20 Regions
	* 61 zones
	* 134 network edge locations
	* available in 200+ countries and territories
	* Still expanding
	* For most recent updates on regions, locations etc refer [https://cloud.google.com/about/locations](https://cloud.google.com/about/locations)
* Zone
	* Data center
	* High availability, reliability, redundancy
	* When application is launched we generally make it available in multiple zones to make application highly available
* Region
	* Collection of multiple data centers
	* 1 Region will have atleast 2 zones
* Network edge locations
	* Delivers static contact to enhance user experience
	
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
	* Services through which customers can interact and manager their deployments
![picture](pictures/building-blocks.jpg)

# Key GCP services
* Compute
	* Compute Engine 
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