<!-- ========================== HEADER =============================== -->

<h1 align="center">👋 Hi, I'm <strong>Bhargav Gondaliya</strong></h1>
<p align="center">
  🔥 <b>BCA Student | AI & ML Enthusiast | Python Developer | Problem Solver</b>  
  🚀 Passionate about building intelligent systems using Machine Learning & Automation  
  💡 Learning → Building → Improving → Repeating  
</p>

<p align="center">
  <a href="https://github.com/bgbapu"><img src="https://img.shields.io/badge/GitHub-000?logo=github&style=for-the-badge"></a>
  <a href="https://www.linkedin.com/in/bhargav-gondaliya-22063a363/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&style=for-the-badge"/></a>
  <a href="https://instagram.com/bg_bapu_99"><img src="https://img.shields.io/badge/Instagram-E4405F?logo=instagram&style=for-the-badge"/></a>
</p>

---

## 🔥 About Me

- 🎓 BCA Student & aspiring **AI/ML Engineer**
- 🧠 Focused on **Logic Building • Problem Solving • Clean Code**
- 🔍 Exploring **Machine Learning, Deep Learning & Data Analysis**
- ⚡ Building real-world ML based projects

---

## 🛠 Tech Stack

| Languages | Tools | AI/ML |
|---|---|---|
| Python • C • Java • HTML/CSS | Git • VS Code • PyCharm • Linux | Pandas • NumPy • Matplotlib • Scikit-Learn • SQL |
| JavaScript (learning) | API/Automation | ML Projects • Data Visualization |

---

## 📌 Projects

| Project | Tech | Status |
|---|---|---|
| 🧠 ML House Price Prediction | Python, Pandas, Sklearn | 🔥 Uploading Soon |
| 🤖 Automation + AI Toolkit | Python, NLP | 🔥 In Build |
| 📈 Salary Prediction Model | ML Regression | ✔ Ready (Private) |
| 🐍 Python CLI Utility Pack | Python Scripts | 🚧 In Progress |

> More will be uploaded soon — stay tuned! 🚀

---

## 📊 GitHub Stats

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=bgbapu&show_icons=true&theme=tokyonight&hide_border=true" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=bgbapu&layout=compact&theme=tokyonight&hide_border=true" />
</p>

---

## 🐍 Contribution Snake Animation

### 📍 Step-1 → Create file  
`/.github/workflows/snake.yml`

```yaml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
  push:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - uses: Platane/snk@master
        with:
          github_user_name: bgbapu
          outputs: dist/snake.svg
      - uses: crazy-max/ghaction-github-pages@v2
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
