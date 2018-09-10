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

画布元素-----
1.canvas 画布功能


媒体元素------
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


表单元素-------
1.datalist表单和input配合使用
2.output元素（部分浏览器支持）


语义和结构元素----------
1.section 块
2.article 独立的内容
3.aside 配合article使用，是内容以外的部分
4.nav 导航使用标签
5.header 页眉可以在section也可以在article标签中，可以如下使用
   <pre>
    <article>
        <header>
            <h1>Internet Explorer 9</h1>
            <p><time pubdate datetime="2011-03-15"></time></p>
        </header>
    </article>
    </pre>
6.footer页脚  标签定义文档或者文档的一部分区域的页脚。
7.time标签 IE9及以上
8.progress标签  IE10及以上
9.mark标记标签高亮  IE9及以上
10.figure 标签规定独立的流内容（图像、图表、照片、代码等等） IE9及以上浏览器
11.figcaption  IE9及以上
  <figcaption> 标签为 <figure> 元素定义标题。
  <figcaption> 元素应该被置于 <figure> 元素的第一个或最后一个子元素的位置。



