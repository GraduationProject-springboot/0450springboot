# [首页查询更多项目](https://github.com/GraduationProject-springboot) 包安装运行


# 0450springboot微乐校园pf

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1ULbQeREgz?p=50)


# 绪论
## 1.1 研究背景
当前社会各行业领域竞争压力非常大，随着当前时代的信息化，科学化发展，让社会各行业领域都争相使用新的信息技术，对行业内的各种相关数据进行科学化，规范化管理。这样的大环境让那些止步不前，不接受信息改革带来的信息技术的企业随时面临被淘汰，被取代的风险。所以当今，各个行业领域，不管是传统的教育行业，餐饮行业，还是旅游行业，医疗行业等领域都将使用新的信息技术进行信息革命，改变传统的纸质化，需要人手工处理工作事务的办公环境。软件信息技术能够覆盖社会各行业领域是时代的发展要求，各种数据以及文件真正实现电子化是信息社会发展的不可逆转的必然趋势。本微乐校园也是紧跟科学技术的发展，运用当今一流的软件技术实现软件系统的开发，让考试信息完全通过管理系统实现科学化，规范化，程序化管理。从而帮助信息管理者节省事务处理的时间，降低数据处理的错误率，对于基础数据的管理水平可以起到促进作用，也从一定程度上对随意的业务管理工作进行了避免，同时，微乐校园的数据库里面存储的各种动态信息，也为上层管理人员作出重大决策提供了大量的事实依据。总之，微乐校园是一款可以真正提升管理者的办公效率的软件系统。
## 1.2 目的和意义
信息数据的处理完全依赖人工进行操作，会耗费大量的人工成本，特别是面对大量的数据信息时，传统人工操作不仅不能对数据的出错率进行保证，还容易出现各种信息资源的低利用率与低安全性问题。更有甚者，耽误大量的宝贵时间，尤其是对信息的更新，归纳与统计更是耗财耗力的过程。所以电子化信息管理的出现就能缓解以及改变传统人工方式面临的处境，一方面可以确保信息数据在短时间被高效处理，还能节省人力成本，另一方面可以确保信息数据的安全性，可靠性，并可以实现信息数据的快速检索与修改操作，这些优点是之前的旧操作模式无法比拟的。因此微乐校园为数据信息的管理模式的升级与改革提供了重要的窗口。
## 1.3 论文结构安排
为了帮助用户更好的了解和理解程序的开发流程与相关内容，本文将通过六个章节进行内容阐述。

第一章：描述了程序的开发背景，程序运用于现实生活的目的与意义，以及程序文档的结构安排信息；

第二章：描述了程序的开发环境，包括程序开发涉及到的技术，程序开发使用的数据存储工具等信息；

第三章：描述了程序着手进行开发时，会面临的可行性问题，并对程序功能以及性能要求进行描述；

第四章：描述了程序大功能模块下的功能细分信息，以及存储程序数据的数据库表文件结构的设计信息等；

第五章：描述了程序的功能实现界面的内容，也对程序操作人员操作的部分功能进行了描述；

