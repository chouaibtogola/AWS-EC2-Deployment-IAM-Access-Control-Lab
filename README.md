# AWS-EC2-Deployment-IAM-Access-Control-Lab


# Project Overview

This hands-on AWS lab demonstrates how to deploy and manage cloud infrastructure using Amazon EC2 and AWS IAM. The project focuses on launching production and development EC2 instances, organizing resources with tags, and implementing secure access control policies using IAM users, groups, and custom JSON policies.

The lab also includes testing user permissions through both the AWS Console and the IAM Policy Simulator to validate least-privilege access principles commonly used in real-world DevOps and cloud security environments.

Project Description

In this lab, I worked as a DevOps engineer responsible for managing AWS infrastructure for a company environment. The objective was to increase computing capacity by deploying EC2 instances while securely onboarding a development intern with restricted permissions.

# Key Tasks Completed
Launched two Amazon EC2 instances:
Production environment instance
Development environment instance
Configured AWS resource tags:
Env = production
Env = development
Created a custom IAM policy using JSON to:
Allow EC2 actions only on development-tagged instances
Allow read-only EC2 describe actions
Deny tag modification actions
Created:
IAM User Group
IAM User for the intern
AWS Account Alias for simplified login
Assigned the custom IAM policy to the development group
Tested access permissions by:
Attempting to stop the production instance (denied)
Successfully stopping the development instance (allowed)
Explored the IAM Policy Simulator for permission validation
Cleaned up AWS resources to avoid unnecessary cloud charges


# Technologies & Services Used
Amazon Web Services
Amazon EC2
AWS Identity and Access Management
JSON IAM Policies
AWS Management Console




