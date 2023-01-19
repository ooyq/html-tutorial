### 导航
- [HTML介绍](#HTML介绍)
	- [简单示例](一个简单的HTML示例)
	- [示例解释](#示例解释)
	- [中文编码](#中文编码)
- [HTML标签](#HTML标签)
- [HTML元素](#HTML元素)
- [Web浏览器](#Web浏览器)
- [HTML页面结构](#HTML页面结构)
- [<!DOCTYPE>声明](#<!DOCTYPE>声明)
- [HTML文档后缀名](#HTML文档后缀名)

## HTML介绍
**HTML 是创建Web页面的标准标记语言**
> - HTML 代表超文本标记语言(**H**yper**T**ext **M**arkup **L**anguage)
> - HTML 不是一种编程语言，而是创建Web页面的标准标记语言
> - HTML 描述了Web页面的结构，HTML文档也叫做 web 页面
> - HTML 由一系列元素组成，元素告诉浏览器如何显示内容
> - HTML 元素标记内容片段，如“这是一个标题”，“这是一个段落”，“这是一个链接”，等等

##### 一个简单的HTML示例
```html
<!DOCTYPE html>
<html>

<head>
	<meta charset="UTF-8">
	<title>页面标题</title>
</head>

<body>
	<h1>我的第一个标题</h1>
	<p>我的第一个段落</p>
</body>

</html>
```
##### 示例解释
- `< !DOCTYPE html>`声明定义为HTML5文档
- `<html>`元素是HTML页面的根元素
- `<head>`元素包含关于HTML页面的元信息(meta)
- `<title>`元素描述了文档的标题
- `<body>`元素定义了文档的主体，是所有可见内容的容器，如标题、段落、图像、超链接、表格、列表等
- `<h1>`元素定义了一个一级标题
- `<p>`元素定义了一个段落

##### 中文编码
对于中文网页需要声明编码，否则会出现乱码，需要在头部将字符声明为 UTF-8 或 GBK。
- `<meta charset="UTF-8">`
- `<meta charset="GBK">`

## HTML标签
- HTML 标记标签通常被称为 HTML 标签 (HTML tag)

- HTML 标签是由尖括号包围的关键词，比如 `<html>`

- HTML 标签通常是成对出现的，比如 `<b>` 和 `</b>`

- 标签对中的第一个标签是开始标签，第二个标签是结束标签

- 开始和结束标签也被称为开放标签和闭合标签`<标签名> 内容在这里</标签名>`

## HTML元素
**HTML 标签** 和 **HTML 元素** 通常都是描述同样的意思

> 一个HTML元素由一个开始标记、一些内容和一个结束标记定义:

`<标签名> 内容在这里… </标签名>`

> HTML元素包括从开始标签到结束标签的所有内容:

`<h1>我的第一个标题</h1>`

`<p>我的第一个段落</p>`

| 开始标签 | 元素内容 | 结束标签 |
| ------------ | ------------ | ------------ |
| `<h1>` |  我的第一个标题 | `</h1>` |
| `<p>` |  我的第一个段落 | `</p>` |
| `<br>` | 空 | 空 |

**注意:**
一些HTML元素没有内容(比如`<br>`元素)，这些元素称为空元素，空元素没有结束标签!

## Web浏览器
**网络浏览器的目的是读取HTML文档并正确显示它们**

浏览器不显示HTML标记，而是使用它们来确定如何显示文档:

![](https://raw.githubusercontent.com/oovy/html-tutorial/main/gallery/docs/tutorial/introduction/image1.jpg)

## HTML页面结构
下面是一个HTML页面结构的可视化:

![](https://raw.githubusercontent.com/oovy/html-tutorial/main/gallery/docs/tutorial/introduction/image2.jpg)

**注意:**
`<body>`部分中的内容将显示在浏览器中

`<title>`元素中的内容将显示在浏览器的标题栏或页面的选项卡中

## <!DOCTYPE>声明
**`<!DOCTYPE>`声明有助于浏览器中正确显示网页**

声明是不区分大小写的，以下方式均可：

```html
<!DOCTYPE html>
<!DOCTYPE HTML>
<!Doctype Html>
<!doctype html>
```

## HTML文档后缀名
**以下两种后缀名没有区别，都可以使用**

- .html
- .htm
