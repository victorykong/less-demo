### Base

* https://less.bootcss.com/
* 转换输出命令：lessc less/index.less ./css/index.css


### 两种方式

* 浏览器直接引入

```
<!-- 浏览器引入方式 注意顺序 和 /less -->
<link rel="stylesheet/less" href="./less/index.less">
<link rel="stylesheet/less" href="./less/index2.less">
<link rel="stylesheet/less" href="./less/index3.less">
<link rel="stylesheet/less" href="./less/index4.less">
<link rel="stylesheet/less" href="./less/index5.less">
<script src="https://cdn.staticfile.org/less.js/3.11.1/less.min.js"></script>

```


* 使用类似 React 此类框架，需要使用脚手架的形式，安装对应的 loader




