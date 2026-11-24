<div align="center">

<img src="assets/hero.svg" width="100%" alt="Yashraj Ayaskanta Garnayak, Cloud and DevOps, M.Sc. High Integrity Systems at Frankfurt UAS. Animated header with a drifting gradient and a small network of connected nodes." />

<a href="https://github.com/Yashraj-Garnayak">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=2F81F7&center=true&vCenter=true&width=620&lines=Cloud+%26+DevOps+%7C+AWS+%C2%B7+Terraform+%C2%B7+Kubernetes;M.Sc.+High+Integrity+Systems+%40+Frankfurt+UAS;Open+to+Werkstudent+roles+in+Germany" alt="Typing intro" width="100%" />
</a>

📍 Frankfurt am Main, Germany &nbsp;·&nbsp; 🎓 Frankfurt UAS &nbsp;·&nbsp; ☁️ AWS Certified Cloud Practitioner

<a href="https://www.linkedin.com/in/yashraj-ayaskanta-garnayak-3162471b1/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://disarj.hashnode.dev"><img src="https://img.shields.io/badge/Blog-Hashnode-2962FF?style=for-the-badge&logo=hashnode&logoColor=white" alt="Hashnode blog" /></a>
<a href="mailto:yashrajgarnayak.lev@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

</div>

---

## 🧑‍💻 About me

- 🎓 **M.Sc. High Integrity Systems** student at Frankfurt University of Applied Sciences (since 10/2026)
- ☁️ I build and automate cloud infrastructure: **AWS, Terraform, Docker, Kubernetes, CI/CD**
- 🔬 I like measuring things honestly: my CDN project reports where ML helps *and* where it doesn't
- ✍️ I write beginner-friendly DevOps guides on [Hashnode](https://disarj.hashnode.dev)
- 🏆 **1st place**, Brain1 48-hour Hackathon (10/2026)
- 🇩🇪 Learning German (A1) · 💼 **Looking for Werkstudent roles in Cloud / DevOps / Platform / SRE**

---

## 🚀 Featured project

### [Predictive CDN Cache](https://github.com/Yashraj-Garnayak/predictive-cdn-cache)

> Can a model that predicts next-hour popularity beat classic cache rules on real CDN traffic?

Replays **real Meta CDN traces** (3 edge clusters, ~57M requests → 2.9M hourly rows) through four cache policies: **LRU, LFU, Predictive and Hybrid**, with a gradient-boosting demand model and tests against data leakage.

| Region | LRU | LFU | Predictive | **Hybrid** |
|:--|:--:|:--:|:--:|:--:|
| eag | 80.97 | 69.13 | 80.98 | **81.18** |
| nha | 50.53 | 21.42 | 50.55 | **50.93** |
| prn | 67.42 | 56.54 | 67.43 | **67.80** |

<sub>Hit rate %, cache size 200, held-out hours. Hybrid beat LRU in every region by 0.2–0.4 pts, stable across 3 seeds.</sub>

**Stack:** Python · scikit-learn · FastAPI · WebSockets · D3 · PostgreSQL on Azure · Docker · pytest (85 tests)

---

## 📂 More projects

| Project | What it shows |
|:--|:--|
| 🏆 [**Tile Rush: Adaptive Reflex Trainer**](https://github.com/Yashraj-Garnayak/Brain_1_hackathon) | 1st place, Brain1 Hackathon. Team of four; web + Android game on one shared API |
| [**Three-Tier App on AWS**](https://github.com/Yashraj-Garnayak/three-tier-project) <sub>(course-based)</sub> | Terraform for a Jenkins server on AWS (VPC, subnet, IGW, route table, SG, EC2, IAM) + Kubernetes manifests |
| [**Two-Tier Flask App**](https://github.com/Yashraj-Garnayak/two-tier-flask-app) <sub>(course-based)</sub> | Docker + Jenkins CI/CD pipeline |

---

## ☁️ DevOps concepts in motion

<p align="center">
  <img src="assets/alb.svg" width="430" alt="Animation: an Application Load Balancer rotates requests across three servers, routes /api and /images to separate target groups, stops sending traffic to a server that fails its health check, and resumes when it recovers." />
  <img src="assets/asg.svg" width="430" alt="Animation: an Auto Scaling Group adds a third EC2 instance when CPU passes 70 percent and a CloudWatch alarm fires, then scales back in when traffic drops. Desired capacity goes 2, 3, 2 within min 2 and max 4." />
</p>

---

## 🛠️ Tech stack

**Cloud**<br/>
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS" />
<img src="https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" alt="Azure" />

**IaC & CI/CD**<br/>
<img src="https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white" alt="Terraform" />
<img src="https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white" alt="Jenkins" />
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />

**Containers & Orchestration**<br/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes" />

**Monitoring**<br/>
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" alt="Prometheus" />
<img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" alt="Grafana" />
<img src="https://img.shields.io/badge/CloudWatch-FF4F8B?style=flat-square&logo=amazoncloudwatch&logoColor=white" alt="CloudWatch" />

**Languages & Tools**<br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Bash" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />

---

## ✍️ Popular writing

- 📘 [How to Install Jenkins on AWS EC2 (step-by-step for beginners)](https://disarj.hashnode.dev/how-to-install-jenkins-on-aws-ec2-a-step-by-step-guide-for-beginners)
- ⚖️ [How to create an Amazon Application Load Balancer](https://disarj.hashnode.dev/amazon-elastic-load-balancer-a-step-by-step-guide)
- 💾 [Step-by-step guide to EBS volumes in AWS](https://disarj.hashnode.dev/all-about-elastic-block-store-ebs)

---

## 🌱 Currently

- 🔧 Applying for Werkstudent roles in Cloud/DevOps
- 📚 M.Sc. coursework in High Integrity Systems
- 🗣️ Learning German

---

## 📊 GitHub stats

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=Yashraj-Garnayak&show_icons=true&hide_border=true&theme=github_dark&count_private=true" />
  <img src="https://github-readme-stats.vercel.app/api?username=Yashraj-Garnayak&show_icons=true&hide_border=true&count_private=true" alt="GitHub stats" width="49%" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=Yashraj-Garnayak&layout=compact&hide_border=true&theme=github_dark" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Yashraj-Garnayak&layout=compact&hide_border=true" alt="Top languages" width="49%" />
</picture>

</div>

---

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Yashraj-Garnayak/Yashraj-Garnayak/output/github-contribution-grid-snake-dark.svg" />
  <img alt="Animated snake eating my GitHub contribution graph" src="https://raw.githubusercontent.com/Yashraj-Garnayak/Yashraj-Garnayak/output/github-contribution-grid-snake.svg" />
</picture>

</div>

---

<div align="center">

💬 **Hiring a Werkstudent for Cloud or DevOps in Germany?** [Let's connect on LinkedIn](https://www.linkedin.com/in/yashraj-ayaskanta-garnayak-3162471b1/)

</div>
