---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: patio_food.jpg
widget1:
  title: "Accommodation"
  url: '/accommodation/'
  image: bed.jpg
  text: 'Located in the heart of the valley, come here for a perfect escape and experience a life in nature like never before.'

widget2:
  title: "Traditional food"
  url: '/food/'
  image: patio_food.jpg
  text: 'Enjoy sumptuous traditional Berber dishes prepared with fresh ingredients sourced from local farmers and local markets, which will leave your palate satisfied.'

widget3:
  title: "Activities"
  url: '/activities/'
  image: camels.jpeg
  text: 'Enjoy of full day trek, a guided hikes or a relaxed ballade with mules.
  Read feedback from our guests to get a real sense of what lies ahead.'



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
  url: '/contact/'
  text: Any questions? Don't hesitate to send us an email
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
breadcrumb: true
---
<!-- ![mountain_teamaking]({{site.urlimg }}/mountain_teamaking.jpeg){:class="img-responsive"} -->

  <!-- video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>' -->

<!-- <div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div> -->
