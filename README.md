### Hi there 👋


[![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=currentScript)](https://github.com/anuraghazra/github-readme-stats)

<!--START_SECTION:waka-->
WAKATIME_API_KEY=de2515ab-0ce1-43dd-ac27-464db5470224
GH_TOKEN=dfd608aa1e45ec88c78646dbea9d1e595e582af7 

SHOW_LINES_OF_CODE=true
SHOW_OS=false
SHOW_PROJECTS=flase
SHOW_TIMEZONE=false
SHOW_LANGUAGE_PER_REPO=false


name: Waka Readme

on:
  schedule:
    # Runs at 12am IST
    - cron: '30 18 * * *'

jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: ubuntu-latest
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
          GH_TOKEN: ${{ secrets.GH_TOKEN }}
<!--END_SECTION:waka-->

- 🔭 I’m currently working on a clicker game made in JavaScript
- 🌱 I’m currently learning JavaScript and Frameworks
- 📫 How to reach me: [@CurrentScript](https://twitter.com/CurrentScript) on Twitter
- ⚡ Fun fact: i'm 15
