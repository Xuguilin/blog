---
layout: post
title: AWS Summit 2014旧金山站总结
---

{{ page.title }}
================

<p class="meta">2014/03/31 - 上海 By 徐桂林</p>

AWS Summit 2014 San Francisco站总结：整体来说，这个会议还是挺有意思和价值。可以让我们更好了解AWS整个生态系统和发展动向，学习到一些不错的AWS实战经验。如果说美中不足之处就是在于针对开发者的内容可能缺少一些深度和干货。

## 什么是AWS Summit？

- AWS Summit 是AWS在全球各地举办的针对AWS用户和开发人员的技术峰会。每年都会有多站，其中今年在全球各地（北美、欧洲，亚洲）有超过12站。其中，San Francisco是今年的第一站。
- AWS  Summit一般是1天的会议，包括半天的Keynote和半天的Breakout Sessions。另外还会有AWS Ecosystem内各种公司的Expo。
- AWS Summit 是一个免费的会议，任何人都可以在它的网上注册。
- AWS 为AWS Summit单独做了一个App。你可以在这里（http://guidebook.com/app/aws/）下载到该软件来了解更多AWS  Summit活动的最新消息。

## AWS Summit 2014 San Francisco基本情况如何？

- 这次会议参加人数超过4000人，除了上午的Keynote（由 Andy Jassy, SVP of Amazon主讲）外，另外还有28个breakout sessions。多达几十家的AWS生态系统内公司参加展览。
- 对这次会议第一个感觉就是人超多，比我想象的要多得多，而且其中还有很多像我这样的从Asia飞过去的人参加会议。而且我的同事告诉我，就这个Summit四年前参加的人才400人。
- 整个会议主要的演讲嘉宾都是AWS的人，但其中有一组Session是Sponsors来讲的。让我比较意外的是，这些演讲中最受欢迎的主要是”Introduction"系列（Introduction to EC2 / Database Services) 和与IT运维相关的。后来和美国同事沟通后，感觉我们确实算是AWS的 Early Adoptor了。即使在美国，很多开发和IT人员也是才开始使用AWS云服务。
- 整个会议中能看到非常多的Startups公司的人参加。很多Startups都是一开始就完全基于AWS来快速实现他们的想法，而且AWS还为Startups设立了专门的服务社区。这次会议中也有不少专门为Startups准备的Session，而且我感觉这些Session的整体质量反而是比较高。

## 这次会议的Keynote讲了些什么？

- 这次Keynote占了一半的时间，由Andy Jassy主讲，并请来了Flipboard、Infor等多家在AWS上面运行服务的知名公司负责人来讲他们的案例。其中Flipboard讲了他们怎样用AWS服务在全球快速Delivery由用户自己编辑的上百万份杂志，而他们整个的Ops team只有3个人。
- Andy Jassy讲的主题是”为什么人们这么快的开始使用AWS服务“。他分析主要有下面的几个原因：
	- AWS提供了灵活性（Agility）
	- AWS提供非常全面的服务（Platform Breadth）
	- AWS是一个持续改进和创新的平台（Continual Invention/Innovation) 
	- AWS可以帮助客户节省成本并保持灵活性（Cost Saving / Flexibility）。AWS邀请了Flipboard的人来讲他们怎样用AWS服务在全球快速Delivery由用户自己编辑的上百万份杂志，而他们整个的Ops team只有3个人。
	- AWS正在帮大家快速迁移传统系统（Migrating existing System）。AWS邀请了Infor公司来介绍他们是怎样基于AWS平台为传统行业打造各种各样的Suites的。

- 除了上面的这些内容，Andy还特意讨论了”Private Cloud“的问题（可见，私有云还一直是AWS的一个痛呀）。他主要强调了现在私有云的普遍问题（如缺少高质量的运维和自动化等），然后强调AWS其实也为构建私有云提供了大量的服务（如VPC、Direct Connect、Storage Gateway等）。

## 这次Keynote上AWS还做了下面的Announcement:

- 最大的消息当然算是其第42次降价。不知道是不是针对Google Cloud Services头一天的大降价，AWS这次的降价幅度非常大。其中存取平均降价50%左右，计算平均降价30%左右，从4月1号开始生效。具体降价细节可见（http://aws.typepad.com/aws/2014/03/aws-price-reduction-42-ec2-s3-rds-elasticache-and-elastic-mapreduce.html）
- AWS讲继续推出或更新EC2实例类型。接下来几周会推出全新的Memory Optimized新实例R3并更新Storage/IO Optimized实例HS1。

你可以在网上观看这次Keynote的Live Video（https://aws.amazon.com/live/）

## 这次会议的Breakout Sessions内容如何？

- 个人感觉这次Breakout Sessions中市场推广和做AWS普及的目的比较明显。而如前面所说，其中的基本介绍和IT运维的Sessions比较多，而且也比较欢迎。但是，针对开发人员的Session感觉数量偏少而且深度也欠佳。
- 你可以在这里（https://aws.amazon.com/aws-summit-2014/san-francisco/）找到整个Breakout session的列表。其中，我比较推荐的Session有如下几个
	- Maximizing EC2 and Elastic Block Store Disk Performance
	- Scaling on AWS for the First 10 Million Users
	- From One to Many:  Evolving VPC Design

- 另外，你可以在下面的链接中找到这次会议所有Session的Slides和Video（其中Video可能还要几天才能观看）
	- Slides：http://www.slideshare.net/amazonwebservices
	- Videos: https://www.youtube.com/user/AmazonWebServices/

## 还有其他相关信息？

- 除了上面的Sessions，会议上的Sponsoer的展览也是很有趣的一个去处。总共应该有超过30+家参加展览，但是我发现其中的赞助商同质化也比较严重，基本上就是”Monitoring“、”Deployment“和”Management“这三个领域。所以，个人觉得AWS这个生态已经开始建立，但是仍然还不够丰富。
- 在所有展览中，我最感兴趣的是一家基于做AWS monitoring服务的公司：StackDriver（http://www.stackdriver.com/）。它可以帮助我们收集AWS CloudWatch数据，添加自定义的Monitoring指标并自动构建实时Dashboard，而且它能同时支持Windows和Linux平台。个人觉得这正是我们Team要的服务。
- 另外，这次会议在最后还由于AWS Social Networking活动（尽管整个会议是免费的，AWS还是比较厚道地提供了午餐、酒水和饮料，但限量供应）。比较有趣的是，我在这里还遇到了最近才买的，目前Amazon最畅销的AWS书籍《Amazon Web Services for Dummies》作者。

整体来说，这个会议还是挺有意思和价值的。可以让我们更好的了解AWS整个生态系统和发展动向，学习到一些不错的AWS实战经验。如果说美中不足之处就是在于针对开发者的内容可能缺少一些深度和干货。

大家如果有任何关于这次会议的问题、想法，欢迎联系我。
