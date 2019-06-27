# 鲜花搭配APP设计
鲜花搭配可能在大多数人的日常生活中并不常遇到，但每逢婚庆、演出、生日、祭奠等重要场合，鲜花却又是不可或缺的。搭配合适的鲜花能使我们在重要场合中表现出礼貌和得体，在社交上扮演着重要的角色。然而，鲜花的搭配有着多种多样的规则和惯例，平常人一般没有深入的了解，从而难以选择合适的鲜花搭配。为了解决这个矛盾，我们计划开发一个以自动化地为用户量身定制合适的鲜花搭配为核心、并配套以相应的资源生态的手机APP。

客户端代码：https://github.com/laf070810/flower_app

服务器代码：https://github.com/guhaiqiao/Flower_app

## APP名称
我们的APP名称初定为“桃之夭夭”。一方面，桃之夭夭本意为“桃花怒放”，“花”与APP的主要功能相符合，并且符合大众认知，能够让大众对APP的功能有直观感受。另一方面，桃之夭夭比喻事物繁荣兴盛，既表明APP上的产品质量优良，又暗示了APP有着十分光明的发展前景，具有良好的寓意。

## APP市场定位
我们的APP主要属于生活类APP中的外卖类（鲜花配送类）APP，但也辅以其他功能。目前的应用市场上相似的鲜花配送类APP比较多，但这些APP提供的大多数都是简单的鲜花预定配送服务，鲜花搭配种类比较有限固定，没有提供用户个性化搭配的功能。因此，我们的APP将以为用户生成个性化的鲜花搭配为切入点，并配套以完善的生态环境，打造一个拥有个性化搭配功能和社区功能的综合性鲜花配送服务平台，这将使得我们的APP具有很强的竞争能力。


我们APP的目标用户主要有：
1. 有购买鲜花需求的普罗大众
2. 对鲜花和配花有着独特兴趣的人群
3. 有定期用花需求的组织（如公司、学校等）

## APP功能描述

### 根据用户需求自动生成鲜花搭配
用户可设置限定条件如：
1.	形状（花篮、花束、花车等）
2.	用途（婚庆、生日、贺礼、祭奠等）
3.	对象（父母、同学、朋友、老师、领导等）
4.	喜好（喜欢玫瑰花、不喜欢康乃馨等）
5.	价格（100\~150、180\~200等，价格的区间由用户自己设定）
6.	支数（6\~8支主花、4\~6支配花等）
7.	图案（心形图案、520图案、I❤YOU图案等）
8.	文字（生日快乐、LOVE等）
9.	饰品（小熊、贺卡、丝带、蝴蝶结等）

各商家会提前设定每种花的价格、搭配费用等，该APP会根据鲜花搭配的相关理论生成符合用户设定条件的花束搭配和效果图并呈现出来。若用户并未给出所有的限定条件或根据用户给出的限定条件，算法生成的搭配不止一种，则该APP会将这几种搭配都呈现给用户，用户可根据自己的喜好选择这几种鲜花搭配方案，然后由商家进行快速配送。

### 自主插花功能
APP内含有插花模块，当用户达到一定等级后即可解锁。在插花模块中，用户可自主选择鲜花的种类，支数，大小，通过拖拽方式将各种鲜花移至屏幕中央的插花区域。在这个区域，用户可以三维旋转单支鲜花的摆放方向，或是改变鲜花的位置，搭配出属于自己的鲜花花束。在搭配过程中，用户可以随时旋转花束整体，在插花的过程中实时观察花束的整体效果，从而找到最好的插花位置，达到更好的插花效果。插花结束后，用户还可以选择包装的颜色，材质，额外的装饰等等。最后，用户可以选择保存方案并输入方案名称，从而将刚刚搭配完成的鲜花花束保存至我的作品中，留待欣赏或是继续完善。

### 社区功能
在社区模块中，用户可以发表帖子，交流关于鲜花搭配的经验或是讨论鲜花方面的相关话题。用户可以通过图片分享自己最近看到的喜欢的鲜花搭配，或是交流关于鲜花的小知识，探讨哪几种鲜花搭配更加美观等等。此外，用户还可以点赞评论其他用户的帖子，与该帖的作者进一步交流，从而找到志同道合的花友，一起探讨鲜花搭配的话题。在这个模块中，还有一个专属插花功能的话题，用户可以将自己在插花模块完成的作品发布至该话题中，其他用户可以进行点赞评论，点赞达到一定数量的搭配方案将会推荐至相关商家，若商家采纳了该方案，方案的作者将会获得一定的受益。

### 人工配花功能
用户达到一定等级后即可解锁人工配花功能。在人工配花模块中，用户可在各商家的众多插花师中选择一位，说明自己的喜好，用途，价格等，插花师会根据个人的经验给出几种相应的鲜花搭配方案。用户可随时提出需求，插花师会根据用户的需求随时进行方案的更改，并给出自己的建议等等，从而最大化满足用户的需求，并给出最好的搭配方案。若用户同意该方案，可直接提交订单至相关商家，完成鲜花配送。

### 小课堂功能
在小课堂模块中，用户可以通过观看视频学习插花技巧，了解鲜花的保存方法。APP还会推出专属精品课程，用户可以选择付费学习或是成为VIP免费观看。此外用户也可以查询某种鲜花的相关内容，如中英文名称，图片，花语，相似鲜花，最佳搭配，有关故事等等，在丰富知识的同时享受其中的乐趣。

### 用户相关功能
#### 等级制度
所有用户初始等级为Lv.1，用户可通过购买产品、发表帖子、邀请新用户等方式获得经验值，达到一定数值即可升级。在用户达到一定等级后即可解锁插花功能，人工配花功能。

#### VIP会员
用户可通过充值成为VIP会员，从而直接享受插花功能，人工配花功能及免费观看学习各种视频等，此外，用户还可以充值成为SVIP，在享受VIP的各种功能的基础之上可以优先配送或优先选择在线插花师等等。

### 其他设计亮点
除以上各方面的设计亮点以外，我们还有以下的设计亮点：
1. 每日推送介绍一种花的小知识，包括习性、养殖方法、花语等，还会在当天对这种花进行一定价格的优惠。
2. 在特殊的节日，推出相应的优惠。

## 主要界面原型设计
我们的APP是一个提供多方面服务的综合性平台，因此具有较为复杂的交互界面设计，简要阐述如下：


主界面主要分“首页”、“社区”、“课程”、“我的”四大界面。

首页提供根据用户喜好自动推荐的鲜花搭配，采用下滑刷新的推送流模式。点击首页右下角的浮动按钮可进入筛选条件界面，用户在此界面选择一定的筛选条件后可搜索现成的搭配方案或自动生成新的搭配方案并同时生成搭配效果图。同时首页也提供人工配花的入口，点击入口可以进入人工配花服务界面。

社区界面提供类似微信朋友圈一样的推送信息流，显示不同用户发的想法、分享或设计方案。

课程界面提供花卉及鲜花搭配相关的文章讲解与视频课程，既包含免费课程也包含VIP课程。

“我的”界面提供个人主页、个人信息、我的订单、我的设计、我的收藏、系统设置等用户相关的服务。

## 技术实现的初步架构
APP采用C/S架构，客户端向服务器发送请求，服务器给予相应的响应。服务器端提供数据管理，数据共享以及相应算法的实现，并通过http传输数据至客户端。客户端则加载服务器返回的数据并与用户交互。服务端现采用python的flask与客户端通信，使用sqlite存储数据。

## 项目进度
本项目目前尚处于初步阶段，仅进行了基本的UI设计并实现了简单的用户管理和社区分享功能。

