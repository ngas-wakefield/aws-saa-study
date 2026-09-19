# SAA-C03 Study Plan

## Daily structure

Use this pattern on required weekdays:

- **30–40 min** — Skill Builder / official AWS source
- **10–15 min** — tiny notes, diagram, or comparison
- **5–10 min** — closed-book recall
- **20–30 min** — scenario questions
- **5–10 min** — update confidence and mistakes

The goal is to complete a finite unit, not to study indefinitely.

## Setup — 19–20 September

### Saturday 19 September — optional
- Set up the repo/project
- Take a **20-question mixed diagnostic** closed-book
- Record top five weak areas
- Do not study first; use this as a baseline

### Sunday 20 September — optional
- Review the exam mental model
- Learn the six Well-Architected pillars
- Understand the four exam concerns: secure, resilient, performant, cost-optimized

---

## Week 1 — Architecture Foundations

### Monday 21 September
**Well-Architected + Regions / Availability Zones**

Done when you can:
- name the six pillars
- explain Region vs AZ
- explain why Multi-AZ matters
- identify the primary architecture concern in a scenario

Validation: 5 scenario questions + closed-book teach-back.

### Tuesday 22 September
**IAM: users, groups, roles, policies, STS**

Done when you can:
- choose user vs role
- explain least privilege
- explain temporary credentials / AssumeRole
- distinguish identity-based and resource-based policies

Validation: closed-book comparison + 8 questions.

### Wednesday 23 September
**VPC fundamentals**

Study:
- public/private subnets
- route tables
- internet gateway
- NAT gateway
- VPC endpoints

Validation: draw a VPC from memory and narrate traffic flow + 5 questions.

### Thursday 24 September
**EC2 + Auto Scaling**

Study:
- horizontal vs vertical scaling
- Auto Scaling Groups
- target tracking / step / scheduled scaling
- CloudWatch metrics

Validation: explain scale out/in vs up/down + 8 questions.

### Friday 25 September
**Elastic Load Balancing + Route 53**

Study:
- ALB vs NLB
- target groups / health checks
- Route 53 routing policies
- DNS failover

Validation: comparison + routing-policy drill + 8 questions.

### Weekend — optional
- Draw a basic three-tier architecture
- 25 mixed questions
- Revisit only missed concepts

---

## Week 2 — Storage & Databases

### Monday 28 September
**Amazon S3**
- object storage
- durability / availability concepts
- storage classes
- lifecycle rules

Validation: choose storage class for five scenarios + 8 questions.

### Tuesday 29 September
**EBS + EFS + S3 vs EBS vs EFS**

Validation: write the object/block/file comparison from memory + 8 questions.

### Wednesday 30 September
**RDS + Aurora**
- Multi-AZ
- read replicas
- backups
- RDS Proxy

Validation: explain Multi-AZ vs read replica + 8 questions.

### Thursday 1 October
**DynamoDB**
- access patterns
- NoSQL use cases
- on-demand vs provisioned capacity

Validation: choose RDS/Aurora/DynamoDB for four workloads + 8 questions.

### Friday 2 October
**Caching**
- CloudFront
- ElastiCache
- database/application caching

Validation: draw where each cache sits + 8 questions.

### Weekend — optional
- Storage/database architecture exercise
- 30 focused questions
- Retest weak comparisons

---

## Week 3 — Resiliency

### Monday 5 October
**SQS**
- Standard vs FIFO
- visibility timeout
- dead-letter queues
- loose coupling

Validation: explain the message lifecycle + 8 questions.

### Tuesday 6 October
**SNS + EventBridge**
- pub/sub
- fanout
- event routing

Validation: SQS vs SNS vs EventBridge from memory + 8 questions.

### Wednesday 7 October
**High availability vs fault tolerance**

Validation: take a single-AZ design and improve it + 8 questions.

### Thursday 8 October
**Disaster recovery**
- RPO / RTO
- Backup & Restore
- Pilot Light
- Warm Standby
- Active/Active

Validation: order strategies conceptually by recovery capability/cost + 8 questions.

### Friday 9 October
**Resilient architecture synthesis**

Validation:
- draw a decoupled Multi-AZ architecture
- explain failure paths
- 12 mixed resiliency questions

### Weekend — optional
- Queue/Multi-AZ lab
- 30 resiliency questions
- classify every miss: knowledge, misread, confusion, or overthinking

---

## Week 4 — Serverless & Performance

### Monday 12 October
**Lambda + API Gateway**

Validation: compare Lambda with always-on compute + 8 questions.

### Tuesday 13 October
**ECS, EKS, Fargate**

Validation:
- ECS vs EKS
- Lambda vs Fargate
- 8 questions

### Wednesday 14 October
**CloudFront + Global Accelerator**

Validation: compare caching/content delivery vs network acceleration + 8 questions.

### Thursday 15 October
**Connectivity**
- VPN
- Direct Connect
- PrivateLink / VPC endpoints
- VPC Peering
- Transit Gateway

Validation: build a decision tree from memory + 8 questions.

### Friday 16 October
**Data ingestion and processing**
- Kinesis
- Firehose
- Glue
- Athena
- EMR
- DataSync

Validation: classify six workloads + 8 questions.

### Weekend — optional
- Serverless/performance architecture
- 30 high-performance questions
- revisit weak network/data topics

---

## Week 5 — Security & Cost Depth

### Monday 19 October
**KMS + encryption + ACM/TLS**

Validation: explain KMS key policy vs IAM permission at exam level + 8 questions.

### Tuesday 20 October
**Application/workload security**
- WAF
- Shield
- GuardDuty
- Macie
- Secrets Manager
- Cognito

Validation: service-to-problem matching drill + 8 questions.

### Wednesday 21 October
**Organizations + SCPs + Control Tower + federation**

Validation: explain IAM policy vs SCP vs role + 8 questions.

### Thursday 22 October
**Compute cost**
- On-Demand
- Savings Plans
- Reserved Instances
- Spot
- right-sizing

Validation: four-way purchasing comparison + 8 questions.

### Friday 23 October
**Storage/database/network cost + cost tools**
- lifecycle/tiering
- database capacity
- data-transfer / NAT costs
- Cost Explorer
- Budgets

Validation: identify five cost optimizations in one architecture + 8 questions.

### Weekend — optional
- Build one-page comparison sheet
- 40 mixed security/cost questions
- any topic under ~70% becomes a Week 6 revisit

---

## Week 6 — Exam Practice

### Monday 26 October
**Domain 1 — Security practice**
- 20 timed questions
- explain every wrong/guessed option

### Tuesday 27 October
**Domain 2 — Resilience practice**
- 20 timed questions
- review weak comparisons

### Wednesday 28 October
**Domain 3 — Performance practice**
- 20 timed questions
- review service-choice triggers

### Thursday 29 October
**Domain 4 — Cost practice**
- 20 timed questions
- review cost trade-offs

### Friday 30 October
**Full timed practice exam**
- 65 questions
- exam-like conditions
- mark wrong **and guessed** answers for review

### Saturday 31 October — optional readiness gate
- review every mock miss
- retest Red/Amber topics
- no new broad content

## Readiness target

Use this as a study heuristic, not as a conversion to AWS's scaled score:

- required plan mostly complete
- no core Red topics
- recent scenario practice around **80%+**
- one strong timed full mock
- can explain why wrong answers are wrong
