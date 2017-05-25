###### 内容与Demo来自 [青玉伏案的博客](http://www.cnblogs.com/ludashi/p/6145344.html) || [Demo](https://github.com/lizelu/PerfectDemo)   

#### 一、Perfect框架简介

> Perfect框架是目前比较完善的Swift服务端框架之一，当然其他的还有Vapor等其他的开源框架，横向的对比了一下，还是Perfect的功能全面一些，目前Perfect的最新版本是2.0，由加拿大一创业团队开发并维护。Perfect框架也是开源的，在Github上可以找到相关的源代码（Perfect-Github地址：https://github.com/PerfectlySoft/Perfect ）。Perfect的官网地址：https://www.perfect.org/ ，官网上有相关的Demo以及使用文档，关键是其开发文档有中文版的，这一点还是比较好的，官方开发文档地址：https://www.perfect.org/docs/index_zh_CN.html 。

#### 二、示例展示

> 接下来我们先来看一下使用Swift3.0开发的服务端和iOS端的小Demo。在博客的开头我们也提到过，我们要展示的Demo是一个简单的笔记。包括登录、注册、笔记的增删改查等功能。我们的服务端和iOS客户端都是使用Swift3.0来实现的，当然服务端就是使用的上述的Perfect框架。接下来我们整体的看一下Demo的效果，后续的博客会给出更为具体的实现方式。

 
下方就是我们Demo运行的具体效果，首先输入用户名点击下一步，如果用户已注册，让其输入密码登录。登录后进入笔记列表页面，可以对相应的笔记进行增删改查操作，具体做法如下所示。下图左边就是iOS客户端运行的效果，右边就是MySQL中的数据更新情况。

![运行效果](http://images2015.cnblogs.com/blog/545446/201612/545446-20161208170159257-690509734.gif)

###### 内容与Demo来自 [青玉伏案的博客](http://www.cnblogs.com/ludashi/p/6145344.html) || [Demo](https://github.com/lizelu/PerfectDemo) 

---
写在最后：此项目已解决了一些坑点，如果PerfectTemplate文件中Demo不能正常运行，请解压"[PerfectTemplate.zip](http://10.36.16.11/pengyef/PerfectTemplate/PerfectTemplate.zip) "文件中的内容运行




