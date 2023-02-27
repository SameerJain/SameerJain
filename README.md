### Hi there 👋
- 🔭 I’m currently working on ...
  - Python and Java Fundamentals
- 🌱 I’m currently learning ...
  - Systems Level Programming
  - Dynamic Memory Allocation
  - Emacs 
- 📫 How to reach me: ...
  - Email: sameerjain501@gmail.com
  - Linkedin: https://www.linkedin.com/in/sameer-jain-a110b5235/
 

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=SameerJain&show_icons=true&theme=tokyonight)

<img src="https://github-readme-streak-stats.herokuapp.com/?user=SameerJain&theme=tokyonight" width="48%" > <img src="https://github-readme-stats.vercel.app/api/top-langs?username=SameerJain&show_icons=true&locale=en&layout=compact&theme=tokyonight" alt="ovi" />

![Snake animation](https://github.com/madushadhanushka/github-readme/blob/output/github-contribution-snake.svg)

name: Contribution snake

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:

jobs:
  build:
    name: Jobs to update snake grid
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: SameerJain
          svg_out_path: dist/github-contribution-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

<!--
**SameerJain/SameerJain** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 
- 
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...

- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
