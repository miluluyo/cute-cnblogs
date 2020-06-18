# cute-cnblogs 自定义博客园样式美化二期来啦~

> **说明**
>
> cute-cnblogs 可爱的博客园样式美化、自定义博客园样式 二期样式已经编写完毕了，如果说 [一期样式](https://www.cnblogs.com/IsAlpaca/) 给人的感觉是简洁清爽的小婴儿的话，那么 [二期样式](https://www.cnblogs.com/miluluyo/) 就是一个有自己小个性（花样）的小朋友了~
>
> 与一期一样，需要文件的可以来 [github](https://github.com/miluluyo/cute-cnblogs/) ，喜欢我写的样式可以帮我点个 star 喔 ღゝ◡╹)ノ♡
>
> （PS：有什么问题也可以留言到 [github issues](https://github.com/miluluyo/cute-cnblogs/issues) 中喔~）
>
> 好了，让我们撸起袖子开始更换二期样式吧~



## 博客示例


ღゝ◡╹)ノ♡ [麋鹿鲁哟的博客园](https://www.cnblogs.com/miluluyo/)


## 介绍

可爱的博客园样式美化、自定义博客园样式  ღゝ◡╹)ノ♡

* :book: 本样式以简约可爱为核心，美化博客园的显示效果，增加自定义导航；
* :shaved_ice: 基于博客园主题“SimpleMemory”进行的样式修改；
* :strawberry: 阅读目录导航；
* :palm_tree: 支持响应式；

![Image text](https://images.cnblogs.com/cnblogs_com/miluluyo/1765646/o_200617103910bg.png)  

## 功能

### 一期功能

* :apple: 顶部背景点点动效随鼠标而动
* :tangerine: 导航栏自定义
* :cherries: 页面诗意诗句模块
* :banana: 看板娘-猫(ฅ´ω`ฅ) （自行决定是否添加，因为这个有些影响加载速度）
* :peach: 音乐-网易云 （自行决定是否添加）
* :pineapple: ~~上吊的猫（PS：回到顶部）~~（已用其余按钮代替此功能）
* :watermelon: 底部跳动的鱼<・)))><<
* :grapes: 点击页面跳动的小豆子~~及可爱的文字~~（自行决定是否添加可爱文字的点击）
* :lemon: 评论增加OωO聊天表情
* :tomato: 页面不同的导航背景及人物背景

<hr>

### 二期增加功能

* :pear: 侧边栏显示
* :seedling: 侧边栏公告栏及个人信息显示
* :books: 阅读目录（标题 h1 > h2 > h3 写了三级目录）
* :cloud: 主题皮肤切换（浅白、暗黑、阅读）
* :bamboo: 仿主播点赞功能点击推荐
* :snowflake: 赞赏模块功能

## 模版选定
博客皮肤选定： 博客园 **Custom** 标准模板（与一期不同喔）

## 使用方法

### 基本操作

请按照顺序进行操作喔~

* 首先记得申请JS权限
* 其次博客皮肤选择 **Custom**
* 在此需要获取数据（不然点击头像的关注会失败）
	找一个没有登陆的浏览器访问自己的博客园，F12弹出窗口，找到 +加关注，复制follow括号里的内容，暂且先存在一个地方
	![Image text](https://images.cnblogs.com/cnblogs_com/miluluyo/1765646/o_200617014038info.jpg)

* 勾选禁用模板默认CSS

<br/>

* 创建一个新随笔（这里使用选项中的TinyMCE(推荐)来编写的） —— “友链”；（注意，此处已与一期不同）
* 点击 “编辑 HTML 源代码” 插入以下代码，修改自己的文本内容后，点击更新；
* 只勾选 高级选项中的 “发布”、“允许评论”;

``` html
<p style="text-align: center;">欢迎来到我的友链小屋</p>
<div class="friendsbox">
<div id="app">
<h6 style="text-align: center; color: #2daebf;">展示本站所有友情站点，排列不分先后，均匀打乱算法随机渲染的喔！</h6>
<div class="unionbox-box" style="display: flex; flex-wrap: wrap; justify-content: space-between; margin-bottom: 1.5rem; margin-top: 1.5rem;">&nbsp;</div>
<hr style="position: relative; margin: 1rem 0; border: 1px dashed #9eabb3; width: calc(100%); height: 0;" />
<h2 style="text-align: center;">友链信息</h2>
<h5 style="text-align: left; line-height: 30px;">博客名称：<a href="javascript:void(0)">麋鹿鲁哟</a><br />博客网址：<a href="javascript:void(0)">https://www.cnblogs.com/miluluyo/</a><br />博客头像：<a href="javascript:void(0)">https://pic.cnblogs.com/avatar/1273193/20190806180831.png</a><br />博客介绍：<a href="javascript:void(0)">大道至简，知易行难。</a></h5>
<h2 style="text-align: center;">join us</h2>
<h5 style="text-align: center; color: #2daebf;">如需友链，请添加微信（s978761）告知，格式如下</h5>
<table class="table friendstable" style="margin: 0 auto;">
<tbody>
<tr><th><strong>字段</strong></th><th><strong>字义</strong></th></tr>

</tbody>

</table>

</div>

</div>
```

<br/>

* 最后分别复制以下区域代码，并根据参数更改数据（PS：路径可进行更改也可不更改，我觉得更改后速度会快一点，自行down文件上传到博客园文件中，并更改引入路径，文件都在 [github](https://github.com/miluluyo/cute-cnblogs/) 中，喜欢记得给我个star喔~）

### 页面定制CSS代码

复制 https://blog-static.cnblogs.com/files/miluluyo/cute-cnblogs2.css 的文件内容放到 页面定制CSS代码 区域

### 博客侧边栏公告

``` html
<link href="https://blog-static.cnblogs.com/files/miluluyo/tippy.min.css" rel="stylesheet">
<script src="https://blog-static.cnblogs.com/files/miluluyo/jquery2.min.js"></script>
<script src="https://blog-static.cnblogs.com/files/miluluyo/tippy.js"></script>
<script src="https://blog-static.cnblogs.com/files/miluluyo/milusidebar.js"></script>

<script>
milusidebar({
	'names' : '麋鹿鲁哟',/*你的博客园名呐*/
	'notice' : '<b>温馨提示</b><span><a href="https://github.com/miluluyo/cute-cnblogs" target="_black">cute-cnblogs</a> &nbsp;样式已开源</span><b style="margin-top: 3px;"><a style="font-size:10px" href="https://www.cnblogs.com/IsAlpaca/" target="_black">查看一期样式</a></b>',/*里面文字自己可以更改喔*/
	'headerUrl' : 'https://images.cnblogs.com/cnblogs_com/miluluyo/1765646/o_200519075219notice5.png',/*这个是公告栏的背景图啦，我觉得这个可爱，如果你有更好看的可以自行更改喔*/
	'follow' : 'a1e76459-101d-47af-a8b6-08d523685c8c', /*还记的开始让你复制follow括号里的内容吗，对，就放到这里就好啦*/
	'sidebarInfo' : [[
	      {'icon':'#icon-github1','url':'https://github.com/miluluyo','title':'github'},
	      {'icon':'#icon-weixin','url':'','title':'微信','classname':'popper_weixin','click':false},
	      {'icon':'#icon-QQ','url':'http://wpa.qq.com/msgrd?v=3&uin=978761587&site=qq&menu=yes','title':'QQ'},
	      {'icon':'#icon-juejin','url':'https://juejin.im/user/5d18adce5188256e98090e33','title':'掘金'}
	  ],[
	      {'icon':'#icon-weibobangding','url':'https://www.weibo.com/6001406082/profile?topnav=1&wvr=6','title':'微博'},
	      {'icon':'#icon-csdn','url':'https://blog.csdn.net/qq_39394518','title':'CSDN'},
	      {'icon':'#icon-bilibili','url':'https://space.bilibili.com/100007925','title':'bilibili'},
	      {'icon':'#icon-yuquemianlogo','url':'https://www.yuque.com/miluluyo','title':'语雀'}
	]],/*这个模块是个人信息内那些小图标们，别忘记更改喔，具体参数，可以参考下面的表格喔*/
	'signature':'靡不有初  鲜克有终',/*来一句你自己喜欢的句子吧*/
	'popper_weixin':'<div class="popper_box"><p><b>很高兴认识你鸭~  (づ｡◕ᴗᴗ◕｡)づ</b> </p><div class="popper_box_con"><div class="popper_box_con_li"><img src="https://images.cnblogs.com/cnblogs_com/miluluyo/1765646/o_200614064005qrcode.jpg" alt="">公众号：麋鹿鲁哟</div><div class="popper_box_con_li"><img src="https://images.cnblogs.com/cnblogs_com/miluluyo/1493340/t_wxh.jpg" alt="">微信号：s978761</div></div><p>（加我记得备注 博客园 喔）</div>',/*这里是微信图标的弹窗内容，可以自行更改内容喔*/
	'portrait':'https://images.cnblogs.com/cnblogs_com/miluluyo/1765646/o_200515061851tx.jpg'
})/*这个是头像图片喔，你可以上传到相册里，然后F12获取，或者使用博客园的那个链接也可以的撒~*/
</script>
```
#### 参数说明

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
	 		<td>names</td>
	 		<td>字符串</td>
	 		<td>'麋鹿鲁哟'</td>
	 		<td>博客园名称</td>
	 	</tr>
	 	<tr>
	 		<td>notice</td>
	 		<td>字符串</td>
	 		<td>'&lt;b&gt;温馨提示&lt;/b&gt;&lt;span&gt;&lt;a href="https://github.com/miluluyo/cute-cnblogs" target="_black"&gt;cute-cnblogs&lt;/a&gt; &nbsp;样式已开源&lt;/span&gt;&lt;b style="margin-top: 3px;"&gt;&lt;a style="font-size:10px" href="https://www.cnblogs.com/IsAlpaca/" target="_black"&gt;查看一期样式&lt;/a&gt;&lt;/b&gt;'</td>
	 		<td>公告内容</td>
	 	</tr>
	 	<tr>
	 		<td>headerUrl</td>
	 		<td>字符串</td>
	 		<td>'https://images.cnblogs.com/cnblogs_com/miluluyo/1765646/o_200519075219notice5.png'</td>
	 		<td>公告栏的背景图</td>
	 	</tr>
	 	<tr>
	 		<td>follow</td>
	 		<td>字符串</td>
	 		<td>'a1e76459-101d-47af-a8b6-08d523685c8c'</td>
	 		<td>复制follow括号里的内容，这是关注的那个码</td>
	 	</tr>
	 	<tr>
	 		<td>sidebarInfo</td>
	 		<td>数组</td>
	 		<td>[[
	      			{'icon':'#icon-github1','url':'https://github.com/miluluyo','title':'github'},
	      			{'icon':'#icon-weixin','url':'','title':'微信','classname':'popper_weixin','click':false},
	      			{'icon':'#icon-QQ','url':'http://wpa.qq.com/msgrd?v=3&uin=978761587&site=qq&menu=yes','title':'QQ'},
	      			{'icon':'#icon-juejin','url':'https://juejin.im/user/5d18adce5188256e98090e33','title':'掘金'}
	  		],[
	      			{'icon':'#icon-weibobangding','url':'https://www.weibo.com/6001406082/profile?topnav=1&wvr=6','title':'微博'},
	      			{'icon':'#icon-csdn','url':'https://blog.csdn.net/qq_39394518','title':'CSDN'},
	      			{'icon':'#icon-bilibili','url':'https://space.bilibili.com/100007925','title':'bilibili'},
	      			{'icon':'#icon-yuquemianlogo','url':'https://www.yuque.com/miluluyo','title':'语雀'}
			]]</td>
	 		<td>个人信息内那些小图标们<br>
			icon 图标<br>
			url 跳转链接<br>
			title 提示名字<br>
			classname 要添加的class名<br>
			click 是否允许点击跳转<br>
			本框架有扩展的icon，文件在 github 中的 icon 文件夹内，可以下载去查看</td>
	 	</tr>
	 	<tr>
	 		<td>signature</td>
	 		<td>字符串</td>
	 		<td>'靡不有初  鲜克有终'</td>
	 		<td>个人信息签名 （写一句喜欢的话吧）</td>
	 	</tr>
	 	<tr>
	 		<td>popper_weixin</td>
	 		<td>字符串</td>
	 		<td>'&lt; div class="popper_box"&gt;&lt; p&gt;&lt; b&gt;很高兴认识你鸭~  (づ｡◕ᴗᴗ◕｡)づ&lt; /b&gt; &lt; /p&gt;&lt; div class="popper_box_con"&gt;&lt; div class="popper_box_con_li"&gt;&lt; img src="https://images.cnblogs.com/cnblogs_com/miluluyo/1765646/o_200614064005qrcode.jpg" alt=""&gt;公众号：麋鹿鲁哟&lt; /div&gt;&lt; div class="popper_box_con_li"&gt;&lt; img src="https://images.cnblogs.com/cnblogs_com/miluluyo/1493340/t_wxh.jpg" alt=""&gt;微信号：s978761&lt; /div&gt;&lt; /div&gt;&lt; p&gt;（加我记得备注 博客园 喔）&lt; /div&gt;'</td>
	 		<td>微信焦点弹窗，内容可自行更改，可以放一些公众号啊啥的~</td>
	 	</tr>
	 	<tr>
	 		<td>portrait</td>
	 		<td>字符串</td>
	 		<td>'https://images.cnblogs.com/cnblogs_com/miluluyo/1765646/o_200515061851tx.jpg'</td>
	 		<td>头像图片路径</td>
	 	</tr>
 	</tbody>
</table>


### 页首Html代码

``` html
  <div id="set_btn_box">
    <div class="set_btn fly_top fadeIn animated">
        <svg class="icon" aria-hidden="true"><use xlink:href="#icon-zhiding"></use></svg>
    </div>
    <div class="set_btn article_icon_btn catalogue_btn">
        <svg class="icon" aria-hidden="true" style="color:#97A1A7"><use xlink:href="#icon-dagang"></use></svg>
    </div>
    <div class="set_btn article_icon_btn comment">
        <a href="#comment_form_container"><svg class="icon" aria-hidden="true" style="color:#97A1A7"><use xlink:href="#icon-linedesign-01"></use></svg></a>
    </div>
    <div class="set_btn skin_btn">
        <svg class="icon" aria-hidden="true" style="color:#97A1A7"><use xlink:href="#icon-pifu"></use></svg>
    </div>
    <div class="set_btn gratuity">
        <svg class="icon" aria-hidden="true" style="color:#97A1A7"><use xlink:href="#icon-dashang"></use></svg>
    </div>
    <div class="set_btn article_icon_btn artice_recommend">
        <svg class="icon" aria-hidden="true" style="color:#97A1A7"><use xlink:href="#icon-tuijian2"></use></svg>
    </div>
     <canvas id="thumsCanvas" width="200" height="400" style="width:100px;height:200px"></canvas>
    <div class="set_btn catalogue">
        <svg class="icon" aria-hidden="true" style="color:#97A1A7"><use xlink:href="#icon-cebianlan-"></use></svg>
    </div>
</div>
<script src='https://blog-static.cnblogs.com/files/miluluyo/canvas2.js'></script>
<!--
<link href="//files.cnblogs.com/files/linianhui/lnh.cnblogs.css" rel="stylesheet"/>-->
```

**页脚Html代码**

```html
  <style id="ceshicss">
@media (max-width: 767px){
#set_btn_box {width: 100vw;left: 0;right: 0;bottom: 0;background: hsla(0,0%,100%,.6);height: 49px;display: flex;justify-content: space-between;align-items: center;padding: 12px 40px;border-top: 1px solid #e8e8e8;box-sizing: border-box;}
.set_btn {margin-top: 0;}
.set_btn.fly_top.fadeIn.animated {position: absolute;right: 10px;bottom: 60px;}
.container{bottom:50px}}
#mainContent{width:90%}
</style>
<link href="https://blog-static.cnblogs.com/files/miluluyo/tippy.min.css" rel="stylesheet">
<script src="https://unpkg.com/@popperjs/core@2.4.2/dist/umd/popper.min.js"></script>
<script src="https://blog-static.cnblogs.com/files/miluluyo/tippy.js"></script>
<link rel='stylesheet' href='https://cdn.bootcss.com/animate.css/3.7.2/animate.min.css'>
<script src="https://at.alicdn.com/t/font_1825850_klax1ao4o6.js"></script>
<script src="https://blog-static.cnblogs.com/files/miluluyo/three.min.js"></script>
<script src='https://blog-static.cnblogs.com/files/miluluyo/star.js'></script>
<link rel="stylesheet" href="https://blog-static.cnblogs.com/files/miluluyo/OwO.min.css" />
<script src="https://blog-static.cnblogs.com/files/miluluyo/OwO2.min.js"></script>
<script src="https://blog-static.cnblogs.com/files/miluluyo/cute-cnblogs2.js"></script>
<script src="https://blog-static.cnblogs.com/files/miluluyo/monitoring2.js"></script>

<script>

miluframe({
  Youself:'https://www.cnblogs.com/miluluyo/', /*个人的博客园链接*/
  /*博客园导航信息*/
    custom:[{
      name:'首页',
      link:'https://www.cnblogs.com/miluluyo/',
      istarget:false
    },{
      name:'联系',
      link:'https://msg.cnblogs.com/send/%E9%BA%8B%E9%B9%BF%E9%B2%81%E5%93%9F',
      istarget:true
    },{
      name:'技能树',
      link:'https://miluluyo.github.io/',
      istarget:true
    },{
      name:'留言板',
      link:'https://www.cnblogs.com/miluluyo/p/11578505.html',
      istarget:false
    },{
      name:'相册',
      link:'https://www.cnblogs.com/miluluyo/gallery.html',
      istarget:false
    },{
      name:'友链',
      link:'https://www.cnblogs.com/miluluyo/p/11633791.html',
      istarget:false
    },{
      name:'维护',
      link:'https://www.cnblogs.com/miluluyo/p/12092009.html',
      istarget:false
    },{
      name:'投喂',
      link:'https://www.cnblogs.com/miluluyo/p/gratuity.html',
      istarget:false
    },{
      name:'管理',
      link:'https://i.cnblogs.com/',
      istarget:true
    }],
    /*向别人展示自己的友链信息*/
    resume:{
        "name":"麋鹿鲁哟",
        "link":"https://www.cnblogs.com/miluluyo/",
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
    /*友链表格头信息，这个可以忽略*/
    details:[{
        field: 'name',
        literal: '昵称',
      },{
        field: 'introduction',
        literal: '标语',
      },{
        field: 'url',
        literal: '链接地址',
      },{
        field: 'headurl',
        literal: '头像地址',
      }],
    /*浏览器顶部小图标*/
    logoimg:'https://images.cnblogs.com/cnblogs_com/miluluyo/1765646/o_200519070633f12.png',
    /*文章页面标题前的图标，此处图标有扩展，下面会提到图标*/
    cuteicon:['icon-caomei','icon-boluo','icon-huolongguo','icon-chengzi','icon-hamigua','icon-lizhi','icon-mangguo','icon-liulian','icon-lizi','icon-lanmei','icon-longyan','icon-shanzhu','icon-pingguo','icon-mihoutao','icon-niuyouguo','icon-xigua','icon-putao','icon-xiangjiao','icon-ningmeng','icon-yingtao','icon-taozi','icon-shiliu','icon-ximei','icon-shizi'],
    /*赞赏，若true则显示此按钮，false则不显示*/
    isGratuity:true,
    /*赞赏按钮焦点显示赞赏内容，内容可自行更改*/
    gratuity:'<div class="popper_box"><p><b>要请我喝奶茶吗  (づ｡◕ᴗᴗ◕｡)づ</b> </p><div class="popper_box_con"><div class="popper_box_con_li"><img src="https://images.cnblogs.com/cnblogs_com/miluluyo/1765646/o_200521053817wx.png" alt="">微信扫码</div><div class="popper_box_con_li"><img src="https://images.cnblogs.com/cnblogs_com/miluluyo/1765646/o_200521053827zfb.png" >支付宝扫码</div></div><p><b>留下一句你觉得很励志与美的话给我吧~</b>&nbsp;&nbsp;<b><a href="https://www.cnblogs.com/miluluyo/p/12930946.html">GO</a></b></div>'
})
</script>
<!-- 点赞 -->
<canvas width="1777" height="841" style="position: fixed; left: 0px; top: 0px; z-index: 2147483647; pointer-events: none;"></canvas><script src="https://blog-static.cnblogs.com/files/miluluyo/mouse-click.js"></script>

<!-- 以下内容是否添加你随意 -->

<script>
  /*在文章页面添加古诗词*/
  $("#navigator").after('<div class="poem-wrap"><div class="poem-border poem-left"></div><div class="poem-border poem-right"></div><h1>念两句诗</h1><div id="poem_sentence"></div><div id="poem_info"></div></div>')
</script>
<script src="https://sdk.jinrishici.com/v2/browser/jinrishici.js" charset="utf-8"></script>
<script type="text/javascript">
  jinrishici.load(function(result) {
    var sentence = document.querySelector("#poem_sentence")
    var info = document.querySelector("#poem_info")
    sentence.innerHTML = result.data.content
    info.innerHTML = '【' + result.data.origin.dynasty + '】' + result.data.origin.author + '《' + result.data.origin.title + '》'
  });
</script>

<script type="text/javascript">
/* 鼠标特效，我觉得太花哨了就注释了，喜欢的自己打开注释就可以 */
/*var a_idx = 0;
jQuery(document).ready(function($) {
    $("body").click(function(e) {
        var a = new Array("❤去活出你自己。❤","❤今天的好计划胜过明天的完美计划。❤","❤不要轻言放弃，否则对不起自己。❤","❤紧要关头不放弃，绝望就会变成希望。❤","❤如果不能改变结果，那就完善过程。❤","❤好好活就是干有意义的事，有意义的事就是好好活！❤","❤你真正是谁并不重要，重要的是你的所做所为。❤","❤你不想为你的信仰冒一下险吗?难道想等你老了，再后悔莫及吗?❤","❤有些鸟儿是关不住的，它的每一根羽毛都闪耀着自由的光辉。❤","❤决定我们成为什么样人的，不是我们的能力，而是我们的选择。❤","❤掉在水里你不会淹死，呆在水里你才会淹死，你只有游，不停的往前游。❤","❤有些路，只能一个人走。❤","❤希望你眼眸有星辰，心中有山海。❤","❤从此以梦为马，不负韶华。❤","❤人的成就和差异决定于其业余时间。❤","❤佛不要你皈依，佛要你欢喜。❤","❤ダーリンのこと　大好きだよ❤","❤小猫在午睡时，地球在转。❤","❤我，混世大魔王，申请做你的小熊软糖。❤","❤决定好啦，要暗暗努力。❤","❤呐，做人呢最紧要开心。❤","❤好想邀请你一起去云朵上打呼噜呀。❤","❤永远年轻，永远热泪盈眶。❤","❤我生来平庸，也生来骄傲。❤","❤我走得很慢，但我从不后退。❤","❤人间不正经生活手册。❤","❤我是可爱的小姑娘，你是可爱。❤","❤数学里，有个温柔霸道的词，有且仅有。❤","❤吧唧一口，吃掉难过。❤","❤你头发乱了哦。❤","❤健康可爱，没有眼袋。❤","❤日月星辰之外，你是第四种难得。❤","❤你是否成为了了不起的成年人？❤","❤大家都是第一次做人。❤","❤何事喧哗？！❤","❤人间有味是清欢。❤","❤你笑起来真像好天气。❤","❤风填词半句，雪斟酒一壶。❤","❤除了自渡，他人爱莫能助。❤","❤昨日种种，皆成今我。❤","❤一梦入混沌 明月撞星辰❤","❤保持独立 适当拥有❤","❤谢谢你出现 这一生我很喜欢❤","❤做自己就好了 我会喜欢你的❤","❤太严肃的话，是没办法在人间寻欢作乐的❤","❤愿你余生可随遇而安，步步慢。❤","❤黄瓜在于拍，人生在于嗨❤","❤奇变偶不变，符号看象限。❤","❤从来如此，便对么？❤","❤今天我这儿的太阳，正好适合晒钙 你呢❤","❤未来可期，万事胜意。❤","❤星光不问赶路人 时光不负有心人❤","❤我当然不会试图摘月，我要月亮奔我而来❤","❤女生要修炼成的五样东西： 扬在脸上的自信，长在心底的善良， 融进血里的骨气，刻进命里的坚强，深到骨子里的教养❤","❤燕去燕归，沧海桑田。纵此生不见，平安惟愿❤","❤我想认识你 趁风不注意❤","❤我一直想从你的窗子里看月亮❤","❤长大应该是变温柔，对全世界都温柔。❤","❤别在深夜做任何决定❤","❤山中何事，松花酿酒，春水煎茶。❤","❤桃李春风一杯酒，江湖夜雨十年灯。❤","❤欲买桂花同载酒，终不似，少年游。❤");
        var le = Math.ceil(Math.random()*a.length); 
        var $i = $("<span></span>").text(a[le]);/*a[a_idx]*/
        /*a_idx = (a_idx + 1) % a.length;
        var x = e.pageX,
        y = e.pageY;
        $i.css({
            "z-index": 999999999999999999999999999999999999999999999999999999999999999999999,
            "top": y - 20,
            "left": x,
            "position": "absolute",
            "font-weight": "bold",
            "color": "rgb("+~~(255*Math.random())+","+~~(255*Math.random())+","+~~(255*Math.random())+")"
        });
        $("body").append($i);
        $i.animate({
            "top": y - 180,
            "opacity": 0
        },
        2000,
        function() {
            $i.remove();
        });
    });
});*/
</script>


<!--音乐，只在PC端宽度>1000px时显示-->
<link rel="stylesheet" href="https://blog-static.cnblogs.com/files/miluluyo/APlayer.min.css">
<div id="player" class="aplayer aplayer-withlist aplayer-fixed" data-id="3116636104" data-server="netease" data-type="playlist" data-order="random" data-fixed="true" data-listfolded="true" data-theme="#2D8CF0"></div>
<script src="https://blog-static.cnblogs.com/files/miluluyo/APlayer.min.js"></script>
<script src="https://blog-static.cnblogs.com/files/miluluyo/Meting.min.js"></script>

<!--猫，只在PC端显示，移动端不加载了，因为会卡顿页面-->
<script src="https://eqcn.ajz.miesnfu.com/wp-content/plugins/wp-3d-pony/live2dw/lib/L2Dwidget.min.js"></script>
<script>
  var mobile_flag = isMobile();
  if(mobile_flag){
    //console.info("移动端")
  }else{
    //console.info("PC端")
    L2Dwidget.init({
        "model": {
            "jsonPath": "https://unpkg.com/live2d-widget-model-hijiki/assets/hijiki.model.json",
            "scale": 1
        },
        "display": {
            "position": "left",
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
            "opacityDefault": 0.7,
            "opacityOnHover": 0.2
        }
    });
    window.onload = function(){
      $("#live2dcanvas").attr("style","position: fixed; opacity: 0.7; left: 70px; bottom: 0px; z-index: 1; pointer-events: none;")
    }
  }

</script>

<script>

/*记录访问数据，我用了两个，一个是这个在 https://clustrmaps.com/ 网站，另一个是 https://www.51.la/ 这个网站*/
/*
	第一种：https://clustrmaps.com/
	注册账号，添加自己博客园的链接，选择自定义Customize,
	选择 Image based (basic version for websites that don't support javascript)，调整到你喜欢的样式，然后复制
	：这个我插入在了侧边栏的最底部，把生成的代码粘贴到append内，这就完事了
*/
$('#sideBarMain').append('')

/*
	第二种：https://www.51.la/
	注册账号，点控制台，添加统计ID，统计图标显示我是不显示的
	这个目前插入的js好像报错，我的是很早之前生成的，还能用，因此还是推荐用第一种吧

	别的地方也有这种很多统计访问数据的，可以自己找找看呢

*/
</script>
```

#### 参数说明

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
	 		<td>[{
	 		      name:'首页',
	 		      link:'https://www.cnblogs.com/miluluyo/',
	 		      istarget:false
	 		    },{
	 		      name:'联系',
	 		      link:'https://msg.cnblogs.com/send/%E9%BA%8B%E9%B9%BF%E9%B2%81%E5%93%9F',
	 		      istarget:true
	 		    },{
	 		      name:'技能树',
	 		      link:'https://miluluyo.github.io/',
	 		      istarget:true
	 		    },{
	 		      name:'留言板',
	 		      link:'https://www.cnblogs.com/miluluyo/p/11578505.html',
	 		      istarget:false
	 		    },{
	 		      name:'相册',
	 		      link:'https://www.cnblogs.com/miluluyo/gallery.html',
	 		      istarget:false
	 		    },{
	 		      name:'友链',
	 		      link:'https://www.cnblogs.com/miluluyo/p/11633791.html',
	 		      istarget:false
	 		    },{
	 		      name:'维护',
	 		      link:'https://www.cnblogs.com/miluluyo/p/12092009.html',
	 		      istarget:false
	 		    },{
	 		      name:'投喂',
	 		      link:'https://www.cnblogs.com/miluluyo/p/gratuity.html',
	 		      istarget:false
	 		    },{
	 		      name:'管理',
	 		      link:'https://i.cnblogs.com/',
	 		      istarget:true
	 		}]</td>
	 		<td>导航信息<br>
name 导航名<br>
link 导航链接<br>
istarget true跳转到新页面上，false当前页面打开</td>
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
	 		      headurl 头像地址
	 		</td>
	 	</tr>
	 	<tr>
	 		<td>clicktext</td>
	 		<td>数组</td>
	 		<td>[{
	 		        field: 'name',
	 		        literal: '昵称',
	 		      },{
	 		        field: 'introduction',
	 		        literal: '标语',
	 		      },{
	 		        field: 'url',
	 		        literal: '链接地址',
	 		      },{
	 		        field: 'headurl',
	 		        literal: '头像地址',
	 		}]</td>
	 		<td>友链表格头信息，这项可以忽略掉</td>
	 	</tr>
	 	<tr>
	 		<td>logoimg</td>
	 		<td>字符串</td>
	 		<td>'https://images.cnblogs.com/cnblogs_com/miluluyo/1765646/o_200519070633f12.png'</td>
	 		<td>浏览器顶部小图标</td>
	 	</tr>
	 	<tr>
	 		<td>cuteicon</td>
	 		<td>数组</td>
	 		<td>['icon-caomei','icon-boluo','icon-huolongguo','icon-chengzi','icon-hamigua','icon-lizhi','icon-mangguo','icon-liulian','icon-lizi','icon-lanmei','icon-longyan','icon-shanzhu','icon-pingguo','icon-mihoutao','icon-niuyouguo','icon-xigua','icon-putao','icon-xiangjiao','icon-ningmeng','icon-yingtao','icon-taozi','icon-shiliu','icon-ximei','icon-shizi']</td>
	 		<td>文章页面标题前的图标，此处图标我只放入了一些水果的icon，不过可以自己引入文件进行修改名字添加自己想加的，本框架有扩展的icon，文件在 github 中的 icon 文件夹内，可以下载去查看</td>
	 	</tr>
	 	<tr>
	 		<td>gratuity</td>
	 		<td>字符串</td>
	 		<td>'&lt;div class="popper_box"&gt;&lt;p&gt;&lt;b&gt;要请我喝奶茶吗  (づ｡◕ᴗᴗ◕｡)づ&lt;/b&gt; &lt;/p&gt;&lt;div class="popper_box_con"&gt;&lt;div class="popper_box_con_li"&gt;&lt;img src="https://images.cnblogs.com/cnblogs_com/miluluyo/1765646/o_200521053817wx.png" alt=""&gt;微信扫码&lt;/div&gt;&lt;div class="popper_box_con_li"&gt;&lt;img src="https://images.cnblogs.com/cnblogs_com/miluluyo/1765646/o_200521053827zfb.png" &gt;支付宝扫码&lt;/div&gt;&lt;/div&gt;&lt;p&gt;&lt;b&gt;留下一句你觉得很励志与美的话给我吧~&lt;/b&gt;&nbsp;&nbsp;&lt;b&gt;&lt;a href="https://www.cnblogs.com/miluluyo/p/12930946.html"&gt;GO&lt;/a&gt;&lt;/b&gt;&lt;/div&gt;'</td>
	 		<td>赞赏按钮焦点显示赞赏内容，内容可自行更改</td>
	 	</tr>
	 	<tr>
	 		<td>isGratuity</td>
	 		<td>布尔值</td>
	 		<td>true</td>
	 		<td>默认true，若true则显示此按钮，false则不显示</td>
	 	</tr>
 	</tbody>
</table>

### 更换顶部背景图
当前框架使用了一张图片，也可以自己进行更换成随机图片API

在css样式中
```css
 #blogTitle{background:url(https://images.cnblogs.com/cnblogs_com/miluluyo/1764887/o_20051406472117.jpg) center center / cover no-repeat #222;overflow:hidden;width:100%;height:40vh;max-height:40vh;box-shadow:0 1px 2px rgba(150,150,150,.7);       /*搜索这个 更换 background: url() 里的链接 即可*/
```


更多内容请查看 [cute-cnblogs 自定义番外篇]()
（PS：可以使用番外篇里的随机图片API喔~）


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
> 为了响应大家的号召，方便大家技术交流，之前建立了一个微信群，如果大家有需要可以扫码（或者搜我微信号：s978761）加我好友，我邀请你加入～本群是一个纯交流学习工作的群，不准发布广告、营销相关的信息！对了，加我记得备注上：博客园+名称 加群 喔~
>
> 
><div style="display: inline-block; vertical-align: top; padding: 5px;"><img src="https://images.cnblogs.com/cnblogs_com/miluluyo/1493340/t_wxh.jpg" alt="" width="207" height="207" style="width: 150px; height: 150px;" />
><p style="text-align: center;">微信号：s978761</p>
></div>
><div style="display: inline-block; vertical-align: top; padding: 5px;"><img src="https://images.cnblogs.com/cnblogs_com/miluluyo/1765646/o_200614064005qrcode.jpg" alt="" width="206" height="206" style="width: 150px; height: 150px;" />
><p style="text-align: center;">公众号：麋鹿鲁哟</p>
></div>
></div>
> 