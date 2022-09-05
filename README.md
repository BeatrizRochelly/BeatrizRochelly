## Olá! Eu sou Beatriz Rochelly 👋

- 👀 Estou interessada em aprender ainda mais sobre tecnologia.
- 🌱 Atualmente estou aprendendo a ser um desenvolvedora Java Full Stack.
- 💞️ Estou procurando colaborar em projetos que ajudem outras pessoas.
- 📫 Como chegar até mim: https://www.linkedin.com/in/beatriz-rochelly/

<div align="center">
  <a href="https://github.com/BeatrizRochelly">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=beatrizrochelly&show_icons=true&theme=dracula&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=beatrizrochelly&layout=compact&langs_count=7&theme=dracula"/>
</div>
<div style="display: inline_block"><br>
 <img align="center" alt="Bia-Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
 <img align="center" alt="Bia-Ts" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-plain.svg">
 <img align="center" alt="Bia-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
 <img align="center" alt="Bia-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
 <img align="center" alt="Bia-ANGULAR" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/angularjs/angularjs-original.svg" />
 <img align="center" alt="Bia-JAVA" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" />
 <img align="right" alt="Rafa-pic" height="150" style="border-radius:50px;" src="https://i.imgur.com/tOw7h5l.png" />
 </div>
 
 ##
 <div> 
  <a href="https://www.youtube.com/channel/UCY9aXz35jD_67PjKsR1dJTg" target="_blank"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" target="_blank"></a>
  <a href="https://www.instagram.com/bialirios/" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
   <a href="https://www.linkedin.com/in/beatriz-rochelly/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
 
</div>

name: Generate Datas

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:

jobs:
  build:
    name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: beatrizrochelly
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
  
 
 

<!---
BeatrizRochelly/BeatrizRochelly is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
