# Hi there, I'm Nguyễn Đình Trọng 👋

I am a Software Engineering student at Gia Dinh University, Ho Chi Minh City, Vietnam. I have a strong passion for DevOps, cloud infrastructure, CI/CD pipelines, and system reliability. Rather than just learning theory, I actively practice deploying, scaling, and troubleshooting real-world web applications on live production servers.

* 🎯 **Target Role:** DevOps Intern / Fresher DevOps Engineer
* 📍 **Location:** Ho Chi Minh City, Vietnam
* ✉️ **Email:** [cutrong236@gmail.com](mailto:cutrong236@gmail.com)

---

### 🛠️ Tech Stack & Tools

| Category | Badges |
|---|---|
| **OS & Scripting** | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white) |
| **Cloud & Hosting** | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) |
| **DevOps & CI/CD** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white) |
| **Development** | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) |

---

### 🚀 Featured Production Project

#### 💈 [Salon Dương Chí Website](https://salonduongchi.website)
A full-stack hair salon management and booking web application.
* **Code Repository:** [dinhtron027/wepsalonhair](https://github.com/dinhtron027/wepsalonhair)
* **Production URL:** [salonduongchi.website](https://salonduongchi.website)
* **Architecture:**
  * **Domain & DNS:** Namecheap domain mapped to an AWS EC2 Elastic IP address.
  * **Reverse Proxy:** Host-level Nginx managing SSL termination (Let's Encrypt / Certbot) and routing requests.
  * **Containers:** Multi-container Docker Compose structure hosting a Vite/React frontend container and a Node.js/Express API container.
  * **Database:** MongoDB Atlas (Cloud Database).
  * **CI/CD:** Automated GitHub Actions pipeline deploying to EC2 on push to the `main` branch.

```
User ➔ Namecheap DNS ➔ AWS EC2 (Elastic IP) ➔ Host Nginx (HTTPS Let's Encrypt)
                                                   ├─➔ Frontend Container (Vite Build served by Nginx)
                                                   └─➔ Backend API Container (Express Node.js)
                                                               └─➔ MongoDB Atlas Cloud
```

---

### 🔧 DevOps Practice & Production Troubleshooting

Deploying and maintaining the project on a live production server has given me valuable experience in resolving real-world infrastructure issues:

* 💾 **Disk Space Management:** Diagnosed and fixed server downtime caused by full disks by setting up Docker log rotation and cleaning dangling Docker volumes/images.
* 🛡️ **Reverse Proxy & Routing:** Configured Nginx proxy rules to properly route requests, handle API headers, and serve search-engine optimization files (`sitemap.xml`, `robots.txt`) directly through the container setup without static route fallback errors.
* 🚦 **Port & Process Management:** Resolved port conflicts on the host machine, managed background Node.js processes, and optimized container ports mapping.
* 🔄 **Git & Lock Conflicts:** Handled package compilation and file-system lock conflicts within the CI/CD runners to ensure smooth continuous delivery.
* 📱 **Mobile Responsive Optimizations:** Diagnosed and patched frontend runtime issues related to `localStorage` exceptions in restricted mobile WebViews (e.g., Safari private tabs), safeguarding user authentication and state managers against crashes.

---

### 📚 Currently Learning & Exploring

I am continuously working to expand my infrastructure knowledge, focus on scalability, and improve system observability:

* 🐳 **Kubernetes & Helm** (Container Orchestration & Packaging)
* 🏗️ **Terraform** (Infrastructure as Code)
* 🔄 **Jenkins & ArgoCD** (Advanced CI/CD and GitOps)
* 📊 **Prometheus & Grafana** (System Observability and Metrics Monitoring)

---

### 📊 GitHub Statistics

| | |
|---|---|
| [![Dinhtron027's GitHub Stats](https://github-readme-stats.vercel.app/api?username=dinhtron027&show_icons=true&theme=nord&count_private=true)](https://github.com/dinhtron027) | [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=dinhtron027&layout=compact&theme=nord)](https://github.com/dinhtron027) |

---

### 🤝 Connect with me

* 📧 Email: [cutrong236@gmail.com](mailto:cutrong236@gmail.com)
* 💼 LinkedIn: [Nguyễn Đình Trọng](https://linkedin.com/in/nguyen-dinh-trong)
* 🐙 GitHub Profile: [github.com/dinhtron027](https://github.com/dinhtron027)

*Thanks for visiting my profile! Feel free to reach out if you want to collaborate on DevOps practices or Software Engineering projects.*
