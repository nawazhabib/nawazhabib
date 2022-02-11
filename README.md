### Hi, this is me Habib 👋

<table>
<tr>
  <td valign="center">
    🎓 I am currently pursuing my Bachelor's in Computer Science Engineering.
    🌱 I am currently learning Java and Java Web Developing.
    🎯 My Goal is to Contribute to Java Web Development.
    ✨ I love to learn Java new features.
<!-- <td >
# this is my daily.dev card, you can edit this accordingly
    <img src="https://pixabay.com/illustrations/java-software-software-development-2327538/" width="300" alt="Mr. Ånand's Dev Card"/></a>
  </td> -->

</tr>
</table>

![GitHub Activity Graph](https://activity-graph.herokuapp.com/graph?username=Habib-qazwsx&theme=dracula&hide_border=true)

## Stats📈
<p align="center">
<img width="40%" src="https://github-readme-stats.vercel.app/api/top-langs?username=Habib-qazwsx&show_icons=true&theme=dracula&title_color=ff8000&text_color=ffffff&bg_color=6a6a6a&locale=en&layout=compact&hide_border=true" alt="Habib-qazwsx" /> 
<img width="48%" src="https://github-readme-stats.vercel.app/api?username=Habib-qazwsx&show_icons=true&theme=dracula&title_color=ff8000&text_color=ffffff&bg_color=6a6a6a&locale=en&hide_border=true" alt="Habib-qazwsx" />
<img width="48%" src="https://github-readme-streak-stats.herokuapp.com/?user=Habib-qazwsx&theme=highcontrast&hide_border=true" alt="Habib-qazwsx" />
</p>

name: Update README

on:
  schedule:
    - cron: '*/30 * * * *'
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    name: Update this repo's README with recent activity

    steps:
      - uses: actions/checkout@v2
      - uses: jamesgeorge007/github-activity-readme@master
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

