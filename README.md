<h1 align="center">Hey there 👋, I'm Miguel</h1>

🎓 Studying **Informatics and Computing Engineering** at **FEUP**  
💡 Interested in **software engineering**, **optimization**, **automation**, and **algorithms**  
🚀 Passionate about building efficient systems that connect logic and creativity  

---

### 🧠 Tech Stack

#### 🖥️ Programming Languages
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=FFD43B)
![Haskell](https://img.shields.io/badge/Haskell-5D4F85?style=for-the-badge&logo=haskell&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

---

### ⚙️ Tools & Technologies
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)

---


### 🏆 GitHub Trophies (Highlights Only)
<div align="center">

![trophy](https://github-profile-trophy.vercel.app/?username=14miguel&theme=tokyonight&no-frame=true&margin-w=10&column=4&title=Commits,Repositories,PullRequest,Issues)
name: Generate Snake

on:
  schedule: # corre todos os dias à meia-noite
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout repo content
        uses: actions/checkout@v3

      - name: Generate Snake animation
        uses: Platane/snk@v3
        with:
          github_user_name: 14miguels
          outputs: dist/snake.svg

      - name: Push Snake animation to the output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

</div>

---

### 🐍 My GitHub Activity
<div align="center">

![snake gif](https://github.com/14miguel/14miguel/blob/output/snake.svg)

</div>

---

### 💬 Quote
> “Code smart, build real, and never stop optimizing.”
