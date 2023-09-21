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
  title: "iOS & Android Apps"
  # url: 'http://phlow.github.io/feeling-responsive/blog/'
  image: widget-1-302x182.jpg
  text: 'We specialize in crafting exceptional mobile experiences. Our team of skilled developers is passionate about creating captivating iOS and Android applications that enhance your daily life. Whether you seek entertainment, productivity, or utility, our apps are designed to provide seamless functionality and a user-friendly interface.'
widget2:
  title: "AI SaaS Tools"
  # url: 'http://phlow.github.io/feeling-responsive/info/'
  text: 'Embracing the power of artificial intelligence, we offer a range of AI SaaS (Software as a Service) tools. These intelligent solutions are designed to optimize your business processes, automate tasks, and provide invaluable insights. From machine learning algorithms to natural language processing, our AI tools are tailored to meet your unique needs.'
  image: webdesign_screenshot_moritz_sauer.jpg
  # video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title: "Open Source Projects"
  # url: 'https://github.com/Phlow/feeling-responsive'
  image: widget-github-303x182.jpg
  text: 'We actively contribute to the open source community by developing and supporting projects that promote transparency, accessibility, and shared knowledge. Our dedication to open source extends our commitment to technological progress beyond our own products.'
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
  # url: https://tinyletter.com/feeling-responsive
  # text: Inform me about new updates and features ›
  # style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>