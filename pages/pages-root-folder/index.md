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
  title: "For Businesses"
  url: '/'
  image: widget-1-302x182.jpg
  text: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse ut magna nisi.Nulla malesuada hendrerit sem, a        lobortis quam molestie vitae..'
widget2:
  title: "For Care Homes"
  url: '/'
  text: '<em>Lorem ipsum</em> consectetur adipiscing elit. Suspendisse ut magna nisi.Nulla malesuada hendrerit sem, a        lobortis quam molestie vitae..'
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "For Individuals"
  url: '/'
  image: widget-github-303x182.jpg
  text: '<em>Lorem ipsum</em> consectetur adipiscing elit. Suspendisse ut magna nisi.Nulla malesuada hendrerit sem, a        lobortis quam molestie vitae..'
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
callforaction:
  url: /
  text: Latest News and development ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/ZCwX8axRkg4" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
