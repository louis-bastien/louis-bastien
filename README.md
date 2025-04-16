# 👋 Hi, I'm Louis Bastien

I'm a **founder-turned-software engineer** with over 10 years of experience in infrastructure, server management, and web hosting. After running Obambu, a hosting company serving 2,000+ clients, I transitioned into hands-on engineering—building backend systems, web apps, and automation tools.

At **42 School**, I’ve completed projects ranging from low-level C/C++ system programming to full-stack web applications using **Python**, **Django**, and **JavaScript**. I’ve developed REST APIs, real-time features, and scalable backend logic—deploying services with **Docker**, **CI/CD pipelines**, and AWS.

I'm currently:
- Deepening my full-stack skills with **Node.js** and **TypeScript**
- Adding **Redis Pub/Sub** and **Celery** into personal tools like `cPsentry`
- Learning **Terraform** and **Kubernetes** for production-ready infrastructure

## 🧰 Tech Toolbox

#### 🖥️ Languages
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

#### 🧩 Frameworks
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)

#### ⚙️ DevOps
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Vault](https://img.shields.io/badge/Vault-000000?style=for-the-badge&logo=vault&logoColor=white)

#### 🚀 Learning
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)

---

## 🏫 42 School Progress

I’m currently a student at **42**, a rigorous peer-to-peer software engineering program. Projects range from low-level C to full-stack and DevOps challenges.

[![lbastien's 42 stats](https://badge.mediaplus.ma/colorfulwaves/lbastien?1337Badge=off&UM6P=off)](https://github.com/oakoudad/badge42)


## 🚀 Projects

### Transcendence 
[![Repo](https://img.shields.io/badge/GitHub-Transcendence-blue?logo=github)](https://github.com/louis-bastien/ft_transcendence-showcase)

A **multiplayer Pong web app** with:
- **Full-stack**: Django (backend) + JavaScript/HTML/CSS (frontend)
- **Docker**: Containerized services with dedicated environments for dev and prod
- **AWS deployment**: EC2 hosting, S3 for storage (Vault secrets), automatic deployment via GitHub Actions
- **Monitoring**: Prometheus/Grafana setup with alerting rules
- Developed both **local (offline)** and **remote (online)** multiplayer game logic, using **WebSockets** for real-time sync
- Contributed to backend and frontend: implemented language-switch functionality using Python i18n and improved interface design and UX
---

### cPsentry 
[![Repo](https://img.shields.io/badge/GitHub-cPsentry-blue?logo=github)](https://github.com/louis-bastien/cPsentry)

A **custom server monitoring/security tool** for cPanel and KVM-based infra:
- **Python** + **Flask** + some **Bash**  
- Tracks mail queues, DB status, Apache health, filesystem usage  
- Telegram alerts and dynamic IP blocking with iptables  

---

### Inception 
[![Repo](https://img.shields.io/badge/GitHub-Inception-blue?logo=github)](https://github.com/louis-bastien/inception)

Multi-container **Docker Compose** project simulating a production-like local hosting environment:
- Hosts **WordPress (PHP-FPM)**, **Redis** caching, **MariaDB**, Adminer, FTP, **MailHog**, and a static site built with **HTML/Tailwind CSS**  
- Demonstrates container orchestration, network isolation, volume persistence, and SSL configuration  
- Focused on modular service design and local development workflows

---

### Minishell & IRC

[![Minishell](https://img.shields.io/badge/GitHub-Minishell-blue?logo=github)](https://github.com/louis-bastien/minishell)
[![IRC](https://img.shields.io/badge/GitHub-IRC-blue?logo=github)](https://github.com/louis-bastien/IRC)

- **Minishell**: A tiny Unix shell in C, managing signals, redirections, pipes, and built-in commands  
- **IRC**: A socket-based IRC server in C++, handling concurrency (epoll), RFC compliance, and network protocols  

These projects showcase my **C/C++** skills and low-level understanding of Unix systems.

---

## 🌱 Current Focus

- **Infrastructure as Code**: Learning Terraform to provision cloud infrastructure in a repeatable, scalable way  
- **Container Orchestration**: Exploring Kubernetes and Helm for production-grade service deployment and scaling  
- **Secrets Management**: Moving from entrypoint-based Vault injection to using the **Vault Agent Sidecar Injector** for more secure and maintainable secret delivery  
- **Tooling Improvements**: Actively extending [cPsentry](https://github.com/louis-bastien/cPsentry) with:
  - Safer `iptables` interactions (manual IP unblocking + better control)
  - Unifying monitoring for both **KVM hypervisors** and **cPanel servers** into a single app

## 📫 Get in Touch

- **LinkedIn**: [linkedin.com/in/louisbastien](https://www.linkedin.com/in/louisbastien)  
- **Email**: louisbas@hotmail.fr

<!-- End of README -->