第六章：描述了程序功能的测试内容，并介绍了系统测试的概念与方法。
# 2 相关技术
## 2.1 SSM框架介绍
本课题程序开发使用到的框架技术，英文名称缩写是SSM，在JavaWeb开发中使用的流行框架有SSH、SSM、SpringMVC等，作为一个课题程序采用SSH框架也可以，SSM框架也可以，SpringMVC也可以。SSH框架是属于重量级别的框架，配置繁琐，不够灵活，修改程序需要修改好多个文件，并且运行起来也占用内存较高，CPU使用率相对也高，SpringMVC是Spring开发的一套MVC架构，更灵活更好用，SSM框架取中间值，既没有SSH臃肿，也没有SpringMVC简化，属于中间级别的，在配置过程和使用过程中更能编写和理解。MyBatis框架取代Hibernate框架是因为它更灵活，不需要完全在框架里操作，它在数据操作上可以写出更灵活的代码，它的性能也比Hibernate框架更稳定。总的来说，使用SSM框架是通过综合考虑而使用的，网上有很多的使用教程和心得体会，而且SSM又是这么的流行，用SSM框架开发是顺其自然的。
## 2.2 VUE介绍  
Vue (读音 /vjuː/，类似于 view) 是一套用于构建用户界面的渐进式框架。与其它大型框架不同的是，Vue 被设计为可以自底向上逐层应用。Vue 的核心库只关注视图层，不仅易于上手，还便于与第三方库或既有项目整合。另一方面，当与[现代化的工具链](https://v2.cn.vuejs.org/v2/guide/single-file-components.html)以及各种[支持类库](https://github.com/vuejs/awesome-vue#libraries--plugins)结合使用时，Vue 也完全能够为复杂的单页应用提供驱动。

## 2.3 Mysql数据库介绍
开发的程序面向用户的只是程序的功能界面，让用户操作程序界面的各个功能，那么很多人就会问，用户使用程序功能生成的数据信息放在哪里的？这个就需要涉及到数据库的知识了，一般来说，程序开发通常就会对常用数据存储工具的特点进行分析比对，比如Mysql数据库的特点与优势，Access数据库的特点与优势，Sqlserver数据库的特点与优势等，最终看哪个数据库与需要开发的程序比较匹配，也符合程序功能运行需要的数据存储要求，比如，需要开发商业级别的程序，存储的数据对数据库要求较高，可以选用Oracle，如果只是比较简单的程序，对数据存储没有过多要求，可以选用微软旗下的Access，当开发程序要求数据库占用空间小，并能满足程序数据存储要求时，就可以考虑Oracle公司从瑞典MySQL AB公司在很早之前就收购过一个关系型数据库，它是现在的Mysql数据库。在数据库工具里面它是最受认可的其中一个应用软件。需要说明的信息就是，本程序的开发就运用到了此数据库。它将程序数据通过使用不同的数据表格进行保存，在增加了程序数据的存储速度的时候，也提高了数据库的灵活性。 图2.3展示的就是MySQL的架构图。

![](/md/blog.001.png)

图2.3 MySQL数据库架构图



# 3 系统分析
当用户确定开发一款程序时，是需要遵循下面的顺序进行工作，概括为：系统分析-->系统设计-->系统开发-->系统测试，无论这个过程是否有变更或者迭代，都是按照这样的顺序开展工作的。系统分析就是分析系统需要做什么的问题，主要目的就是确定系统的功能，这也为接下来的工作做了一个好的开端。
## 3.1 系统可行性分析
开发一款程序软件不仅需要时间，也需要人力，物力资源。而进行可行性分析这个环节就是解决用户这方面的疑问，看看程序在当前的条件下是否可以进行开发。
### 3.1.1 技术可行性分析
此程序选用的开发语言是Java，这种编程语言有着丰富的数据类型，在指令控制语句上也比较完善，更重要的就是对类与对象的大力支持，这些优点为程序开发者提供了技术保障，尤其是现在代码都逐渐模块化，有关系统功能开发的源码在网络上都公开展示了，所以让具备一定计算机开发基础的开发人员独立开发系统在技术上也逐渐容易。
### 3.1.2 经济可行性分析
开发此程序最关键的设备就是一台电脑，无论是学校计算机室配备的电脑，还是自己入学以来购置的笔记本，都是可以符合开发要求的设备，另外在网络上，学校本已完全覆盖了校园网，所以在设备以及网络上无须考虑经济问题。
### 3.1.3 运行可行性分析
随着电脑软件以及配套硬件的完善升级，当下的计算机环境是一片大好，尤其是计算机已经广泛普及到家家户户，所以计算机设备现在是随处可见，由于本次开发的程序占有的资源耗费较小，在一般的电脑或笔记本上都能轻松运转起来。

通过上面的可行性描述，可以从经济，技术，运行方面解决程序开发是否可行的问题。因此可以认为该程序软件是可以进行开发的。
## 3.2 系统性能分析
系统性能分析也是比较重要的内容，进行系统性能分析就是为了确保系统的功能要能够在生活中运行使用时，达到规定的指标，因此一个完整的系统软件，是需要进行系统的性能分析这个步骤的。本次进行性能分析主要从易用性指标，可扩展性指标，系统健壮性指标，系统安全性指标这几个方面进行分析。
### 3.2.1 易用性指标
本次程序软件的开发的目的就是让使用者可以通过使用该软件提高信息数据的管理效率，同时该程序软件也需要针对不同的操作用户设置对应的功能，因此，此程序的操作流程应该尽量与用户日常操作软件的行为习惯相贴合，另外，程序软件的设计与开发也应考虑非计算机专业用户的计算机操作水平，要让大部分使用者都可以轻松操作程序提供的各个功能。
### 3.2.2 可扩展性指标
当前需要开发的程序软件是根据当下的用户需求进行设计开发的，但是随着时间的推移，社会大环境的改变，开发出的程序也是需要与时俱进的，需要根据用户不断变换的需求进行相应的功能内容的扩展，需要注意的就是，当对成型的程序进行功能模块新增时，仍然需要保证程序原有架构以及功能不能受到影响，新增的功能模块在系统中也能够运行正常，该指标达标也就可以保证此程序是可以在满足信息管理要求下，从容应对市场环境的变化。
### 3.2.3 健壮性指标
程序软件的开发就是为了投入使用时，可以一直稳定的处理各种数据信息，程序软件一旦不稳定，也会给使用者带来干扰。因此从性能分析的角度，就要要求程序软件在应对使用者的误操作，或者是使用者因为各种原因，填写有误的数据等情况时，程序要一直保持稳定，并能够正常让使用者进行使用。当程序的某个功能模块出现异常时，程序的其它功能模块也要能够确保正常使用。程序的健壮性指标达标可以让使用者产生良好的用户体验。
### 3.2.4 安全性指标
程序软件的安全问题是首要问题，毕竟程序对应数据库里面存放的数据信息是庞大的，里面也包括了许多重要的个人信息，这就对程序要具备一个完善的安全机制提出了要求。因此程序必须要设置登录功能用以进行用户身份的检查，以及身份和权限的匹配，通过对不同用户身份进行功能约束，绝不容忍用户越权操作程序。另外，也需要时刻防范计算机病毒，还有黑客，通过采取针对性的办法进行安全应对，确保程序时刻处于安全的环境，让使用者放心使用。
## 3.3 系统流程分析
### 3.3.1 操作流程分析
程序上交给用户进行使用时，需要提供程序的操作流程图（如图3.1所示），这样便于用户容易理解程序的具体工作步骤，现如今程序的操作流程都有一个大致的标准，即先通过登录页面提交登录数据，通过程序验证正确之后，用户才能在程序功能操作区页面操作对应的功能。

![](/md/blog.002.png)

图3.1 程序操作流程图
### 3.3.2 登录流程分析
在这个部分，需要对程序的登录功能模块的运行流程（如图3.2所示），进行单独说明。程序设置登录模块也是为了安全起见，让用户使用放心，登录模块主要就是让用户提交登录信息，程序进行数据验证，验证通过的用户才能够成功登录程序。

![](/md/blog.003.png)

图3.2 程序登录流程图
### 3.3.3 信息添加流程分析
程序的添加功能就是提供给操作者录入信息的功能，不管是涉及到用户信息添加，还是其它功能模块涉及到的信息添加，程序的信息添加流程（如图3.3所示）都是一致的。程序都是先对操作者录入的数据进行判定，这个判定规则是一段提前编写完成的程序代码，当程序判定数据符合要求时，才会把操作者录入的数据登记在数据表里面，比如添加的用户信息，就会把新添加的用户信息写入用户信息的数据表文件里面。

![](/md/blog.004.png)

图3.3 信息添加流程图
### 3.3.4 信息删除流程分析
当从程序里面删除某种无效数据时，遵循程序的信息删除流程（如图3.4所示），先要选中操作者需要删除的数据，程序为了预防操作者误删信息，也会进行提示，当操作者真正确定要删选中的信息时，该信息就会从数据库中被永久删除。

![](/md/blog.005.png)

图3.4 信息删除流程图
## 3.4 系统功能分析
程序功能需要花费一定时间进行分析与设计，需要从大量的参考资料或者是社会上同种类型的程序中吸收对此程序开发有用的知识，可以将其它同类型程序中的合理功能部分规划到此程序里面，另外程序功能也需要针对用户的需求进行分析与设计。
# 4 系统设计
## 4.1 总体功能
微乐校园是根据需求定制开发，开发软件选用idea平台配合MySQL数据库进行开发环境的搭建操作，网站采用为微信小程序结构进行开发，用户通过小程序访问项目,管理人员通过访问系统数据仅仅需要在客户端安装谷歌浏览器或者是当下常用浏览器就可以访问网站后台管理内容。
## 4.2 系统概要设计
本次拟开发的系统为了节约开发成本，也为了后期在维护和升级上的便利性，打算通过浏览器来实现系统功能界面的展示，让程序软件的主要事务集中在后台的服务器端处理，前端部分只用处理少量的事务逻辑。下面使用一张图（如图4.2所示）来说明程序的工作原理。

![](/md/blog.006.png)

图4.2 程序工作的原理图
## 4.3 系统功能结构设计
在分析并得出使用者对程序的功能要求时，就可以进行程序设计了。如图4.3展示的就是管理员功能结构图，管理员在后台主要管理代跑管理、代跑收藏管理、代跑留言管理、代跑订单管理、字典管理、叫车管理、用户咨询管理、二手商品管理、二手商品评价管理、二手商品订单管理、失物招领管理、司机管理、用户管理、约战校园管理、约战校园留言管理、管理员管理等。

![结构设计图](/md/blog.007.jpeg "结构设计图")


图4.3 管理员功能结构图
## 4.4 数据库设计
程序功能操作不管是添加，修改，还是删除等功能产生的数据都是经由数据库进行数据保存和更新的，所以一个数据库设计的好坏也是程序是否好坏的判定标准，因为程序的成功，有一半的功劳都是靠数据库的优秀设计。数据库一旦设计得良好是可以减轻开发人员的开发负担的。
### 4.4.1 数据库E-R图设计
这个部分的设计需要使用到E-R图绘制工具，常用的工具就是Visio工具来绘制E-R模型图，这款工具不仅可以快速创建需要的E-R模型图，而且该工具提供的操作界面很简单，可以短时间内修改绘图界面的图形或者是文字的属性。在绘制E-R模型图时，要分清楚各个图形代表的含义，以免绘制出错，E-R模型图由长方形（实体），椭圆形（属性），菱形（关系）这三部分图形符号组成，绘制期间要区分开来，用准确的图形符号代表相应的数据元素。

（1）下图是代跑订单实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\7.2\img\代跑订单.jpg](/md/blog.008.jpeg "C:/Users/Administrator/Desktop/temp111\7.2\img\代跑订单.jpg")

