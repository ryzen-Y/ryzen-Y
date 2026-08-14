from pathlib import Path

readme = r'''<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=00bfbf&height=120&section=header"/>

[![Typing SVG](https://readme-typing-svg.herokuapp.com/?color=00bfbf&size=35&center=true&vCenter=true&width=1000&lines=Hello,+I'm+Mirza+Tauhid;CSE+Student+%7C+Developer+%7C+ML+Enthusiast;Welcome+to+my+profile!+%3A%29)](https://git.io/typing-svg)

<h3 align="center">
    Computer Science & Engineering Student
</h3>

<p align="center">
    <a href="https://github.com/ryzen-Y">
        <img src="https://komarev.com/ghpvc/?username=ryzen-Y&label=Profile%20Views&color=00bfbf&style=flat" alt="Profile Views"/>
    </a>
</p>

## 👨‍💻 About Me

Hi! I'm **Mirza Tauhid**, a Computer Science & Engineering student who enjoys learning by building real-world projects.

- 🔭 Currently practicing with **real-life coding projects**
- 🤝 Looking to collaborate on **student projects and beginner-friendly coding projects**
- 🌱 Currently learning **Machine Learning, Python, C++, and software project structure**
- 🧠 Interested in **Data Structures & Algorithms, Machine Learning, Deep Learning, and software development**
- 💬 Ask me about **coding, learning in public, and student life**
- 🎯 My goal is to continuously improve by building, experimenting, and solving problems
- ⚡ Fun fact: **I enjoy learning by building real projects**

## 🛠️ Tech Stack

### Languages
<p align="center">
    <img src="https://skillicons.dev/icons?i=c,cpp,java,python" />
</p>

### Data Science & Machine Learning
<p align="center">
    <img src="https://skillicons.dev/icons?i=python" />
    <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
    <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
    <img src="https://img.shields.io/badge/Matplotlib-ffffff?style=for-the-badge&logo=Matplotlib&logoColor=black"/>
    <img src="https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white"/>
</p>

### Database, Cloud & Tools
<p align="center">
    <img src="https://skillicons.dev/icons?i=mysql,aws,git,github,vscode" />
</p>

## 📈 GitHub Activity

<p align="center">
  <a href="https://github.com/ryzen-Y">
    <img height="150em" src="https://streak-stats.demolab.com?user=ryzen-Y&theme=aura&hide_border=false&border_radius=10" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/ryzen-Y">
    <img height="150em" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=ryzen-Y&theme=aura" />
  </a>
  <a href="https://github.com/ryzen-Y">
    <img height="150em" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=ryzen-Y&theme=aura" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/ryzen-Y">
    <img height="150em" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=ryzen-Y&theme=aura" />
  </a>
  <a href="https://github.com/ryzen-Y">
    <img height="150em" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=ryzen-Y&theme=aura&utcOffset=6" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/ryzen-Y">
    <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=ryzen-Y&theme=aura" />
  </a>
</p>

## 🌐 Connect With Me

<div align="center">

<a href="mailto:mirzaaliuntauhid@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<a href="https://www.linkedin.com/in/mirza-tauhid-b811353aa/">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://www.facebook.com/mirza.tauhid.507/">
  <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white"/>
</a>

<a href="https://instagram.com/iam__tauhid1">
  <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/>
</a>

</div>

## 💻 Coding Profiles

<div align="center">

<a href="https://leetcode.com/u/Mirzatauhiid/">
  <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black"/>
</a>

<a href="https://codeforces.com/profile/mirzaaliuntauhid">
  <img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white"/>
</a>

</div>

<div align="center">
<br>
<p><b>Thanks for visiting my profile!</b></p>
<img src="https://profile-counter.glitch.me/ryzen-Y/count.svg" />
<br>
</div>

<h2 align="center">✨ Keep Learning. Keep Building. Keep Growing. ✨</h2>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=00bfbf&height=120&section=footer"/>
'''

out = Path("/mnt/data/README_ryzen-Y.md")
out.write_text(readme, encoding="utf-8")
print(f"Created: {out}")
