## Hi there 👋

<!--
**Raffol/Raffol** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- name: Half-year calendar
  uses: lowlighter/metrics@latest
  with:
    filename: metrics.plugin.isocalendar.svg
    token: ${{ secrets.METRICS_TOKEN }}
    base: ""
    plugin_isocalendar: yes

- 🔭 I’m currently working on some projects and do science :D
- 🌱 I’m currently learning ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) 
and 
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
- My stack, what I can do and am still learning (there is no limit to perfection):
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)

![PhpStorm](https://img.shields.io/badge/phpstorm-143?style=for-the-badge&logo=phpstorm&logoColor=black&color=black&labelColor=darkorchid)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

- My hobby are photo and video:
![Adobe](https://img.shields.io/badge/adobe-%23FF0000.svg?style=for-the-badge&logo=adobe&logoColor=white)
![Adobe Lightroom Classic](https://img.shields.io/badge/Adobe%20Lightroom%20Classic-31A8FF.svg?style=for-the-badge&logo=Adobe%20Lightroom%20Classic&logoColor=white)
![Adobe Photoshop](https://img.shields.io/badge/adobe%20photoshop-%2331A8FF.svg?style=for-the-badge&logo=adobe%20photoshop&logoColor=white)
![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white)

- 🤔 I’m looking for help if possible



- 😄 Pronouns: Junior Web-Dev
![macOS](https://img.shields.io/badge/mac%20os-000000?style=for-the-badge&logo=macos&logoColor=F0F0F0)
[Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)

-->
(https://github-readme-stats.vercel.app/api?Raffol=alexeyshpavda)](https://github.com/anuraghazra/github-readme-stats)
(https://github-readme-stats.vercel.app/api/top-langs/?Raffol=anuraghazra&layout=compact)](https://github.com/anuraghazra/github-readme-stats)


- uses: Platane/snk@v3
  with:
  # github user name to read the contribution graph from (**required**)
  # using action context var `github.repository_owner` or specified user
  github_user_name: ${{ github.repository_owner }}

  # list of files to generate.
  # one file per line. Each output can be customized with options as query string.
  #
  #  supported options:
  #  - palette:     A preset of color, one of [github, github-dark, github-light]
  #  - color_snake: Color of the snake
  #  - color_dots:  Coma separated list of dots color.
  #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
  #                 Exactly 5 colors are expected.
  outputs: |
  dist/github-snake.svg
  dist/github-snake-dark.svg?palette=github-dark
  dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
