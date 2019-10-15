

<div align="center">
  
#  cute-cnblogs

</div>

>**说明** <br/>
>“我经常有那种感觉，如果这个事情来了，你却没有勇敢地去解决掉，它一定会再来。生活真是这样，它会一次次地让你去做这个功课直到你学会为止。”  —— 《像我这样笨拙地生活》<br/>
> 博客园样式一直是我想改的，之前使用过别人写好的样式模版，加了很多东西，可惜有一天全丢失了，博客园帮忙找回来了一部分，但是不全面，基本相当于废了，于是决定重头再来，自己写一套样式。<br/>
> 以下是我的博客样式 <br/>
> [github 链接](https://github.com/miluluyo/cute-cnblogs/) 喜欢的可以帮我点个 star 喔 <br/>

## 介绍

可爱的博客园样式美化、自定义博客园样式  ღゝ◡╹)ノ♡

* :book: 本样式以简约可爱为核心，美化博客园的显示效果，增加自定义导航；
* :shaved_ice: 基于博客园主题“SimpleMemor”进行的样式修改；
* :strawberry: 支持响应式；

## 博客示例

 ღゝ◡╹)ノ♡ [麋鹿鲁哟的博客园](https://www.cnblogs.com/miluluyo/)

![Image text](https://raw.githubusercontent.com/miluluyo/photo_gallery/master/cute-cnblogs.jpg)  

## 功能

* :apple: 导航点点动效随鼠标而动
* :tangerine: 导航栏自定义
* :cherries: 页面诗意诗句模块
* :banana: 看板娘-猫(ฅ´ω`ฅ)
* :peach: 音乐-网易云
* :pineapple: 上吊的猫（PS：回到顶部）
* :watermelon: 底部跳动的鱼<・)))><<
* :grapes: 点击页面跳动的小豆子及可爱的文字
* :lemon: 评论增加OωO聊天表情
* :tomato: 页面不同的导航背景及人物背景
* :pear: github跳转小三角
 
 ## 使用方法

* 首先记得申请JS权限
* 其次博客皮肤选择 SimpleMemor
* 勾选禁用模板默认CSS
<br/>
* 创建一个新随笔（这里使用选项中的TinyMCE(推荐)来编写的） —— “友链”；
* 点击 “编辑 HTML 源代码” 插入以下代码，点击更新；
* 只勾选 高级选项中的 “发布”、“允许评论”;
``` html
<p style="text-align: center;">欢迎来到我的友链小屋</p>
<div class="friendsbox">&nbsp;</div>
``` 
<br/>
* 最后分别复制以下区域代码，并根据参数更改数据（PS：路径可进行更改也可不更改，自行down文件上传到博客园文件中，并更改引入路径）

**页面定制CSS代码**

``` css
  #home{display:none}
  .showpage {position: fixed;width: 100%;height: 100%;text-align: center;left: 0;top: 0;}
  .showpage img{position: absolute;top: 50%;left: 50%;transform: translate(-50%,-50%);}
``` 

**页首Html代码**

``` html
  <div class="showpage" id="showpage"> <img src="https://images.cnblogs.com/cnblogs_com/elkyo/1566714/o_showpage .gif"> <div>
  <link rel='stylesheet' href='https://blog-static.cnblogs.com/files/elkyo/cute-cnblogs.css'>
  <link rel='stylesheet' href='https://cdn.bootcss.com/animate.css/3.7.2/animate.min.css'>
  <link rel="stylesheet" href="https://blog-static.cnblogs.com/files/elkyo/siyuan.css" />
  <script src="https://cdn.bootcss.com/jquery/3.4.1/jquery.min.js"></script>
  <script src="https://blog-static.cnblogs.com/files/elkyo/monitoring.js"></script>
  <link rel="stylesheet" href="https://blog-static.cnblogs.com/files/elkyo/OwO.min.css" />
  <script src="https://blog-static.cnblogs.com/files/elkyo/OwO.min.js"></script>
  <script src="https://blog-static.cnblogs.com/files/elkyo/cute-cnblogs.js"></script>
  <script src="https://sdk.jinrishici.com/v2/browser/jinrishici.js" charset="utf-8"></script>
  <script src="https://blog-static.cnblogs.com/files/elkyo/three.min.js"></script>
  <script src='https://blog-static.cnblogs.com/files/elkyo/star.js'></script>
  <script>
  miluframe({
      /*个人链接地址*/
    Youself:'https://www.cnblogs.com/miluluyo/',
    /*导航栏信息*/
    custom:[{
      name:'留言板',
      link:'https://www.cnblogs.com/miluluyo/p/11578505.html',
      istarget:false
    },{
      name:'技能树',
      link:'https://miluluyo.github.io/',
      istarget:true
    }],
    /*自己的友链页面后缀*/
    Friends_of_the:'p/11633791.html',
    /*自己的友链信息*/
    resume:{
        "name":"麋鹿鲁哟",
        "link":"https://www.cnblogs.com/miluluyo",
        "headurl":"https://images.cnblogs.com/cnblogs_com/elkyo/1558759/o_o_my.jpg",
        "introduction":"大道至简，知易行难。"
    },
    /*友链信息*/
    unionbox:[{
        "name":"麋鹿鲁哟",
        "introduction":"生活是没有标准答案的。",
        "url":"https://www.cnblogs.com/miluluyo",
        "headurl":"https://images.cnblogs.com/cnblogs_com/elkyo/1558759/o_o_my.jpg"
      },{
        "name":"麋鹿鲁哟的技能树",
        "introduction":"大道至简，知易行难。",
        "url":"https://miluluyo.github.io/",
        "headurl":"https://images.cnblogs.com/cnblogs_com/elkyo/1558759/o_o_my.jpg"
      }],
    /*github链接*/
    githuburl:'https://github.com/miluluyo'
  })
  </script>
```

**页脚Html代码**

```html
  <!-- 底部加了小鱼<・)))><<~ -->
  <div id="jsi-flying-fish-container" class="container"></div>
  <script src='https://blog-static.cnblogs.com/files/elkyo/fish.js'></script>
  <style>
  @media only screen and (max-width: 767px){
  #sidebar_search_box input[type=text]{width:calc(100% - 24px)}
  }
  </style>

  <!--音乐-->
  <link rel="stylesheet" href="https://blog-static.cnblogs.com/files/elkyo/APlayer.min.css">
  <div id="player" class="aplayer aplayer-withlist aplayer-fixed" data-id="3025663508" data-server="netease" data-type="playlist" data-order="random" data-fixed="true" data-listfolded="true" data-theme="#2D8CF0"></div>
  <script src="https://blog-static.cnblogs.com/files/elkyo/APlayer.min.js"></script>
  <script src="https://blog-static.cnblogs.com/files/elkyo/Meting.min.js"></script>

  <!--看板娘 - 猫-->
  <script src="https://eqcn.ajz.miesnfu.com/wp-content/plugins/wp-3d-pony/live2dw/lib/L2Dwidget.min.js"></script>
  <script>
      L2Dwidget.init({
          "model": {
              jsonPath: "https://unpkg.com/live2d-widget-model-hijiki/assets/hijiki.model.json",<!--这里改模型，前面后面都要改-->
              "scale": 1
          },
          "display": {
              "position": "left",<!--设置看板娘的上下左右位置-->
              "width": 100,
              "height": 200,
              "hOffset": 70,
              "vOffset": 0
          },
          "mobile": {
              "show": true,
              "scale": 0.5
          },
          "react": {
              "opacityDefault": 0.7,<!--设置透明度-->
              "opacityOnHover": 0.2
          }
      });
  window.onload = function(){
       $("#live2dcanvas").attr("style","position: fixed; opacity: 0.7; left: 70px; bottom: 0px; z-index: 1; pointer-events: none;")
  }
  </script>
  <!--点击冒点-->
  <canvas width="1777" height="841" style="position: fixed; left: 0px; top: 0px; z-index: 2147483647; pointer-events: none;"></canvas><script src="https://blog-static.cnblogs.com/files/elkyo/mouse-click.js"></script>
