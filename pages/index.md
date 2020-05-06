---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
permalink: /index.html
header:
  image_fullwidth: bubble-light.jpg
widget1:
  title: "2020神國教育論壇開放報名囉"
  date: '2020/01/08 (三)'
  url: '/news/'
  image: news/god-kindom-2020.jpg
  text: '主題：教養子女的猶太智慧2～大師級素養教育內涵 <br/>
時間：2020.02.01(六)上午9點～下午5點<br/>
地點：台南晨光教會 (台南市東區崇德三街12號B1)<br/>
講員：猶太籍柏偉志牧師、底波拉師母<br/>
<a href="https://bit.ly/2020%E7%A5%9E%E5%9C%8B%E6%95%99%E8%82%B2%E8%AB%96%E5%A3%87%E7%B7%9A%E4%B8%8A%E5%A0%B1%E5%90%8D?fbclid=IwAR1zUJMx-63n2qOW65IYbcPSWjiBNobNpOdDfMf1BOQCufjZQI20wplJlKs">線上報名</a>'
widget2:
  title: "2019年聖經朗誦比賽正式開跑囉！"
  date: 2019/07/01 (一)
  url: '/news/'
  video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
  text: '活動地點：台南善牧堂（701 東區長榮路三段1號）<a href="http://bit.ly/2RJFNz5">線上報名</href>'
widget3:
  title: "親子朗誦課程：花兒姐姐的親子朗誦小學堂"
  date: 2019/05/28 (二)
  url: '/news/'
  image: news/recite-class-2019.jpg
  text: '6/22（六）下午1～6點在晨光教會<br/>
<a href="http://bit.ly/2MzbDzq">線上報名</href>'
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
  url: https://bit.ly/%E9%98%BF%E7%88%BE%E6%B3%95%E7%B4%A2%E6%9B%B8%E8%A1%A8%E5%96%AE?fbclid=IwAR1RvhSUk2LThJ0JMQ4MhZsjr4RcCSqMaHLoNI9XzEr30qKF4J8ffSwK1dM
  text: 索取大字注音版讀經本（網站測試中） ›
  style: alert

#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <video width="1280" height="720" src="blob:https://www.youtube.com/6eb86451-780b-4584-bdce-143e363854c6" frameborder="0" allowfullscreen></video>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
