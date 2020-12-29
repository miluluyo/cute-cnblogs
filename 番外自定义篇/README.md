# 番外篇

> 自己搭框架玩吧~ 这里给一些自定义代码喔~ 自己探索喔~ （部分代码与本皮肤一致，但有的不喔~）
> 这里将持续更新~

## [一期博客园框架样式](https://www.cnblogs.com/miluluyo/p/cute-cnblogs.html)
![Image text](https://raw.githubusercontent.com/miluluyo/photo_gallery/master/cute-cnblogs.jpg)  

## [二期博客园框架样式](https://www.cnblogs.com/miluluyo/p/cute-cnblogs2.html)
![Image text](https://images.cnblogs.com/cnblogs_com/miluluyo/1765646/o_200617103910bg.png) 


## 模版选定
博客皮肤选定 建议选择博客园 **Custom** 标准模板喔~<br />

## 重置样式
清除浏览器默认样式，并配置适合设计的基础样式（此处使用的nec的css reset）
```css
/* reset */
html,body,h1,h2,h3,h4,h5,h6,div,dl,dt,dd,ul,ol,li,p,blockquote,pre,hr,figure,table,caption,th,td,form,fieldset,legend,input,button,textarea,menu{margin:0;padding:0;}
header,footer,section,article,aside,nav,hgroup,address,figure,figcaption,menu,details{display:block;}
table{border-collapse:collapse;border-spacing:0;}
caption,th{text-align:left;font-weight:normal;}
html,body,fieldset,img,iframe,abbr{border:0;}
i,cite,em,var,address,dfn{font-style:normal;}
[hidefocus],summary{outline:0;}
li{list-style:none;}
h1,h2,h3,h4,h5,h6,small{font-size:100%;}
sup,sub{font-size:83%;}
pre,code,kbd,samp{font-family:inherit;}
q:before,q:after{content:none;}
textarea{overflow:auto;resize:none;}
label,summary{cursor:default;}
a,button{cursor:pointer;}
h1,h2,h3,h4,h5,h6,em,strong,b{font-weight:bold;}
del,ins,u,s,a,a:hover{text-decoration:none;}
body,textarea,input,button,select,keygen,legend{font:14px/1.14 arial,\5b8b\4f53;color:#333;outline:0;}
body{background:#fff;}
a,a:hover{color:#333;}
```


## 增加鼠标样式
url可更换为你想更换的图标样式（ico文件可上传在 [博客园文件](https://i.cnblogs.com/files) 中，上传ok后点进文件即可获取路径）
```css
*{cursor: url(https://files-cdn.cnblogs.com/files/miluluyo/cursora.ico),auto;}
```


## 字体颜色及样式
我比较喜欢思源字体，因此贴出思源字体吧~
```css
/*修改字体*/
*{font-family: "Noto Sans SC";font-weight: 100;}
/*修改默认a标签颜色*/
a:visited,a:link{color: #2daebf;text-decoration: none;}
a:hover{color: #f60;text-transform: none}
/*字体大小及颜色*/
#cnblogs_post_body p{font-size: 1rem;}
body, textarea, input, button, select, keygen, legend{color:#7f8c93}
```
```html
<link rel="stylesheet" href="https://blog-static.cnblogs.com/files/miluluyo/siyuan.css" />
```

<br />

## 浏览器图标
href 可更换为自己的图标链接   （文件可上传在 [博客园相册](https://i.cnblogs.com/albums) 中，上传ok后点进图片 F12 获取路径即可）
```javascript
$("head").append('<link type="image/x-icon" rel="icon"  href="https://images.cnblogs.com/cnblogs_com/elkyo/1762178/o_200511031646f12.png">')
```


## 顶部背景图
`#blogTitle 中的 background url 可更换（博主的二期框架使用了一张图片，从网上搜罗了一堆图片API，如有需要，请看文章底部，并加以替换~）<br />
顶部背景图样式如下：
```css
#blogTitle {
    background: url(http://api.dujin.org/bing/1366.php) center center / cover no-repeat rgb(34, 34, 34);
    overflow: hidden;
    width: 100%;
    height: 40vh;
    max-height: 40vh;
    box-shadow: 0 1px 2px rgba(150, 150, 150, .7);
    text-align: center;
    display: table;
}
.vertical {
    display: table-cell;
    vertical-align: middle;
    width: 100%;
    position: relative;
    z-index: 2;
}
#Header1_HeaderTitle {
    font-family: 'Playball', cursive;
    color: #fff;
    font-size: 3rem;
    text-shadow: 0 3px 6px rgba(0, 0, 0, 0.3);
    margin: 10px 0 10px 0;
    letter-spacing: -1px;
    font-weight: 700;
    animation: fade-in-down 1s both;
    animation-delay: .5s;
}
.vertical h2{
    margin: 0;
    font-size: 1rem;
    line-height: 1.5em;
    font-weight: 400;
    letter-spacing: .01rem;
    color: rgba(255, 255, 255, 0.8);
    -webkit-animation: fade-in-down .9s;
    animation: fade-in-down .9s both;
    -webkit-animation-delay: .1s;
    animation-delay: .3s;
    text-shadow: 0 3px 6px rgba(0, 0, 0, 0.5);
    -webkit-box-orient: vertical;
    -webkit-line-clamp: 10;
    overflow: hidden;
    font-family: 'Playball', cursive;
}
```
此处js将文本外部增加了div
```javascript
var blogTitle = $("#blogTitle").html()
$("#blogTitle").html( "<div class='vertical'>"+blogTitle+"</div>" )
```
自定义顶部背景图片（文件可上传在 [博客园相册](https://i.cnblogs.com/albums) 中，上传ok后点进图片 F12 获取路径即可）<br />

## 顶部背景点点动效随鼠标而动
直接引入即可（样式在js里，如需更改，自己手动）
```html
<script src="https://blog-static.cnblogs.com/files/miluluyo/three.min.js"></script>
<script src='https://blog-static.cnblogs.com/files/miluluyo/star.js'></script>
```


## 动漫人物背景图片
div#home::after 中的 background-image 可更换（这里使用了随机二次元图片API，从网上搜罗了一堆图片API，如有需要，请看文章底部，并加以替换~）
```css
/*动漫人物背景图*/
div#home::after{
    content: "";
    background-repeat: no-repeat;
    background-position: center;
    opacity: 0.06;
    -webkit-filter: grayscale(100%);
    -moz-filter: grayscale(100%);
    -ms-filter: grayscale(100%);
    -o-filter: grayscale(100%);
    filter: grayscale(100%);
    filter: gray;
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    z-index: -1;
}
div#home::after {
    background-image: url(https://api.imacroc.cn/acg/);
}
```


## 页面诗意诗句模块
此处调用了 [今日诗词](https://www.jinrishici.com/) 的API
```css
.poem-wrap {
    position: relative;
    width: 1000px;
    max-width: 80%;
    border: 2px solid #797979;
    border-top: none;
    text-align: center;
    margin: 40px auto;
}
.poem-left {
    left: 0;
}
.poem-right {
    right: 0;
}
.poem-border {
    position: absolute;
    height: 2px;
    width: 27%;
    background-color: #797979;
}
.poem-wrap p {
    width: 70%;
    margin: auto;
    line-height: 30px;
    color: #797979;
}
.poem-wrap h1 {
    position: relative;
    margin-top: -20px;
    display: inline-block;
    letter-spacing: 4px;
    color: #797979;
    font-size: 2em;
    margin-bottom: 20px;
}
#poem_sentence {
    font-size: 25px;
}
#poem_info {
    font-size: 15px;
    margin: 15px auto;
}
```
```html
<script>
$("#navigator").after('<div class="poem-wrap"><div class="poem-border poem-left"></div><div class="poem-border poem-right"></div><h1>念两句诗</h1><div id="poem_sentence"></div><div id="poem_info"></div></div>')
</script>
<!--添加古诗词-->
<script src="https://sdk.jinrishici.com/v2/browser/jinrishici.js" charset="utf-8"></script>
<script type="text/javascript">
  jinrishici.load(function(result) {
    var sentence = document.querySelector("#poem_sentence")
    var info = document.querySelector("#poem_info")
    sentence.innerHTML = result.data.content
    info.innerHTML = '【' + result.data.origin.dynasty + '】' + result.data.origin.author + '《' + result.data.origin.title + '》'
  });
