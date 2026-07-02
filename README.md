from pathlib import Path
import pypandoc

md = r"""# Hi 👋, I'm Sabari G

<h3 align="center">Software Engineer • Java Full Stack Developer • Problem Solver</h3>

<p align="center">
Building scalable web applications with Java and continuously improving through DSA, System Design, and real-world projects.
</p>

<p align="center">
  <a href="https://github.com/G-Sabari"><img src="https://komarev.com/ghpvc/?username=G-Sabari&label=Profile%20Views&color=0e75b6&style=flat" /></a>
</p>

---

# 👨‍💻 About Me

- 🎓 Final Year B.Tech Information Technology Student
- 💻 Focused on Java Full Stack Development
- 🌱 Learning Spring Boot, React, MySQL, Docker & AWS
- 📚 Solving DSA daily
- 🚀 Building production-level projects
- 🎯 Goal: Software Engineer at a Product-Based Company (2027)

---

# 🌐 Connect With Me

<p align="center">
<a href="https://linkedin.com/in/YOUR_LINKEDIN"><img src="https://skillicons.dev/icons?i=linkedin"/></a>
&nbsp;&nbsp;
<a href="mailto:YOUR_EMAIL@gmail.com"><img src="https://skillicons.dev/icons?i=gmail"/></a>
&nbsp;&nbsp;
<a href="https://github.com/G-Sabari"><img src="https://skillicons.dev/icons?i=github"/></a>
&nbsp;&nbsp;
<a href="https://leetcode.com/YOUR_USERNAME"><img src="https://skillicons.dev/icons?i=leetcode"/></a>
</p>

---

# 🚀 Tech Stack

### Languages

<img src="https://skillicons.dev/icons?i=java,javascript,html,css,sql"/>

### Frontend

<img src="https://skillicons.dev/icons?i=react,tailwind,bootstrap"/>

### Backend

<img src="https://skillicons.dev/icons?i=spring,nodejs,express"/>

### Database

<img src="https://skillicons.dev/icons?i=mysql,mongodb"/>

### Tools

<img src="https://skillicons.dev/icons?i=git,github,postman,vscode,figma"/>

---

# 🚀 Featured Projects

## 📦 Smart Inventory & Billing System
- Inventory Management
- Billing & Invoice Generation
- Customer Management
- Reports & Analytics

**Tech Stack:** Java • Spring Boot • React • MySQL

## 📊 Mini CRM
- Lead Tracking
- Customer Dashboard
- Sales Pipeline
- Task Management

**Tech Stack:** Java • Spring Boot • React • MySQL

## 🎯 SkillBridge
- ATS Resume Analyzer
- Resume Builder
- AI Mock Interview
- Coding Practice
- Placement Dashboard

**Tech Stack:** Java • Spring Boot • React

---

# 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=G-Sabari&show_icons=true&theme=github_dark&hide_border=true&rank_icon=github&include_all_commits=true&count_private=true"/>

<img height="180em" src="https://streak-stats.demolab.com?user=G-Sabari&theme=github-dark&hide_border=true"/>

<br><br>

<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=G-Sabari&layout=compact&theme=github_dark&hide_border=true&langs_count=8"/>

</div>

---

# 📈 Contribution Graph

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=G-Sabari&theme=github-dark&hide_border=true"/>
</div>

---

# 🏆 GitHub Trophies

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=G-Sabari&theme=tokyonight&no-frame=true&row=1&column=6"/>
</div>

---

# 🎯 Current Focus

- Java
- Spring Boot
- React
- MySQL
- REST APIs
- Spring Security & JWT
- Docker
- AWS
- System Design
- Data Structures & Algorithms

---

# 📚 2026–2027 Goals

- ✅ Solve 500+ DSA Problems
- ✅ Build 3 Production-Level Projects
- ✅ Learn Docker & AWS
- ✅ Learn Microservices
- ✅ Contribute to Open Source
- ✅ Crack a Product-Based Company

---

<div align="center">

## 💬 Favorite Quote

> "First, solve the problem. Then, write the code."

⭐ Thanks for visiting my profile!

</div>
"""

out="/mnt/data/README.md"
pypandoc.convert_text(md,"md",format="md",outputfile=out,extra_args=["--standalone"])
print(out)
