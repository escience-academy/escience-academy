---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header_unsplash_12.jpg
widget1:
  title: "Our Workshops"
  url: 'https://carpentries-work.github.io/carpentries_test_website/workshops/'
  image: panipuri.jpg
  text: 'Our workshops are hands on and interactive.  Learn how to make all your favorite main courses, sides, and desserts!'
widget2:
  title: "Our Lessons"
  url: '/lessons/'
  image: dessert.jpg
  text: 'Our cooking lessons are peer developed and reviewed, so you can directly apply the new skills you learn.'

widget3:
  title: "Get Involved"
  url: 'https://carpentries.org/community/'
  image: sushi.jpg
  text: 'There are so many ways to get involved in this open and supportive community to cook and eat delicious food.'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
old_callforaction:
  old_url: https://tinyletter.com/feeling-responsive
  ext: Inform me about new updates and features ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