</script>
```


## 随机图片API
从网络搜罗来的随机图片API，欢迎补充，有的已注明出处，未标注的表示未查到来源，欢迎指出API来源与出处，如链接已失效，请广大网友告知。
```
/*岁月小筑的随机图片API（https://www.xjh.me/3090.html），API如下：*/
//随机图片API中的环境背景图片
https（推荐）：
https://img.xjh.me/random_img.php?type=bg&ctype=nature&return=302
http（更快，快一点点，不安全，可能会被劫持）：
http://img.xjh.me/random_img.php?type=bg&ctype=nature&return=302
//随机人物背景图片
https（推荐）：
https://img.xjh.me/random_img.php?type=bg&ctype=acg&return=302
http（更快，快一点点，不安全，可能会被劫持）：
http://img.xjh.me/random_img.php?type=bg&ctype=acg&return=302

/*小歪API（https://api.ixiaowai.cn/），API如下：*/
https://api.ixiaowai.cn/api/api.php	//二次元动漫
https://api.ixiaowai.cn/mcapi/mcapi.php	//menhear酱
https://api.ixiaowai.cn/gqapi/gqapi.php	//风景

//二次元随机图
http://www.dmoe.cc/random.php
http://api.mtyqx.cn/api/random.php
https://api.pingping6.com/tools/acg2/index.php