代跑订单实体属性图

（2）下图是用户实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\7.2\img\用户.jpg](/md/blog.009.jpeg "C:/Users/Administrator/Desktop/temp111\7.2\img\用户.jpg")

用户实体属性图

（3）下图是代跑实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\7.2\img\代跑.jpg](/md/blog.010.jpeg "C:/Users/Administrator/Desktop/temp111\7.2\img\代跑.jpg")

代跑实体属性图

（4）下图是失物招领实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\7.2\img\失物招领.jpg](/md/blog.011.jpeg "C:/Users/Administrator/Desktop/temp111\7.2\img\失物招领.jpg")

失物招领实体属性图

（5）下图是司机实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\7.2\img\司机.jpg](/md/blog.012.jpeg "C:/Users/Administrator/Desktop/temp111\7.2\img\司机.jpg")

司机实体属性图

（6）下图是代跑留言实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\7.2\img\代跑留言.jpg](/md/blog.013.jpeg "C:/Users/Administrator/Desktop/temp111\7.2\img\代跑留言.jpg")

代跑留言实体属性图

（7）下图是二手商品实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\7.2\img\二手商品.jpg](/md/blog.014.jpeg "C:/Users/Administrator/Desktop/temp111\7.2\img\二手商品.jpg")

二手商品实体属性图

