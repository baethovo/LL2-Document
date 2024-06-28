# .NET平台 - LL.NET插件开发概述

## ⛳  放在前面

`LiteLoader.NET`（以下简称**LL.NET**）是为LiteLoaderBDS提供的.NET开发平台支持。

**目前本框架还处于开发状态。**

> 欢迎参与到LL.NET的插件开发中来！

从这里开始，你将逐步熟悉LL.NET插件开发的基本要素和流程。

在接触开发之前，你需要对LL.NET有一个成体系的认识。这里的文档，首先将帮助你建立一个大概的知识框架。  
首先熟悉他们，这将是你学习开发的过程中非常重要的一环。



## 📜 插件开发小贴士

这里，有一些在开发插件的时候的建议，希望可以帮到你

- **不要重复**造轮子  
  在条件允许的情况下，尽量使用他人已经编写好的特定功能的类库，而不是每个功能都自己编写一遍。这样，有利于生态的整合和发展。
- 为**用户**思考  
  在设计界面和配置的时候，最好考虑到用户的感受。UI和命令等对外交互的内容尽量做到清晰和一目了然，符合常规的使用习惯。
- 多角度思考**创新**  
  鼓励大家向其他平台已有的优秀插件学习，也欢迎大家作出自己的创新。