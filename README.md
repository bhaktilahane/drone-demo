IA1 DEVOPS
Bhakti Lahane-16100122093

This repository demonstrates how F5 and NGINX can be deployed and managed using Infrastructure as Code (IaC) and integrated into a lightweight CI/CD pipeline with Drone CI.

🔹 Tools & Technologies

Version Control: GitHub (repo for code & pipeline configs)

CI/CD: Drone (drone.io) – container-native, lightweight alternative to Jenkins

IaC: Terraform – infrastructure provisioning

Configuration Management: Ansible – configuration of F5 & NGINX

Collaboration: Slack – notifications integrated with Drone pipeline

🔹 Workflow

Developer pushes code/config to GitHub.

Drone CI pipeline is triggered.

Terraform provisions infrastructure for F5 and NGINX.

Ansible applies configuration and service setup.

Slack receives notifications about pipeline results.


🔹 Key Highlights

Demonstrates alternative CI/CD tool (Drone) in the DevOps lifecycle.

Combines Terraform + Ansible for IaC and configuration.

Shows end-to-end automation: code → infra → config → notification.

Validates DevOps flexibility beyond traditional tools like Jenkins, Docker, Kubernetes.
