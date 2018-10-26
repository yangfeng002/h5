html5要点以及一些相关的demo
为了更好地处理今天的互联网应用，HTML5添加了很多新元素及功能，
比如: 图形的绘制，多媒体内容，更好的页面结构，更好的形式 处理，和几个api拖放元素，定位，包括网页 应用程序缓存，存储，网络工作者，等。
一、html5
html5新增了一些元素，下面我们就一些常用的进行介绍

html5已经被常用浏览器广泛支持，但是IE9以下的浏览器支持的话需要加入一些脚本支持
<!--[if lt IE 9]>
  <script src="http://html5shiv.googlecode.com/svn/trunk/html5.js"></script>
<![endif]-->
<!--[if lt IE 9]>
  <script src="http://cdn.static.runoob.com/libs/html5shiv/3.7/html5shiv.min.js"></script>
<![endif]-->

二、html5新增的元素

画布元素================****
1.canvas 画布功能
  画矩形、对角线、圆形、文本、渐变效果、放置图片
  && svg单独学习

媒体元素================****
1.audio音频
2.video视频
3.source
  设置在video和audio里面的，有src和type属性支持
  type 规定媒体资源的 MIME 类型。
         常见的 MIME 类型：
         视频：
         video/ogg
         video/mp4
         video/webm
         音频：
         audio/ogg
         audio/mpeg


表单元素===================
1.datalist表单和input配合使用
2.output元素（部分浏览器支持）
3.input类型
  color 、 date 、datetime、datetime-local、email、month、number、range、search、tel、time、url、week、
4.表单属性或者input属性



语义和结构元素===============****
1.section 块
2.article 独立的内容
3.aside 配合article使用，是内容以外的部分
4.nav 导航使用标签
5.header 页眉可以在section也可以在article标签中，可以如下使用
    <!--<article>
        <header>
            <h1>Internet Explorer 9</h1>
            <p><time pubdate datetime="2011-03-15"></time></p>
        </header>
    </article>-->
6.footer页脚  标签定义文档或者文档的一部分区域的页脚。
7.time标签 IE9及以上
8.progress标签  IE10及以上
9.mark标记标签高亮  IE9及以上
10.figure 标签规定独立的流内容（图像、图表、照片、代码等等） IE9及以上浏览器
11.figcaption  IE9及以上
  <figcaption> 标签为 <figure> 元素定义标题。
  <figcaption> 元素应该被置于 <figure> 元素的第一个或最后一个子元素的位置。

MathML，数学标记性语言================
被大部分浏览器支持，对应的标签是math
  mystyle 标签 >> 用于设置其包裹的最终表达式的样式。
  mrow 标签 >> 用于包裹一个或多个表达式（可省略）。
  msup 标签 >> 用于包裹上标的表达式（如：指数函数）。
  msub 标签  >>  用于包裹下表的表达式。
  mi 标签  >>      用于包裹字符。
  mn 标签  >>  用于包裹数字。
  mo  标签 >> 用于包裹各种运算符号（+，-，<mo></mo>,<mfrac></mfrac>，<,>,(,)等）
  msqrt 标签 >> 用于开根号。
  <mfenced open="[" close="]">.........</mfenced>   用于包裹矩阵即先定义外围的括号。
  mtable >>  类似table。
  mtr标签 >>     代表矩阵的行。
  mtd标签 >>     代表每行的每一个值。

拖放drag and drop ==============
IE9+浏览器支持
首先，为了使元素可拖动，把 draggable 属性设置为 true
其实拖动元素事件，利用event的dataTransfer对象存储剪贴板的数据 event.dataTransfer.setData("Text",ev.target.id);
最后在目标位置添加拖放的元素


地理定位 Geolocation=================*****
浏览器支持：IE9+


HTML 5 Web 存储=======================*****
HTML5 提供了两种在客户端存储数据的新方法：
localStorage - 没有时间限制的数据存储
sessionStorage - 针对一个 session 的数据存储
传统的还有cookie离线存储

应用缓存(Application Cache)=================***
应用程序缓存为应用带来三个优势：
离线浏览 - 用户可在应用离线时使用它们
速度 - 已缓存资源加载得更快
减少服务器负载 - 浏览器将只从服务器下载更新过或更改过的资源。
注意：所有的主流浏览器都支持，除了Internet Explore









