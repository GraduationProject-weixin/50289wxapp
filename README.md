# [首页查询更多项目](https://github.com/GraduationProject-weixin) 包安装运行


# 50289wxapp微信小程序的大学生科技竞赛管理系统的设计与实现+springboot

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)]()


# 第1章 绪论
## 1.1 课题研究背景与现状
自我国经济快速发展后，我国的科技也日新月益。科技发展中表现最好的是计算机和互联网的应用，渗透到各行各业，我国的电子商务行业和手机支付业务更是处于世界顶峰位置。在现代生活中，无论从最基本的吃、穿、住、行还是到高级管理都充斥着网络和科技的技术，所以也给计算机应用技术造成了更大的压力和责任。互联网的世界中最重要的就是数据，数据时代可以泄露严重的企业机密，一个好的软件更重要的就是安全保密。一味的追求信息数据处理的快速、简单、实用已不能满足现代社会。可以和实际生活相贴合，保证数据的安全，才是一个合格的系统。在保证所需要的功能后又可以实现数据的共享与私密是现代科技所要实现的目的。

本基于微信小程序的大学生科技竞赛管理系统就是依托互联网和计算机技术的新型管理系统，需要硬件以及软件的支持，结合实际与科技使报名的管理可以更加的科学。作为一个学校来说，学生人数都是比较多，相对各方面的管理都是一个相当大的挑战，学校大多都引进了相对化的计算机管理模式，比如我们常见的学生信息管理系统，宿舍管理系统，这都是在信息化发展下的一个产物，而如今已经不仅仅局限在单纯的学校管理方面，已经融入了生活中的方方面面，比如一些学校的比赛，竞赛信息都开始转化为网上模式的进行，学生也可以参与进来，形成了一个互动，直接在网上就可以参与学校的所有竞赛。对学生来说，更加的方面快捷，可以更加实时的了解学校的最新公告，不容易错过，对于学校来说，也是节省了很大的劳力和物力，是一个一举两得的事情。
## 1.2课题开发目的与意义 
现如今的时代就是科技的时代，无论任何细小事情的管理都会有科技的力量。使用科学的办公手段可以高效、准确的完成工作，可以把复杂流程化的繁琐过程进行简化，减少办公人员出错的概率。本基于微信小程序的大学生科技竞赛管理系统采用管理员和学生、主办方相结合，管理员进行竞赛信息的审核，用户信息审核与录入，学生在操作端可以不分时间的查询竞赛信息和在线报名，减少等候时间，主办方可以进行竞赛的在线评分，实现透明化操作。本系统可以改变传统管理方式数据模糊，操作不透明的现象，可以减少管理人员工作量。学校也是一个小社会，在以往经常会有管理人员利用一点小权利在报名方面做文章，学生也没有有效的平台来进行查证；本系统更可以帮助管理人员从手动劳动中解放出来，在信息的查询、信息的更新和安全上都更为优秀。
## 1.3 课题设计思想
本系统在设计时采用功能完整、界面简洁、操作简单的思想进行设计。在系统设计前本人充分掌握相关技术和知识，根据所接触的报名管理工作整理出完整的功能以及流程。然后进行系统的分析，分析系统是否具有开发的价值，本人是否具有系统开发的能力等，为了保证系统开发的完整性，需要事先进行实地的调查，“没有实践就没有发言权”接下来进行系统的设计阶段，系统的设计是系统实现的基础，系统的设计主要是功能的设计和数据库的设计，数据库包括概念结构设计和逻辑结构设计；最后一部分是系统的实现，可以根据系统的设计进行实现，在实现的过程中不断的发展问题和改正问题。
#


#
#
#
#
#
#
#
#
#



# 第2章 系统分析
## 2.1 系统开发工具分析
本系统中采用的开发工具包括软件工具和硬件工具，软件采用了Java语言和MySQL数据库，利用微信小程序技术，框架采用SpringBoot；硬件工具采用windows10操作系统。服务器采用了Tomcat，运行软件为微信开发者工具。
### 2.1.1 微信开发者工具分析
微信开发者工作是微信官方提供的针对微信小程序的开发工具，集中了开发，调试，预览，上传等功能。微信团队发布了微信小程序开发者工具、微信小程序开发文档和微信小程序设计指南，全新的开发者工具，集成了开发调试、代码编辑及程序发布等功能，帮助开发者简单和高效地开发微信小程序。启动工具时，开发者需要使用已在后台绑定成功的微信号扫描二维码登录，后续所有的操作都会基于这个微信的帐号，程序调试主要有三大功能区：模拟器、调试工具和小程序操作区，模拟器模拟微信小程序在客户端真实的逻辑表现，对于绝大部分的 API 均能够在模拟器上呈现出正确的状态。

