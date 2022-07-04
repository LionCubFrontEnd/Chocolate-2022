## 2022 年目标


博主 21 届本科毕业，可以称呼我 Chocolate，在此仓库记录自己 2022 年学习与成长，初心也是为了驱动自己，也让 2022 年的总结增添数据。


希望能在 22 年在哔哩哔哩达成 10w 粉丝:100:成就，<a href="https://space.bilibili.com/351534170">B 站：一百个Chocolate</a><br/>座右铭：学如逆水行舟，不进则退。 QQ交流群：666151691

<a href="https://space.bilibili.com/351534170"><img src="https://img.shields.io/badge/dynamic/json?labelColor=FE7398&logo=bilibili&logoColor=white&label=bilibili%20fans&color=00aeec&query=%24.data.totalSubs&url=https%3A%2F%2Fapi.spencerwoo.com%2Fsubstats%2F%3Fsource%3Dbilibili%26queryKey%3D351534170" /></a>



> 打工的节奏渐渐让我们心态变的浮躁，往往会急于求成，但结果往往达不到期待，「饭要一口一口吃，学习得循序渐进」，在这里沉下心来好好享受学习带来的充实感吧，坚持的习惯会增加更多的幸运值。

## 2022 B 站更新视频列表

> todo...



## 2022 产出文章


