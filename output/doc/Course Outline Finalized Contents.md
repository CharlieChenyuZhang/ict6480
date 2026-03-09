# ITC6480 / AWS Cloud Architecting - Finalized Course Outline Content

## Course Name
AWS Cloud Architecting

## Number of Weeks
15

## Converted From
https://northeastern.instructure.com/courses/200053

## Semester Credits
4

## Course Description
Exposes students to advanced technical topics to help develop expertise in AWS cloud architecture and computing. Students gain the skills to pursue certification as an AWS Certified Solutions Architect-Associate, one of the most valuable IT certificates. The course is designed to teach solution architects how to optimize the use of the AWS Cloud by learning AWS services and how these services fit into cloud-based solutions. The course uses materials provided by AWS Academy, guided instructions, hands-on labs operated by AWS, project work, and free practice exam if students wish to pursue certification after completing the course. Successful students can demonstrate knowledge and skills of how to architect and deploy secure and robust applications on AWS technologies [1].

## Program Learning Outcomes
- PLO1 Computational Knowledge and Skills - Demonstrate proficiency in core computational principles and skills essential to informatics, applying them effectively to address complex, real-world issues.
- PLO2 Advanced Information and AI Technology - Utilize data engineering, cloud computing and cybersecurity along with generative AI tools to improve information processing, automate workflows and enhance decision-making in diverse informatics environments.
- PLO3 Innovation and Design Thinking - Employ a multidisciplinary, research-driven approach to identify informatics challenges, generating creative and impactful solutions that drive positive change for businesses and society.
- PLO4 Communication and Collaboration - Exhibit strong communication skills to clearly convey information; foster collaborative teamwork with shared accountability, adaptability, constructive conflict management and empathy.
- PLO5 IT Management Agility - Apply analytical and research methods to respond effectively to evolving business and technological demands; facilitate cross-functional collaboration and ensure IT scalability and efficiency.
- PLO6 Leadership, Governance, Policy and Ethics - Develop strategic leadership, uphold ethical standards and engage stakeholders effectively; leverage governance and policy expertise to promote accountability, transparency and regulatory compliance.

## Course Overview
This 15-week version of AWS Cloud Architecting expands the prior compressed 6-week shell into a full-semester experience that gives students more time to learn, practice, defend, and refine architecture decisions. The course uses AWS Academy Cloud Architecting materials as the primary technical backbone and integrates weekly labs, quizzes, architecture critiques, discussion-based reflection, and live design defense activities.

Students move from foundational architecture principles into secure identity, storage, compute, database, networking, application security, observability, automation, serverless, data engineering, and disaster recovery. Throughout the semester, students develop a capstone architecture for a realistic business case, using the AWS Well-Architected Framework to justify tradeoffs around security, reliability, performance efficiency, cost optimization, operational excellence, and sustainability.

The course also introduces creative formative assessment through weekly architecture defense. In these activities, students explain their decisions live or asynchronously, engage in structured dialogue, and use AI-supported critique to strengthen their reasoning, communication, and iteration habits. By the end of the course, students are prepared not only to complete a robust cloud architecture project, but also to bridge toward AWS certification readiness.

## Introduction to the Course
This course prepares students to think and act like junior cloud architects. Students learn how to translate business requirements into secure, scalable, resilient, and cost-aware AWS solutions. The instructional model combines short lectures, guided analysis of AWS Academy materials, hands-on labs, design workshops, live or recorded defense, and team-based capstone development.

## Course Learning Outcomes
- CLO1: Evaluate business and technical requirements and translate them into AWS architecture decisions using the AWS Well-Architected Framework.
- CLO2: Design secure AWS solutions that incorporate identity, network, data, and application security controls appropriate to a given use case.
- CLO3: Build and justify storage, compute, database, and networking layers on AWS that satisfy requirements for scalability, reliability, and performance.
- CLO4: Apply automation, event-driven, serverless, and data engineering patterns to improve agility, maintainability, and operational efficiency.
- CLO5: Communicate and defend architecture decisions through diagrams, technical rationale, iterative feedback, and evidence from labs, metrics, and testing.
- CLO6: Deliver a capstone AWS architecture proposal and prototype that reflects governance, cost, resilience, and ethical use of cloud technologies.

## Student Effort
For a 15-week, 4-credit course, students should expect 200 minutes/week of instructional time, 8-12 hours/week of out-of-class work, and a total of 11-14 hours/week of combined course effort.

