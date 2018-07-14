# Awesome .NET Core In Chinese [![Awesome .Net Core In Chinese](netcore.png)](https://github.com/AvensLab/awesome-dotnet-core-cn) (持续更新中...)

> [.NET Core](#frameworks-libraries-and-tools) 类库，工具，框架，软件，文章，书籍，视频等资源汇总。    
有不少朋友对英文不感冒，然而对于IT这行，很多技术文档和资源大都是英文的，   
特别是最前沿的东西，为方便 **你我他** 特整理翻译此汇总。

感谢 [awesome-dotnet](https://github.com/quozd/awesome-dotnet), [awesome-dotnet-cn](https://github.com/jobbole/awesome-dotnet-cn),  [awesome-dotnet-core](https://github.com/thangchung/awesome-dotnet-core)  等做出的贡献。

欢迎各路朋友添砖加瓦! 动手前 [贡献准则](https://github.com/AvensLab/awesome-dotnet-core-cn/blob/master/contributing.md) 请您先看一下。
感谢所有 [做贡献的朋友](https://github.com/AvensLab/awesome-dotnet-core-cn/graphs/contributors)，贡献有您更精彩！

## 正文

* [通用](#通用)
* [框架, 类库，工具](#)
  * [算法与数据结构](#算法与数据结构)
  * [API](#api)
  * [应用框架](#应用框架)
  * [应用模板](#应用模板)
  * [人工智能与机器学习](#人工智能与机器学习)
  * [认证与授权](#认证和授权)
  * [区块链](#区块链)
  * [机器人](#bot)
  * [自动构建](#build-automation)
  * [Web打包压缩](#bundling-and-minification)
  * [缓存](#caching)
  * [CMS](#cms)
  * [代码分析与性能量化](#code-analysis-and-metrics)  
  * [压缩](#compression)
  * [编译器与代码解析转换](#compilers-transpilers-and-languages)
  * [加密](#cryptography)
  * [数据库](#database)
  * [数据库驱动](#database-drivers)
  * [数据库工具](#database-tools-and-utilities)
  * [日期时间](#date-and-time)
  * [分布式计算](#distributed-computing)
  * [电子商务与支付](#e-commerce-and-payments)
  * [异常](#exceptions)
  * [函数编程](#functional-programming)
  * [图像处理](#graphics)
  * [GUI](#gui)
  * [开发工具](#ide)
  * [国际化](#internationalization)
  * [控制反转](#ioc)
  * [日志](#logging)
  * [数据科学](#machine-learning-and-data-science)
  * [邮件](#mail)
  * [数学](#mathematics)
  * [网络](#networking)
  * [杂项与插件](#misc)
  * [ORM](#orm)
  * [性能分析](#profiling)
  * [消息队列](#queue-and-messaging)
  * [查询构造Query Builders](#query-builders)
  * [计划调度](#scheduler-and-job)
  * [SDKs](#sdks)
  * [安全](#security)
  * [搜索](#searching)
  * [序列化](#serialization)
  * [模板引擎](#template-engine)
  * [测试](#testing)
  * [工具集](#tools)
  * [Web 框架](#web-framework)
  * [Web Socket](#web-socket)
  * [Windows服务](#windows-service)
  * [工作流](#workflow)
* [入门包](#starter-kits)
* [示例工程](#sample-projects)
* [文章](#articles)
* [书籍](#books)
* [视频](#videos)
* [播客](#podcasts)
* [社区](#community)

## 通用
* [C# Programming Guide](https://docs.microsoft.com/zh-cn/dotnet/csharp/programming-guide/inside-a-program/coding-conventions) - 微软官方 C# 代码规范。
* [ASP.NET Core Documentation](https://docs.microsoft.com/zh-cn/aspnet/core/?view=aspnetcore-2.1) - 微软ASP.NET Core文档，包含入门、教程、MVC/Web Api、部署、测试等。[离线PDF文档](https://github.com/AvensLab/awesome-dotnet-core-cn/blob/master/asp.net%20core%202018-07-14.pdf)
* [.NET Core Documentation](https://docs.microsoft.com/zh-cn/dotnet/core/) - 微软官方.NET Core文档，包含入门、教程、迁移、部署、测试等。
* [.Net Core SDK](https://www.microsoft.com/net/learn/get-started/windows) - 多平台SDK安装包下载，包括安装教程。
* [.NET Standard](https://docs.microsoft.com/zh-cn/dotnet/standard/net-standard) - .Net Standard 标准及各版本之间的异同。
* [Introducing .NET Standard 2.0](https://blogs.msdn.microsoft.com/dotnet/2016/09/26/introducing-net-standard) - .Net Standard详细的介绍。
* [OpenAPI Specification](https://github.com/OAI/OpenAPI-Specification) - 社区版REST API标准。


## 算法与数据结构
* [Algorithmia](https://github.com/SolutionsDesign/Algorithmia) - 包含图，队列，排序，命令行解析等。 
* [C# Algorithms](https://github.com/aalhour/C-Sharp-Algorithms) - 拿来即用型类库，包含35+数据结构及30+常用算法，如链表，图，树，哈希，排序等。

### API
* [autorest](https://github.com/Azure/autorest) - OpenAPI标准客户端代码生成器，支持C#, Go, Java, Node.js, TypeScript, Python, Ruby, PHP。
* [aspnet-api-versioning](https://github.com/Microsoft/aspnet-api-versioning) - 微软开源项目，可以给API服务加上版本功能，支持 Web API 和 ASP.NET Core。
* [AspNetCoreRateLimit](https://github.com/stefanprodan/AspNetCoreRateLimit) - 功能强大且灵活的限额中间件，支持按IP，ID，时间段设定。
* [CondenserDotNet](https://github.com/Drawaes/CondenserDotNet) - 基于Kestrel和Consul的API反代网关。
* [Flurl](https://github.com/tmenier/Flurl) - Fluent是支持异步链式HTTP请求类库。 [https://flurl.io](https://flurl.io).


## 视频
* [Channel9](https://channel9.msdn.com) - MSDN
* [Channel9](https://www.youtube.com/channel/UCsMica-v34Irf9KVTh6xx-g) - YouTube
 * [ASP.NET Monsters](https://channel9.msdn.com/Series/aspnetmonsters)
* [Visual Studio](https://www.youtube.com/user/VisualStudio/channels)

## 播客
* [.NET Rocks](https://www.dotnetrocks.com)
* [Merge Conflict](http://www.mergeconflict.fm/)
* [The sound of .NET](http://thesoundof.net/?q=.NET+Core)

## 社区
* [ASP.NET](https://forums.asp.net)
* [.NET Foundation](http://forums.dotnetfoundation.org)
* [Channel9](https://channel9.msdn.com)
* [Slack](http://tattoocoder.com/aspnet-slack-sign-up)
* Stack Overflow
  *  [.NET Core](https://stackoverflow.com/questions/tagged/.net-core)
  *  [CoreCLR](https://stackoverflow.com/questions/tagged/coreclr)
  *  [ASP.NET Core](https://stackoverflow.com/questions/tagged/asp.net-core)
  *  [ASP.NET Core MVC](https://stackoverflow.com/questions/tagged/asp.net-core-mvc)
  *  [ASP.NET Core 1.0](https://stackoverflow.com/questions/tagged/asp.net-core-1.0)
  *  [Entity Framework Core](https://stackoverflow.com/questions/tagged/entity-framework-core)


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [AvensLab](https://github.com/AvensLab/awesome-dotnet-core-cn) has waived all copyright and related or neighboring rights to this work.