调试工具分为 6 大功能模块：Wxml、Console、Sources、Network、Appdata、Storage以及WxmlPannel。
### 2.1.2 VUE技术分析
JAVA语言中用于Web技术编程的就是Vue技术，Vue技术可以进行封装，即对动态网页封装起来，把网页的逻辑和网页的设计、显示进行分离，Vue技术支撑着可以重用的组件开发。Vue技术和servlet技术都是一种通过服务器运行的技术，其特点可以把Html页面进行返回，也就是可以使用户使用浏览器进行访问页面。在大型的设计项目中，经常会使用Vue技术和Servlet进行合作，当Vue网页进行请求时，计算机可以利用服务器先进行运行处理，然后再把结果用Html的代码和处理结果一起返回。
### 2.1.3 JAVA语言分析
`    `JAVA语言是现在最受欢迎的语言之一，主要用于网络和Internet中，最开始是用于分布式的语言编程中。主要的特点是具有分布式、面向对象、安全、高效等优点。面向对象指的是根据我们人类的惯有思维进行编写，这样写出来的代码更加的简单易懂，有利用其它程序人员的再次使用。其次Java语言还有封装性的特点，可以把属性和行为都封装到一个类中，Java语言可以把类封装到一个抽象类中，可以不详细描述对象。
### 2.1.4 MySQL数据库分析
MySQL数据库是一种单独可使用的数据库，因为处理能力强、运行速度快，所以广泛应用于中小型的项目中，也成为编程人员在练习中最常使用的数据库。MySQL数据库在安装的时候非常好安装，并且安装速度也非常快，支持Java语言、php语言、Java语言等，兼容性非常好。
### 2.1.5微信小程序分析
[微信]( t )小程序，[小程序](https://baike.baidu.com/item/%E5%B0%8F%E7%A8%8B%E5%BA%8F)的一种，英文名Wechat Mini Program，是一种不需要下载安装即可使用的[应用](_blank)，它实现了应用“触手可及”的梦想，用户扫一扫或搜一下即可打开应用。

全面开放申请后，主体类型为企业、政府、媒体、其他组织或个人的开发者，均可申请注册小程序。微信小程序、微信订阅号、微信服务号、[微信企业号](https://baike.baidu.com/item/%E5%BE%AE%E4%BF%A1%E4%BC%81%E4%B8%9A%E5%8F%B7/14691335)是并行的体系。微信小程序是一种不用下载就能使用的应用，也是一项创新，经过将近两年的发展，已经构造了新的微信小程序开发环境和开发者生态。微信小程序也是这么多年来中国IT行业里一个真正能够影响到普通程序员的创新成果，已经有超过150万的开发者加入到了微信小程序的开发，与我们一起共同发力推动微信小程序的发展，微信小程序应用数量超过了一百万，覆盖200多个细分的行业，日活用户达到两个亿，微信小程序还在许多城市实现了支持地铁、公交服务。微信小程序发展带来更多的就业机会，2017年小程序带动就业104万人，社会效应不断提升。
## 2.2系统需求分析
需求分析顾名思义就是系统是否需要开发，是否有需求。通过详细的分析系统的工作内容以及各阶段、各功能的需求来确定系统的开发实现，对于系统的需求分析从功能方面、性能方面来进行分析。
### 2.2.1 性能需求分析
本基于微信小程序的大学生科技竞赛管理系统可以稳定、快速的运行主要依靠的就是系统在开发中严格的性能要求。性能要求主要包括几个方面：

（1）在系统开发中要注意信息的安全，因为系统中会有大量的个人以及学校的内部信息，在现代社会中数据非常重要，相当于人的隐私，所以需要额外注意；

（2）在系统开发中要注意所使用技术以及所开发功能的先进性，不能刚开发设计好就被淘汰；

（3）在系统开发中要注意所开发的系统要可以进行扩展，人都不会站在未来考虑事情，所以开发的系统必然会不适应今后的社会生活，需要不断的改进，这时候就需要设计好各个端口方便今后其它编程人员的扩展；

（4）在系统开发中要注意所开发的系统的有效性，所开发的系统要可以实现用户的需求，并且可以尽最大可能的满足用户的隐形需求。
### 2.2.2 功能需求分析
所设计的大学生科技竞赛管理系统在角色方面包括学生和管理员以及主办方，功能模块有用户管理、主办方管理、公告栏管理、竞赛分类管理、竞赛信息管理、报名信息管理和竞赛成绩管理、系统管理。主办方可以发布竞赛，学生可以报名，报名后由主办方审核和发布成绩，发布的成绩由管理员审核后才可以在首页里展示。
## 2.3可行性分析
`    `为了保证系统设计的顺利进行，保证系统在时间、空间、运行、开发、技术、财力方面都可行。本大学生科技竞赛管理系统从技术可行性、经济可行性以及操作可行性三方面来进行分析。
### 2.3.1 技术可行性分析
`   `本系统在技术方面采用了硬件和软件两个部分，软件上采用了微信开发者工具、Idea软件和MySQL数据库；硬件采用了本人普通电脑、手机进行开发。
#### 2.3.1.1硬件技术可行性分析
`    `本系统在硬件运行上必没有采用特别要求高的硬件，在市面上流通的计算机、手机都可以使用，当然对于一些特别老旧的计算机，比如很多年的128m内存这样的硬件还是不能运行的。但这些特别老旧的计算机已被淘汰，市场上根本找不到它的流通，所以不需要担心。本人也在多种计算机上测试过，都是可以快速调试运行的，所以本系统在硬件技术上是可行的。
#### 2.3.1.2软件技术可行性分析
`    `本系统在开发软件中采用了MySQL数据库和微信开发者工具，MySQL数据库和微信开发者工具软件都是免费开源的，并且支持多种编程语言，为Java语言提供了完美的组件支持。所以本系统在软件技术可行性分析是可以的。

综合硬件技术和软件技术可行性分析得出本系统在技术可行性上来说非常具有开发价值。
### 2.3.2 经济可行性分析
经济方面的分析可以分为系统的开发、维护成本和系统的收益。本系统的开发是做为练习测试使用，所以不会产生收益，所以本论文不从系统的收益方面进行分析。本系统在系统的开发中涉及的成本费用问题从以下几点来进行分析：

1. 本系统的开发可以改变传统的浪费纸张、查询统计不方便的问题，并且可以有效的降低数据的出错率，可以降低工作人员的管理成本，为使用方节省资金成本；
1. 本系统在开发中所使用的技术都是免费的，本系统也不存在后期的维护和升级补丁，并且本系统在运行配置方面并没有太高的要求；

综合以上两点进行分析，本系统在经济方面的分析是可行的。
### 2.3.3 操作可行性分析
考虑到使用本系统的人员不可能都是专业的编程人员，不可能都是经过专业培训的技术人员，所以在设计中本系统的操作流程非常的简单，采用“看到即所得”的方式进行设计。所有的操作都可以立即给出反应，非常好用。所以本系统在操作的分析上也是可行的。
## 2.4 系统数据流程分析
本系统的流程为用户凭借账号、密码进行登录，进入功能界面，管理员可以管理系统用户的基本信息，学生可以查询用户信息以及在线报名，主办方负责对报名审核和发布成绩等，具体的流程如下图2.1所示：

`        `![](/md/blog.001.png)

图2.1 系统数据流程图
## 2.5系统用例分析
本系统包括学生和管理员和主办方。本系统的用例图如下图2.2所示：

![](/md/blog.002.png)

图2.2系统用例图
## 2.6 界面需求分析
只有一个好的界面才可以吸引更多的用户，界面的设计已成为系统中重要的一部分。界面设计包括输出设计和输入设计，具体的界面设计包括以下方面。
### 2.6.1输出设计分析
对计算机输入的信息进行处理并进行反馈就是输出，输出需要形成有标准的格式给编程人员。系统在开发过程中是先进行输出设计再进行输入设计的，这是因为需要把输出的信息和使用人员进行联系，在输出设计的时候需要把每个部门的信息进行快速的反馈，并且还要以最简洁的格式进行展示。
### 2.6.2输入设计分析
`   `输入的设计非常重要，往往对于数据的输入需要大量的人力和工具才可以实现，因为如果输入的数据有问题，那么问题会随着系统的深入而越来越大，并且不好查找源头。在输入设计的时候需要注意几点：

1. 在信息输入时，应该保证以最少的字段来进行有效的输入，这样可以减少数据的出错，并且对于数据的处理也可以提高效率；
1. 在信息输入时，保证输入的数据的时间，时间越短出错率越低；
1. 信息输入后要进行检查，在起点就进行错误的筛查，以便尽早发现问题进行修改；
1. 信息输入后要记录信息的格式，可以保证当信息要进行转换时发生错误。


# 第3章 系统设计
## 3.1 系统架构设计
### 3.1.1系统功能结构设计
把系统看成一个任务，把本任务进行划分，划分成不同的小任务的过程就是系统的功能结构设计，把小任务完成后再组成完整的任务。系统功能结构设计的过程如下：

1. 首先把系统分成多个小功能模块；
1. 对多个小功能模块进行设计完成；
1. 对多个小功能模块进行连接设计；
1. 多个小功能模块进行整合，设计输出。
### 3.1.2系统网络拓扑结构图
`    `本大学生科技竞赛管理系统在管理端采用的网络拓扑结构为B/S。B/S结构是一种依赖浏览器而进行访问的技术，该结构在如今网络发达的时代中非常好用，用户不需要安装客户端，只需要访问固定的网址就可以进行浏览访问。具体的拓扑图如下图3.1所示：

![](/md/blog.003.png)

图3.1 B/S结构网络拓扑图
## 3.2 系统功能模块图
本基于微信小程序的大学生科技竞赛管理系统包括学生和管理员和主办方三个角色，学生可以浏览竞赛信息然后进行报名，管理员可以对用户信息进行管理，可以发布公告和审核竞赛、成绩。主办方可以录入竞赛信息和审核报名、发布成绩，主要的功能如下图3.2系统功能模块图所示：

![](/md/blog.004.png)

图3.2系统功能模块图
## 3.3数据库设计
数据库又称为DBS，是由系统中的数据以及数据相关的程序组成的。数据库又可以称为数据的集合，设计数据库的主要目的就是为访问数据提供平台，数据库的好坏直接影响着系统的运行速度。
### 3.3.1数据库设计原则
数据库设计的方法一般有从上而下、从下向上、向外扩张和混合方式。数据库的设计分为两个步骤，第一步进行数据库的概念结构设计，对系统中的字段、实体、关系等进行设计；第二步进行数据库的逻辑结构设计，把第一步的概念结构设计转换为逻辑结构。
### 3.3.2 数据库概念结构设计
根据数据分析得出来的结果从下向上进行设计，站在用户的立场上进行视图的开发，然后把视图进行整合，最后得出整合的结果。这个过程就是数据库的概念结构设计，采用ER图来进行表示。Er图可以表示实体以及实体的主键、外键以及关系等，数据库的概念结构设计是独立存在的，不依附任何组件。

1. 学生信息ER图如下图3.3所示：

![](/md/blog.005.png)

图3.3学生信息ER图

1. 竞赛信息ER图如下图3.4所示：

![](/md/blog.006.png)

图3.4竞赛信息ER图

1. 报名信息ER图如下图3.5所示：

![](/md/blog.007.png)

图3.5报名信息ER图

1. 主办方信息ER图如下图3.6所示：

![](/md/blog.008.png)

图3.6主办方信息ER图

1. 管理员信息ER图如下图3.7所示：

![](/md/blog.009.png)

图3.7管理员信息ER图
### 3.3.3 数据库表设计
本系统采用MySQL数据库进行数据库表的设计，数据库表中包括数据的格式、长度、主键等，是非常重要的一部分，本系统中主要的数据库表有管理员信息表，学生信息表，竞赛信息表，报名信息表，主办方信息表等，具体的表结构如下表3.1-3.14所示：

表3.1 baomingxinxi


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto|
|2|addtime|timestamp||||||否|CURRENT\_TIMESTAMP||
|3|jingsaibianhao|varchar|200|||||是|||
|4|jingsaibiaoti|varchar|200|||||否|||
|5|jingsaifenlei|varchar|200|||||否|||
|6|jiezhishijian|varchar|200|||||否|||
|7|jingsaididian|varchar|200|||||否|||
|8|jingsaifengmian|varchar|200|||||否|||
|9|mingcheng|varchar|200|||||是|||
|10|fuzeren|varchar|200|||||是|||
|11|yonghuzhanghao|varchar|200|||||是|||
|12|yonghuxingming|varchar|200|||||是|||
|13|baomingshijian|datetime||||||是|||
|14|crossuserid|bigint|20|||||是|||
|15|crossrefid|bigint|20|||||是|||
|16|sfsh|varchar|200|||||是|否||
|17|shhf|longtext||||||是|||
表3.2 config


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto\_increment|
|2|name|varchar|100|||||否|||
|3|value|varchar|100|||||是|||
表3.3 discussgonggaolan


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto\_increment|
|2|addtime|timestamp||||||否|CURRENT\_TIMESTAMP||
|3|refid|bigint|20|||||否|||
|4|userid|bigint|20|||||否|||
|5|nickname|varchar|200|||||是|||
|6|content|longtext||||||否|||
|7|reply|longtext||||||是|||
表3.4 discussjingsaichengji


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto\_increment|
|2|addtime|timestamp||||||否|CURRENT\_TIMESTAMP||
|3|refid|bigint|20|||||否|||
|4|userid|bigint|20|||||否|||
|5|nickname|varchar|200|||||是|||
|6|content|longtext||||||否|||
|7|reply|longtext||||||是|||
表3.5 discussjingsaixinxi


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto\_increment|
|2|addtime|timestamp||||||否|CURRENT\_TIMESTAMP||
|3|refid|bigint|20|||||否|||
|4|userid|bigint|20|||||否|||
|5|nickname|varchar|200|||||是|||
|6|content|longtext||||||否|||
|7|reply|longtext||||||是|||
表3.6 gonggaolan


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto\_increment|
|2|addtime|timestamp||||||否|CURRENT\_TIMESTAMP||
|3|biaoti|varchar|200|||||是|||
|4|fengmian|varchar|200|||||是|||
|5|riqi|date||||||是|||
|6|neirong|longtext||||||是|||
表3.7 jingsaichengji


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto|
|2|addtime|timestamp||||||否|CURRENT\_TIMESTAMP||
|3|jingsaibianhao|varchar|200|||||是|||
|4|jingsaibiaoti|varchar|200|||||否|||
|5|jingsaifenlei|varchar|200|||||否|||
|6|jingsaididian|varchar|200|||||否|||
|7|jingsaifengmian|varchar|200|||||否|||
|8|mingcheng|varchar|200|||||是|||
|9|fuzeren|varchar|200|||||是|||
|10|jingsaichengji|longtext||||||否|||
|11|fabushijian|datetime||||||是|||
|12|crossuserid|bigint|20|||||是|||
|13|crossrefid|bigint|20|||||是|||
|14|sfsh|varchar|200|||||是|否||
|15|shhf|longtext||||||是|||
表3.8 jingsaifenlei


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto\_increment|
|2|addtime|timestamp||||||否|CURRENT\_TIMESTAMP||
|3|jingsaifenlei|varchar|200|||||是|||
表3.9 jingsaixinxi


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto|
|2|addtime|timestamp||||||否|CURRENT\_TIMESTAMP||
|3|jingsaibianhao|varchar|200|||||是|||
|4|jingsaibiaoti|varchar|200|||||否|||
|5|jingsaifenlei|varchar|200|||||否|||
|6|jiezhishijian|date||||||否|||
|7|jingsaididian|varchar|200|||||否|||
|8|jingsaineirong|longtext||||||否|||
|9|jingsaifengmian|varchar|200|||||否|||
|10|mingcheng|varchar|200|||||是|||
|11|fuzeren|varchar|200|||||是|||
|12|sfsh|varchar|200|||||是|否||
|13|shhf|longtext||||||是|||
|14|clicktime|datetime||||||是|||
|15|clicknum|int|11|||||是|0||
表3.10 storeup


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto\_increment|
|2|addtime|timestamp||||||否|CURRENT\_TIMESTAMP||
|3|userid|bigint|20|||||否|||
|4|refid|bigint|20|||||是|||
|5|tablename|varchar|200|||||是|||
|6|name|varchar|200|||||否|||
|7|picture|varchar|200|||||否|||
|8|type|varchar|200|||||是|1||
|9|inteltype|varchar|200|||||是|||
表3.11 token


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto|
|2|userid|bigint|20|||||否|||
|3|username|varchar|100|||||否|||
|4|tablename|varchar|100|||||是|||
|5|role|varchar|100|||||是|||
|6|token|varchar|200|||||否|||
|7|addtime|timestamp||||||否|CURRENT\_TIMESTAMP||
|8|expiratedtime|timestamp||||||否|CURRENT\_TIMESTAMP||
表3.12 users


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto\_increment|
|2|username|varchar|100|||||否|||
|3|password|varchar|100|||||否|||
|4|role|varchar|100|||||是|管理员||
|5|addtime|timestamp||||||否|CURRENT\_TIMESTAMP||
表3.13 yonghu


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto\_increment|
|2|addtime|timestamp||||||否|CURRENT\_TIMESTAMP||
|3|yonghuzhanghao|varchar|200|||||否|||
|4|yonghuxingming|varchar|200|||||否|||
|5|mima|varchar|200|||||否|||
|6|yonghushouji|varchar|200|||||是|||
|7|youxiang|varchar|200|||||是|||
|8|xingbie|varchar|200|||||是|||
|9|touxiang|varchar|200|||||是|||
表3.14 zhubanfang


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto\_increment|
|2|addtime|timestamp||||||否|CURRENT\_TIMESTAMP||
|3|mingcheng|varchar|200|||||否|||
|4|fuzeren|varchar|200|||||否|||
|5|mima|varchar|200|||||否|||
|6|shoujihaoma|varchar|200|||||是|||
|7|xingbie|varchar|200|||||是|||
|8|youxiang|varchar|200|||||是|||
|9|sfsh|varchar|200|||||是|否||
|10|shhf|longtext||||||是|||



















# 第4章 系统的界面实现
## 4.1系统登录界面的实现
`    `在系统运行成功后，可以进入系统的登录界面，在本界面中包括系统的标题、图片、控件、按钮、下拉框几部分组成。本界面设计的目的是起到安全的作用，当用户想要使用本系统时必须有正确合法的账号和密码才可以。用户的登录的界面实现如下图4.1所示：

![](/md/blog.010.png)

图4.1用户登录界面的实现效果
## 4.2管理员主界面实现
管理员登录系统后，可以对用户进行添加管理，可以对个人密码修改，可以添加公告信息，而且还可以管理竞赛信息、成绩信息、报名信息等。
### 4.2.1个人中心管理界面实现
`     `本功能主要是管理员可以修改个人资料，还可以修改密码。实现界面如下图4.2所示：

![](/md/blog.011.png)

图4.2个人中心管理管理界面
### 4.2.2公告栏管理界面
管理员可以添加和管理公告信息，然后对信息进行管理，其实现界面如下图4.3所示：

![](/md/blog.012.png)

图4.3添加公告信息实现界面
### 4.2.3竞赛信息管理功能的界面的实现
管理员对竞赛信息查询和审核竞赛，实现界面如下图4.4所示：

![](/md/blog.013.png)

图4.4竞赛信息管理功能实现界面
### 4.2.4报名管理功能的实现
管理员也可以看到具体的报名情况、报名信息的实现界面如下图4.5所示：

![](/md/blog.014.png)

图4.5查询报名信息的实现界面
### 4.2.5竞赛成绩管理功能的实现
主办方可以发布成绩，管理员负责审核，竞赛成绩信息的实现界面如下图4.6所示：

![](/md/blog.015.png)

图4.6竞赛成绩查询界面
## 4.3学生角色功能实现
### 4.3.1竞赛信息查看界面的实现
学生可以选择浏览所有的竞赛信息，具体实现如下图4.7所示:

![](/md/blog.016.png)

图4.7竞赛信息界面
### 4.3.2在线报名界面的实现
`     `学生点击竞赛报名后，可以进行报名信息的填写，如下图4.8所示：

![](/md/blog.017.png)

图4.8在线报名实现界面
### 4.3.3我的功能的实现界面
在我的界面里可以查看报名信息和管理收藏信息，实现界面如下图4.9所示：

![](/md/blog.018.png)

图4.9我的实现界面
## 4.4主办方功能实现
主办方的主要功能是对发布竞赛和审核报名以及发布成绩。如下图4.10所示:

![](/md/blog.019.png)

图4.10主办方界面
### 4.5首页界面的实现
在首页中可以看到所有的公告信息，竞赛信息、竞赛成绩，如下图4.11所示：

![](/md/blog.020.png)

图4.11首页实现界面












# 系统测试
`    `系统实现完成后就进