## Intended Structure
- Weekly cadence: one module per week, with selected AWS Academy modules combined where pedagogically appropriate.
- Pre-class work: AWS Academy slides/videos, short readings, preparation prompts, and knowledge checks.
- In-class work: mini-lecture, architecture discussion, lab/demo, and design critique or defense.
- Post-class work: graded lab submission, quiz or discussion, and capstone milestone work.
- Capstone progression: topic selection, architecture draft, midterm design defense, implementation/prototype checkpoints, and final presentation.
- Assessment emphasis: hands-on architecture practice, explanation of decisions, and iterative improvement rather than recall alone.

## Assessment Strategy

### Ungraded Formative - 0%
- AWS Academy knowledge checks
- Practice exam items and self-check activities
- In-class polls, whiteboarding, and concept mapping

### Graded Formative - 70%
- Weekly labs and technical exercises - 30%
- Weekly quizzes - 15%
- Discussions, reflections, and peer feedback - 10%
- Weekly architecture defense / AI-supported critique logs - 15%

### Graded Summative - 10%
- Midterm architecture proposal and live design defense - 10%

### Summative (Signature) - 20%
- Final Assessment: capstone architecture package, presentation, and demonstration - 20%

## Course Layout

### Week 0 - Module 0: Orientation, Tools, and Expectations
**Topics and Subtopics**
- Course goals, grading, pacing, and semester roadmap
- AWS Academy access, lab environment setup, and submission workflow
- Introduction to the cafe business case and capstone expectations
- Overview of weekly design defense and AI-supported feedback process

**MLOs**
- M0O1: Navigate the course structure, platforms, and major deliverables.
- M0O2: Access AWS Academy materials, labs, and required support tools.
- M0O3: Explain how weekly labs, quizzes, discussions, and defense activities fit together.
- M0O4: Identify the capstone expectations, milestones, and evaluation criteria.
- M0O5: Establish a professional workflow for documenting and defending technical decisions.

**Assessment**
- Orientation checklist
- Course introduction discussion
- AWS Academy/lab setup confirmation

**Readings and Resources**
- Syllabus and course policies
- AWS Academy platform onboarding materials
- Capstone overview and defense rubric

### Week 1 - Module 1: Foundations of AWS Cloud Architecting
**Topics and Subtopics**
- Role of the cloud architect and the cafe business case
- Defining cloud architecture and architecture tradeoffs
- AWS Well-Architected Framework
- AWS Global Infrastructure and core best practices

**MLOs**
- M1O1: Describe the role and responsibilities of a cloud architect.
- M1O2: Define cloud architecture in relation to business and technical requirements.
- M1O3: Apply the pillars of the AWS Well-Architected Framework to basic design choices.
- M1O4: Distinguish AWS Regions, Availability Zones, and edge locations.
- M1O5: Frame an initial architecture problem using the cafe scenario.

**Assessment**
- Quiz 1
- Discussion: What makes an architecture decision defensible?
- Short architecture rationale memo

**Readings and Resources**
- AWS Academy Module 1 and Module 2 slides
- AWS Well-Architected Framework
- The Six Advantages and Benefits of Cloud Computing
- AWS Cloud Adoption Framework

### Week 2 - Module 2: Identity and Foundational Security
**Topics and Subtopics**
- Security principles in AWS
- IAM users, groups, roles, and policies
- Authentication vs authorization
- Policy evaluation and least privilege

**MLOs**
- M2O1: Explain foundational AWS security principles and shared responsibility.
- M2O2: Differentiate IAM users, groups, and roles for common scenarios.
- M2O3: Interpret IAM policy structure and effect.
- M2O4: Recommend least-privilege access patterns for a simple workload.
- M2O5: Defend security choices using risk-based reasoning.

**Assessment**
- IAM policy analysis activity
- Guided lab: Exploring AWS Identity and Access Management
- Weekly defense: secure access design walkthrough

**Readings and Resources**
- AWS Academy Module 3 slides
- Guided lab: Exploring IAM
- Supporting reference: Introduction to AWS Security

### Week 3 - Module 3: Storage Architectures with Amazon S3
**Topics and Subtopics**
- Amazon S3 fundamentals and storage use cases
- Data transfer patterns and object lifecycle management
- Versioning, static hosting, and transfer acceleration
- Applying Well-Architected principles to storage choices

