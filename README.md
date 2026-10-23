# Hi, I'm Demi Alabi 👋

### Aspiring Cloud & DevOps Engineer | AWS | Terraform | CI/CD | DevSecOps

I'm developing practical cloud engineering skills through hands-on projects focused on **AWS infrastructure, Infrastructure as Code, CI/CD automation, container security, monitoring, and operational reliability**.

My portfolio demonstrates how I automate deployments, provision cloud resources, test infrastructure changes, troubleshoot failures, and apply security and reliability practices throughout the DevOps lifecycle.

📍 London, United Kingdom

## 🛠️ Technologies & Tools

<p align="left">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS" />
  <img src="https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
</p>

| Area | Technologies & Skills |
|---|---|
| **Cloud** | AWS Lambda, EC2, S3, VPC, IAM, RDS, ALB, CloudWatch |
| **Infrastructure as Code** | Terraform, remote state, state locking, drift detection |
| **CI/CD** | GitHub Actions, automated testing, deployment and teardown workflows |
| **Containers** | Docker, Amazon ECR, Kubernetes, kind |
| **Security** | IAM, OIDC federation, least-privilege access, Trivy, Secrets Manager |
| **Monitoring** | CloudWatch logs, metrics and alarms |
| **Scripting & Version Control** | Python fundamentals, Bash, Linux, Git, GitHub |

*My project repositories document the technologies and implementation evidence. Some additional tools and services remain part of my ongoing learning.*

---

## 🚀 Featured Projects

### 🗺️ [Project Atlas — Serverless AWS DevOps](https://github.com/imed3721/project-atlas-devops)

**Automating a serverless AWS application with Terraform, secure CI/CD, monitoring, and operational testing.**

Project Atlas provisions a Python health-check application on AWS Lambda using Terraform and GitHub Actions. It demonstrates federated AWS authentication, automated testing, infrastructure drift detection, and controlled resource management.

**Key Engineering Highlights**

- **Infrastructure as Code:** Provision Lambda, IAM roles, CloudWatch logging, and a Lambda Function URL using Terraform.
- **Secure CI/CD:** Authenticate GitHub Actions to AWS using OIDC and temporary credentials.
- **Automated Testing:** Run Python unit tests and Terraform validation.
- **Security Testing:** Verify IAM trust-policy restrictions through negative authentication testing.
- **Monitoring:** Configure CloudWatch logging, seven-day log retention, and a Lambda error alarm.
- **Drift & Failure Testing:** Introduce infrastructure changes and application-test failures to validate detection and recovery workflows.
- **Controlled Teardown:** Implement a confirmation-gated Terraform destruction workflow.

**Tech Stack:** AWS Lambda · IAM · OIDC · S3 · CloudWatch · Terraform · GitHub Actions · Python

**Engineering Focus:** Serverless computing · Secure authentication · Infrastructure automation · Monitoring · Troubleshooting

