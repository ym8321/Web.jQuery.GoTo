# Web.jQuery.GoTo
jQuery 前往元素位置

# 範例網站
 https://ym8321.github.io/Web.jQuery.GoTo/.

 # CDN

 ~~~
 <!-- 放在body結尾上方 -->
 <!-- jQuery CDN -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>

<!-- 前往元素 js -->
    <script src="https://github.com/ym8321/Web.jQuery.GoTo/blob/main/goTo.js"></script>

~~~

# 添加 ID

在要前往的元素加上ID
~~~
<section id="box1"></section>
~~~
# 屬性說明

屬性名稱             |        屬性說明
---------------------------------------------
data-gt-target      |  要前往的目標
data-gt-duration    |  持續時間 ，單位為毫秒
data-gt-offset      |  位移，往上位移的值