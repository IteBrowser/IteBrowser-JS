# 欢迎使用IteBrowser-JavaScript！
## 调用方法
只要您引用js文件，那么IteBrowser-JavaScript将绑定在您的**页面**上（**__是页面，不是网站__**），调用方法如下：<br>
### 调用方法:
```html
<!DOCTYPE HTML>
<html>
<head>
  <meta charset="utf-8">
  <title>...</title>
  <!--[if lte IE8]>
    <script src="itebrowser-js/itebrowser.main.js"></script><!--IteBrowser By Rocky(This is WaterMark)-->
    <script>
      window.onload = function(){
          var itebrowser = new IteBrowser();
          itebrowser.run(getElementsByClassName("itebrowser-container"));
      }
    </script>
    <div class="itebrowser-container"></div>
  <![endif]-->
</head>
<body>
...
</body>
</html>
```
## 卸载方法
把`<script src="itebrowser-js/dist/itebrowser.js"></script>`删除即可。
## 其他
```javascript
var Author = "Rocky";
var license = "Mit License";
var forum = "This Repository's Issues(https://github.com/IteBrowser/IteBrowser-JS/issues)";
```
<img src="https://itebrowser.github.io/myfolder/files/img/him.png" />