```

 ## 参数说明

<table style="width:866px;text-align: center;">
	<thead>
		<tr>
	 		<th>名称</th>
	 		<th>类型</th>
	 		<th>默认值/实例</th>
	 		<th>描述</th>
	 	</tr>
	</thead>
 	<tbody>
	 	<tr>
	 		<td>Youself</td>
	 		<td>字符串</td>
	 		<td>https://www.cnblogs.com/miluluyo/</td>
	 		<td>个人博客园首链接</td>
	 	</tr>
	 	<tr>
	 		<td>custom</td>
	 		<td>数组</td>
	 		<td>[{<br>
   name:'相册',<br>
   link:'https://www.cnblogs.com/elkyo/gallery.html',<br>
   istarget:false<br>
  },{<br>
   name:'技能树',<br>
   link:'https://miluluyo.github.io/',<br>
   istarget:true<br>
  },{<br>
   name:'留言板',<br>
   link:'https://miluluyo.github.io/p/11578505.html',<br>
   istarget:false<br>
  }]</td>
	 		<td>导航信息<br>
name 导航名<br>
link 导航链接<br>
istarget true跳转到新页面上，false当前页面打开</td>
	 	</tr>
	 	<tr>
	 		<td>Friends_of_the</td>
	 		<td>字符串</td>
	 		<td>11633791</td>
	 		<td>友链文章的后缀名，</td>若字符串为空则不显示友链</td>
	 	</tr>
	 	<tr>
	 		<td>resume</td>
	 		<td>对象</td>
	 		<td>{<br>
      "name":"麋鹿鲁哟",<br>
      "link":"https://www.cnblogs.com/miluluyo/",<br>
      "headurl":"https://images.cnblogs.com/cnblogs_com/<br>elkyo/1558759/o_o_my.jpg",<br>
      "introduction":"大道至简，知易行难。"<br>
  }</td>
	 		<td>自己的友链信息<br>
name 导航名<br>
link 导航链接<br>
headurl 头像<br>
introduction 语录</td>
	 	</tr>
	 	<tr>
	 		<td>unionbox</td>
	 		<td>数组</td>
	 		<td>[{<br>
      "name":"麋鹿鲁哟",<br>
      "introduction":"生活是没有标准答案的。",<br>
      "url":"https://www.cnblogs.com/miluluyo",<br>
      "headurl":"https://images.cnblogs.com/cnblogs_com/<br>elkyo/1558759/o_o_my.jpg"<br>
    },{<br>
      "name":"麋鹿鲁哟的技能树",<br>
      "introduction":"大道至简，知易行难。",<br>
      "url":"https://miluluyo.github.io/",<br>
      "headurl":"https://images.cnblogs.com/cnblogs_com/<br>elkyo/1558759/o_o_my.jpg"<br>
    }]</td>
	 		<td>友链数组<br>
name 昵称<br>
introduction 标语<br>
url 链接地址<br>
headurl 头像地址</td>
	 	</tr>
	 	<tr>
	 		<td>clicktext</td>
	 		<td>新数组</td>
	 		<td>new Array("ヾ(◍°∇°◍)ﾉﾞ加油哟~ ——麋鹿鲁哟",<br>"生活是没有标准答案的。  ——麋鹿鲁哟"),</td>
	 		<td>点击页面时候的弹出显示</td>
	 	</tr>
	 	<tr>
	 		<td>githuburl</td>
	 		<td>字符串</td>
	 		<td>https://github.com/miluluyo</td>
	 		<td>github链接</td>
	 	</tr>
 	</tbody>
</table>
