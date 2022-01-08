## 2022 年目标


博主 21 届本科毕业，可以称呼我 Chocolate，在此仓库记录自己 2022 年学习与成长，初心也是为了驱动自己，也让 2022 年的总结增添数据。


希望能在 22 年在哔哩哔哩达成 10w 粉丝:100:成就，<a href="https://space.bilibili.com/351534170">B 站：一百个Chocolate</a><br/>座右铭：学如逆水行舟，不进则退。 QQ交流群：666151691

<a href="https://space.bilibili.com/351534170"><img src="https://img.shields.io/badge/dynamic/json?labelColor=FE7398&logo=bilibili&logoColor=white&label=bilibili%20fans&color=00aeec&query=%24.data.totalSubs&url=https%3A%2F%2Fapi.spencerwoo.com%2Fsubstats%2F%3Fsource%3Dbilibili%26queryKey%3D351534170" /></a>



> 打工的节奏渐渐让我们心态变的浮躁，往往会急于求成，但结果往往达不到期待，「饭要一口一口吃，学习得循序渐进」，在这里沉下心来好好享受学习带来的充实感吧，坚持的习惯会增加更多的幸运值。

## 2022 B 站更新视频列表

> todo...



## 2022 产出文章

> todo...

## 2022 阅读的一些优秀文章

> 部分文章会写一些读完心得，仅个人一些想法，仅做参考，也许会有表述不足之处，可以指正交流。


### React

