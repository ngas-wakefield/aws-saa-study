# Source Material

Use this as the source map for the study tickets. The goal is not to read every page end-to-end. Use the ticket's checklist to decide what to extract.

## Primary sources

1. **AWS Skill Builder — SAA-C03 Exam Prep Plan**  
   https://skillbuilder.aws/  
   Use this as the main learning path, labs, question sets, and official practice-exam source.

2. **AWS Certified Solutions Architect – Associate**  
   https://aws.amazon.com/certification/certified-solutions-architect-associate/  
   Current exam overview and official prep path.

3. **Official SAA-C03 Exam Guide**  
   https://docs.aws.amazon.com/aws-certification/latest/solutions-architect-associate-03/solutions-architect-associate-03.html  
   Use this to keep study inside the actual exam scope.

4. **AWS Well-Architected Framework**  
   https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html  
   Use this for architecture trade-offs, reliability, performance, security, and cost reasoning.

5. **AWS Architecture Center**  
   https://aws.amazon.com/architecture/  
   Use when a ticket asks you to draw or critique an architecture.

## Architecture foundations

### IAM
- https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html
- https://docs.aws.amazon.com/IAM/latest/UserGuide/id_roles.html
- https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies.html

### VPC
- https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html
- https://docs.aws.amazon.com/vpc/latest/userguide/vpc-nat.html
- https://docs.aws.amazon.com/vpc/latest/privatelink/what-is-privatelink.html

### EC2 Auto Scaling
- https://docs.aws.amazon.com/autoscaling/ec2/userguide/what-is-amazon-ec2-auto-scaling.html
- https://docs.aws.amazon.com/autoscaling/ec2/userguide/autoscaling-load-balancer.html

### Elastic Load Balancing
- https://docs.aws.amazon.com/elasticloadbalancing/latest/userguide/what-is-load-balancing.html

### Route 53
- https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/Welcome.html

## Storage & databases

### Amazon S3
- https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html
- https://docs.aws.amazon.com/AmazonS3/latest/userguide/storage-class-intro.html
- https://docs.aws.amazon.com/AmazonS3/latest/userguide/object-lifecycle-mgmt.html

### Amazon EBS
- https://docs.aws.amazon.com/ebs/latest/userguide/what-is-ebs.html

### Amazon EFS
- https://docs.aws.amazon.com/efs/latest/ug/whatisefs.html

### Amazon RDS / Aurora
- https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html
- https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Concepts.MultiAZ.html
- https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_ReadRepl.html
- https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/CHAP_AuroraOverview.html

### DynamoDB
- https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html
- https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/HowItWorks.ReadWriteCapacityMode.html

### ElastiCache
- https://docs.aws.amazon.com/AmazonElastiCache/latest/dg/WhatIs.html

## Resiliency & event-driven architecture

### SQS
- https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/welcome.html
- https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/sqs-visibility-timeout.html
- https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/sqs-dead-letter-queues.html

### SNS
- https://docs.aws.amazon.com/sns/latest/dg/welcome.html

### EventBridge
- https://docs.aws.amazon.com/eventbridge/latest/userguide/eb-what-is.html

### Disaster recovery / RPO / RTO
- https://docs.aws.amazon.com/wellarchitected/latest/reliability-pillar/rel_planning_for_recovery_disaster_recovery.html
- https://docs.aws.amazon.com/prescriptive-guidance/latest/strategy-database-disaster-recovery/defining.html
- https://docs.aws.amazon.com/whitepapers/latest/disaster-recovery-workloads-on-aws/disaster-recovery-options-in-the-cloud.html

## Serverless & performance

### Lambda
- https://docs.aws.amazon.com/lambda/latest/dg/welcome.html

### API Gateway
- https://docs.aws.amazon.com/apigateway/latest/developerguide/welcome.html

### ECS / EKS / Fargate
- https://docs.aws.amazon.com/AmazonECS/latest/developerguide/Welcome.html
- https://docs.aws.amazon.com/eks/latest/userguide/what-is-eks.html
- https://docs.aws.amazon.com/AmazonECS/latest/developerguide/AWS_Fargate.html

### CloudFront / Global Accelerator
- https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html
- https://docs.aws.amazon.com/global-accelerator/latest/dg/what-is-global-accelerator.html

### Hybrid/private networking
- https://docs.aws.amazon.com/vpn/latest/s2svpn/VPC_VPN.html
- https://docs.aws.amazon.com/directconnect/latest/UserGuide/Welcome.html
- https://docs.aws.amazon.com/vpc/latest/privatelink/what-is-privatelink.html
- https://docs.aws.amazon.com/vpc/latest/peering/what-is-vpc-peering.html
- https://docs.aws.amazon.com/vpc/latest/tgw/what-is-transit-gateway.html

### Data & analytics
- https://docs.aws.amazon.com/streams/latest/dev/introduction.html
- https://docs.aws.amazon.com/firehose/latest/dev/what-is-this-service.html
- https://docs.aws.amazon.com/glue/latest/dg/what-is-glue.html
- https://docs.aws.amazon.com/athena/latest/ug/what-is.html
- https://docs.aws.amazon.com/emr/latest/ManagementGuide/emr-what-is-emr.html
- https://docs.aws.amazon.com/datasync/latest/userguide/what-is-datasync.html

## Security

### KMS
- https://docs.aws.amazon.com/kms/latest/developerguide/overview.html

### WAF / Shield
- https://docs.aws.amazon.com/waf/latest/developerguide/what-is-aws-waf.html

### GuardDuty
- https://docs.aws.amazon.com/guardduty/latest/ug/what-is-guardduty.html

### Macie
- https://docs.aws.amazon.com/macie/latest/user/what-is-macie.html

### Secrets Manager
- https://docs.aws.amazon.com/secretsmanager/latest/userguide/intro.html

### Cognito
- https://docs.aws.amazon.com/cognito/latest/developerguide/what-is-amazon-cognito.html

### Organizations / SCPs / Control Tower
- https://docs.aws.amazon.com/organizations/latest/userguide/orgs_introduction.html
- https://docs.aws.amazon.com/organizations/latest/userguide/orgs_manage_policies_scps.html
- https://docs.aws.amazon.com/controltower/latest/userguide/what-is-control-tower.html

## Cost optimization

### Compute purchasing models
- https://docs.aws.amazon.com/savingsplans/latest/userguide/what-is-savings-plans.html
- https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/using-spot-instances.html
- https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-reserved-instances.html

### Cost tools
- https://docs.aws.amazon.com/cost-management/latest/userguide/ce-what-is.html
- https://docs.aws.amazon.com/cost-management/latest/userguide/budgets-managing-costs.html

## How to use a source for exam study

Do **not** try to memorize the whole service guide.

For each ticket, extract only:

- what problem the service solves
- when to choose it
- when not to choose it
- scaling model
- availability/resiliency behavior
- security controls
- performance characteristics
- major cost trade-offs
- similar services and how to distinguish them
- exam trigger words
- one architecture example

Then close the source and validate from memory.
