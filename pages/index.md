---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  title: "Translational AI Center"
carousels:
  - images: 
    - image: carousel/ExampleCarousel1.png
    - image: carousel/ExampleCarousel1.png
    - image: carousel/ExampleCarousel1.png
    - image: carousel/ExampleCarousel1.png
widget1:
  title: "About"
  url: 'https://adityabalu.github.io/TrAC/blog/'
  image: TrACResearch.png
widget2:
  title: "Research"
  url: 'https://adityabalu.github.io/TrAC/info/'
  video: '<a href="#" data-reveal-id="videoModal"><img src="https://adityabalu.github.io/TrAC/images/TrACResearch.png" width="302" height="182" alt=""/></a>'
widget3:
  title: "Publications"
  url: 'https://adityabalu.github.io/TrAC/Publications/'
  image: Publications.svg

news:
  defaults:
    layout: post
  output: true
  permalink: /_news/:path/

news_limit: 5

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
# callforaction:
#   url: https://tinyletter.com/feeling-responsive
#   text: Inform me about new updates and features ›
#   style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

