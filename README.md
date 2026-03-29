<h1 align="center">Hi 👋, I'm Abhiram</h1>
<h3 align="center">AI/ML Enthusiast • Builder • Future Entrepreneur</h3>

---

## 🚀 About Me  
- 🔭 Building **ML systems** like *Genka* & *GutMax 360*  
- 👯 Open to collaborating on **AI/ML + real-world projects**  
- 🤝 Looking for help with **deployment & system design**  
- 🌱 Learning **ML, DSA, FastAPI, End-to-End AI Systems**  
- 💬 Ask me about **Python, ML, Projects, Consistency**  
- ⚡ Fun fact: I analyze food labels like datasets 😄  

---

## 🌐 Connect With Me  
<p align="left">
<a href="https://linkedin.com/in/m-sai-abhiram-2a6a372a6" target="blank">
<img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin" />
</a>
<a href="mailto:msabhiram.07@gmail.com">
<img src="https://img.shields.io/badge/Gmail-red?style=for-the-badge&logo=gmail" />
</a>
</p>

---

## 💻 Tech Stack  

### 👨‍💻 Languages  
![Python](https://img.shields.io/badge/python-ffdd54?style=for-the-badge&logo=python&logoColor=black)
![Java](https://img.shields.io/badge/java-orange?style=for-the-badge&logo=openjdk)
![C](https://img.shields.io/badge/c-blue?style=for-the-badge&logo=c)

### 🌐 Web & Backend  
![HTML](https://img.shields.io/badge/html-orange?style=for-the-badge&logo=html5)
![CSS](https://img.shields.io/badge/css-blue?style=for-the-badge&logo=css3)
![Flask](https://img.shields.io/badge/flask-black?style=for-the-badge&logo=flask)
![FastAPI](https://img.shields.io/badge/FastAPI-green?style=for-the-badge&logo=fastapi)

### 🤖 AI / ML  
![TensorFlow](https://img.shields.io/badge/tensorflow-orange?style=for-the-badge&logo=tensorflow)
![PyTorch](https://img.shields.io/badge/pytorch-red?style=for-the-badge&logo=pytorch)
![Scikit-Learn](https://img.shields.io/badge/sklearn-yellow?style=for-the-badge&logo=scikit-learn)
![OpenCV](https://img.shields.io/badge/opencv-black?style=for-the-badge&logo=opencv)

### 🗄️ Databases  
![MySQL](https://img.shields.io/badge/mysql-blue?style=for-the-badge&logo=mysql)
![MongoDB](https://img.shields.io/badge/mongodb-green?style=for-the-badge&logo=mongodb)
![Postgres](https://img.shields.io/badge/postgres-blue?style=for-the-badge&logo=postgresql)

### ⚙️ Tools & DevOps  
![Docker](https://img.shields.io/badge/docker-blue?style=for-the-badge&logo=docker)
![Kubernetes](https://img.shields.io/badge/kubernetes-blue?style=for-the-badge&logo=kubernetes)
![Git](https://img.shields.io/badge/git-orange?style=for-the-badge&logo=git)
![GitHub](https://img.shields.io/badge/github-black?style=for-the-badge&logo=github)

---

## 📊 GitHub Stats  

<p align="center">
<img src="https://github-readme-stats.vercel.app/api?username=abhiram5856&show_icons=true&theme=tokyonight" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=abhiram5856&layout=compact&theme=tokyonight" />
</p>

---

## 🔥 Streak Stats  
<p align="center">
<img src="https://streak-stats.demolab.com?user=abhiram5856&theme=tokyonight" />
</p>

---

## 📈 Contribution Graph  
[![Abhiram's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=abhiram5856&theme=tokyo-night)](https://github.com/abhiram5856)

---

## 🐍 Contribution Snake  

<p align="center">
<img src="https://raw.githubusercontent.com/abhiram5856/abhiram5856/output/github-contribution-grid-snake.svg" />
</p>

👉 **IMPORTANT (DO THIS STEP):**  
To enable snake animation:  
1. Go to your repo → **Settings → Actions → General → Enable Read/Write permissions**  
2. Create `.github/workflows/snake.yml`

Paste this:

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: abhiram5856
          outputs: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
