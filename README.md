# Slide插件demo，初学者可以拿来练手


- 使用(基于jquery，必须先引入jquery)
```shell
  <link rel="stylesheet" type="text/css" href="css/slide.css"/>
  <script src="js/jquery-1.10.min.js"></script>
  <script src="js/slide.js"></script>
```
- html结构
```shell
  <div class="slide-container">
    <div class="slide-warp">
      <div class="slide"><img src="images/1.png" alt=""></div>
      <div class="slide"><img src="images/2.png" alt=""></div>
    </div>
    <div class="slide-nav-btn"></div>
    <div class="slide-prev"></div>
    <div class="slide-next"></div>
   </div>
```
- 插件调用
```shell
new slide('.slide-container',{
    speed:400
    //、、、、
  });
```
- 演示地址
  https://hellosanbao.github.io/git-slide/
