<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=00bfbf&height=120&section=header"/>
  
[![Typing SVG](https://readme-typing-svg.herokuapp.com/?color=00bfbf&size=35&center=true&vCenter=true&width=1000&lines=HELLO,+MY+NAME+is+Airton+Acacio+Sales;I'm+26+years+old;I+am+from+Fortaleza,+CE;I+am+a+full+stack+web+development;Be+Welcome!+:%29)](https://git.io/typing-svg)


<div align="center">  
  <img width="49%" height="195px" src="https://github-readme-stats.vercel.app/api?username=Airton-Sales&show_icons=true&count_private=true&hide_border=true&title_color=00bfbf&icon_color=00bfbf&text_color=c9d1d9&bg_color=0d1117" alt="Matheus Maia Alvarez github stats" /> 
  <img width="41%" height="195px" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Airton-Sales&layout=compact&hide_border=true&title_color=00bfbf&text_color=00bfbf&bg_color=0d1117" />
</div>

[![Ashutosh's github activity graph](https://github-readme-activity-graph.vercel.app/graph?username=Airton-Sales&bg_color=000000&color=15e5a6&line=07e9a5&point=0a855c&area=true&hide_border=true)](https://github.com/ashutosh00710/github-readme-activity-graph)

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Airton-Sales&theme=dracula&row=2&no-bg=true&column=3&margin-w=15&margin-h=15" />
</p>

<div align="center">  
<a href="https://www.instagram.com/airton8758/" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white"</a>
</div> 

# GitHub Action for generating a contribution graph with a snake eating your contributions.

name: Generate Snake

# Controls when the action will run. This action runs every 6 hours.

on:
  schedule:
      # every 6 hours
    - cron: "0 */6 * * *"

# This command allows us to run the Action automatically from the Actions tab.
  workflow_dispatch:

# The sequence of runs in this workflow:
jobs:
  # This workflow contains a single job called "build"
  build:
    # The type of runner that the job will run on
    runs-on: ubuntu-latest

    # Steps represent a sequence of tasks that will be executed as part of the job
    steps:

    # Checks repo under $GITHUB_WORKSHOP, so your job can access it
      - uses: actions/checkout@v2

    # Generates the snake  
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: Airton-sales
          # these next 2 lines generate the files on a branch called "output". This keeps the main branch from cluttering up.
          gif_out_path: dist/github-contribution-grid-snake.gif
          svg_out_path: dist/github-contribution-grid-snake.svg

     # show the status of the build. Makes it easier for debugging (if there's any issues).
      - run: git status

      # Push the changes
      - name: Push changes
        uses: ad-m/github-push-action@master
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
          branch: master
          force: true

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          # the output branch we mentioned above
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
 
### Main skills:
![JavaScript](https://img.shields.io/badge/-JavaScript-0D1117?style=for-the-badge&logo=javascript&labelColor=0D1117&textColor=0D1117)&nbsp;
![Node.JS](https://img.shields.io/badge/-Node.JS-0D1117?style=for-the-badge&logo=node.js&labelColor=0D1117&textColor=0D1117)&nbsp;
 
### Tools:
![Visual Studio Code](https://img.shields.io/badge/-Visual%20Studio%20Code-0D1117?style=for-the-badge&logo=visual-studio-code&logoColor=blue&labelColor=0D1117)&nbsp;
![Git](https://img.shields.io/badge/-Git-0D1117?style=for-the-badge&logo=git&labelColor=0D1117)&nbsp;
![GitHub](https://img.shields.io/badge/-GitHub-0D1117?style=for-the-badge&logo=github&labelColor=0D1117)&nbsp;
![Windows](https://img.shields.io/badge/-Windows-0D1117?style=for-the-badge&logo=windows&labelColor=0D1117)&nbsp;
 
### Other Knowledge:
![HTML](https://img.shields.io/badge/-HTML-0D1117?style=for-the-badge&logo=html5&labelColor=0D1117)&nbsp;
![CSS](https://img.shields.io/badge/-CSS-0D1117?style=for-the-badge&logo=CSS3&logoColor=1572B6&labelColor=0D1117)&nbsp; 
![Tailwind](https://img.shields.io/badge/Tailwind_-CSS-0D1117?style=for-the-badge&logo=tailwind-css&logoColor=1572B6&labelColor=0D1117)&nbsp;
![Figma](https://img.shields.io/badge/-figma-0D1117?style=for-the-badge&logo=figma&labelColor=0D1117)&nbsp;
  
### Studying in this moment:
![JavaScript](https://img.shields.io/badge/-JavaScript-0D1117?style=for-the-badge&logo=javascript&labelColor=0D1117&textColor=0D1117)&nbsp;
![React.js](https://img.shields.io/badge/-React.js-0D1117?style=for-the-badge&logo=react&labelColor=0D1117)&nbsp;
![Node.JS](https://img.shields.io/badge/-Node.JS-0D1117?style=for-the-badge&logo=node.js&labelColor=0D1117&textColor=0D1117)&nbsp;

<div align="center">
<br><p align="centre"><b>Visitors Count</b></p>  
<p align="center"><img align="center" src="https://profile-counter.glitch.me/{Airton-Sales}/count.svg" /></p> 
<br></div>

<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=00bfbf&height=120&section=footer"/>