- :pencil2: [GitHub 到底怎么找优秀的开源项目？有些资源自己找就可以了 | 非常实用技巧 | 效率起飞](https://github.com/LionCubFrontEnd/Chocolate-2022/issues/1)（:trophy: 创作时间：1 月 10 日）
- :pencil2: [前端移动端适配 - 媒体查询适配方案（个人笔记）](https://github.com/LionCubFrontEnd/Chocolate-2022/issues/2)(:trophy: 创作时间：2 月 10 日)
- :pencil2: [关于 antd@4 之后 tree 树形控件不能横向排列这件事](https://github.com/LionCubFrontEnd/Chocolate-2022/issues/3)(:trophy: 创作时间：2 月 25 日)


## 2022 阅读的一些优秀文章

> 部分文章会写一些读完心得，仅个人一些想法，仅做参考，也许会有表述不足之处，可以指正交流。


### React

- :white_check_mark: [从零搭建 React 全家桶框架教程](https://github.com/brickspert/blog/issues/1)「非常有用的文章，博主是 ahooks 作者，很优秀，这个是 17 年写的文章，足以看出个人沉淀。如标题所示“零基础”，目前是第一次读完，打算还要跟着再手写一遍，感谢博主的分享，真是学到了！关于 webpack 那块讲解的很详细到位，对于一些潜在的问题也会拓展，而技术发展也比较快，一些版本可能已经更新了，在这里标记一下我会写一份 22 年的搭建教程，向优秀的博主学习」
- :white_check_mark: [助你完全理解 React 高阶组件（Higher-Order Components）](https://github.com/brickspert/blog/issues/2)「这篇文章内容不是很多，但是非常经典，开头用函数来模拟高阶组件，这一块基本上就可以理解高阶组件了，之后有一个很关键点，就是引入了 redux，这个是真的有用，之前学习的时候都没有弄明白 redux 为什么要这么做，现在醍醐灌顶，点赞，不过由于是 17 年的，所以写法上以 class 语法，之后在新版 react 官网文档看看 hooks 版本的高阶组件介绍吧」
- :white_check_mark: [从零实现一个 tiny hooks，知其然知其所以然](https://github.com/brickspert/blog/issues/26)「这里我改了博主的原标题【React Hooks 原理】，为啥呢，博主这篇文章也写得不错，从零实现了一个 tiny hooks，不过对于开篇提的几个问题，在后续解释的时候略微简单，第一遍读的时候还是觉得有点懵，就那些问题如果没有看其它一些介绍的话还不太清楚，所以这篇读的话后续有点吃力，但这个实现的 tiny hooks 还是比较出神入化的，讲的比较清楚，至于后面 React 官方用链表实现那里就结束了，开始还是蛮期待有后续的，提了一下就就结束了，之后再找找好文继续了解一下，所以这篇文章我更想叫做从零实现一个 tiny hooks」
- :white_check_mark: [React 项目性能分析及优化](https://github.com/brickspert/blog/issues/36)「这篇文章由浅入深的讲解了常用的一些性能优化的方式，从 Chrome 自带的性能查看到使用 React 相关工具，再到最后引入一些平常写代码的时候需要注意的点，为什么会有这个坑，以及遇到一些坑的解决方式。纵观可以看出作者优秀的思维，借用评论区的一些术语来说，就是在编码之前就要思考怎么规划，编码之中还要对代码进行思考，最后在页面的时候可以查看性能分析，根据结果以及结合工具再反复思考。」


### React Hooks

- :white_check_mark: [React Hooks 使用误区，驳官方文档](https://github.com/brickspert/blog/issues/45)「在我工作之初那会，也遇到过和作者相同的问题，一些关于 hooks 的写法也相同，问过同届的同事也大概就说了一下 useCallback 和 useMemo 用法以及区别，然而看完这篇博客之后又是醍醐灌顶，感觉看完之后对于 React 源码这块想要了解的心思更多了，等看一些文章之后，我会开始学习一下 React 源码。而就在最近，我其实在工作中使用 useCallback 不算很多的，有朋友说他们要求就是只要函数就会包一层 useCallback，当时我也很纳闷，如果都必须包一层，那用这个有啥意义，干脆直接集成进去就好了。看完文章之后我立即转发了过去，受益啦。而后续文章提及的 ahooks 工作中也有使用，确实挺香的，在这里也说下就是之后也会来学习一下，我觉得还是很重要的」


### React Router

- :white_check_mark: [react-router v4 使用 history 控制路由跳转](https://github.com/brickspert/blog/issues/3)「关于 react-router 的一些思考，主要是关于这个 history 跳转的问题，其中例举了三种方法，不过现在看组内写的代码，是在使用 react-router-dom 中的 useHistory，这个用起来比较方便，直接在组件中 `const history = useHistory();` 使用即可」

### React-use

- :white_check_mark: [useRequest-蚂蚁中台标准请求 Hooks](https://github.com/brickspert/blog/issues/35)「一篇关于 ahooks 的介绍，这种自定义 hook 其实工作阶段使用了 antd pro 之后了解到的，就是从官方文档底部的推荐看到的，当时打开后就发现了新世界一样，有了这些优秀的 Hooks 之后，许多一些逻辑都可以复用了，而且解决方式更简单方便了，效率拉满」


### React 状态管理库

- :white_check_mark: [完全理解 redux（从零实现一个 redux）](https://github.com/brickspert/blog/issues/22)「这篇文章真的是高赞👍🏻，过去那会关于 redux 理解还不够清晰，看完了之后醍醐灌顶，我是看了两遍才理解清楚，第一遍的时候有些地方感觉看的不是很明白，第二遍看的时候就彻底懂了，发现发布-订阅这种设计模式到处都有用到，以及那个 compose 源码的写法，难怪以前看面试题的时候经典遇到要用 reduce 写法，好神奇的感觉，不知不觉就被带入这块知识当中。但我觉得最精华的部分应该就是中间件那块了，过去学习 Koa 的时候就有遇到中间件的概念，但是一直没理解明白，这次看到 redux 文章之后一下就明白了，博主真是十分用心，膜拜，我觉得对于 redux 不太理解或者仅仅使用的同学都可以看一看，最棒的教程」
- :white_check_mark:[Recoil - Facebook 官方 React 状态管理器](https://github.com/brickspert/blog/issues/38)「这篇讲了 React 状态管理器，先 mark 一下」

### React 源码

- :ballot_box_with_check: [React技术揭秘](https://react.iamkasong.com/)「最近一直在看的文档，先努力看完，后续再回顾一遍。」


### TypeScript

- :ballot_box_with_check: [2021 typescript史上最强学习入门文章(2w字)](https://juejin.cn/post/7018805943710253086)「在读」

### 微前端
- :white_check_mark: [基于微前端的大型中台项目融合方案](https://github.com/brickspert/blog/issues/41)


### 技术人生

- :white_check_mark: [2022 年如何成为一名优秀的大前端 Leader？](https://juejin.cn/post/7034419410706104356)「优秀的前端Leader要学会适当的拒绝，学会说No。并不是做的越多越好，而是让团队做的少价值高才好。这背后其实是当下互联网技术发展到一定阶段，出现了专业壁垒的问题。需要更加了解业务，了解技术的专业人士来制定方案。」
- :white_check_mark: [25 岁，毕业写前端的这三年](https://juejin.cn/post/6844903842593636360)「前端毕业后的三年，从纯粹的赶需求到造轮子、做分享和带团队，再到与开源社区接触，博主还认识了一些开源社区的大佬们，最后在稿定科技工作时走出了之前几年在 CPU 上编写逻辑的瓶颈。喜欢这个词：`程序员三大浪漫`，所谓「编程语言、操作系统和计算机图形学」，从传统的 Web 前端的领域知识学习到开始认识需要更多跨领域和学科的知识，非常值得学习」
- :white_check_mark: [再见了，字节跳动](https://juejin.cn/post/7047706117584977934)「在字节跳动一年的成长感悟，一份裸辞的经历，期间面试了许多家公司，发现对于跳槽的一些公司算法考察会比较多，文中一些面试题值得参考，最后博主去了 jerry.ai（捷瑞网络技术），开始了 965 不内卷的居家办公生活，博主说有利也有弊。开字节跳动也许又是一份新的开始」
- :white_check_mark: [精读《为什么专家不再关心技术细节》](https://github.com/ascoders/weekly/blob/master/%E5%95%86%E4%B8%9A%E6%80%9D%E8%80%83/103.%E7%B2%BE%E8%AF%BB%E3%80%8A%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%93%E5%AE%B6%E4%B8%8D%E5%86%8D%E5%85%B3%E5%BF%83%E6%8A%80%E6%9C%AF%E7%BB%86%E8%8A%82%E3%80%8B.md)「一篇对于前端发展路径的思考，从初期技术热情极大到做许多大型项目，再转向综合性思考，最后到了带团队/关注方法论，这里就摘录一下作者的总结吧，技术细节学习难度不大，只是说在需要深入的时候在深入最佳，专家需要眼界宽阔，格局放大，技术细节学习的能力已经足够，但已经不是核心竞争力；在深入技术细节之前，要先理解业务，把握方向，指引方向比走路更重要，要成为引路人。」
- :white_check_mark: [毕业五年还在卷：2021 年终总结](https://zhuanlan.zhihu.com/p/451468340)「没想到在知乎也刷到大佬的文章了，新鲜出炉的 21 年年终总结，讲述自己毕业 5 年之后的想法，看到一个非常有意思的评论：「看别人的年终总结：压力山大，我一年的总结：摸鱼。」看完这篇文章之后，让我想到一位心理学老师讲的，成功的人往往都是会有一些焦虑的，甚至会有一段长时间思考的过程，或者就是说感觉很闲没啥事做的时刻，因为他们在思考，在反思，如何做的更好，每天花费很多时间在追剧和游戏上的人是不会觉得闲的，每天的时间有限。其实读完之后我依旧觉得作者还是很优秀，只是可能随着自己成长，对自己的标准更高了，现在适当放慢脚步也是挺好的。但为了生活，还是要继续卷下去呀」



### Git

- :white_check_mark: [Pull Request 与 Merge Request 的区别](https://github.com/brickspert/blog/issues/37)「一开始开标题我以为是有区别，但其实看完之后发现并没有很多区别哈哈，后面作者的一些吐槽也很有意思，大概明白他们其实没啥区别就行了」

### 前端发展
- :white_check_mark: [年终盘点大前端：前端进入深水区，面向开发者的低代码持续升温](https://juejin.cn/news/7051213466127826952)「摘录自原文：大前端整体健康发展中，虽然增速变缓，但多学科融合、上下游提效，以及深水区深耕，低代码等领域还是飞驰值得期待的。前端自身从标准化向成熟探索过渡，深化垂类和有深度的技术创新，当下前端已进入深水区。面向开发者的低代码持续升温，多状态视图、逻辑编排和状态可视化都是值得关注的方向。Node.js社区健康稳步的发展中，将从性能好向好用的方向转变，在易用性和好用性上有很大提升。在新基建之上，开发一个高可用系统的成本越来越低，需要思考前后端合作模式，更一进步对分工进行拆分。有人说这是前端3.0，也有人说这可能FFB（frontend for backbene），究竟是啥，日渐清晰，让我们拭目以待吧」

### 面试/跳槽/经验
- :white_check_mark: [大厂社招前端-走心面试经验分享](https://juejin.cn/post/6939707197135781924)「正好最近有朋友询问我面试以及跳槽的事情，就刷到了这篇文章，同样也是程序媛，这位博主最后拿了三家大厂 offer，让我比较敬佩的是在职期间边工作边准备的，这样确实会占据很多周末的时间，但功夫不负有心人呀，全程看完感觉对我而言给了不少动力，说不定今年或者明年我也会遇到更换工作的问题，之后还看了博主最新的几篇文章，最后是选择去了字节跳动，分享自己在字节遇到的一些压力与挑战，从博主一系列文章看得出，平常有给自己定计划定目标的好习惯，文章中一些思维导图也非常棒，这样的人必定会成功嘿嘿，向优秀的博主学习。嗷，对了，其中推荐的一本算法书还是挺不错的，「数据结构与算法用 javascript 描述」」


### 工具库

- [60+ 实用 React 工具库，助力你高效开发！](https://juejin.cn/post/7036162494573838367)

### 前端学习/路径/提升/进阶

- :white_check_mark: [近 20 人爆肝数周，写给初中级前端的万字高级进阶指南](https://juejin.cn/post/7017645909483716615)



### 版权申明

阅读心得都是我一字一句敲出来的，如需转载，请附上原文链接，表示对原作者的尊重。谢谢合作！

### 排版

笔记内容按照 <a href="https://mazhuang.org/wiki/chinese-copywriting-guidelines/">中文文案排版指北</a>进行排版。


> 学如逆水行舟，不进则退
