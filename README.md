# zcf-cli

使用泽元开发框架脚手架创建项目的命令行工具

### 安装

前提: [Node.js](https://nodejs.org/en/) (>=8.x) 和 [Git](https://git-scm.com/).

``` bash
$ npm install -g zcf-cli
```

### 用法

``` bash
zcf init <template-name> <project-name>
```

Example:

``` bash
zcf init zcf-vue-admin my-project
```

上面的命令将模板从 [zcf-templates/zcf-vue-admin](https://github.com/abeet/zcf-vue-admin)拉取下来, 按提示配置后, 生成项目到目录 `./my-project/`.

### 工程模板

当前可用的模板:

- [zcf-vue-admin](https://github.com/abeet/zcf-vue-admin) -  基于 vue + Element UI 适用于后台系统的多页应用工程

- [elrond-childapp-vue](https://github.com/abeet/elrond-childapp-vue) - 基于 vue + Element UI 的前端微服务子应用工程

### License

[MIT](http://opensource.org/licenses/MIT)
