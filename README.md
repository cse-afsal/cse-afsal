<!-- ======================= HEADER ======================= -->
<h1 align="center">Hi, I'm Afsal S 👋</h1>
<h3 align="center">Aspiring Software Engineer · AI Enthusiast</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=3000&pause=1000&color=00F700&center=true&vCenter=true&repeat=true&width=700&lines=Aspiring+Full+Stack+Developer;Python+%7C+Django+%7C+React;AI+%26+Web+Development+Enthusiast;Building+Projects+and+Learning+Every+Day" alt="Typing animation" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=cse-afsal&label=Profile%20Views&color=0e75b6&style=flat-square" alt="Profile views" />
  <img src="https://img.shields.io/github/followers/cse-afsal?label=Followers&style=flat-square&logo=github" alt="Followers" />
  <img src="https://img.shields.io/badge/Open%20to-Internships%20%26%20Collaboration-2ea44f?style=flat-square" alt="Open to opportunities" />
</p>

---

## 👨‍💻 About Me

I'm a second-year Computer Science student focused on full stack web development and AI. I enjoy turning ideas into real, working products and sharpening my fundamentals along the way.

- 🎓 Second Year CSE Student
- 💻 Full Stack Web Development & AI
- 🐍 Learning Python, Django, React & Data Structures and Algorithms
- 🧩 Practicing problem solving on LeetCode
- 🚀 Building real-world projects

---

## 🛠️ Tech Stack

**Languages**

<p>
  <img src="https://skillicons.dev/icons?i=python,cpp,c,js,html,css&theme=dark" alt="Languages" />
</p>

**Frameworks & Libraries**

<p>
  <img src="https://skillicons.dev/icons?i=django,react,nodejs,tailwind&theme=dark" alt="Frameworks" />
</p>

**Tools & Platforms**

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode,figma,mysql&theme=dark" alt="Tools" />
</p>

---

## 🎯 Current Focus

| Area | What I'm working on |
| :-- | :-- |
| **Backend** | Building APIs and apps with Django |
| **AI** | Developing AI-powered web applications |
| **Problem Solving** | Daily DSA practice |
| **Frontend** | Improving UI/UX skills |
| **DevOps** | Deployment and cloud basics |

---

## 📌 Featured Project

### 🤖 AI Mock Interview Platform

An AI-powered mock interview website that helps candidates practice and improve.

- 📄 Resume-based interview questions
- 💬 Real-time AI feedback
- 🎥 Video interview support
- 🧾 Built-in resume builder
- 📈 Performance analytics

<!-- Add your repo link below, e.g. [View Repository](https://github.com/cse-afsal/your-repo-name) -->
<!-- [🔗 View Repository](https://github.com/cse-afsal/REPO-NAME) -->

---

## 📊 GitHub Analytics

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=cse-afsal&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&include_all_commits=true&cache_seconds=21600" alt="GitHub stats" />
  <img height="170" src="https://streak-stats.demolab.com/?user=cse-afsal&theme=tokyonight&hide_border=true&background=0D1117" alt="GitHub streak" />
</p>

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=cse-afsal&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&langs_count=8&cache_seconds=21600" alt="Top languages" />
</p>

### 📈 Contribution Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=cse-afsal&theme=tokyo-night&hide_border=true&bg_color=0D1117&area=true" alt="Contribution graph" />
</p>

---

name: Generate Contribution Snake

on:
  schedule:
    - cron: "0 */12 * * *" # every 12 hours
  workflow_dispatch:
  push:
    branches:
      - main

permissions:
  contents: write

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-snake.svg
            dist/github-snake-dark.svg?palette=github-dark

      - uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

## 🌐 Connect With Me

<p align="left">
  <a href="mailto:cse.afxal@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
  </a>
  <a href="https://www.linkedin.com/in/YOUR-LINKEDIN/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/cse-afsal">
    <img src="https://img.shields.io/badge/GitHub-171515?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

---

<p align="center"><i>Keep learning · Keep building · Keep growing</i></p>
