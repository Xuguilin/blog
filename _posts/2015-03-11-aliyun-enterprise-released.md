---
layout: post
title: FIT2CLOUD企业版上架阿里云镜像市场，给阿里云用户带来了什么？
---

{{ page.title }}
================

<p class="meta">2015/01/20 - 杭州 By Simon</p>

经过半年的研发和测试，我们本周正式推出了FIT2CLOUD阿里云企业版，并上架阿里云镜像市场( 链接是： [FIT2CLOUD应用交付及运维管理平台Centos 6.5 64位](http://market.aliyun.com/imageproduct/15-123826001-jxsc000119.html) )。FIT2CLOUD企业版以镜像方式交付，部署在用户自身控制的虚机中，安全可靠。欢迎大家使用，部署和管理指南请查看阿里云镜像市场上的商品介绍。如果你有任何问题，请咨询support@fit2cloud.com。

<font color="#aaa" size="2">备注: 镜像市场上线初期的FIT2CLOUD阿里云企业版镜像均为免费,因此用户只需支付ECS费用即可使用FIT2CLOUD企业版，详情请参考:​ [http://help.aliyun.com/knowledge_detail.htm?knowledgeId=5974158](http://help.aliyun.com/knowledge_detail.htm?knowledgeId=5974158)</font>

<h2>一、FIT2CLOUD阿里云企业版有哪些功能？</h2>

FIT2CLOUD 阿里云企业版是专为阿里云用户打造的一站式运维及持续交付平台，帮助用户打通从代码到服务的通道。其功能涵盖云资源管理、服务器自动化、应用代码管理、应用部署、监控告警等，具体包括：

 1. 导入包月虚机进行分类管理：FIT2CLOUD可以对用户的包月虚机进行分类管理，用户可以按照应用系统进行分类管理，也可以按照开发、测试、生产环境进行分类管理；
 2. 一键创建应用所需的云资源：在FIT2CLOUD中，一个应用系统对应于一个集群，一个集群包括若干个虚机组。用户可以定义每个虚机组下的虚机镜像类型、数量、虚机规格大小、数据盘大小、防火墙、关联的负载均衡。集群启动后，FIT2CLOUD会自动创建这些资源，并自动设置这些资源之间的关联关系；
 3. 虚机安装和配置：虚机启动前，用户可以预定义虚机启动后所要执行的脚本。虚机启动后，用户可以同时在多个虚机上执行脚本，无需SSH登录到每个虚机运行命令；
 4. 代码部署：FIT2CLOUD可以帮助用户将代码有序、可控可视化地部署到指定虚机上，实现部署的自动化、标准化和可视化；FIT2CLOUD代码部署兼容AWS CodeDeploy(Amazon内部部署平台Apollo的公开版本) appspec.yml规范；
 5. 统一的监控告警：FIT2CLOUD支持虚机和站点的监控。用户可以自己定义监控脚本，实现自定义监控；
 6. 自动伸缩功能：FIT2CLOUD支持基于时间的伸缩和基于监控数据的伸缩；

<h2>二、FIT2CLOUD阿里云企业版有哪些特点？</h2>

 1. 安装快速简单：整个安装部署过程只需要几分钟就可以完成。
 2. 系统管理方便：可集中管理云账号且所有操作可追踪，方便系统安全管理和审计。
 3. 使用灵活高效：支持导入虚机和FIT2CLOUD启动虚机两种模式，可管理高达万台虚机规模，提供代码部署、监控告警、批量执行脚本等丰富功能。
 4. 数据安全可控：整个FIT2CLOUD企业版本的数据都保存在用户的虚拟机上，FIT2CLOUD不会上传任何用户业务数据。
 5. 版本持续更新：FIT2CLOUD系统初次交付通过镜像完成，之后，FIT2CLOUD可以帮助用户按需更新企业版，保证用户系统的安全、稳定。
 6. 专业技术支持：拥有资深云管理支持团队。成员有多年云管理经验，运营过万台规模虚机集群。

<h2>三、FIT2CLOUD阿里云企业版给阿里云用户带来了什么？</h2>

<h3>3.1 打通从代码到服务的通道</h3>

IaaS会是新常态，将成为互联网和企业的基础设施。云IT和传统IT有很大的不同。 使用IaaS只是第一步，企业应该利用上云这个契机，在应用架构、部署管理工具、开发运维协作方式也进行转变。我们把持续交付分解成三条主线（从代码到服务）:
 
 * 从Code到Artifacts仓库；
 * 从Artifacts到Running Service；
 * 从开发、测试环境到准生产、生产环境。

针对以上过程中实际的需求，FIT2CLOUD提供一站式的应用交付及运维管理工具，同时还提供方法论来帮助企业打通从代码到服务的通道，提升持续交付能力。

![打通从代码到服务的通道](/images/from-code-to-service.png =600x)

针对阿里云用户，FIT2CLOUD基于阿里云的服务帮助阿里云用户无缝衔接这三条主线：

 * 实现基于阿里云OSS的统一Artifact仓库；提供Jenkins插件，方便上传Build Artifact到阿里云OSS
 * 应用全生命周期的自动化管理：云资源的创建和管理、虚机自动化安装和配置、代码部署, 监控告警。
 * 统一DTAP环境的部署和管理。

<h3>3.2 提供一站式的应用交付及运维管理平台</h3>

FIT2CLOUD阿里云企业版完全基于阿里云的API，这是FIT2CLOUD传统IT运维管理工具最大区别所在。基于阿里云云平台的API，FIT2CLOUD:

 * 实时感知云基础设施的变化, 自动衔接基础设施变化与应用管理运维操作各个阶段的任务；
 * 实现真正意义上包含基础设施在内的一键部署。
 * 最大限度地将应用的交付过程自动化，提高效率和避免手工操作的不规范和风险；
 * 简化项目过程的管理及沟通成本，提高效率，让项目开发测试运维人员可以自助创建环境和变更环境，而不依赖于特定的人。
 * 为阿里云用户提供一站式应用交付及运维管理平台，如下图所示：
 
 ![应用交付及运维管理平台](/images/app-delivery-ops-platform.png =600x)

相比较IaaS领域的领头羊AWS，FIT2CLOUD企业版给阿里云带来了大量AWS产品体系内拥有的服务，让国内用户在享受阿里云优秀的基础设施服务同时，也同样可以使用到非常丰富的运维、管理和部署服务（如下图），从而提升云上效率。

![阿里云AWS部署服务对比](/images/aws-aliyun-deploy-management-service.png =600x)

<h3>3.3 云账号及资源的集中安全管理</h3>

FIT2CLOUD系统中有两类用户,即系统管理员和普通用户。其中系统管理员负责整个系统的配置、日常管理工作,而普通用户为使用FIT2CLOUD系统进行云上运维和代码部署的开发、测试
及运维人员。其中普通用户由FIT2CLOUD管理员创建和管理。通过这种用户管理体系,可以帮助用户实现对于云账号及资源的集中安全管理,具体体现如下: 

 * 集中管理阿里云的账号。系统管理员拥有阿里云账号信息，然后通过FIT2CLOUD把云账号对应的AccessKey授权给普通用户，让其可以使用该云账号的资源。但普通账号无法修改,查看相应云账号的信息。由于普通用户没有具体的阿里云账号信息,仅通过FIT2CLOUD实现对于阿里云资源的访问。在发生人员转岗、离职等情况下只需禁用、删除相应FIT2CLOUD账号,不用修改阿里云账号或者AccessKey来避免权限外流。 
 * 灵活管理FIT2CLOUD普通账号。FIT2CLOUD管理员可以非常方便得添加、修改、删除或者禁用一个普通账号,以适应实际团队变化的需求。同时,FIT2CLOUD还可以通过给普通用户授权不同阿里云账号下的AccessKey,达到不同用户操作不同阿里云账号的目的,实现资源访问的隔离。 
 * 追踪所有用户操作。FIT2CLOUD内所有用户(包括系统管理员和普通用户)的日常操作都可追踪,系统管理员可以查看自己或者任意一个普通用户的操作记录。这样可以及早发现潜在风险,进行事后回归分析,满足安全审计规范。 

总结而言,通过FIT2CLOUD的”系统管理员 + 普通账号“两层账号体系,利用阿里云账号的AccessKey,达到了”主­子“账号效果,方便用户更好管理,控制自己的云上基础设施。