- :white_check_mark:[从零搭建 React 全家桶框架教程](https://github.com/brickspert/blog/issues/1)「非常有用的文章，博主是 ahooks 作者，很优秀，这个是 17 年写的文章，足以看出个人沉淀。如标题所示“零基础”，目前是第一次读完，打算还要跟着再手写一遍，感谢博主的分享，真是学到了！关于 webpack 那块讲解的很详细到位，对于一些潜在的问题也会拓展，而技术发展也比较快，一些版本可能已经更新了，在这里标记一下我会写一份 22 年的搭建教程，向优秀的博主学习」
- :white_check_mark:[助你完全理解 React 高阶组件（Higher-Order Components）](https://github.com/brickspert/blog/issues/2)「这篇文章内容不是很多，但是非常经典，开头用函数来模拟高阶组件，这一块基本上就可以理解高阶组件了，之后有一个很关键点，就是引入了 redux，这个是真的有用，之前学习的时候都没有弄明白 redux 为什么要这么做，现在醍醐灌顶，点赞，不过由于是 17 年的，所以写法上以 class 语法，之后在新版 react 官网文档看看 hooks 版本的高阶组件介绍吧」
- :white_check_mark:[从零实现一个 tiny hooks，知其然知其所以然](https://github.com/brickspert/blog/issues/26)「这里我改了博主的原标题【React Hooks 原理】，为啥呢，博主这篇文章也写得不错，从零实现了一个 tiny hooks，不过对于开篇提的几个问题，在后续解释的时候略微简单，第一遍读的时候还是觉得有点懵，就那些问题如果没有看其它一些介绍的话还不太清楚，所以这篇读的话后续有点吃力，但这个实现的 tiny hooks 还是比较出神入化的，讲的比较清楚，至于后面 React 官方用链表实现那里就结束了，开始还是蛮期待有后续的，提了一下就就结束了，之后再找找好文继续了解一下，所以这篇文章我更想叫做从零实现一个 tiny hooks」
- :white_check_mark:[React 项目性能分析及优化](https://github.com/brickspert/blog/issues/36)「这篇文章由浅入深的讲解了常用的一些性能优化的方式，从 Chrome 自带的性能查看到使用 React 相关工具，再到最后引入一些平常写代码的时候需要注意的点，为什么会有这个坑，以及遇到一些坑的解决方式。纵观可以看出作者优秀的思维，借用评论区的一些术语来说，就是在编码之前就要思考怎么规划，编码之中还要对代码进行思考，最后在页面的时候可以查看性能分析，根据结果以及结合工具再反复思考。」

### React Router

- :white_check_mark:[react-router v4 使用 history 控制路由跳转](https://github.com/brickspert/blog/issues/3)「关于 react-router 的一些思考，主要是关于这个 history 跳转的问题，其中例举了三种方法，不过现在看组内写的代码，是在使用 react-router-dom 中的 useHistory，这个用起来比较方便，直接在组件中 `const history = useHistory();` 使用即可」

### React-use

- :white_check_mark:[useRequest-蚂蚁中台标准请求 Hooks](https://github.com/brickspert/blog/issues/35)「一篇关于 ahooks 的介绍，这种自定义 hook 其实工作阶段使用了 antd pro 之后了解到的，就是从官方文档底部的推荐看到的，当时打开后就发现了新世界一样，有了这些优秀的 Hooks 之后，许多一些逻辑都可以复用了，而且解决方式更简单方便了，效率拉满」


### React 状态管理库

- :white_check_mark:[完全理解 redux（从零实现一个 redux）](https://github.com/brickspert/blog/issues/22)「这篇文章真的是高赞👍🏻，过去那会关于 redux 理解还不够清晰，看完了之后醍醐灌顶，我是看了两遍才理解清楚，第一遍的时候有些地方感觉看的不是很明白，第二遍看的时候就彻底懂了，发现发布-订阅这种设计模式到处都有用到，以及那个 compose 源码的写法，难怪以前看面试题的时候经典遇到要用 reduce 写法，好神奇的感觉，不知不觉就被带入这块知识当中。但我觉得最精华的部分应该就是中间件那块了，过去学习 Koa 的时候就有遇到中间件的概念，但是一直没理解明白，这次看到 redux 文章之后一下就明白了，博主真是十分用心，膜拜，我觉得对于 redux 不太理解或者仅仅使用的同学都可以看一看，最棒的教程」
- :white_check_mark:[Recoil - Facebook 官方 React 状态管理器](https://github.com/brickspert/blog/issues/38)「这篇讲了 React 状态管理器，先 mark 一下」

### 技术人生

- :white_check_mark:[2022 年如何成为一名优秀的大前端 Leader？](https://juejin.cn/post/7034419410706104356)「优秀的前端Leader要学会适当的拒绝，学会说No。并不是做的越多越好，而是让团队做的少价值高才好。这背后其实是当下互联网技术发展到一定阶段，出现了专业壁垒的问题。需要更加了解业务，了解技术的专业人士来制定方案。」
- :white_check_mark:[25 岁，毕业写前端的这三年](https://juejin.cn/post/6844903842593636360)「前端毕业后的三年，从纯粹的赶需求到造轮子、做分享和带团队，再到与开源社区接触，博主还认识了一些开源社区的大佬们，最后在稿定科技工作时走出了之前几年在 CPU 上编写逻辑的瓶颈。喜欢这个词：`程序员三大浪漫`，所谓「编程语言、操作系统和计算机图形学」，从传统的 Web 前端的领域知识学习到开始认识需要更多跨领域和学科的知识，非常值得学习」
- :white_check_mark:[再见了，字节跳动](https://juejin.cn/post/7047706117584977934)「在字节跳动一年的成长感悟，一份裸辞的经历，期间面试了许多家公司，发现对于跳槽的一些公司算法考察会比较多，文中一些面试题值得参考，最后博主去了 jerry.ai（捷瑞网络技术），开始了 965 不内卷的居家办公生活，博主说有利也有弊。开字节跳动也许又是一份新的开始」


### Git

- :white_check_mark:[Pull Request 与 Merge Request 的区别](https://github.com/brickspert/blog/issues/37)「一开始开标题我以为是有区别，但其实看完之后发现并没有很多区别哈哈，后面作者的一些吐槽也很有意思，大概明白他们其实没啥区别就行了」


### 工具库

- [60+ 实用 React 工具库，助力你高效开发！](https://juejin.cn/post/7036162494573838367)


### 版权申明

阅读心得都是我一字一句敲出来的，如需转载，请附上原文链接，表示对原作者的尊重。谢谢合作！

### 排版

笔记内容按照 <a href="https://mazhuang.org/wiki/chinese-copywriting-guidelines/">中文文案排版指北</a>进行排版。


> 学如逆水行舟，不进则退
