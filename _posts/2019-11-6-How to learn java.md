---
layout: post
title:  如何自学JAVA    #title
date:  2019-11-6 #2019-
img: post-7.jpg
tags: [Blog,Java]
published: true
---

1.基础知识学习
-------------------------
首推[《Java核心技术》][Core Java Volume I]，主要是体系完整，实例多，可操作性强。对初学者，重点只讲前6章，也就是下面的内容：
: 1.Java程序设计概述
: 2.Java程序设计环境
: 3.Java的基础程序设计结构
: 4.对象与类
: 5.继承
: 6.接口与内部类

**学习流程：**
![第一阶段]({{site.baseurl}}/assets/img/post-7-2.jpg)

**学习过程建议：**

注重笔记:
>因为是自学，不像在企业中学了就能够实践，印象自然特别深刻。而自学因为没有实践的及时反馈，所以记笔记就显得特别重要。因为记笔记就像写作一样，是整理思路的绝佳方法。同时学习笔记也是你以后开发，面试的绝好资料。学习编程，人跟人是不一样的，别人觉得难理解的东西，对你却不一定；而你觉得难理解的东西，别人可能又会觉得特简单。而学习笔记就是自己专有的“难点手册”，有点像高考时的“错题本”，以后无论是在面试前，还是在日常工作中，随时都可以翻出来看看，自是获益匪浅。

做好demo管理:
>**千言万语都没有一段代码来的实在。**
>在整个学习的过程中，就某个知识点，无论当时理解的多透彻，调试的多棒，只要时间一长，等到了实用的时候，肯定会碰到各种各样的问题，一些看似简单的东西，此时死活就是调不通，正所谓人到事中迷。这个时候，如果你手头恰有运行良好的demo，打开参考一下（甚至直接拷贝过来），问题自然迎刃而解。而且因为这些demo都是你亲手调试出来，印象自然特别深刻，一碰到问题，在脑子中自会立刻涌现。所以说，在学习的过程，一定要善待你调通的demo，千万不要用完了就扔，等后来碰到困难，想要用时却找不到，追愧莫及。正确的做法就是把所有调通的demo，分门别类的保存起来，到时候查起来自是得心应手。



2.Javaweb框架学习(Spring)
-------------------------
Spring已经当今主流成为Javaweb开发框架，是任何一个Java程序员都必须掌握的内容。因此，在掌握了Java基础知识后，接下来应转入Spring的学习。

推荐书籍:[《Spring实战》][Spring in Action],[《设计模式》][Head First],等

**推荐网课**:[JavaEE实战框架系列][JavaEELesson]

**学习流程：**
![第二阶段]({{site.baseurl}}/assets/img/post-7-3.jpg)

在正式接触Spring知识之前，先进行 Maven和Junit的学习。

Maven和Junit，从实用角度看都不难理解，上网搜索就可以满足学习的需要。

Spring的学习又分为多个阶段：Spring Core、Spring MVC、Spring Boot等

Spring MVC是建立在Spring Core之上，在Web MVC领域的具体应用。因此，在学习Spring MVC之前，除了学习Spring Core，还必须掌握与Java Web相关的知识，其中最核心的就是Servlet。

在通常的Java学习中，建议要掌握一些基本的前端知识特别是JavaScript，从而便于对Spring MVC进行测试。

Spring是Java学习中最难的部分。但是，一旦跨过这个门槛，从此之后，你基本就踏上了开发级Java学习的通途。

关于Spring的学习资料，我推荐《Spring实战》，虽然我个人对它并不十分满意，但已是我读过的最好的书。阅读的过程中，真遇到不理解的东西，记着随时上网搜索。

**提示:**
>JavaWeb与Spring对初学者不算简单，因此最好能找或买个好网课学习配合相关书籍，不用太长时间，2个课时即可，然后就是在你遇到大的困难时，尽量找人点拨下，需要1到3个月的时间。

3.其他方面
-------------------------
Spring只是Javaweb编程的基础设施，想真正参与企业级项目开发中，亦或是对Java原理机制还想了解，还有些东西绕不过，包括:
: [MySql][mysql]
: [Mybatis][mybatis]
: Redis
: Servlet
: JVM
: Tomcat
: Git
: ...
总之在成为真正从事创造性工作的程序员的过程中，学习从未停止！

4.参考
-------------------------
**Links:**
: [Java高效学习路线][link4.1]
: [学习Spring之前先学习什么][link4.2]
: [Java没必要学习的知识][link4.3]
: [W3school][link4.4]

[link4.1]:https://zhuanlan.zhihu.com/p/84032726
[link4.2]:https://zhuanlan.zhihu.com/p/64001753
[link4.3]:https://www.zhihu.com/question/305924723/answer/557800752
[link4.4]:https://www.w3school.com.cn/

[mysql]:https://www.mysql.com/
[mybatis]:https://blog.mybatis.org/
[JavaEELesson]:https://study.163.com/series/1202814605.htm
[Head First]:https://book.douban.com/subject/2243615/
[Spring in Action]:https://book.douban.com/subject/26767354/
[Core Java Volume I]:https://book.douban.com/subject/26880667/
