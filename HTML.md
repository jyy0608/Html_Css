# HTML

```html
<标签名>aaaa</标签名>
```

`例：`

<h1>一级标题</h1>
<h2>二级标题</h2>
<p>段落</p>
<p>段落</p>
<p>段落</p>
<p>段落</p>





```html
<html>
    <head>子标签1
        <title></title>
    </head>
    <body>
        网页主体
        <!--
		注释
		-->
        <img> 不需要写结束
        <img />    自结束标签
        <input>  不需要写结束
        <input />    自结束标签
    </body>
</html>
```

`例：`

<html>

    <head>
        <title>标题</title>
    </head>
​    <body>
        <h1>一级标题</h1>
        <h2>二级标题</h2>
        <p>段落</p>
        <p>段落</p>
        <p>段落</p>
        <p>段落</p>
​    </body>
</html>





## 标签中的属性

属性，在标签中（开始标签或自结束标签）才可以设置属性
			属性是一种明值对（x=y）

属性用于设置标签中的内容如何显示

属性和标签名或其他属性应该使用空格隔开

属性名和值不能瞎写，应该根据文档中的规定来编写,有些属性有属性值，有些没有，如果有属性值，属性值应该使用引号引起来



## 文档声明

迭代
			网页的版本
				HTML4
				XHTML2.0
				HTML5
				...

​			文档声明（doctype)

```html
		<!doctype html>
		<!DOCTYPE HTML>
```

编码和解码的规则称为字符集（charset）

**乱码**: 如果编码和解码采用的字符集不同就会出现乱码问题

```html
<head>
<!--可以通过meta标签来设置网页的字符集，来避免乱码问题-->
<meta charset="utf-8">
	<title>网页的基本结构</title>
</head>
```



## HTML文档

[HTML 教程 (w3school.com.cn)](https://www.w3school.com.cn/html/index.asp)

