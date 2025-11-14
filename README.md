<div align="center">

<img src="https://raw.githubusercontent.com/fr0gger03/fr0gger03/main/assets/header.svg" alt="Tom Twyman - Solutions Architect" width="100%"/>

### @fr0gger03

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/tomtwyman)
[![Blog](https://img.shields.io/badge/📝_Blog-occasional--it.com-006699?style=flat-square)](https://www.occasional-it.com)

</div>

---

<div align="center">

[![Python](https://img.shields.io/badge/Python-3.9%2B-006699?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-3.1-22aadd?style=flat-square&logo=flask&logoColor=white)](https://flask.palletsprojects.com/)
[![Docker](https://img.shields.io/badge/Docker-Compose-004366?style=flat-square&logo=docker&logoColor=white)](https://www.docker.com/)
[![AWS](https://img.shields.io/badge/AWS-Lambda-0693e3?style=flat-square&logo=amazon-aws&logoColor=white)](https://aws.amazon.com/lambda/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-006699?style=flat-square&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![k3s](https://img.shields.io/badge/k3s-Kubernetes-22aadd?style=flat-square&logo=kubernetes&logoColor=white)](https://k3s.io/)

</div>

---

## 👨‍💻 About Me

I'm a career, presales-focused solutions architect / systems engineer focused on building practical solutions that solve real problems. My work spans full-stack web applications, cloud automation, and self-hosted infrastructure. Though I don't consider myself a developer, I am an avid hobbyist and a technologist - I enjoy working with Python, containerization, and building tools that make infrastructure management and development workflows more fun and efficient.

- 🔧 python-based CLI tools for extending infrastructure management
- 🔧 Building production-ready Flask applications with comprehensive test coverage
- 🐳 Containerizing everything with Docker multi-stage builds
- ☁️ Automating AWS Lambda development and VMware Cloud workflows
- 🏠 Running a Raspberry Pi k3s cluster with self-hosted services
- 🔐 Managing secrets securely with 1Password CLI

---

## 🛠️ Tech Stack

### Languages & Frameworks
- **Python** (3.9-3.12) - Flask, SQLAlchemy, Pandas, NumPy, Pydantic
- **SQL** - PostgreSQL, database design and optimization
- **Frontend** - HTML/CSS, Jinja2 templates
- **Shell** - Bash/Zsh scripting for automation

### DevOps & Cloud
- **Containerization** - Docker, Docker Compose, multi-stage builds
- **Cloud Platforms** - AWS Lambda, VMware Cloud on AWS
- **Orchestration** - Kubernetes (k3s)
- **CI/CD** - GitHub Actions, automated deployments
- **Security** - Docker Scout, Let's Encrypt/SSL management

### Infrastructure & Tools
- **VMware Datacenter Infrastructure** - VMware ESXi / vSphere / VMware Cloud Foundation, VMware vSAN, VMC on AWS
- **Nutanix Datacenter Infrastructure** - Nutanix Cloud Infrastructure, Nutanix Unified Storage, Nutanix Cloud Clusters
- **Web Servers** - nginx (reverse proxy, load balancing)
- **Databases** - PostgreSQL, database migrations
- **Version Control** - Git, GitHub
- **Testing** - pytest, pytest-flask, testcontainers
- **Monitoring** - Datadog integration
- **Hardware** - Raspberry Pi cluster with k3s

### 📜 Industry Certifications
- [View all my badges on Credly](https://credly.com/users/tom-twyman)- Nutanix, VMware, Dell, EMC, Cisco
- [View all my Microsoft certifications- expired](https://learn.microsoft.com/en-us/users/thomastwyman-0902/transcript/d9kr0sw6jl4wpz0?tab=credentials-tab&source=docs) - MCP, MCT, MCSAx2, MCSEx2
- Expired Citrix Certifications - CCAx3, CCSPx2, CCEA, CCIA, CCI
- [Photographic evidence for all the old stuff!](https://photos.app.goo.gl/R4ZAnm2dsoE91cuw5)

---

## 🚀 Featured Projects

### 📊 [Flask Pandas Data Analysis Platform](https://github.com/fr0gger03/flask_pandas) ⭐

Full-stack web application for Excel data ingestion and transformation using Pandas.

**Highlights:**
- User authentication with Flask-Login and bcrypt
- PostgreSQL database with SQLAlchemy ORM
- Comprehensive test suite (100+ tests) with pytest and testcontainers
- Production deployment with Gunicorn, nginx, and Docker Compose
- Excel file processing with Pandas and NumPy

**Tech:** Python • Flask • PostgreSQL • Docker • nginx • Pandas

---

### 🔄 [AWS Lambda Docker Development](https://github.com/fr0gger03/aws-python-lambda-demo)

Streamlined Docker-based development workflow for AWS Lambda functions with local testing.

**Problem Solved:** Minimize AWS dependency during development while maintaining consistent deployment experience.

**Highlights:**
- Single multi-stage Dockerfile with ARG-based function selection
- Local testing with AWS Lambda Runtime Interface Emulator
- Support for multiple Lambda functions from one codebase
- Docker Compose integration for rapid development

**Tech:** Python • Docker • AWS Lambda • boto3 • Datadog

---

### ☁️ [VMware Cloud Automation Suite](https://github.com/fr0gger03/vmware-cloud-sizer-companion-cli)

Python CLI tools for VMware Cloud on AWS automation and management.

**Projects:**
- **[VMware Cloud Sizer CLI](https://github.com/fr0gger03/vmware-cloud-sizer-companion-cli)** - Automate VMware Cloud sizing via API for presales workflows
- **[Python Client for VMC](https://github.com/fr0gger03/python-client-for-vmware-cloud-on-aws)** - SDDC automation and management
- **[SDDC Import/Export](https://github.com/fr0gger03/sddc-import-export-for-vmware-cloud-on-aws)** - Backup and restore network/security configurations

**Highlights**
- Comprehensive, multi-level command/argument structure with argparse
- Use of JSON payloads to fetch / write data to cloud-based REST APIs

**Use Case:** Enable VMware and partner presales teams to script and automate cloud sizing and SDDC management.

**Tech:** Python • VMware Cloud APIs • CLI development

---

### 🐳 [Docker Security & Demos](https://github.com/fr0gger03/docker-scout-demo)

Demonstrations of Docker containerization best practices and security scanning.

**Highlights:**
- Docker Scout integration for vulnerability scanning
- Multi-stage build optimization
- Security best practices for production containers

**Tech:** Docker • Dockerfile • Docker Scout

---

### 🐳 [MS Office Powerpoint Automation ](https://github.com/fr0gger03/skurge-pptx)

Using the python-pptx library to automate creation of Powerpoint slides using a template.

**Highlights**
- JSON paylod with content in table format
- Feeding content into table / slide objects with python-pptx

---

### 🏠 Self-Hosted Infrastructure

Raspberry Pi k3s cluster running production services with SSL and reverse proxy.

**Highlights:**
- AudioBookshelf server with dual SSL certificates (Let's Encrypt + self-signed)
- nginx reverse proxy with HTTP/2, WebSocket support
- Automated certificate management and renewal
- Production deployment on 4-node Raspberry Pi cluster

**Tech:** Docker • k3s • nginx • Raspberry Pi • Let's Encrypt

---

## 📈 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=fr0gger03&show_icons=true&theme=default&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=fr0gger03&layout=compact&theme=default&hide_border=true)

---

## 🔍 Currently Working On

- Enhancing test coverage and CI/CD pipelines for Flask applications
- Exploring container orchestration patterns with k3s
- Building CLI tools for infrastructure automation
- Expanding self-hosted service portfolio on Raspberry Pi cluster

---

## 📫 Connect With Me

<div align="center">
  <a href="https://www.linkedin.com/in/tomtwyman">
    <img src="https://img.shields.io/badge/LinkedIn-Tom_Twyman-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://www.occasional-it.com">
    <img src="https://img.shields.io/badge/Blog-Occasional_IT-006699?style=for-the-badge&logo=wordpress&logoColor=white" alt="Blog" />
  </a>
</div>

<br>

<div align="center" style="font-family: 'Montserrat', sans-serif;">
  <h3 style="color: #006699;">🚀 Open to Collaborate On</h3>
  <p>
    <strong>Python Web Applications</strong> • <strong>Docker & Containerization</strong><br>
    <strong>Infrastructure Automation</strong> • <strong>Self-Hosted Solutions</strong><br>
    <strong>Cloud Architecture</strong> • <strong>DevOps Tooling</strong>
  </p>
</div>

---

<div align="center">
  <p>
    <em style="color: #006699; font-size: 1.1em;">💡 Always learning, always building</em>
  </p>
  <p style="color: #1e3846;">
    <sub>Check out my <a href="https://www.occasional-it.com" style="color: #22aadd;">blog</a> for technical musings and industry insights</sub>
  </p>
</div>
