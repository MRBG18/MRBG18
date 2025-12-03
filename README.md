<!-- ============================= -->
<!--      🔥 BHARGAV GONDALIYA     -->
<!-- ============================= -->

<h1 align="center">👋 Hi, I'm <strong>Bhargav Gondaliya</strong></h1>
<h3 align="center">BCA Student | AI/ML Enthusiast | Python Developer | Problem Solver</h3>

<div align="center">
  🚀 Passionate about Machine Learning, Data Science & Building Real-world Projects  
  🔍 I love solving problems & exploring automation and AI innovations  
</div>
<br>

---

### 📌 Connect With Me

<p align="center">
  <a href="https://github.com/bgbapu"><img src="https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github" /></a>
  <a href="https://www.linkedin.com/in/bhargav-gondaliya-22063a363"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin" /></a>
  <a href="mailto:bhargavgondaliya999@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail" /></a>
  <a href="https://instagram.com/bg_bapu_99"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram" /></a>
</p>

---

## 🧠 About Me

- 🎓 Bachelor of Computer Applications (BCA)
- 🧩 I break problems → understand → optimize → solve
- 🐍 Strong in Python | Data | Machine Learning
- 🏗 Currently building **AI + ML projects**
- 🧑‍💻 Improving everyday learning by building real projects

---

## ⚡ Tech Stack

| Languages | Frameworks & Tools | Databases | Other Skills |
|----------|-------------------|-----------|---------------|
| Python, C, Java, JavaScript | TensorFlow, Scikit-Learn, Pandas, NumPy | MySQL, SQLite | Git, GitHub, Linux, Automation |
| HTML, CSS, React (Basic) | Flask, Streamlit | MongoDB (Learning) | Clean Code, Problem Solving |

---

## 📈 GitHub Analytics

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=bgbapu&show_icons=true&theme=react" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=bgbapu&layout=compact&theme=react" />
</p>

🐍 **Contribution Snake Animation (Works Now ✓)**

> 🔥 Must keep this file: `/.github/workflows/snake.yml`

```yml
name: Generate Snake

on:
  schedule: 
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: platane/snk@v3
      - uses: platane/snk@v3
        with:
          github_user_name: bgbapu
          outputs: |
            dist/snake.svg

      - uses: actions/upload-artifact@v3
        with:
          name: snake
          path: dist/snake.svg

      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
