Get Started
=====

## 基于ueditor富文本编辑器的表格组件

UEditor是由百度web前端研发部开发所见即所得富文本web编辑器，具有轻量，可定制，注重用户体验等特点，开源基于MIT协议，允许自由使用和修改代码。

## 入门部署和体验 ##

### 第一步：创建demo文件 ###
解压下载的包，在解压后的目录创建demo.html文件，填入下面的html代码

```html
<!DOCTYPE HTML>
<html lang="en-US">
<head>
	<meta charset="UTF-8">
	<title>ueditor demo</title>
</head>
<body>
	<!-- 加载编辑器的容器 -->
	<script id="container" name="content" type="text/plain">这里写你的初始化内容</script>
	<!-- 配置文件 -->
	<script type="text/javascript" src="ueditor.config.js"></script>
	<!-- 编辑器源码文件 -->
	<script type="text/javascript" src="ueditor.all.js"></script>
	<!-- 实例化编辑器 -->
	<script type="text/javascript">
	    var ue = UE.getEditor('container');
	</script>
</body>
</html>
```

### 第二步：插入表格 ###
在控制台输入如下代码即可插入默认(五行五列)的表格,也可以右键选择插入表格功能.
```javascript
    ueditor.execCommand("inserttable");
```


### 自定义的参数

组件有很多可自定义的参数项，在实例化的时候可以传入给编辑器：
```javascript
    此处待补充
```

配置项也可以通过ueditor.config.js文件修改，具体的配置方法请看[前端配置项说明](http://fex.baidu.com/ueditor/#start-config1.4 前端配置项说明.md)

### 设置表格的功能

用户可以通过execCommand()命令对表格组件进行功绑定,具体如下:

```javascript
    此处待补充
```

ueditor的更多API请看[API 文档](http://ueditor.baidu.com/doc "ueditor API 文档")

## 相关链接 ##

ueditor 官网：[http://ueditor.baidu.com](http://ueditor.baidu.com "ueditor 官网")

ueditor API 文档：[http://ueditor.baidu.com/doc](http://ueditor.baidu.com/doc "ueditor API 文档")

ueditor github 地址：[http://github.com/fex-team/ueditor](http://github.com/fex-team/ueditor "ueditor github 地址")

## 详细文档

ueditor 文档：[http://fex.baidu.com/ueditor/](http://fex.baidu.com/ueditor/)


