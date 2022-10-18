# Autotools tutorial and demos

我个人认为 ["GNU Autotools: a tutorial"](http://free-electrons.com/pub/conferences/2016/elc/petazzoni-autotools-tutorial/) (by Thomas Petazzoni) 这篇文档是目前关于GNU Autotools培训的最好的文档。至少对我而言，它帮助我在极短的时间内理解autotools系列工具的基本使用方法，使我能够很快地读懂由autoconf/automake/libtool这一系列GNU autotools构建的软件工程，调整和修改这些项目也不再是什么困难的事情，更不用说去构建一个简单的Autotools工程了。 

Github上可以下载到这份培训文档配套的[demo codes](https://github.com/tpetazzoni/autotools-demo)，每个演示程序都很简洁明了。原始的demo codes是按git branch的方式来组织培训文档中涉及的20多段代码的。在这里，我把它们重新拆分出来，放在同一个目录下，这样便于学习和参考的过程中阅读和比较。

另外，《Autotools》 (2ND EDI T ION, by John Calcote)也是一本非常好的关于Autotools的书籍，它更深入地介绍了Autotools, 让我们更容易理解为什么会有Autotools这样的一套工具出现。我尝试着阅读了前五个章节，收获很大，但是，至少目前我没有太多的时间继续阅读下去。也许未来，等我的方向更加明确，并且有了更多的时间以后，我会继续把它读完。

感谢这些文档和书籍的作者们，他们的无私精神是我们的典范！

## 整体架构
![](doc/pics/overall%20organization.png)

## 测试环境
- autoconf (GNU Autoconf) 2.69
- automake (GNU automake) 1.16.1
- libtool (GNU libtool) 2.4.6

## 关于Demos
- autoconf basics demos: demo01 ~ demo05b
- automake basics demos: demo06 ~ demo07
- autoconf advanced demos: demo08 ~ demo14
- automake advanced demos: demo15 ~ demo21

## 参考文档：
- http://free-electrons.com/pub/conferences/2016/elc/petazzoni-autotools-tutorial/
- https://github.com/tpetazzoni/autotools-demo