**MLOs**
- M3O1: Explain how Amazon S3 supports durable and scalable storage.
- M3O2: Select S3 features that match access, lifecycle, and hosting requirements.
- M3O3: Compare storage design decisions in terms of cost, performance, and manageability.
- M3O4: Configure a simple static website architecture on S3.
- M3O5: Justify storage-layer decisions using architecture principles.

**Assessment**
- Lab: Creating a Static Website for the Cafe
- Quiz 2
- Storage design reflection

**Readings and Resources**
- AWS Academy Module 4 slides
- Demo references for S3 transfer acceleration, lifecycle policies, and versioning
- Supporting reference: Hosting Static Websites on AWS

### Week 4 - Module 4: Compute Architectures with Amazon EC2
**Topics and Subtopics**
- EC2 in multi-tier architectures
- AMIs, instance types, and storage options
- User data and repeatable provisioning
- Pricing models and cost-aware compute choices

**MLOs**
- M4O1: Identify when Amazon EC2 is an appropriate compute choice.
- M4O2: Recommend instance types and storage options for workload needs.
- M4O3: Explain how AMIs and user data support repeatable deployments.
- M4O4: Compare EC2 pricing options for cost-sensitive decisions.
- M4O5: Defend compute-layer design choices for a realistic business case.

**Assessment**
- Lab: Dynamic website / EC2 deployment
- Quiz 3
- Weekly defense: compute and cost tradeoff analysis

**Readings and Resources**
- AWS Academy Module 5 slides
- Guided lab: Introducing Amazon EFS
- Supporting reference: How AWS Pricing Works

### Week 5 - Module 5: Database Architectures on AWS
**Topics and Subtopics**
- Database layer considerations and workload fit
- Amazon RDS, replicas, backups, and proxy
- DynamoDB and purpose-built databases
- Migration patterns into AWS databases

**MLOs**
- M5O1: Compare relational, NoSQL, and purpose-built database approaches.
- M5O2: Determine when Amazon RDS is the appropriate service choice.
- M5O3: Determine when DynamoDB is the appropriate service choice.
- M5O4: Describe database migration and availability considerations.
- M5O5: Justify a database-layer architecture for the course case study.

**Assessment**
- Guided lab: Creating an Amazon RDS Database
- Database migration challenge activity
- Discussion: choosing the right data layer

**Readings and Resources**
- AWS Academy Module 6 slides
- Amazon RDS and DynamoDB service overviews
- Demo references for automated backup and read replicas

### Week 6 - Module 6: Networking Foundations with Amazon VPC
**Topics and Subtopics**
- Virtual Private Cloud fundamentals
- Subnets, route tables, internet gateway, and security groups
- Isolating public and private resources
- Monitoring and planning a network environment

**MLOs**
- M6O1: Explain the role of Amazon VPC in AWS networking.
- M6O2: Design subnets and routing for public/private separation.
- M6O3: Select foundational VPC controls for isolation and security.
- M6O4: Build and monitor a simple VPC-based network environment.
- M6O5: Evaluate a network design using Well-Architected criteria.

**Assessment**
- Guided lab: Creating a Virtual Private Cloud
- Challenge lab: VPC networking environment for the Cafe
- Network diagram submission

**Readings and Resources**
- AWS Academy Module 7 slides
- Demo: Creating an Amazon VPC in the AWS Management Console
- Supporting reference: Optimize Your Architecture by Looking at Network Strategy

### Week 7 - Module 7: Hybrid and Multi-VPC Connectivity
**Topics and Subtopics**
- VPC peering and Transit Gateway
- Site-to-Site VPN and Direct Connect
- Network scaling and cross-environment design
- Architecture checkpoint for capstone connectivity decisions

**MLOs**
- M7O1: Compare options for connecting multiple VPCs and remote networks.
- M7O2: Recommend a connectivity pattern for scale, cost, and manageability.
- M7O3: Explain how Transit Gateway simplifies complex network topologies.
- M7O4: Evaluate tradeoffs between VPN and Direct Connect.
- M7O5: Integrate network connectivity choices into a broader architecture narrative.

**Assessment**
- Guided lab: Creating a VPC Peering Connection
- Midterm checkpoint workshop
- Capstone architecture draft review

**Readings and Resources**
- AWS Academy Module 8 slides
- Activity: Configure AWS Transit Gateway Routes
- AWS Site-to-Site VPN and AWS Direct Connect references

