# Hi, I'm Demi Alabi 👋

### Aspiring Cloud & DevOps Engineer | AWS | Terraform | CI/CD | Kubernetes

I'm building practical cloud engineering skills through hands-on projects focused on **cloud infrastructure, Infrastructure as Code, CI/CD automation, containerisation, security, and operational reliability**.

My portfolio demonstrates how I provision and manage AWS resources, automate deployments, test infrastructure changes, troubleshoot failures, and apply DevOps and DevSecOps practices to real-world engineering scenarios.

📍 London, United Kingdom

---

## 🛠️ Technical Skills

- **Cloud & AWS:** Amazon S3, EC2, VPC, IAM, Lambda, RDS, Application Load Balancer, Systems Manager, CloudWatch
- **Infrastructure as Code:** Terraform, remote state management, infrastructure planning and drift detection
- **CI/CD & Automation:** GitHub Actions, workflow automation, validation, deployment and teardown pipelines
- **Containers & Orchestration:** Docker, Kubernetes, kind, Amazon ECR, Amazon EKS fundamentals
- **Security & DevSecOps:** IAM, OIDC federation, least-privilege access, Trivy vulnerability scanning, AWS Secrets Manager
- **Monitoring & Observability:** Amazon CloudWatch, CloudWatch Agent, Grafana, Amazon SNS
- **Operating Systems & Scripting:** Linux, Bash, Python fundamentals
- **Version Control:** Git, GitHub, branching, pull requests and version-controlled workflows

---

## 🚀 Featured Projects

### 🗺️ [Project Atlas — Serverless AWS DevOps Platform](https://github.com/imed3721/aws-devops-platform)

**Automating serverless AWS infrastructure with Terraform, secure CI/CD, monitoring, and operational testing.**

Project Atlas provisions and manages a Python health-check application using AWS Lambda, Terraform, and GitHub Actions. It demonstrates secure AWS authentication, automated testing, infrastructure drift detection, monitoring, and controlled resource teardown.

**Key Engineering Highlights**

- **Infrastructure as Code:** Provision Lambda, IAM roles, CloudWatch logging, and Lambda Function URLs using Terraform.
- **Secure CI/CD:** Authenticate GitHub Actions to AWS using OIDC federation instead of long-lived access keys.
- **Automated Testing:** Run Python unit tests and Terraform validation through CI workflows.
- **Security Testing:** Test IAM trust-policy restrictions to verify that only appropriately trusted workflows can assume the deployment role.
- **Monitoring & Observability:** Configure CloudWatch logs, seven-day log retention, and a Lambda error alarm.
- **Drift Detection & Recovery:** Introduce configuration changes, identify drift through Terraform planning, and document reconciliation.
- **Failure Testing:** Intentionally trigger a unit-test failure, verify that CI detects the regression, and confirm recovery.
- **Controlled Teardown:** Implement a confirmation-gated Terraform destruction workflow and investigate IAM permission issues encountered during cleanup.

**Tech Stack:** AWS Lambda · IAM · OIDC · Amazon S3 · CloudWatch · Terraform · GitHub Actions · Python

**Engineering Focus:** Serverless computing · Secure authentication · Infrastructure automation · Monitoring · Testing · Troubleshooting

