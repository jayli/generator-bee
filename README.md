a yeoman generator for kissy-gallery

## install
### 安装yeoman

````sh
npm install yo grunt-cli -g
````

### 安装kissy-gallery目录生成器

````sh
npm install generator-kpm -g
````

### 生成组件目录

比如你的组件目录是offline，进入该目录，然后执行命令：

````sh
yo kpm 1.0
````

默认版本为1.0。

### 打包组件

在组件目录下执行如下命令：

````sh
grunt
````

可以修改gruntfile.js来自定义组件的构建。

### 发布一个新的版本

在组件目录下执行如下命令：

````sh
yo kpm:version 1.1
````

### 获取本组件 cdn refer

在组件目录下执行如下命令：

````sh
yo kpm:refer
yo kpm:refer index-min.js
yo kpm:refer 1.0/index-min.js
````
*  默认是当前版本的 index-min.js
*  版本未输入的话，默认为当前版本

##changelog

* 旧changelog已清空