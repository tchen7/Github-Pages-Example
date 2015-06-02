<!-----
layout:     post
title:      我为什么写博客？
category: blog
description: 写博客这个这么古老的行为，还有必要拿出来说吗，我看有。
----->

## 评论系统测试

基于jeckll和github建立的博客是静态的，因此不能自带评论系统。 我们需要使用第三方的评论插件。 我只是想测试下Disqus评论是否好用。

## 技术很简单，不用担心

或者你很幸运不是一个程序员，或者你是一个不用搞这些乱七八糟东西的程序员，那么相信我，你一样可以搭起来一个跟我的一模一样的个人站点的。

我要特别鸣谢以下几个站点、技术：

* [GoDaddy][]
* [DNSPod][]
* [GitHub][]
* [Jekyll][]
* [Disqus][]

下面我来做一个简要说明，完整的搭建方法，我后面会专门写一篇博客分享给大家，等不及的可以自己去找资料哈。

### GoDaddy & DNSPod

[GoDaddy][]是一家非常不错的域名注册商，良好的用户体验，飞快的生效速度，给力的优惠码，也支持支付宝，永远不用担心国内那些流氓厂商的流氓行为，注册了域名，就可以放心不会被别人抢走。在Godaddy注册域名是一件很简单的事情，按照提示走就完全没有问题，唯一需要动脑筋的可能是，你要想一个既有个人标识，又没有被别人注册的域名了，我觉得我的[BeiYuu][]还是不错的，呵呵。

Godaddy一切都很完美，直到遇到了GFW，原因你肯定懂。前段时间推上风传Godaddy的DNS服务器被墙，导致域名不能解析，看起来好像自己的站被墙了一样，这个确实是个闹心的事情，还好国内有DNS服务的替代产品，而且做得还非常的不错，也是免费的，功能强大，速度快，不用担心被和谐，所以隆重推荐[DNSPod][]给大家，可以试用一下，把DNS服务迁移到DNSPod来，解决后顾之忧，配置比较简单，不懂的可以等我后面的博客啦，哈。

### GitHub & Jekyll

[GitHub][]是一个非常优秀的产品，爆发式的增长，各大优质开源软件的蜂涌而至，只能说明人们太需要他了。**Social Coding**是他的Slogan，产品的设计确实解决了很多代码交流的难题，让世界更平，让交流更畅，关于Git的学习，大家可以移步这里[Pro Git中文版[7]，这也是一个本身就在Github维护的一个项目，高质量的翻译了Git入门书，讲解详细，是学习Git的好资料。

GitHub是一个伟大的产品，[GitHub Pages][]是他伟大的一部分，GitHub Pages基于[Jekyll][]博客引擎，当我深入的研究了他之后，我深深的想给Jekyll的作者一个拥抱，列举一下Jekyll的优点：

- 可以单独放在自己的服务器上，他也是GitHub Pages的基础，质量可靠
- 将博客最重要的功能抽取出来，去除了[WordPress][]的复杂、烦躁的东西，一切都是清晰可控的 
- 可以方便的使用[Markdown][8]等其他标记语言 
<li>清晰、简洁的文件组织，完美的永久链接方案，既漂亮、又可定制</li>
<li>博客静态化，速度快</li>
- [Jekyll][]是完美的 

### Disqus

[Jekyll][]都很不错，但是可能有些童鞋会不满意于他不提供评论功能，这个时候，[Disqus][]的出现就显得是雪中送炭了。

Disqus是一个社会化的评论解决方案，请允许我使用这个烂透了的词，调用它的接口非常简单，在自己的页面加载他的一段JS代码即可，如果别人注册了Disqus，那么就可以方便的留言，交流，一处登录，处处方便，而且Disqus也提供了一些spam等策略，不用自己操心了，并且可以和一些现有的博客系统很好的转换对接。越来越多的网站开始使用Disqus的服务了，这是一个非常不错的趋势，Jekyll配合[Disqus][]实在是完美了。我别无所求了。

## TL;DR

写到这里，基本的点已经介绍完毕，看看Jekyll生成的博客页面，我心满意足，虽然文笔很烂，语句多不通顺，但是这是一个新的开始了，我觉得心灵都纯洁了不少，这不是发一条微博什么能带来的快乐。

对于那些对上述技术不是很熟悉的童鞋来说，搭建起来可能还是需要花费些功夫的，我会在后面写一篇专门的教程，给有需要的人，等不及了的，可以自己研究下，**生命在于折腾**。

[BeiYuu]:    http://beiyuu.com  "BeiYuu"
[Steve Losh]:   http://stevelosh.com/   "Steve Losh"
[Derek Sivers]: http://sivers.org/  "Derek Sivers"
[GoDaddy]:  http://godaddy.com  "Godaddy"
[GitHub]: http://github.com "Github:social coding"
[Jekyll]:   https://github.com/mojombo/jekyll
[Disqus]: http://disqus.com "Disqus"
[DNSPod]: http://dnspod.cn "DNSPod"
[GitHub Pages]: http://pages.github.com "GitHub Pages"
[WordPress]:    http://wordpress.org    "WordPress"
[7]: http://progit.org/book/zh/    "Pro Git"
[8]: http://markdown.tw/    "Markdown语法"