### Week 8 - Module 8: Securing Users, Applications, and Data
**Topics and Subtopics**
- Identity federation and multi-account access
- AWS Organizations and service control policies
- Amazon Cognito for application-facing identity
- Encryption at rest with AWS KMS and related security services

**MLOs**
- M8O1: Extend IAM-based design to federation and multi-account governance.
- M8O2: Explain how AWS Organizations and SCPs strengthen governance.
- M8O3: Apply application-level identity patterns with Amazon Cognito.
- M8O4: Recommend encryption and key management strategies for data at rest.
- M8O5: Defend layered security choices across users, apps, and data.

**Assessment**
- Midterm Assessment: architecture proposal and live design defense
- Guided lab: Securing Applications by Using Amazon Cognito
- Guided lab: Encrypting Data at Rest by Using AWS Encryption Options

**Readings and Resources**
- AWS Academy Module 9 slides
- Supporting references: Introduction to AWS Security and AWS KMS Cryptographic Details
- AWS Organizations overview

### Week 9 - Module 9: Observability, Elasticity, and High Availability
**Topics and Subtopics**
- Monitoring with Amazon CloudWatch and Amazon EventBridge
- Auto Scaling and elasticity patterns
- Database scaling and load balancing
- DNS failover with Amazon Route 53

**MLOs**
- M9O1: Explain how observability supports resilient architecture decisions.
- M9O2: Design elasticity with Amazon EC2 Auto Scaling.
- M9O3: Recommend a high-availability pattern using load balancing and failover.
- M9O4: Evaluate database and DNS scaling strategies.
- M9O5: Defend reliability decisions using measurable system behavior.

**Assessment**
- Guided lab: Creating a Highly Available Environment
- Challenge lab: Scalable and highly available Cafe environment
- Quiz 4

**Readings and Resources**
- AWS Academy Module 10 slides
- Demo references for CloudWatch, Auto Scaling, and Route 53 routing
- Supporting reference: The Business Value of AWS

### Week 10 - Module 10: Automation and Infrastructure as Code
**Topics and Subtopics**
- Why automation matters in cloud architecture
- Infrastructure as code principles
- AWS CloudFormation templates and Quick Starts
- AI-assisted productivity and review in cloud implementation

**MLOs**
- M10O1: Explain when architecture automation improves speed and consistency.
- M10O2: Interpret core concepts of infrastructure as code.
- M10O3: Analyze and customize AWS CloudFormation templates.
- M10O4: Use AI-assisted workflows responsibly to accelerate infrastructure tasks.
- M10O5: Defend automation choices in terms of reliability, repeatability, and governance.

**Assessment**
- Guided lab: Automating Infrastructure with AWS CloudFormation
- Challenge lab: Automating Infrastructure Deployment
- Weekly defense: explain an IaC template and its tradeoffs

**Readings and Resources**
- AWS Academy Module 11 slides
- Supporting references: Overview of Deployment Options on AWS, Managing Your AWS Infrastructure at Scale, Managing Your Infrastructure as Code

### Week 11 - Module 11: Caching and Performance Optimization
**Topics and Subtopics**
- Why caching matters for latency and scale
- CloudFront for edge delivery
- ElastiCache for database and application acceleration
- Cost and performance tradeoffs in caching strategy

**MLOs**
- M11O1: Explain how caching improves user experience and system performance.
- M11O2: Design a content delivery strategy with Amazon CloudFront.
- M11O3: Identify use cases for ElastiCache in application architectures.
- M11O4: Evaluate the tradeoffs of caching layers in terms of freshness and complexity.
- M11O5: Recommend a performance optimization strategy for a specific workload.

**Assessment**
- Guided lab: Streaming Dynamic Content Using Amazon CloudFront
- Optimization memo
- Discussion: performance vs cost tradeoffs

**Readings and Resources**
- AWS Academy Module 12 slides
- Supporting reference: Maintaining Performance and Availability While Lowering Cost With AWS
- CloudFront and ElastiCache service references

### Week 12 - Module 12: Decoupled and Event-Driven Architectures
**Topics and Subtopics**
- Tight vs loose coupling
- Amazon SQS, Amazon SNS, and Amazon MQ
- Event-driven communication patterns
- Designing for resilience and integration flexibility

**MLOs**
- M12O1: Distinguish tightly coupled and loosely coupled architectures.
- M12O2: Select between SQS, SNS, and MQ for common integration needs.
- M12O3: Explain how message-based design improves resilience and scalability.
- M12O4: Propose an event-driven redesign for a simple application workflow.
- M12O5: Defend decoupling choices in terms of maintainability and fault isolation.

