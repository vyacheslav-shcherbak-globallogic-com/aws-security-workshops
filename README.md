# AWS Security Workshops

Within AWS there are a variety of services that can be used to secure your environments and workloads. This repository contains a collection of security oriented workshops that will guide you through prepared scenarios that represent common use cases and operational tasks and give you hands on experience with a wide range of AWS services.  The workshops closely align with the [Security Pillar](https://d1.awsstatic.com/whitepapers/architecture/AWS-Security-Pillar.pdf) components of our Well-Architected Framework, which can be used to help you structure your selection and implementation of controls that are right for your organziation.  Captured below are the high level security components:

![Components](./images/security-components-color.png "Categorization of AWS Security Services")

## Workshops

> Please review and complete all prerequisites before attempting these workshops.

Title               | Description
:---: | :---
[Scaling threat detection and response on AWS](./threat-detection-wksp/)                           | This hands-on workshop is where you will learn about a number of AWS services involved with threat detection and response as we walk through real-world threat scenarios. Learn about the threat detection capabilities of AWS services and the available response options. For each hands-on scenario, we review methods to detect and respond to threats using the following services: AWS CloudTrail, Amazon VPC flow logs, Amazon CloudWatch Events, Amazon Macie, AWS Lambda, Amazon Inspector, Amazon GuardDuty and AWS Security Hub.
[Cloud-powered Forensics](./forensics-wksp/)                           | This workshop demonstrates various techniques to perform practical evidence gathering from AWS sources and simple forensic tasks on Amazon EC2 instances. To orchestrate these tasks we will demonstrate a combination of industry tooling and AWS serverless services like Lambda with AWS Step Functions and managed services like Athena to give you a deeper understanding of the tasks you can and should do to secure critical evidence in case of need.
[Detection with Machine Learning](./detection-ml-wksp/)                           | This workshop shows how you can use an IP-based machine learning algorithm with Amazon SageMaker to augment and enrich findings from AWS Security services such as Amazon GuardDuty. You'll learn how to load the notebook in SageMaker, train the model, and score findings to determine abnormality of the activity.

## Prerequisites

### AWS Account

In order to complete these workshops you'll need a valid, usable AWS Account with Admin permissions.  The code and instructions in these workshops assume only one student is using a given AWS account at a time. If you try sharing an account with another student, you'll run into naming conflicts for certain resources. 

Use a **personal account** or create a new AWS account to ensure you have the neccessary access. This should not be an AWS account from the company you work for.

All of the resources you will launch as part of these workshops are eligible for the AWS free tier if your account is less than 12 months old. See the [AWS Free Tier](https://aws.amazon.com/free/) page for more details.  If you are doing this workshop as part of an AWS sponsored event, you will receive credits to cover the costs.

### Browser

We recommend you use the latest version of Chrome or Firefox to complete this workshop.

### Text Editor

For any workshop module that requires use of the AWS Command Line Interface (see above), you also will need a **plain text** editor for writing scripts. Any editor that inserts Windows or other special characters potentially will cause scripts to fail.

## License Summary

This sample code is made available under a modified MIT license. See the [LICENSE](LICENSE) file.
