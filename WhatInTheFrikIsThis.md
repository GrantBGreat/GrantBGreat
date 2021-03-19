# What is it?
This is a personal repository holding a Readme.md file. On github, you can create a repository called the same as your username and the Readme file inside of it will be dispayed on your profile.

# What are metrics?
I used [github metrics](https://github.com/lowlighter/metrics) inside my readme in order to show more about what I do. It uses github actions to update an svg that is embeded in my Readme every 2 hours using `[{cron: "* */2 * * *"}]` in order to not get ratelimited by [the Brain Games website](https://realbraingames.com/#/). The settings for my metrics can be found below and for more information about how to set them up, click [here](https://github.com/lowlighter/metrics/blob/master/README.md). For more information about cron schedules, click [here](https://jasonet.co/posts/scheduled-actions/).

# My settings:
```yml
  user: GrantBGreat
  template: classic
  base: ""
  config_timezone: America/Toronto
  plugin_introduction: yes
  plugin_introduction_title: yes
  plugin_isocalendar: yes
  plugin_isocalendar_duration: half-year
  plugin_languages: yes
  plugin_languages_colors: github
  plugin_languages_threshold: 0%
  plugin_lines: yes
  plugin_pagespeed: yes
  plugin_pagespeed_url: "https://realbraingames.com/#/"
```
