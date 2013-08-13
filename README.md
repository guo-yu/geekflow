![logo](http://ww2.sinaimg.cn/large/61ff0de3gw1e7lgf88hb2j202s00vt8h.jpg) geekflow ![](https://badge.fury.io/js/geekflow.png)
---

![banner](http://ww1.sinaimg.cn/large/61ff0de3gw1e7lgz448qvj20h80bhgme.jpg)

geekflow 是一套工具集的代码集合，这些工具致力于将初创企业的 `展现/用户界面层` 开发变得简单易行，通过对`本地开发环境`，模拟线上环境的`预发布环境`与`线上生产环境` 进行组合，编写自动化脚本，最大程度上低成本地实现`中小型创业公司`的`高可维护`的前端环境。

### 如何安装

````
$ npm install geekflow
````

### 理解geekflow

geekflow 包括以下几个流程：

- 本地开发环境的服务器一件部署命令行工具
- 模拟真实数据的API接口列表，用于在本地环境调试真实数据
- 本地开发环境的测试账户自动切换工具，用于调试数据业务逻辑
- 集成 Grunt 的代码校验与自动化单元测试
- 集成 Git 的自动化部署工具，实现各个环境之间的快速部署与回滚