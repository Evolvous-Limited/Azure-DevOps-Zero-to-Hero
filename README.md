# AzureDevOps-Zero-to-Hero with real-time projects

Welcome to our comprehensive course on Azure DevOps, where we'll dive deep into concepts, demos, and real-time projects to help you master Azure DevOps and bolster your DevOps skills.
**This playlist will be published on a YouTube channel and is free for anyone to use and follow.**

(https://www.youtube.com/watch?v=A_N5oHwwmTQ&list=PLl4APkPHzsUXseJO1a03CtfRDzr2hivbD&pp=iAQB)

Refer to my blog <a href="https://dev.to/ibrahimsi/azure-devops-zero-to-hero-47j6/"><img src="https://github.com/Ibrahimsi/Test-Azure/assets/41462796/fd84882c-f257-4c6b-a1c8-b7eca5c78465" height="60px"></a></img></a>


### Day 1: Introduction to Azure DevOps and Basic Concepts 🌟
**Status**: Check out 👉 [Day1](https://github.com/Ibrahimsi/Azure-DevOps-Zero-to-Hero/tree/main/Day1) 👈 folder for notes and useful links ✅

- What is Cloud Computing
- IaaS VS PaaS VS SaaS
- What is a Shared Responsibility Model
- What is a Traditional Build and Deployment workflow
- What is a Waterfall model in SDLC
- Problems with the traditional software development life cycle (SDLC)
- What is Agile, and how does it solve the above challenges 
- What is DevOps and Why It Matters
- What is CI/CD
- What is Azure DevOps and a quick walkthrough
- Creating an Azure DevOps Organization
- Creating an Azure DevOps Project
- Azure DevOps Pricing
- Azure DevOps hosting options: Azure DevOps Services VS Azure DevOps Server

### Day 2: Azure Boards and Agile Project Management 📊
**Status**: Check out 👉 [Day2](https://github.com/Ibrahimsi/Azure-DevOps-Zero-to-Hero/tree/main/Day2) 👈 folder for notes and useful links ✅

- What are Azure DevOps Boards 
- What are Azure board processes, agile, scrum, basic, and CMMI
- Managing work items in Azure boards
- Azure board implementation using basic process
- Working with teams, areas, and iterations
- Filters in backlogs and boards
- Azure board implementation using the scrum process
- Sprint planning and capacity planning
- Product backlog and taskboard
- Customizing Kanban boards
- Customizing dashboards
- Work item query
- Customizing team process

### Day 3: Mastering Git and Source Control in Azure DevOps 🌿
**Status**: Check out 👉 [Day3](https://github.com/Ibrahimsi/Azure-DevOps-Zero-to-Hero/tree/main/Day3) 👈 folder for notes and useful links ✅

- Introduction to Source Control and Azure Repos
- Git vs TFVC
- Configure Visual Code
- Cloning the repo
- Commit changes
- Reviewing history
- Working with branches
- Tagging a release
- Managing repository
- Managing Pull requests
- Sample application code

### Day 4: Build Pipeline 🚀
**Status**: Check out 👉 [Day4](https://github.com/Ibrahimsi/Azure-DevOps-Zero-to-Hero/tree/main/Day4) 👈 folder for notes and useful links ✅


#### Note: For the demo, We will be using the YouTube Clone website 

- Provision Azure App Service to host the website.
- Creating Build Pipelines using the classic editor
- Creating build pipeline using YAML
- YAML pipeline structure, the difference between jobs, stages, steps, and tasks
- Creating a multi-stage CICD pipeline
- variables, triggers, Build properties, agents
- Publishing and Download Build Artifacts


### Day5: 🚀 Continuous Delivery with Azure DevOps Release Pipeline
**Status**: Check out 👉 [Day5](https://github.com/Ibrahimsi/Azure-DevOps-Zero-to-Hero/tree/main/Day5) 👈 folder for notes and useful links ✅

#### Note: this is a continuation of the previous blog.

- Automating Deployment with a multi-stage Release Pipelines
- Continuous Deployment Triggers
- Continuous delivery using deployment slots to enable **Blue-Green deployment**
- Deployment gates such as Query Work Items and Approvals before the prod deployment
- Update the code to test the entire CICD process with the Build and Release pipeline


### Day 6: Azure Test Plans and Testing 🧪
**Status**: Check out 👉 [Day6](https://github.com/Ibrahimsi/Azure-DevOps-Zero-to-Hero/tree/main/Day6) 👈 folder for notes and useful links ✅

#### Note: We will be using the Youtube Clone website to implement the below steps
- Azure Test Plan Overview
- Features of Azure test plan
- Managing Test Plans, Suites and Cases
- Subscribe to the test plan free trial
- Authoring, Running, and Analyzing Manual Tests
- Azure Test and Feedback extension

### Day 7: Basic Project Artifacts with Azure Artifacts 📦
**Status**: Check out 👉 [Day7](https://github.com/Ibrahimsi/Azure-DevOps-Zero-to-Hero/tree/main/Day7) 👈 folder for notes and useful links ✅

#### Note: In this blog, We will use a ✔ Nike Landing page as a sample application for CICD using Azure Artifacts

- Overview of Azure Artifacts
- Create the Azure DevOps project and check out the application code
- Set up the infra using Azure Web App
- Create Azure Artifacts feed to host the packages
- Create the CI pipeline that builds the package and pushes it to the feed
- Create the CD pipeline that consumes the package
- Promote the package to trigger the release pipeline
- Upstream packages in Azure Artifacts

### Day 8: Infrastructure as Code (IaC) with Terraform and Azure DevOps🚀

**Status**: Check out 👉 [Day8](https://github.com/Ibrahimsi/Azure-DevOps-Zero-to-Hero/tree/main/Day8) 👈 folder for notes and useful links ✅

- Introduction to IaC and Tools
- Various Terraform commands and workflow
- Creating Terraform configuration files
- Setting up terraform backend with Azure storage
- Executing Terraform commands using CLI
- Azure DevOps CI Pipeline to init, plan, and archive the plan file
- Azure DevOps CD pipeline to apply the changes


### Day9: Self Hosted agents 👨‍🔧 on Azure Virtual machine scale sets 🧑‍💻

**Status**: Check out 👉 [Day9](https://github.com/Ibrahimsi/Azure-DevOps-Zero-to-Hero/tree/main/Day9) 👈 folder for notes and useful links ✅

- Microsoft-hosted vs. self-hosted agents
- Use case of self-hosted agents
- Ways to setup self-hosted agents: VM, VMSS, container
- What is a Virtual machine scale set
- Set up a self-hosted agent using VMSS
- Register the agent on an agent pool
- Install custom utilities on the agent
- Use the self-hosted agent on a pipeline
- Comparison between self-hosted and Microsoft-hosted agents
- work folder walkthrough on agent

### Day 10 Managing Containers with Azure DevOps
**Status**: Check out 👉 [Day10](https://github.com/Ibrahimsi/Azure-DevOps-Zero-to-Hero/tree/main/Day10) 👈 folder for notes and useful links ✅

- What is a container
- Understanding Virtual machine V/s Containers.
- Challenges with the non-containerized applications
- Docker Architecture
- Containerize a sample To-Do list web app written in React JS.
- Benefits of a multi-stage docker file
- What are Azure container instances(ACI)
- Azure DevOps CICD Pipeline to deploy to ACI


### Day 11  Implementing end-to-end CI/CD using Azure DevOps on Kubernetes.
**Status**: Check out 👉 [Day11](https://github.com/Ibrahimsi/Azure-DevOps-Zero-to-Hero/tree/main/Day11) 👈 folder for notes and useful links ✅

- Basic Introduction of Kubernetes and its benefits
- Kubernetes Architecture
- What is the control plane and its components
- What are Nodes and types of Nodes
- What is a Pod/Deployment/Service
- Azure DevOps CICD Pipeline for a web app running on Kubernetes
- Sample application: My Health Care - Microservices-based Healthcare management app


  
### Day 12  Security and Permissions in Azure DevOps 🔐
**Status**: Check out 👉 [Day12](https://github.com/Ibrahimsi/Azure-DevOps-Zero-to-Hero/tree/main/Day12) 👈 folder for notes and useful links ✅

- Enabling advanced security in Azure DevOps
- Dependency Scanning
- Secret scanning and managing alerts
- How to use secrets in your pipeline
- Code scanning for vulnerabilities
- Sample Application: My Health Care - Microservices-based Healthcare management app

### Day 13: Serverless app CI/CD 🐳
**Status**: Check out 👉 [Day13](https://github.com/Ibrahimsi/Azure-DevOps-Zero-to-Hero/tree/main/Day13) 👈 folder for notes and useful links ✅

- Introduction to Azure functions
- Use case and benefits of an Azure function
- Introduction to the sample app to be used for this demo: Serverless QR Code Generator
- Demo creating the Azure function and deploying locally
- Publishing the function to Azure using CLI tools
- Build and release pipeline for building and deploying the code to Azure Functions

  
### Day 14: Azure DevOps wiki
**Status**: Check out 👉 [Day14](https://github.com/Ibrahimsi/Azure-DevOps-Zero-to-Hero/tree/main/Day14) 👈 folder for notes and useful links ✅

- Overview of wiki
- Creating and editing a project Wiki
- Publishing code as Wiki
- How we can use Azure DevOps wiki to collaborate on a project


### Day 15: Azure DevOps Security best practices 🚢
**Status**: Check out 👉 [Day15](https://github.com/Ibrahimsi/Azure-DevOps-Zero-to-Hero/tree/main/Day15) 👈 folder for notes and useful links ✅

- Azure DevOps Access Control
- Organization Settings
- Agent pools Management
- Pipeline settings
- Project-level Settings
- Pipeline security
- Repo settings
- Authentication and Authorization
- Secrets and credentials access


### Day 16: Issue and troubleshooting Azure DevOps
**Status**: Check out 👉 [Day16](https://github.com/Ibrahimsi/Azure-DevOps-Zero-to-Hero/tree/main/Day16) 👈 folder for notes and useful links ✅

Most common issues you have faced throughout the series and solutions.

- No hosted parallelism has been purchased or granted
- No Configuration Files Found Error: Terraform
- Classic Editor (or) Release pipeline not visible in Azure DevOps
- After Deployment, Deployment Succeded but did not load any data
- Deployment Slots

 
## 🔗 Join our community 👇  

<a href="https://github.com/Ibrahimsi/"><img src="https://user-images.githubusercontent.com/91791257/235086411-9ec7aa5e-c095-44ce-b9e6-57b3bc3fead2.png" height="60px"></img></a>
<a href="https://linkedin.com/in/ibrahim-si/"><img src="https://img.icons8.com/fluency/2x/linkedin.png" height="60px"></img></a>
<a href="https://medium.com/@ibrahims/"><img src="https://github.com/Ibrahimsi/Test-Azure/assets/41462796/f72becca-276a-4ae8-9827-975cc830bb4a)" height="60px"></a></img></a>
<a href="https://dev.to/ibrahimsi/"><img src="https://github.com/Ibrahimsi/Test-Azure/assets/41462796/fd84882c-f257-4c6b-a1c8-b7eca5c78465" height="60px"></a></img></a>
<a href="https://learningwise.quora.com/"><img src="(https://github.com/Ibrahimsi/Test-Azure/assets/41462796/ef073cb9-7fb2-4d3f-ade1-ab8b8b60daf4)" height="60px"></a></img></a>
<a href="https://hashnode.com/@IbbuS/"><img src="https://github.com/Ibrahimsi/Test-Azure/assets/41462796/42b02e94-0af9-4c0a-8222-100c2e1e71fd" height="60px"></a></img></a>