/*东方Project随机图片API （https://img.paulzzh.tech/），API如下：*/
https://img.paulzzh.tech/touhou/random		

/*随机二次元图片API（https://api.julym.com/html/doc-ecy.html），API如下：*/*/
https://api.imacroc.cn/acg/			

/*保罗随机动漫壁纸API（https://api.paugram.com/help/wallpaper），API如下：*/
https://api.paugram.com/wallpaper/		

//随机人物API
https://api.lyiqk.cn/purelady?1559f782	

//Bing的随机图片
https://uploadbeta.com/api/pictures/random/?key=BingEverydayWallpaperPicture	

//Bing当日壁纸
http://api.dujin.org/bing/1366.php	

//一个API的网站（自行寻找里面API）
https://source.unsplash.com/
```

<br />持续更新中…<br />


## 最后
### 请吃糖
> 
> <div align="left">
> <p style="text-align: left;">如果您喜欢这里，感觉对你有帮助，并且有多余的软妹币的话，不妨投喂一颗糖喔~</p>
> <p style="text-align: left;"><img src="https://img2020.cnblogs.com/blog/1273193/202005/1273193-20200521150703930-2108950474.gif" alt="" style="display: block;" /></p>
> <p style="text-align: left;">&lt;(▰˘◡˘▰)&gt; 谢谢老板~</p>
> <div style="display: inline-block; vertical-align: top; padding: 5px;"><img src="https://img2020.cnblogs.com/blog/1273193/202005/1273193-20200521153000481-1688702336.png" alt="" width="207" height="207" style="width: 150px; height: 150px;" />
> <p style="text-align: center;">微信扫码</p>
> </div>
> <div style="display: inline-block; vertical-align: top; padding: 5px;"><img src="https://img2020.cnblogs.com/blog/1273193/202005/1273193-20200521153017174-2136545586.png" alt="" width="206" height="206" style="width: 150px; height: 150px;" />
> <p style="text-align: center;">支付宝扫码</p>
> </div>
> <p style="text-align: left;">赞赏的时候，留下一句你觉得很励志与美的话给我吧~</p>
> <p style="text-align: left;">（也可以加一个博客园给我喔，会添加在名字的旁边喔~点击可以跳转~ 例如：<a href="https://www.cnblogs.com/miluluyo/p/gratuity.html" target="_blank">去瞧瞧都有谁赞赏了</a>
> </p>
> </div>
> 

> 
> 为了响应大家的号召，方便大家技术交流，之前建立了一个微信群，如果大家有需要可以关注公众号，发送“加群”即可～本群是一个纯交流学习工作的群，不准发布广告、营销相关的信息！
>
> 
><div style="display: inline-block; vertical-align: top; padding: 5px;"><img src="https://images.cnblogs.com/cnblogs_com/miluluyo/1765646/o_200614064005qrcode.jpg" alt="" width="206" height="206" style="width: 150px; height: 150px;" />
><p style="text-align: center;">公众号：麋鹿鲁哟</p>
></div>
></div>
> 
