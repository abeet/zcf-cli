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

- [zcf-vue-admin](https://github.com/abeet/zcf-vue-admin) - 适合于后台系统的首页应用工程后端框架为 springboot+zving framework，前端为vue2 + Element UI.

- [koa-vue-admin](https://github.com/abeet/koa-vue-admin) - 适合于后台系统的首页应用工程后端框架为 koa+sequelize，前端为vue2 + Element UI.

### License

[MIT](http://opensource.org/licenses/MIT)
