##mdpress

###项目介绍

博客系统那么多，新写一个的出发点是 wordpress 太卡了，我就想好好写文章，能够不时更换一个模板，加一下自己喜欢的小功能。

这个项目是基于[Editor.md](https://pandao.github.io/editor.md/examples/index.html "Editor.md")创建的，主要在原有的基础上增加了保存功能，这样的话，你就可以直接在编辑完之后保存啦～～

demo: [Angiris Council](http://mdpress-tyraeldemo.rhcloud.com/)

###依赖

保存查看功能需要：tidy扩展<br/>
不需要保存查看功能无特殊依赖

因为我们的保存功能解析标题是解析标签&lt;h2&gt;的标签为标题，所以使用到了HTML解析功能，这里使用的是[bupt1987](https://github.com/bupt1987/HtmlParser "bupt1987")同学提供的html-parser库。而这个库依赖于tidy扩展，所以你的PHP运行环境需要支持tidy.

###作者介绍
想知道更多关于我的东西，请访问我的网站：   [liuliqiang.info](http://liuliqiang.info)

###联系我

欢迎戳邮件：liqianglau@outlook.com

### 痛点

- 文章找不到
- 图裂了

### 特性

- 目录结构强大
- 支持搜索
- 代码高亮[可根据语言/可高量指定行]
- 图片上传方便
- 统一的图片管理功能，保证图片不丢失

###Screen Shoot
**Index**
![](http://ooo.0o0.ooo/2016/07/27/579978371acf9.jpg)
**Archive**
![](http://ooo.0o0.ooo/2016/07/27/5799783689c9f.jpg)

**Admin Login**
![1.pi](http://ooo.0o0.ooo/2016/07/27/5799783457de9.jpg)
**Admin Main**
![2.pi](http://ooo.0o0.ooo/2016/07/27/5799783ceb8a4.jpg)
**Post List**
![3.pi](http://ooo.0o0.ooo/2016/07/27/5799783a4fa9d.jpg)
**Post Editing**
![4.pic_hd](http://ooo.0o0.ooo/2016/07/27/5799783c46069.jpg)
**Tags List**
![5.pi](http://ooo.0o0.ooo/2016/07/27/579978398a840.jpg)

###Updated History

- v0.1 
	- 2015-02-18 14:38:03 
	
	创建项目，并且实现基本功能
	
- v0.2 
	- 2015-02-21 11:57:03 

	增加保存，查看功能

- v0.3 
	- 2016-06-04 13:03:31 

	重构代码结构
