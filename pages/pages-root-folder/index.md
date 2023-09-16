---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: psh/banner-4.png
widget1:
  title: "Facebook"
  url: 'https://www.facebook.com/prosperssidehustle'
  image: psh/fb-thumb.png
  text: 'Here is the PSH FB Page.'
widget2:
  title: "Windsong Commons, May 2023"
  url: ''
  text: 'Prosper Side Hustle @ Windsong Commons 12 May 2023'
  video: '<a href="#" data-reveal-id="videoModal"><img src="images/psh/frontpage-video-thumb.png" width="302" height="182" alt=""/></a>'
widget3:
  title: "YouTube"
  url: 'https://www.youtube.com/@prosperssidehustle9843'
  image: psh/youtube-icon-logo-png-transparent.png
  text: 'Here is the PSH YouTube Channel.'
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
  url: /contact/
  text: Get in touch with the band! Check out all of our social media or just phone us!
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
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/YrUHJj4IWqs" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>

<div style="width: 75%;">
<p>Prosper’s Side Hustle is a cover band based in Prosper, Texas! We all love good music and are doing this for the fun of it! Most have been in bands in the past, and are continuing a life long hobby.</p>

<p>We chose our music based on our waxing nostalgia… mainly focusing on a wide range of genres from the 1960s to the 2000s, and occasionally something else! Our catalog ranges from Creedence to Petty, from Fleetwood to Matthews, from Crow to the Crowes!</p>

<p>Come check us out!</p>
</div>
