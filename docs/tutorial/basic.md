### 导航
- [标题](#HTML标题) 
- [段落](#HTML段落) 
- [链接](#HTML链接) 
- [图片](#HTML图片)
- [如何查看HTML源代码](#如何查看HTML源代码)

# HTML基本示例
在本章中，我们将展示一些基本的HTML示例

如果我们使用的标签你还没有学过，不要担心，您将在下面的章节中学到它们。
<br>

## HTML文档
所有HTML文档必须以文档类型声明开头:`<!DOCTYPE html>`

HTML文档本身以`<HTML>`开始，以`</HTML>`结束

HTML文档的可见部分位于`<body>`和`</body>`之间

##### 示例
```html
<!DOCTYPE html>
<html>
<body>
	<h1>我的第一个标题</h1>
	<p>我的第一个段落</p>
</body>
</html>
```
<br>

## <!DOCTYPE声明>
**<!DOCTYPE>声明表示文档类型，帮助浏览器正确显示网页**

它只能出现一次，在页面顶部(在任何HTML标记之前)

`<!DOCTYPE>`声明不区分大小写，以下方式均可：

```html
<!DOCTYPE html>
<!DOCTYPE HTML>
<!Doctype Html>
<!doctype html>
```

<br>

## HTML标题
**HTML标题用`<h1>`到`<h6>`标签定义**

`<h1>`定义了最重要的标题

`<h6>`定义最不重要的标题

```html
<h1>一级标题</h1>
<h2>二级标题</h2>
<h3>三级标题</h3>
```
> <h1>一级标题</h1><h2>二级标题</h2><h3>三级标题</h3>

<br>

## HTML段落
**HTML段落用`<p>`标签定义**

```html
<p>这是一个段落</p>
<p>这是另一个段落</p>
```
> <p>这是一个段落</p><p>这是另一个段落</p>

<br>

## HTML链接
**HTML链接用`<a>`标签定义**

链接的目的地在**href**属性中指定

属性用于提供关于HTML元素的附加信息

```html
<a href="https://github.com/eoooy">这是一个链接</a>
```
> <a href="https://github.com/eoooy">这是一个链接</a>

<br>

## HTML的图片
**HTML图像用`<img>`标记定义**

源文件(src)，替代文本(alt)，宽度(width)和高度(height)作为属性提供:

```html
<img src="example.png" alt="example" width="150" height="150">
```
<img src="https://raw.githubusercontent.com/oovy/html-tutorial/main/gallery/docs/tutorial/basic/example.png" alt="example" width="150" height="150">

<br>

## 如何查看HTML源代码
您是否曾经看到一个Web页面并想知道“嘿!他们是怎么做到的?”

#### 查看HTML源代码:
在HTML页面中单击鼠标右键，选择“**查看页面源代码**”(在Chrome中)或“**查看源代码**”(在Edge中)，或其他浏览器中的类似内容，这将打开一个包含页面HTML源代码的窗口。

#### 检查HTML元素:
右键单击一个元素(或空白区域)，选择“**Inspect**”或“**Inspect element**”来查看元素是由什么组成的(你会看到HTML和CSS)。

您还可以在打开的元素或样式面板中实时编辑HTML或CSS。