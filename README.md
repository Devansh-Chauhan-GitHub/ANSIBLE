# ANSIBLE
🔷 What is Ansible?

Ansible is primarily used for configuration management, automation, and application deployment in infrastructure environments.

# Ansible – Major Use Cases (Interview Guide)

## What is Ansible?

Ansible is an IT automation tool primarily used for configuration management, application deployment, orchestration, and environment automation across servers.

---

# Major Use Cases of Ansible

## 1) Configuration Management

Ensuring systems are always in the desired state.

Examples:

* Ensure Docker is installed
* Ensure specific package version
* Ensure NGINX service is running
* Ensure configuration files exist with correct content

Interview Line:
"We use Ansible to maintain consistent configuration across multiple environments and prevent configuration drift."

---

## 2) Application Deployment

Automating application releases to servers.

Examples:

* Pull latest application code
* Restart services
* Update configuration files
* Run database migrations

Commonly integrated with CI/CD tools like Jenkins or GitHub Actions.

Interview Line:
"We integrate Ansible into CI/CD pipelines for automated and repeatable deployments."

---

## 3) Infrastructure Provisioning (Limited Use)

Ansible can provision infrastructure such as VMs and networking resources, though tools like Terraform are generally preferred for full infrastructure lifecycle management.

---

## 4) Environment Bootstrapping

Automating setup of newly created servers.

Examples:

* Install Docker
* Install monitoring agents
* Configure system users
* Apply security hardening

One command can make a fresh VM production-ready.

---

## 5) Security & Compliance Automation

Automating security-related configurations.

Examples:

* OS hardening
* SSH configuration
* Patch management
* Disable root login
* Configure firewall rules

Useful in enterprise and production environments.

---

## 6) Multi-Server Orchestration

Coordinating actions across multiple server types.

Example workflow:

* Deploy application on web servers
* Restart application services
* Run database migrations
* Clear cache

Ensures correct execution order across distributed systems.

---

## 7) Hybrid / Multi-Cloud Management

Ansible can manage:

* Public cloud (GCP, AWS, Azure)
* On-prem servers
* Hybrid environments

Provides centralized automation across diverse infrastructure.

---

# Typical Enterprise Workflow

Terraform → Create Infrastructure
Ansible → Configure Infrastructure
CI/CD → Deploy Application
Monitoring → Observe System

Ansible plays a critical role in the configuration and automation layer.

---

# Concise Interview Answer

"Ansible is primarily used for configuration management, automated application deployment, environment bootstrapping, security hardening, and orchestration across multiple servers. It is commonly integrated with CI/CD pipelines to ensure consistent and repeatable infrastructure management."