**Assessment**
- Guided lab: Building Decoupled Applications by Using Amazon SQS
- Event-driven architecture critique
- Quiz 5

**Readings and Resources**
- AWS Academy Module 13 slides
- SQS, SNS, and Amazon MQ service overviews
- Instructor examples on event-driven patterns

### Week 13 - Module 13: Serverless, Containers, and Microservices
**Topics and Subtopics**
- Serverless thinking and microservice characteristics
- AWS Lambda, API Gateway, and Step Functions
- Container-based microservices on AWS
- Decomposing a monolith into services

**MLOs**
- M13O1: Define serverless and microservices in AWS architecture terms.
- M13O2: Architect a basic serverless workflow using Lambda and API Gateway.
- M13O3: Explain when containers are more appropriate than pure serverless options.
- M13O4: Use Step Functions to model workflow orchestration.
- M13O5: Defend a decomposition strategy for a monolithic system.

**Assessment**
- Guided lab: Implementing a Serverless Architecture on AWS
- Serverless architecture challenge
- Capstone design review

**Readings and Resources**
- AWS Academy Module 14 slides
- Supporting reference: AWS Serverless Multi-Tier Architectures
- Optional guided lab: Breaking a Monolithic Node.js Application into Microservices

### Week 14 - Module 14: Data Engineering Patterns on AWS
**Topics and Subtopics**
- Data characteristics and ingestion patterns
- Batch vs real-time data pipelines
- Storage, transformation, analytics, and visualization services
- Architecture choices for data-intensive workloads

**MLOs**
- M14O1: Classify data workloads by velocity, volume, and variety.
- M14O2: Select an AWS ingestion pattern for batch or streaming use cases.
- M14O3: Recommend services for storage, transformation, and analysis.
- M14O4: Evaluate tradeoffs in data pipeline design across performance, cost, and complexity.
- M14O5: Present a defensible data architecture for a business scenario.

**Assessment**
- Activity: Data Pipeline Architecture
- Capstone progress demo
- Reflection: selecting the right data stack

**Readings and Resources**
- AWS Academy Module 15 slides
- Activity: Choosing Data Storage for a Bank Application
- AWS data analytics and visualization service references

### Week 15 - Module 15: Resilience, Certification Readiness, and Capstone Synthesis
**Topics and Subtopics**
- Disaster planning, RPO, and RTO
- Backup and disaster recovery patterns
- Bridging to AWS Solutions Architect - Associate certification
- Final capstone integration, presentation, and reflection

**MLOs**
- M15O1: Identify disaster recovery strategies that fit business continuity requirements.
- M15O2: Compare DR patterns using RPO/RTO targets and service constraints.
- M15O3: Connect semester content to AWS certification domains and readiness planning.
- M15O4: Integrate security, reliability, cost, and performance reasoning into a final architecture package.
- M15O5: Present and defend a complete AWS architecture solution with professional clarity.

**Assessment**
- Final Assessment: capstone architecture package, presentation, and demonstration
- Disaster recovery design exercise
- Certification bridge / practice exam reflection

**Readings and Resources**
- AWS Academy Module 16 and Module 17 slides
- Guided lab: Configuring Hybrid Storage and Migrating Data with AWS Storage Gateway S3 File Gateway
- Supporting references: A Practical Guide to Cloud Migration, Cost Optimization with AWS

## Media Summary
- Graphics: 15-20 architecture diagrams, deployment diagrams, policy diagrams, and comparison charts embedded across modules.
- Infographics: Well-Architected summaries, storage/compute/database decision trees, networking patterns, and DR strategy comparisons.
- Stock images: minimal use; prioritize technical diagrams and AWS reference visuals over decorative imagery.
- Video tops and tails: short intro/outro segments for each weekly module or lecture recording to reinforce key outcomes and next steps.

## Discovery Summary
The revised outline keeps the existing catalog description and PLO language unchanged, preserves the AWS Academy Cloud Architecting core sequence, and expands the former compressed 6-week Canvas organization into a 15-week structure better suited to a 4-credit semester course. The resulting design distributes technical depth more evenly, adds room for reflection and defense, introduces a creative weekly architecture critique model, and builds a clear path from foundational AWS services to capstone delivery and certification readiness.
