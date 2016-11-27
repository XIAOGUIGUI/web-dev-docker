# 前端开发环境 Docker 镜像

## 前端开发工具

### 基础环境

| 名称 | 说明 | 版本 |
| --- | --- | --- |
| [node](http://www.npmjs.com) | Node.js 基础环境 | 6.9.1 (LTS) |
| [python](https://www.python.org) | Python 基础环境，编译 sass 必要环境 | V2.X |

### 模块管理器

| 名称 | 说明 | 版本 |
| --- | --- | --- |
| [npm](http://www.npmjs.com) | Node.js 官方推出的 JavaScript 包工具 | v3.10.8 |
| [yarn](https://yarnpkg.com) | Facebook 推出的开源 JavaScript 包工具 | latest |
| [bower](https://bower.io) | Twitter 推出的 JavaScript 包管理工具 | latest |
| [cnpm](https://npm.taobao.org) | 淘宝推出的 npm 淘宝源镜像版 | latest |

### 模块加载器

| 名称 | 说明 | 版本 |
| --- | --- | --- |
| [webpack](http://webpack.github.io) | 前端资源模块化管理和打包工具 | latest |
| [browserify](http://browserify.org) | CommonJS 模块浏览器端支持工具 | latest |

### 构建工具

| 名称 | 说明 | 版本 |
| --- | --- | --- |
| [gulp](http://gulpjs.com) | 自动化构建工具 | latest |
| [grunt](http://gruntjs.com) | 自动化构建工具 | latest |


### 编译工具

| 名称 | 说明 | 版本 |
| --- | --- | --- |
| [babel](https://babeljs.io) | ES6 代码编译工具 | latest |
| [coffee-script](http://coffeescript.org) | JavaScript 预处理语言编译工具 | latest |
| [less](http://lesscss.org) | CSS 预处理语言编译工具 | latest |
| [node-sass](https://www.npmjs.com/package/node-sas) | CSS 预处理语言编译工具 | latest |

### 框架工具

| 名称 | 说明 | 版本 |
| --- | --- | --- |
| [vue-cli](https://github.com/vuejs/vue-cli) | Vue.js 命令行工具 | latest |


### 开发工具

| 名称 | 说明 | 版本 |
| --- | --- | --- |
| [webpack-dev-server](http://webpack.github.io/docs/webpack-dev-server.html) | 小型的 node.jsExpress 服务器 | latest |
| [anywhere](https://www.npmjs.com/package/anywhere) | 随启随用的静态文件服务器 | latest |

### 系统工具

| 名称 | 说明 | 版本 |
| --- | --- | --- |
| [curl](https://curl.haxx.se) | HTTP 请求工具 | latest |
| [wget](http://www.gnu.org/software/wget/wget.html) | 文件下载工具 | latest |
| [vim](http://www.vim.org) | 文本编辑器 | latest |
| [git](https://git-scm.com) | 免费、开源的分布式版本控制工具 | latest |
| [zsh](http://www.zsh.org) | 强大的 Shell 增强工具 | latest |
| [oh-my-zsh](http://ohmyz.sh) | zsh 的扩展工具 | latest |


```shell
docker run -idt -v <workspace-path>:/workspace --name frontend zsh
docker exec -it frontend zsh
```