[Explore the repository and implementation evidence →](https://github.com/imed3721/aws-devops-platform)

---

### 🎯 [Operation GoldenEye — AWS Infrastructure Automation](https://github.com/imed3721/operation-goldeneye)

**A James Bond-inspired DevOps project demonstrating secure AWS infrastructure provisioning, cloud networking, CI/CD automation, and infrastructure lifecycle management.**

Operation GoldenEye uses Terraform and GitHub Actions to provision AWS networking resources and an internet-facing Application Load Balancer (ALB). It integrates AWS IAM OIDC authentication, remote Terraform state management, and automated workflows for deployment, drift detection, and controlled teardown.

**Key Engineering Highlights**

- **Infrastructure as Code:** Define AWS networking and load-balancing resources using Terraform.
- **Secure CI/CD Authentication:** Use GitHub Actions and IAM OIDC federation without long-lived AWS access keys.
- **AWS Networking:** Build a VPC with two public subnets across Availability Zones, an internet gateway, route tables, and security groups.
- **Load Balancing:** Configure an internet-facing Application Load Balancer with an HTTP listener and a fixed demonstration response.
- **Remote State Management:** Store Terraform state in Amazon S3 with versioning and Block Public Access.
- **Drift Detection:** Introduce controlled changes and use Terraform plans to identify configuration differences.
- **Lifecycle Management:** Automate validation, planning, deployment, and teardown through GitHub Actions.
- **Operational Troubleshooting:** Investigate workflow results and verify infrastructure cleanup.

**Tech Stack:** AWS · Terraform · GitHub Actions · IAM · OIDC · Amazon S3 · Amazon VPC · Application Load Balancer · Git

**Engineering Focus:** Cloud networking · Infrastructure automation · Secure authentication · Change management · Resource lifecycle management

[Explore the repository and implementation evidence →](https://github.com/imed3721/operation-goldeneye)

---

### ☁️ [AWS DevOps Platform — Cloud Infrastructure & Database Automation](https://github.com/imed3721/aws-devops-platform)

**A hands-on AWS project demonstrating infrastructure provisioning, private networking, database management, monitoring, and secure deployment workflows.**

This project explores the management of AWS infrastructure using Terraform and GitHub Actions, with an emphasis on private networking, Amazon RDS for PostgreSQL, secure authentication, remote state, and operational monitoring.

**Key Engineering Highlights**

- **Infrastructure as Code:** Provision and manage AWS resources using version-controlled Terraform configuration.
- **Secure CI/CD:** Authenticate GitHub Actions to AWS using OIDC and IAM roles.
- **Private Networking:** Configure VPC networking, private subnets, routing, and security groups.
- **Database Infrastructure:** Deploy Amazon RDS for PostgreSQL within private networking.
- **Remote State Management:** Use Amazon S3 for Terraform state storage and consistent infrastructure operations.
- **Monitoring & Alerting:** Configure CloudWatch alarms for database CPU utilisation and available storage.
- **Secrets Management:** Use AWS Secrets Manager and IAM permissions to support secure credential handling.
- **Drift Detection:** Identify differences between declared infrastructure and deployed AWS resources.
- **Lifecycle Management:** Automate infrastructure validation, deployment, and controlled teardown.

**Tech Stack:** AWS · Terraform · GitHub Actions · IAM · OIDC · Amazon S3 · Amazon VPC · Amazon RDS · PostgreSQL · CloudWatch · AWS Secrets Manager

**Engineering Focus:** Infrastructure as Code · Cloud networking · Database infrastructure · Monitoring · Secure access · Troubleshooting

[Explore the repository and implementation evidence →](https://github.com/imed3721/aws-devops-platform)

---

### 🕷️ [Project Web-Slinger — Secure DevOps & Container Security](https://github.com/imed3721/project-web-slinger)

**A DevSecOps project demonstrating container security, automated software delivery, Kubernetes deployment verification, and infrastructure drift recovery.**

Project Web-Slinger combines Python application development, Docker, GitHub Actions, Terraform, and Kubernetes testing. It integrates Trivy vulnerability scanning, AWS OIDC authentication, Amazon ECR image publishing, and automated validation to demonstrate secure, traceable software delivery.

**Key Engineering Highlights**

- **Continuous Integration:** Automate application and configuration checks through GitHub Actions.
- **Containerisation:** Package a Python application into a portable Docker image.
- **Container Security:** Integrate Trivy scanning and block releases containing fixable HIGH or CRITICAL vulnerabilities according to the configured policy.
- **Secure CI/CD:** Authenticate to AWS using IAM OIDC federation.
- **Image Publishing & Traceability:** Publish approved container images to Amazon ECR and record image tags, digests, and source commits.
- **Infrastructure as Code:** Manage AWS infrastructure using Terraform and remote state in Amazon S3.
- **Kubernetes Verification:** Deploy manifests to a temporary kind cluster and verify rollout completion, replica readiness, and health probes.
- **Drift Detection & Recovery:** Change the replica count, identify differences with `kubectl diff`, and restore the declared configuration.
- **Controlled Teardown:** Use a manually triggered destruction workflow with plan review and protected-environment approval.
- **Operational Evidence:** Retain workflow artifacts, logs, and test results to document implementation and troubleshooting.

**Tech Stack:** Python · Docker · GitHub Actions · Trivy · AWS IAM · OIDC · Amazon ECR · Terraform · Amazon S3 · Kubernetes · kind · kubectl · Bash · Git

**Engineering Focus:** DevSecOps · Container security · CI/CD · Kubernetes · Infrastructure as Code · Release traceability · Drift recovery

*Environment note: Kubernetes deployment and recovery tests run on a temporary kind cluster in GitHub Actions; this project does not claim a persistent production EKS deployment.*

[Explore the repository and implementation evidence →](https://github.com/imed3721/project-web-slinger)

---

## ⚙️ My Engineering Approach

- **Automation:** Reduce repetitive manual work through scripts and CI/CD workflows.
- **Infrastructure as Code:** Define and manage cloud resources using version-controlled configuration.
- **Security:** Apply least-privilege access, secure authentication, and automated vulnerability checks.
- **Reliability:** Test changes, investigate failures, and verify recovery behaviour.
- **Observability:** Use metrics, logs, and alerts to understand infrastructure and application health.
- **Continuous Improvement:** Learn from implementation challenges, troubleshoot issues, and document engineering decisions.

---

## 📚 Currently Learning & Improving

- **AWS:** Deepening my understanding of IAM, networking, serverless services, and cloud infrastructure.
- **Terraform:** Improving infrastructure design, remote state management, and drift detection.
- **Kubernetes:** Developing deployment, troubleshooting, and workload recovery skills.
- **DevSecOps:** Exploring secure CI/CD, container scanning, and credential management.
- **Linux & Scripting:** Strengthening command-line administration, Bash automation, and Python fundamentals.
- **Cloud Operations:** Improving monitoring, incident troubleshooting, and infrastructure lifecycle management.

---

## 🤝 Let's Connect

I'm interested in **Junior DevOps Engineer, Junior Cloud Engineer, and Cloud Support Engineer** opportunities where I can contribute, learn from experienced engineers, and continue developing my cloud engineering skills.

- **LinkedIn:** [Connect with me](https://www.linkedin.com/in/demi-a-186443200/)
- **Email:** [demialabi11@outlook.com](mailto:demialabi11@outlook.com)
- **GitHub:** [Explore my projects](https://github.com/imed3721)

---

*Building practical cloud engineering skills, one project at a time.* ☁️
