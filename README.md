👩‍💻 Manasi | 💻 Web Developer | 🇬🇧 England 

[Instagram](https://www.instagram.com/m4nasi/) • [Twitter](https://twitter.com/m4nasi) 

Hi 👋
- 🔭 I’m currently working from home
- 🌱 I’m currently learning **C# and XAML**
- 💬 Languages: Python, HTML, CSS, C#, XAML
- 😄 Pronouns: she/her
- 👯 I’m looking to collaborate on a potential project
- 📫 How to reach me: [@m4nasi](https://twitter.com/m4nasi) on Twitter
<hr>
<!--<img align="centre" src="https://github-readme-stats.vercel.app/api?username=m4nasi&theme=dark&show_icons=true" /> -->
# Visit https://github.com/lowlighter/metrics/blob/master/action.yml for full reference
name: Metrics
on:
  # Schedule updates
  schedule: [{cron: "0 * * * *"}]
  # Lines below let you run workflow manually and on each commit
  push: {branches: ["master", "main"]}
  workflow_dispatch:
jobs:
  github-metrics:
    runs-on: ubuntu-latest
    steps:
      - uses: lowlighter/metrics@latest
        with:
          # Your GitHub token
          token: ${{ secrets.METRICS_TOKEN }}
          # GITHUB_TOKEN is a special auto-generated token restricted to current repository, which is used to push files in it
          committer_token: ${{ secrets.GITHUB_TOKEN }}

          # Options
          user: m4nasi
          template: classic
          base: ""
          config_animated: yes
          config_timezone: Europe/London
          plugin_languages: yes
<!--
<img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=m4nasi&layout=compact" />

<!--**m4nasi/m4nasi** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

-->