（8）下图是叫车实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\7.2\img\叫车.jpg](/md/blog.015.jpeg "C:/Users/Administrator/Desktop/temp111\7.2\img\叫车.jpg")

叫车实体属性图

（9）下图是约战校园实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\7.2\img\约战校园.jpg](/md/blog.016.jpeg "C:/Users/Administrator/Desktop/temp111\7.2\img\约战校园.jpg")

约战校园实体属性图

（10）下图是用户咨询实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\7.2\img\用户咨询.jpg](/md/blog.017.jpeg "C:/Users/Administrator/Desktop/temp111\7.2\img\用户咨询.jpg")

用户咨询实体属性图

（11）下图是二手商品评价实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\7.2\img\二手商品评价.jpg](/md/blog.018.jpeg "C:/Users/Administrator/Desktop/temp111\7.2\img\二手商品评价.jpg")

二手商品评价实体属性图

（12）下图是二手商品订单实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\7.2\img\二手商品订单.jpg](/md/blog.019.jpeg "C:/Users/Administrator/Desktop/temp111\7.2\img\二手商品订单.jpg")

二手商品订单实体属性图

（13）下图是代跑收藏实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\7.2\img\代跑收藏.jpg](/md/blog.020.jpeg "C:/Users/Administrator/Desktop/temp111\7.2\img\代跑收藏.jpg")

