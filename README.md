# Font-end-interview

[![Build Status](https://travis-ci.org/nieyafei/front-end-interview.svg?branch=master)](https://travis-ci.org/nieyafei/front-end-interview)
[![MIT Licence](https://badges.frapsoft.com/os/mit/mit.svg?v=103)](https://opensource.org/licenses/mit-license.php)

前端面试interview的综合题目收集，持续更新，勿浅尝辄止

> 此项目此后不会进行更新，已废弃，数据已合并到http://codehtml.cn/front-end-interview

- [在线访问](http://codehtml.cn/front-end-interview)

### clone或者Fork之后clone到本地

### 安装环境

> npm i docsify-cli -g

### 启动本地查看

> docsify serve docs

### 面试题列表

#### 网络基础、HTTP、TCP/IP

  * [HTTP状态码及其含义](./docs/basic.md)
  * [HTTP的请求方法](./docs/http-request.md)
  * [<span></span>GET和POST区别？](./docs/http-get-post.md)
  * [http 2.0对于http 1.x有哪些优点？](./docs/http/http-1.md)
  * [TCP/IP协议图](./docs/http/tcp-ip-1.md)
  * [TCP三次握手和四次挥手的全过程](./docs/http/http-3.md)
  * [TCP/IP 和 HTTP 的区别和联系是什么？](./docs/http/http-2.md)
  * [OSI，TCP/IP，五层协议的体系结构，以及各层协议](./docs/http/http-bas.md)
  * [在下面的IP地址中属于C类地址的是哪一个?](./docs/http/http-4.md)
  * [了解交换机、路由器、网关的概念，并知道各自的用途](./docs/http/http-5.md)
  * [描述RARP(Reverse Address Resolution Protocol)协议](./docs/http/http-6.md)
  * [从输入URL到页面加载发生了什么](./docs/http/http-7.md)
  * [http的状态码中，499是什么？如何出现499，如何排查跟解决?](./docs/http/http-8.md)
  * [设计一个策略和方法，实现在https的前端项目里进行http请求](./docs/http/http-9.md)
  * [TCP和UDP的区别](./docs/http/http-10.md)
  * [fetch发送2次请求的原因](./docs/http/http-11.md)

#### 浏览器有关

  * [常见的浏览器内核有哪些?](./docs/browser/001.md)
  * [什么是浏览器同源策略？](./docs/browser/002.md)
  * [浏览器的主要组成部分是什么？](./docs/browser/003.md)
  * [怎么预防文件上传漏洞？](./docs/browser/004.md)
  * [window.opener安全问题](./docs/browser/005.md)

#### React

  * [什么是虚拟DOM？](./docs/react/re-18.md)
  * [类组件和函数组件之间的区别是啥？](./docs/react/re-19.md)
  * [constructor(){ this.target = this.func.bind(this); },JSX里onChange={this.target}的写法，为什么要比非bind的func = () => {}的写法效率高 请解释其中的原理](./docs/react/re-17.md)
  * [setState更新state何时同步何时异步？](./docs/react/re-16.md)
  * [调用 setState 之后发生了什么？](./docs/react/re-1.md)
  * [React 中 Element 与 Component 的区别是？](./docs/react/re-2.md)
  * [什么情况下你会优先选择使用 Class Component 而不是 Functional Component？](./docs/react/re-3.md)
  * [React 中 refs 的作用是什么？](./docs/react/re-4.md)
  * [React 中 keys 的作用是什么？](./docs/react/re-5.md)
  * [如果你创建了类似于下面的Twitter元素，那么它相关的类定义是啥样子的？](./docs/react/re-6.md)
  * [Controlled Component 与 Uncontrolled Component 之间的区别是什么？](./docs/react/re-7.md)
  * [在生命周期中的哪一步你应该发起 AJAX 请求？](./docs/react/re-8.md)
  * [shouldComponentUpdate 的作用是啥以及为何它这么重要？](./docs/react/re-9.md)
  * [如何告诉 React 它应该编译生产环境版本？](./docs/react/re-10.md)
  * [为什么我们需要使用 React 提供的 Children API 而不是 JavaScript 的 map？](./docs/react/re-11.md)
  * [概述下 React 中的事件处理逻辑](./docs/react/re-12.md)
  * [createElement 与 cloneElement 的区别是什么？](./docs/react/re-13.md)
  * [传入 setState 函数的第二个参数的作用是什么？](./docs/react/re-14.md)
  * [此代码块有错误吗？](./docs/react/re-15.md)
  * [如何避免在React重新绑定实例？](./docs/react/re-20.md)

#### Vue

  * [你能写一个 Vue 的双向数据绑定吗？](./docs/vue/v-1.md)
  * [vue 如何解析模板？](./docs/vue/temp.md)
  * [写React/Vue项目时为什么要在组件中写key，其作用是什么?](./docs/vue/v-2.md)

#### Node

* [什么是错误优先的回调函数？](./docs/node/n-1.md)
* [如何避免回调地狱？](./docs/node/n-2.md)

#### 算法

* [<span></span>常见排序算法的时间复杂度,空间复杂度](./docs/algorithm-1.md)
* [素数: 你将如何验证一个素数？](./docs/algorithm/alg-2.md)
* [素数因子: 如何求出一个数的所有素数因子？](./docs/algorithm/alg-3.md)
* [用二分查找实现 indexOf 方法，不允许用递归（鹅厂）](./docs/algorithm/alg-4.md)
* [「移动零」，给定一个数组 nums，编写一个函数将所有 0 移动到数组的末尾，同时保持非零元素的相对顺序。](./docs/algorithm/alg-5.md)

#### 综合

  * [介绍下 npm 模块安装机制，为什么输入 npm install 就可以自动安装对应的模块？](./docs/compre/com-1.md)
  * [webpack 中，module，chunk 和 bundle 的区别是什么？](./docs/compre/com-2.md)
  * [webpack 中，filename 和 chunkFilename 的区别?](./docs/compre/com-3.md)
  * [webpackPrefetch、webpackPreload 和 webpackChunkName 到底是干什么的？](./docs/compre/com-4.md)
  * [webpack 中，hash、chunkhash、contenthash 有什么不同？](./docs/compre/com-5.md)
  * [webpack 中，sourse-map的eval、cheap、inline 和 module 各是什么意思？](./docs/compre/com-6.md)
  * [<span></span>前端需要注意哪些SEO?](./docs/inv-1.md)  
  * [hybrid 和 h5 有何区别？](./docs/compre/hybrid-h5.md)
  * [介绍下webpack热更新原理，是如何做到在不刷新浏览器的前提下更新页面?](./docs/compre/webpack-hot.md)