[Explore the repository and implementation evidence →](https://github.com/imed3721/project-atlas-devops)

---

### 🎯 [Operation GoldenEye — AWS Infrastructure Automation](https://github.com/imed3721/operation-goldeneye)

**A James Bond-inspired DevOps project demonstrating secure AWS infrastructure provisioning, cloud networking, CI/CD automation, and infrastructure lifecycle management.**

Operation GoldenEye uses Terraform and GitHub Actions to provision AWS networking resources and an internet-facing Application Load Balancer. It demonstrates OIDC authentication, remote Terraform state management, drift detection, and controlled teardown.

**Key Engineering Highlights**

- **Infrastructure as Code:** Define AWS networking and load-balancing resources using Terraform.
- **Secure CI/CD:** Authenticate GitHub Actions to AWS through IAM OIDC federation.
- **Cloud Networking:** Configure a VPC, two public subnets across Availability Zones, an internet gateway, route tables, and security groups.
- **Load Balancing:** Deploy an internet-facing ALB with an HTTP listener and a fixed demonstration response.
- **Remote State:** Store Terraform state in Amazon S3 with versioning and Block Public Access.
- **Drift Detection:** Investigate infrastructure changes using Terraform plans.
- **Lifecycle Management:** Automate validation, deployment, and teardown workflows.

**Tech Stack:** AWS · Terraform · GitHub Actions · IAM · OIDC · S3 · VPC · Application Load Balancer · Git

**Engineering Focus:** Cloud networking · Infrastructure automation · Secure authentication · Change management

[Explore the repository and implementation evidence →](https://github.com/imed3721/operation-goldeneye)

---

### ☁️ [AWS DevOps Platform — Infrastructure & Database Automation](https://github.com/imed3721/aws-devops-platform)

**A hands-on AWS project demonstrating secure infrastructure provisioning, private networking, database management, monitoring, and operational troubleshooting.**

This project uses Terraform and GitHub Actions to manage AWS infrastructure, including private networking and Amazon RDS for PostgreSQL. It explores secure authentication, remote state management, monitoring, and infrastructure lifecycle operations.

**Key Engineering Highlights**

- **Infrastructure as Code:** Provision AWS resources through version-controlled Terraform configuration.
- **Secure CI/CD:** Use GitHub Actions and OIDC to authenticate to AWS without long-lived access keys.
- **Private Networking:** Configure VPC networking, private subnets, routing, and security groups.
- **Database Infrastructure:** Provision Amazon RDS for PostgreSQL within private networking.
- **Remote State:** Manage Terraform state in Amazon S3 with state locking.
- **Monitoring & Alerting:** Configure CloudWatch alarms for database CPU utilisation and available storage.
- **Secrets Management:** Integrate AWS Secrets Manager and IAM permissions.
- **Drift Detection:** Identify configuration differences and investigate reconciliation.
- **Lifecycle Management:** Automate infrastructure validation, deployment, and controlled teardown.

**Tech Stack:** AWS · Terraform · GitHub Actions · IAM · OIDC · S3 · VPC · RDS · PostgreSQL · CloudWatch · Secrets Manager

**Engineering Focus:** Infrastructure as Code · Cloud networking · Database infrastructure · Monitoring · Secure access

[Explore the repository and implementation evidence →](https://github.com/imed3721/aws-devops-platform)

---

### 🕷️ [Project Web-Slinger — DevSecOps & Container Security](https://github.com/imed3721/project-web-slinger)

**A DevSecOps project demonstrating secure software delivery, container vulnerability scanning, Kubernetes deployment verification, and infrastructure drift recovery.**

Project Web-Slinger combines Python, Docker, GitHub Actions, Terraform, and Kubernetes testing. It integrates Trivy vulnerability scanning, AWS OIDC authentication, Amazon ECR image publishing, and automated validation.

**Key Engineering Highlights**

- **Continuous Integration:** Automate application tests and configuration checks through GitHub Actions.
- **Containerisation:** Package a Python application into a Docker image.
- **Container Security:** Use Trivy to scan images and block releases with fixable HIGH or CRITICAL vulnerabilities under the configured policy.
- **Secure CI/CD:** Authenticate to AWS through IAM OIDC federation.
- **Image Traceability:** Publish approved images to Amazon ECR and record tags, digests, and source commits.
- **Infrastructure as Code:** Manage AWS resources using Terraform and remote state in Amazon S3.
- **Kubernetes Verification:** Deploy manifests to a temporary kind cluster and verify rollouts, replica readiness, and health probes.
- **Drift Detection & Recovery:** Detect replica-count changes using `kubectl diff` and restore the declared configuration.
- **Controlled Teardown:** Use a manually triggered Terraform destruction workflow with plan review and protected-environment approval.

**Tech Stack:** Python · Docker · GitHub Actions · Trivy · AWS IAM · OIDC · Amazon ECR · Terraform · S3 · Kubernetes · kind · kubectl · Bash · Git

**Engineering Focus:** DevSecOps · Container security · CI/CD · Kubernetes · Infrastructure as Code · Release traceability

*Environment note: Kubernetes deployment and recovery tests run on a temporary kind cluster in GitHub Actions; this project does not claim a persistent production EKS deployment.*

[Explore the repository and implementation evidence →](https://github.com/imed3721/project-web-slinger)

---

## ⚙️ My Engineering Approach

- **Automation:** Reduce repetitive manual work through scripts and CI/CD workflows.
- **Infrastructure as Code:** Manage cloud resources through version-controlled configuration.
- **Security:** Apply least-privilege access, secure authentication, and automated vulnerability scanning.
- **Reliability:** Test changes, investigate failures, and validate recovery behaviour.
- **Observability:** Use logs, metrics, and alarms to understand application and infrastructure health.
- **Documentation:** Record implementation decisions, testing evidence, troubleshooting, and lessons learned.

## 📚 Currently Learning & Improving

- **AWS:** Deepening my knowledge of IAM, networking, serverless services, and cloud operations.
- **Terraform:** Improving infrastructure design, state management, and drift detection.
- **Kubernetes:** Developing deployment, troubleshooting, and workload recovery skills.
- **DevSecOps:** Exploring secure CI/CD, container scanning, and credential management.
- **Linux & Scripting:** Strengthening command-line administration, Bash automation, and Python fundamentals.
- **Monitoring:** Building a deeper understanding of observability, alerting, and operational troubleshooting.

## 🤝 Let's Connect

I'm interested in **Junior DevOps Engineer, Junior Cloud Engineer, and Cloud Support Engineer** opportunities where I can contribute, learn from experienced engineers, and continue developing my cloud engineering skills.

- 💼 **LinkedIn:** [Connect with me](https://www.linkedin.com/in/demi-a-186443200/)
- 📧 **Email:** [demialabi11@outlook.com](mailto:demialabi11@outlook.com)
- 🐙 **GitHub:** [Explore my repositories](https://github.com/imed3721)

---

*Building practical cloud engineering skills, one project at a time.* ☁️
