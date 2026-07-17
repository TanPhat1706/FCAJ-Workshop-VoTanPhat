---
title: "Published Blogs"
date: 2024-01-01
weight: 3
chapter: false
pre: " <b> 3. </b> "
---

This section lists and introduces the technical blog posts compiled and publicly published by the team on the [AWS Study Group VN](https://www.facebook.com/groups/awsstudygroupfcj) community. These posts synthesize production experiences, architectural discussions, and the latest cloud computing updates gathered throughout the project implementation process.

### [Blog 1: Architectural Discussion on the Mini Social Network Project](3.1-Blog1/)
This post details the architectural design of the "Mini Social Network" project, which applies a standard 3-Tier Architecture on AWS. The system is logically decoupled into a Data Plane (Data Access & Processing flows) and a Control Plane (Operations & CI/CD flows), highlighting the team's infrastructure isolation and security solutions. The post also includes a valuable Q&A section based on real-world feedback from expert engineers within the AWS community.

### [Blog 2: Cloud Migration Diary – From a $35 Lesson to a Cost-Optimized Architecture](3.2-Blog2/)
This post shares the practical journey of migrating a monolithic application from a traditional VPS hosting environment to a robust Cloud-Native architecture on AWS. The content focuses on how the team confronted and overcame classic challenges, such as unexpected NAT Gateway costs, SPA routing issues on Amazon S3, and source code performance bottlenecks. The blog also demonstrates how the team broke down tasks by specialized roles (Ops, UI/UX, Observability, DevSecOps) to optimize the infrastructure.

### [Blog 3: Amazon ECS Launches High-Resolution Metrics, Speeding Up Service Auto Scaling by 4x](3.3-Blog3/)
Based on the latest technological updates from AWS, this post provides an in-depth analysis of the newly released high-resolution metrics feature (20-second granularity) for Amazon ECS. It explains the core mechanism behind this breakthrough that reduces scale-out delay by up to 76% (from 363 seconds down to 86 seconds), enabling cloud systems to react instantly to traffic spikes while cutting down on capacity padding waste and compute costs.