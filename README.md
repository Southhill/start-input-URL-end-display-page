# 概述
这个git仓库主要是写:**从用户开始输入URL到最后屏幕上页面展示之间到底发生了什么?**(以下简称该问题)  
我认为写这个过程很有意义。对普通的互联网用户（以下简称大众）来说，最多的行为就是浏览器浏览网页了。这可以帮助大众更好的理解浏览器的工作流程。而对以编程为主业的工程师可以对整个计算机体系有管中窥豹的了解（*你们对力量一无所知*）。当然，刚开始我的[初衷](./Original_intention.md)真的很简单[笑脸]

# 过程
## 结构
本仓库大致从三个大的阶段（涉及点）论述该问题。
- 用户端：PC端，移动端。
- 网络间：处于用户端和服务端的部分，比如DNS，数据链路，etc.
- 服务端：处理用户请求的部分，可以狭义的理解为服务器处理的部分。

## 范围
也就是论述的颗粒度的控制，目标是处理机器最底层的过程。每个过程的论述最终都会具体到机器的实现上来，所以应该不会出现整棵树不断生长直至无穷的结果。[万剑归宗]

## 结果
最终会区分一些版本：
- [面向大众的版本](./conclusion/conclusion4normal.md)，考虑到大众的计算机知识的掌握度，必须写的简单明要。
- 面向web开发工程师的版本。
- 以及最终极的细无巨细的版本。
# 进度
由于论述的任务之细，所以有必要建立一个进度和任务页面，  
目前的进度为零。
具体[看这里](./task_and_schedule.md)
# 说在最后
按我的描述蓝图，以我个人所掌握的知识是不能完成其百分之一二的。自从计算机出现后，这个信息时代最重要最伟大的发明一路狂飙，整个计算机体系不断膨胀扩展，细无巨细地发展着。这个体系真是太庞大了，常人不能见其万一。如果真要写书的话，可能一本书都不能论述的完。而一个人掌握的知识太局限了，所以欢迎感兴趣的同学fork仓库，并做贡献。