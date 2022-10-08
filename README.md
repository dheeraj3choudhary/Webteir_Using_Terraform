# Webteir_Using_Terraform
Provision Application Web Teir on AWS Using Terraform

Welcome back to the series of **Deploying On AWS Cloud Using Terraform** 👨🏻‍💻. This terraform usecase is created for DevOps - Infrastructure Automation on AWS Project.
Based on our previous learnings from last 9 blogs series we are going to create a real time basic web application teir to have some handons and understand how its implementation works in realtime.

If you are a beginner for Terraform and want to start your journey towards infra-as-code developer as part of your devops role, buckle up 🚴‍♂️ and lets get started and understand core Terraform concepts by implementing it...🎬 

### ❗️❗️Pre-Requisite❗️❗️


## 🔎Basic Terraform Configurations🔍
As part of basic configuration we are going to setup 3 terraform files  
1.  **Providers File**:- Terraform relies on plugins called "**providers**" to interact with cloud providers, SaaS providers, and other APIs.  
Providers are distributed separately from Terraform itself, and each provider has its own release cadence and version numbers.  
The [Terraform Registry](https://registry.terraform.io/browse/providers) is the main directory of publicly available Terraform providers, and hosts providers for most major infrastructure platforms. Each provider has its own documentation, describing its resource types and their arguments.  
We would be using [AWS Provider](https://registry.terraform.io/providers/hashicorp/aws/latest/docs) for our terraform series. Make sure to refer Terraform AWS documentation for up-to-date information.  
Provider documentation in the Registry is versioned; you can use the version menu in the header to change which version you're viewing.
