## Salesforce Sales Cloud Einstein, Activity Platform SRE Team

**AMTS Software Engineer (full-time)**

### Contributions

 - Infrastructure as Code: Manage and provision data center using HashiCorp tech stack (Terraform, Nomad, Consul, Vault, Packer) and AWS; Troubleshoot with ACL bootstrap and Nomad outage recovery.

 - Cost Management: Implement an IAM role with Terraform that enables the non-technical personnel to access AWS billing information, configure SAML Authentication (SSO) in Duo Access Gateway with Microsoft Active Directory Federation Service (AD FS). Create shell script for Packer Provisioner that automatically tag EBS root volume during instance bootstrap which helps with EBS cost breakdown by Metadata tags.  

 - Service Monitoring: Build a monitoring system for simple email service (SES) to track email bouncing. Send SES event to Simple Notification Service (SNS) topic and configure a Lambda function to be the SNS topic subscriber. Integrate with Slack to receive SNS message publication via incoming webhook.
 
 - Network and security: Carry out a hotfix to enable service access by modifying inbound rules for the ELB security group. Refactor terraform code to create the module for the account-level configuration that manages password policy and CloudTrail. Perform software patching to deal with security vulnerabilities.

### Technologies
 - Nomad
 - Consul
 - AWS
 - Vault
 - Terraform
 - Storm
 - Teamcity
 - Atlantis