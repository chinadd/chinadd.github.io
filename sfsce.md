## Salesforce, Sales Cloud, Activity Platform SRE Team

**AMTS Software Engineer (Jan 2020 - Apr 2021)**

**MTS Software Engineer (May 2021 - Now)**

### Contributions

 - Infrastructure as Code: 
1. Provision and operate immutable, disposable infrastructure, following SDLC best practice: self-containment, phased deployment, systematic and high-level change validation in a secure and cost-efficient way. 
2. Manage and provision data center on AWS using Terraform configuration, conduct service migration to use Nomad as process manager and container orchestrator.

 - Cost Management: 
 Implement an IAM role with Terraform that enables the non-technical personnel to access AWS billing information, configure SAML Authentication (SSO) in Duo Access Gateway with Microsoft Active Directory Federation Service (AD FS). Create shell script for Packer Provisioner that automatically tag EBS root volume during instance bootstrap which helps with EBS cost breakdown by Metadata tags.  

 - Observability: 
 1. Build a monitoring system for simple email service (SES) to track email bouncing. Send SES event to Simple Notification Service (SNS) topic and configure a Lambda function to be the SNS topic subscriber. Integrate with Slack to receive SNS message publication via incoming webhook.
 2. Provision the in-house Kafka backlog monitor on new infrastructure with terraform configuration, which provides a better time resolution for monitoring metrics. 
 
 - Network and security: 
 1. Carry out a hotfix to enable service access by modifying inbound rules for the ELB security group. Refactor terraform code to create the module for the account-level configuration that manages password policy and CloudTrail. 
 2. Monitor security vulnerabilities and have patching SLA compliance stays consistently above 99% every quarter. Developed a customized patching script to perform topology-based server rotation to deal with the accumulation of backlog brought by topology downtime during patching. 

 - Availability and Reliability
 Participate in oncall shifts to handle service disruptions in production environments aiming to deliver and maintain 99.95% availability for all services, including disk alert, auto-scaling group capacity (CPU, Memory, etc) adjustment, failure of new instance to join/sync with the cluster or start nomad process, problem in target group registration for load balancer,  

### Technologies
 - Nomad
 - Consul
 - AWS
 - Vault
 - Terraform
 - Storm
 - Kafka
 - Zookeeper
 - Cassandra
 - MongoDB
 - Teamcity
 - Atlantis
