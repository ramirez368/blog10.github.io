---
layout: default
---


## [Lets Get Started with EC2](https://www.youtube.com/watch?v=8TlukLu11Yo)

[//]: #  There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# What is Amazon EC2?
Amazon Elastic Compute Cloud (Amazon EC2) is a web service that provides secure, resizable compute capacity in the cloud. It is designed to make web-scale cloud computing easier for developers. Amazon EC2’s simple web service interface allows you to obtain and configure capacity with minimal friction. It provides you with complete control of your computing resources and lets you run on Amazon’s proven computing environment.


![Basic Understanding of a EC2 Instance](https://www.tutorialspoint.com/amazon_web_services/images/architecture.jpg)


## Getting Started with Amazon EC2
Amazon EC2 offers the broadest and deepest compute platform with choice of processor, storage, networking, operating system, and purchase model. We offer the fastest processors in the cloud and we are the only cloud with 400 Gbps ethernet networking. We have the most powerful GPU instances for machine learning training and graphics workloads, as well as the lowest cost-per-inference instances in the cloud. More SAP, HPC, Machine Learning, and Windows workloads run on AWS than any other cloud.

## Reliable and Scalable Infrastructure
Increase or decrease capacity within minutes and provide 99.99% availability for each Amazon EC2 region.

## Secure Your Applications
Provide various security standards and features, reduce the risk of human error and eliminate the attack surface.

## Easy Migration
Get started quickly through AWS Migration Tools, AWS Managed Services, or Amazon Lightsail with the help from AWS Professional Services, AWS Support and APN Partners.

## Flexible Pricing
Offer five pricing models to pay for Amazon EC2 instances: On-Demand, Savings Plans, Dedicated Hosts, Spot Instances and Per Second Billing.

![ ](https://i1.wp.com/cloudkatha.com/wp-content/uploads/2021/08/AWS-EC2-Instance-Purchasing-Options-All-You-Need-to-Know-Featured.png?w=1023&ssl=1)

## Create your EC2 resources and launch your EC2 instance

## Important: 
Before you can launch and connect to an Amazon EC2 instance, you need to create a key pair, unless you already have one. You can create a key pair using the Amazon EC2 console, and then you can launch your EC2 instance.

## To create a key pair
Look in Amazon EC2 in the Amazon EC2 User Guide.

## Steps to Launch EC2 Instance and mount an EFS file system


1. Open the Amazon EC2 console at https://console.aws.amazon.com/ec2/.

2. Choose Launch Instance.

3. Choose an Amazon Machine Image (AMI), find an Amazon Linux 2 AMI at the top of the list and choose Select.

4. Choose an Instance Type, choose Next: Configure Instance Details.

5. Configure Instance Details, provide the following information:

* Leave Number of instances at one.

* Leave Purchasing option at the default setting.

* For Network, choose the entry for the same VPC that you noted when you created your EFS file system in Step 1: Create your Amazon EFS file system.

* For Subnet, choose a default subnet in any Availability Zone.

* For File systems, make sure that the EFS file system that you created in Step 1: Create your Amazon EFS file system is selected. The path shown next to the file system ID is the mount point that the EC2 instance will use, which you can change.

* The User data automatically includes the commands for mounting your Amazon EFS file system.

6. Choose Next: Add Storage.

7. Choose Next: Add Tags.

8. Name your instance and choose Next: Configure Security Group.

9. In Step 6: Configure Security Group, set Assign a security group to Select an existing security group. Choose the default security group to make sure that it can access your EFS file system.

You can't access your EC2 instance by Secure Shell (SSH) using this security group. SSH access isn't required for this exercise. To add access by SSH later, you can edit the default security and add a rule to allow SSH. Or you can create a new security group that allows SSH. You can use the following settings to add SSH access:

* Type: SSH

* Protocol: TCP

* Port Range: 22

* Source: Anywhere 0.0.0.0/0

10. Choose Review and Launch.

11. Choose Launch.

12. Select the check box for the key pair that you created, and then choose Launch Instances.



### I hope this was useful to how to setup Apache Server and being expose to more Linux


```
Thank you readers, and wait for next week blog
For Contact e-mail me at ramirez368@hotmail.com

```