代跑收藏实体属性图

（14）下图是约战校园留言实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\7.2\img\约战校园留言.jpg](/md/blog.021.jpeg "C:/Users/Administrator/Desktop/temp111\7.2\img\约战校园留言.jpg")

约战校园留言实体属性图


### 4.4.2 数据库表结构设计
数据库系统一旦选定之后，需要根据程序要求在数据库中建立数据库文件，并在已经完成创建的数据库文件里面，为程序运行中产生的数据建立对应的数据表格，数据表结构设计就是对创建的数据表格进行字段设计，字段长度设计，字段类型设计等，当数据表格合理设计完成之后，才能正常存储相关程序运行产生的数据信息。 

表4.1代跑表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_id|Integer|用户|是|
|3|daipiao\_name|String|代跑标题|是|
|4|daipiao\_photo|String|代跑照片|是|
|5|daipiao\_address|String|代跑地点|是|
|6|daipiao\_lianxiren|String|联系人|是|
|7|daipiao\_lianxifangshi|String|联系方式|是|
|8|daipiao\_types|Integer|代跑类型|是|
|9|daipiao\_new\_money|BigDecimal|代跑金额|是|
|10|daipiao\_time|Date|代跑时间|是|
|11|daipiao\_content|String|代跑内容|是|
|12|daipiao\_zhuangtai\_types|Integer|代跑状态|是|
|13|insert\_time|Date|录入时间|是|
|14|create\_time|Date|创建时间|是|
表4.2代跑收藏表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|daipiao\_id|Integer|代跑|是|
|3|yonghu\_id|Integer|用户|是|
|4|daipiao\_collection\_types|Integer|类型|是|
|5|insert\_time|Date|收藏时间|是|
|6|create\_time|Date|创建时间|是|
表4.3代跑留言表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|daipiao\_id|Integer|代跑|是|
|3|yonghu\_id|Integer|用户|是|
|4|daipiao\_liuyan\_text|String|留言内容|是|
|5|insert\_time|Date|留言时间|是|
|6|reply\_text|String|回复内容|是|
|7|update\_time|Date|回复时间|是|
|8|create\_time|Date|创建时间|是|
表4.4代跑订单表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|daipiao\_order\_uuid\_number|String|订单号|是|
|3|daipiao\_id|Integer|代跑|是|
|4|yonghu\_id|Integer|用户|是|
|5|daipiao\_order\_true\_price|BigDecimal|实付价格|是|
|6|daipiao\_order\_types|Integer|订单类型|是|
|7|daipiao\_order\_payment\_types|Integer|支付类型|是|
|8|insert\_time|Date|订单创建时间|是|
|9|create\_time|Date|创建时间|是|
表4.5字典表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|dic\_code|String|字段|是|
|3|dic\_name|String|字段名|是|
|4|code\_index|Integer|编码|是|
|5|index\_name|String|编码名字|是|
|6|super\_id|Integer|父字段id|是|
|7|beizhu|String|备注|是|
|8|create\_time|Date|创建时间|是|
表4.6叫车表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_id|Integer|用户|是|
|3|siji\_id|Integer|司机|是|
|4|jiaoche\_uuid\_number|String|叫车编号|是|
|5|jiaoche\_name|String|叫车标题|是|
|6|jiaoche\_photo|String|叫车照片|是|
|7|shangche\_time|Date|上车时间|是|
|8|jiaoche\_address|String|上车地点|是|
|9|jiaoche\_quwang\_address|String|去往地点|是|
|10|jiaoche\_types|Integer|叫车类型|是|
|11|jiaoche\_new\_money|BigDecimal|出价|是|
|12|jiaoche\_content|String|叫车详情|是|
|13|insert\_time|Date|叫车时间|是|
|14|jiaoche\_zhuangtai\_types|Integer|叫车状态|是|
|15|create\_time|Date|创建时间|是|
表4.7用户咨询表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_id|Integer|提问人|是|
|3|siji\_id|Integer|回答人|是|
|4|jiaoche\_chat\_issue\_text|String|问题|是|
|5|issue\_time|Date|问题时间|是|
|6|jiaoche\_chat\_reply\_text|String|回复|是|
|7|reply\_time|Date|回复时间|是|
|8|zhuangtai\_types|Integer|状态|是|
|9|jiaoche\_chat\_types|Integer|数据类型|是|
|10|insert\_time|Date|提问时间|是|
|11|create\_time|Date|创建时间|是|
表4.8二手商品表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_id|Integer|用户|是|
|3|shangpin\_name|String|二手商品名称|是|
|4|shangpin\_uuid\_number|String|二手商品编号|是|
|5|shangpin\_photo|String|二手商品照片|是|
|6|shangpin\_types|Integer|商品类型|是|
|7|shangpin\_kucun\_number|Integer|二手数量|是|
|8|shangpin\_old\_money|BigDecimal|二手商品原价|是|
|9|shangpin\_new\_money|BigDecimal|现价/个|是|
|10|shangpin\_clicknum|Integer|二手商品热度|是|
|11|shangpin\_content|String|二手商品介绍|是|
|12|shangpin\_delete|Integer|逻辑删除|是|
|13|insert\_time|Date|录入时间|是|
|14|create\_time|Date|创建时间|是|
表4.9二手商品评价表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|shangpin\_id|Integer|二手商品|是|
|3|yonghu\_id|Integer|用户|是|
|4|shangpin\_commentback\_text|String|评价内容|是|
|5|insert\_time|Date|评价时间|是|
|6|reply\_text|String|回复内容|是|
|7|update\_time|Date|回复时间|是|
|8|create\_time|Date|创建时间|是|
表4.10二手商品订单表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|shangpin\_order\_uuid\_number|String|订单号|是|
|3|shangpin\_id|Integer|二手商品|是|
|4|yonghu\_id|Integer|用户|是|
|5|buy\_number|Integer|购买数量|是|
|6|shangpin\_order\_true\_price|BigDecimal|实付价格|是|
|7|shangpin\_order\_courier\_name|String|联系人|是|
|8|shangpin\_order\_courier\_number|String|联系方式|是|
|9|shangpin\_order\_types|Integer|订单类型|是|
|10|shangpin\_order\_payment\_types|Integer|支付类型|是|
|11|insert\_time|Date|订单创建时间|是|
|12|create\_time|Date|创建时间|是|
表4.11失物招领表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_id|Integer|用户|是|
|3|shiwuzhaoling\_name|String|物品名称|是|
|4|shiwuzhaoling\_uuid\_number|String|物品编号|是|
|5|shiwuzhaoling\_photo|String|物品照片|是|
|6|shiwuzhaoling\_address|String|丢失地点/找到地点|是|
|7|shiwuzhaoling\_types|Integer|物品类型|是|
|8|jutishijian\_time|Date|具体时间|是|
|9|shiwuzhaoling\_clicknum|Integer|热度|是|
|10|shiwuzhaoling\_content|String|详细描述|是|
|11|shiwuzhaoling\_zhuangtai\_types|Integer|状态|是|
|12|insert\_time|Date|录入时间|是|
|13|create\_time|Date|创建时间|是|
表4.12司机表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|siji\_name|String|司机姓名|是|
|3|siji\_phone|String|司机手机号|是|
|4|siji\_id\_number|String|司机身份证号|是|
|5|siji\_photo|String|司机头像|是|
|6|new\_money|BigDecimal|余额|是|
|7|siji\_email|String|电子邮箱|是|
|8|create\_time|Date|创建时间|是|
表4.13用户表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_name|String|用户姓名|是|
|3|yonghu\_phone|String|用户手机号|是|
|4|yonghu\_id\_number|String|用户身份证号|是|
|5|yonghu\_photo|String|用户头像|是|
|6|yonghu\_email|String|电子邮箱|是|
|7|new\_money|BigDecimal|余额|是|
|8|create\_time|Date|创建时间|是|
表4.14约战校园表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_id|Integer|用户|是|
|3|yuezhanxiaoyuan\_name|String|约战校园名称|是|
|4|yuezhanxiaoyuan\_photo|String|约战校园照片|是|
|5|yuezhan\_time|Date|约战时间|是|
|6|yuezhanxiaoyuan\_address|String|约战地点|是|
|7|yuezhanxiaoyuan\_types|Integer|约战校园类型|是|
|8|yuezhanxiaoyuan\_clicknum|Integer|约战校园热度|是|
|9|yuezhanxiaoyuan\_content|String|约战内容|是|
|10|yuezhanxiaoyuan\_delete|Integer|逻辑删除|是|
|11|insert\_time|Date|录入时间|是|
|12|create\_time|Date|创建时间|是|
表4.15约战校园留言表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yuezhanxiaoyuan\_id|Integer|约战校园|是|
|3|yonghu\_id|Integer|用户|是|
|4|yuezhanxiaoyuan\_liuyan\_text|String|留言内容|是|
|5|insert\_time|Date|留言时间|是|
|6|reply\_text|String|回复内容|是|
|7|update\_time|Date|回复时间|是|
|8|create\_time|Date|创建时间|是|
表4.16管理员表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|username|String|学生名|是|
|3|password|String|密码|是|
|4|role|String|角色|是|
|5|addtime|Date|新增时间|是|

