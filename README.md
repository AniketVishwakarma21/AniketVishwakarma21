<br clear="both">

<h2 align="center">Hello 👋, MySelf Aniket Vishwakarma ! 👩‍🎓</h2>

###

<h5 align="center">Hello folks, I'm Aniket Vishwakarma, an aspiring Web Developer. I'm proficient in C, C++, Python, HTML, CSS. I look forward to absorbing knowledge🧠, gaining experience 🏭, collaborating🤝, growing 🌱, upskilling and building impactful websites through my work! Please feel free to reach out and talk about ideas!</h5>

###

<h3 align="left">👩‍💻  About Me</h3>

###

<h6 align="left">. 💻 I’m a pre-final year Computer  Science Student.<br><br>. 📫  Tremendous passion for web  development.<br><br>. 💪 Ask me about Web Development ;<br><br>. 💬 learning DSA in Java</h6>

###

<br clear="both">

<p align="left">Connect With me :</p>

###

<div align="left">
  <a href="https://www.linkedin.com/in/aniket-vishwakarma-729972226/" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="32" height="20" alt="linkedin logo"  />
  </a>
  <a href="https://www.instagram.com/vaniket15/" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/instagram/default.svg" width="32" height="20" alt="instagram logo"  />
  </a>
  <a href="vaniket2021@gmail.com" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/gmail/default.svg" width="32" height="20" alt="gmail logo"  />
  </a>
</div>

###

<h4 align="left">🛠 Language and tools</h4>

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" height="28" alt="c logo"  />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" height="28" alt="cplusplus logo"  />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" height="28" alt="java logo"  />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="28" alt="python logo"  />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original-wordmark.svg" height="28" alt="html5 logo"  />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="28" alt="css3 logo"  />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="28" alt="javascript logo"  />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="28" alt="react logo"  />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="28" alt="git logo"  />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original-wordmark.svg" height="28" alt="github logo"  />
  <img width="10" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" height="28" alt="vscode logo"  />
</div>

###

<img align="right" height="180" src="https://media1.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif"  />

###

<img src="https://raw.githubusercontent.com/aniketvishwakarma21/aniketvishwakarma21/output/snake.svg" alt="Snake animation" />

###

name: Generate snake animation

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"

  workflow_dispatch:

  push:
    branches:
    - master

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    timeout-minutes: 5

    steps:
      - name: generate snake.svg
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: dist/snake.svg?palette=github-dark


      - name: push snake.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

<br clear="both">

<div align="left">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=aniketvishwakarma21&radius=30&theme=nightowl&area=true&order=5" height="220" alt="activity-graph graph"  />
</div>

###
