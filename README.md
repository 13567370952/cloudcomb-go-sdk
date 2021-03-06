CloudComb-Go-SDK
================
网易蜂巢 [OpenAPI](https://c.163.com/wiki/index.php?title=OpenAPI%E4%BB%8B%E7%BB%8D) Go SDK


## `简介`

蜂巢 API 提供更灵活的资源控制方式，满足你的定制化需求，如自动化部署，持续集成等功能。

蜂巢 API 需要使用 API Token 来发起 API 请求。 请到 https://c.163.com 页面登陆到你的账户，查看你的 app key 和 app secret，然后调用生成 API token 接口来获取 token。

API 访问 https://open.c.163.com 。API 采用 Restful API 风格，支持内省，支持 API 访问频率限制。

## `功能特点`

* `支持内省`

    * 为每一个请求响应包含一个 Request-Id 头，并使用 UUID 作为该值。通过在客户端、服务器或任何支持服务上记录该值，它能为我们提供一种机制来跟踪、诊断和调试请求。

* `安全`

    * 所有 API 均采用 Https。

* `频率限制`

    * 针对授权接口，支持基于用户的频率限制，频率值根据用户的等级级别设置；针对非授权接口，支持基于 IP 的频率限制。

## `贡献`

欢迎通过 pull request 的方式提交您的代码修改或新的内容, 我们会亲自阅读所有的PR, 如有需要,会与您沟通讨论,修订完善后合并到我们的 mster 分支上.
 



