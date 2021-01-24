# Chaper1 : Background

第一章将会从一些简单的示例入手，从浅层面、多方面、以面向对象的视角展示ASP .NET Core Identity的主要功能以及分析部分源码。

## 1.1 ASP .NET Core 是什么

ASP.NET Core 是一个跨平台的高性能[开源](https://github.com/dotnet/aspnetcore)Web框架，是由微软和社区开发的下一代ASP .NET。它是一个模块化框架，既可以Windows上的完整.NET Framework上运行，也可以在跨平台.NET Core上运行。

///介绍 .NET .NET CORE ASP.NET ASP.NET CORE

## 1.2 ASP .NET Core Identity 是什么

ASP.NET Core Identity 是将登录功能添加到 ASP.NET Core 应用的成员资格系统。它允许我们创建、读取、更新和删除账户。支持账号验证、身份验证、授权、恢复密码和SMS双因子身份验证，也可以使用外部登录提供程序。 支持的外部登录提供程序包括 [Facebook、Google、Microsoft 帐户和 Twitter](https://docs.microsoft.com/zh-CN/aspnet/core/security/authentication/social/?view=aspnetcore-2.2)。

Identity 可以使用 SQL Server 数据库配置以存储用户名、密码和配置文件数据。 另外，还可以使用另一个永久性存储，例如 Azure 表存储。

ASP .NET Core Identity 官方默认提供的持久化库是Entity Framework 。

Entity Framework Core 是适用于 .NET 的新式对象数据库映射器。 它支持 LINQ 查询、更改跟踪、更新和架构迁移。 EF Core 适用于很多数据库，包括 SQL 数据库（本地和 Azure）、SQLite、MySQL、PostgreSQL 和 Azure Cosmos DB。



## 1.3 ASP .NET Core Identity 用户注册功能

