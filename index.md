---
layout: default
---


## [Lets Get Started with Terraform](https://www.youtube.com/watch?v=HmxkYNv1ksg)

[//]: #  There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Introduction to Terraform
Terraform is an infrastructure as code (IaC) tool that allows you to build, change, and version infrastructure safely and efficiently. This includes low-level components such as compute instances, storage, and networking, as well as high-level components such as DNS entries, SaaS features, etc. Terraform can manage both existing service providers and custom in-house solutions.


![Data Flow Diagram The following diagram shows the way data flows through the various services and data stores in Terraform Enterprise.](https://www.devopsschool.com/blog/wp-content/uploads/2021/07/terraform-architecture-components-workflow-1.jpg)


## Key Features
Infrastructure as Code
You describe your infrastructure using Terraform's high-level configuration language in human-readable, declarative configuration files. This allows you to create a blueprint that you can version, share, and reuse.

## Execution Plans
Terraform generates an execution plan describing what it will do and asks for your approval before making any infrastructure changes. This allows you to review changes before Terraform creates, updates, or destroys infrastructure.

## Resource Graph
Terraform builds a resource graph and creates or modifies non-dependent resources in parallel. This allows Terraform to build resources as efficiently as possible and gives you greater insight into your infrastructure.

## Change Automation
Terraform can apply complex changesets to your infrastructure with minimal human interaction. When you update configuration files, Terraform determines what changed and creates incremental execution plans that respect dependencies.

## Infrastructure as code (IaC) 
tools allow you to manage infrastructure with configuration files rather than through a graphical user interface. IaC allows you to build, change, and manage your infrastructure in a safe, consistent, and repeatable way by defining resource configurations that you can version, reuse, and share.

## Terraform is HashiCorp's infrastructure as code tool.
It lets you define resources and infrastructure in human-readable, declarative configuration files, and manages your infrastructure's lifecycle. Using Terraform has several advantages over manually managing your infrastructure:

## Terraform can manage infrastructure on multiple cloud platforms.
The human-readable configuration language helps you write infrastructure code quickly.
Terraform's state allows you to track resource changes throughout your deployments.
You can commit your configurations to version control to safely collaborate on infrastructure.

## Manage any infrastructure
Terraform plugins called providers let Terraform interact with cloud platforms and other services via their application programming interfaces (APIs). HashiCorp and the Terraform community have written over 1,000 providers to manage resources on Amazon Web Services (AWS), Azure, Google Cloud Platform (GCP), Kubernetes, Helm, GitHub, Splunk, and DataDog, just to name a few. Find providers for many of the platforms and services you already use in the Terraform Registry. If you don't find the provider you're looking for, you can write your own.

## Standardize your deployment workflow
Providers define individual units of infrastructure, for example compute instances or private networks, as resources. You can compose resources from different providers into reusable Terraform configurations called modules, and manage them with a consistent language and workflow.

Terraform's configuration language is declarative, meaning that it describes the desired end-state for your infrastructure, in contrast to procedural programming languages that require step-by-step instructions to perform tasks. Terraform providers automatically calculate dependencies between resources to create or destroy them in the correct order.

### I hope this was useful to how to setup Apache Server and being expose to more Linux


```
Thank you readers, and wait for next week blog
For Contact e-mail me at ramirez368@hotmail.com

```
