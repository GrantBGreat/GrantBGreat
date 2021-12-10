# What is it?
This is a personal repository holding a Readme.md file. On github, you can create a repository called the same as your username and the Readme file inside of it will be dispayed on your profile.

# What are metrics?
I used [github metrics](https://github.com/lowlighter/metrics) inside my readme in order to show more about what I do. It uses github actions to update an svg that is embeded in my Readme every hour using `[{cron: "*0 * * * *"}]` in order to not get ratelimited by [github pages](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages). The settings for my metrics can be found below and for more information about how to set them up, click [here](https://github.com/lowlighter/metrics/blob/master/README.md#%EF%B8%8F-using-github-action-on-your-profile-repository-5-min-setup). For more information about cron schedules, click [here](https://jasonet.co/posts/scheduled-actions/).

# My settings:
```yml
  user: GrantBGreat
  template: classic
  base: ""
  config_timezone: America/Toronto

  # Plugins
  plugin_introduction: yes
  plugin_introduction_title: yes
  plugin_isocalendar: yes
  plugin_isocalendar_duration: half-year
  plugin_languages: yes
  plugin_languages_colors: github
  plugin_languages_threshold: 1.5%
  plugin_languages_details: bytes-size, percentage
  plugin_code: yes
  plugin_code_lines: 12
  plugin_code_load: 100
  plugin_code_visibility: public
  plugin_people: yes
  plugin_people_types: followers, contributors
  plugin_people_limit: 28
  plugin_people_size: 28
  plugin_people_identicons: no
```


#### Discaimer: I am in no ways associated with lowligher or Github Metrics. I just hope this document can help someone out. 🤷‍♂️