# 5 系统实现
系统实现部分就是将系统分析，系统设计部分的内容通过编码进行功能实现，以一个实际应用系统的形式展示系统分析与系统设计的结果。前面提到的系统分析，系统设计最主要还是进行功能，系统操作逻辑的设计，也包括了存储数据的数据库方面的设计等内容，系统实现就是一个最终的实施阶段，将前面的设计成果进行物理转化，最终出具可以运用于实际的软件系统。
## 5.1 管理员功能介绍
### 5.1.1 约战校园列表
如图5.1显示的就是约战校园列表页面，此页面提供给管理员的功能有：查看约战校园、新增约战校园、修改约战校园、删除约战校园等。

![](/md/blog.022.png)

图5.1 约战校园列表页面
### 5.1.2 代跑信息管理
代跑信息管理页面提供的功能操作有：新增代跑，修改代跑，删除代跑操作。下图就是代跑信息管理页面。

![](/md/blog.023.png)

图5.3 代跑信息管理页面
### 5.1.3代跑类型管理
代跑类型管理页面显示所有代跑类型，在此页面既可以让管理员添加新的代跑信息类型，也能对已有的代跑类型信息执行编辑更新，失效的代跑类型信息也能让管理员快速删除。下图就是代跑类型管理页面。

![](/md/blog.024.png)

图5.4 代跑类型列表页面
# 系统









