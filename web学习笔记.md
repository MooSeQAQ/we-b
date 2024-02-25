# 第一周

## 一.HTML

### 简介

什么是 HTML?

HTML 是用来描述网页的一种语言。

- HTML 指的是超文本标记语言: **H**yper**T**ext **M**arkup **L**anguage

- HTML 不是一种编程语言，而是一种**标记**语言

- 标记语言是一套**标记标签** (markup tag)

- HTML 使用标记标签来**描述**网页

- HTML 文档包含了HTML **标签**及**文本**内容

- HTML文档也叫做 **web 页面**

  

什么是HTML 标签？

  HTML 标记标签通常被称为 HTML 标签 (HTML tag)。

  - HTML 标签是由*尖括号*包围的关键词，比如 <html>

  - HTML 标签通常是*成对出现*的，比如 <b> 和 </b>

  - 标签对中的第一个标签是*开始标签*，第二个标签是*结束标签*

  - 开始和结束标签也被称为*开放标签*和*闭合标签*

    ![](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240218163943152.png)



什么是HTML 元素？

- "HTML 标签" 和 "HTML 元素" 通常都是描述同样的意思.

- 但是严格来讲, 一个 HTML 元素包含了开始标签与结束标签。如下例子：

  HTML 元素:

  ![](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240218163926471.png)

### 基础部分

![](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240218163105196.png)

  

- **<!DOCTYPE html>** 声明为 HTML5 文档
- **<html>** 元素是 HTML 页面的根元素
- **<head>** 元素包含了文档的元（meta）数据，如 **<meta charset="utf-8">** 定义网页编码格式为 **utf-8**。
- **<title>** 元素描述了文档的标题
- **<body>** 元素包含了可见的页面内容
- **<h1>** 元素定义一个大标题
- **<p>** 元素定义一个段落

![](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240218164214618.png)

### HTML 属性

- HTML 元素可以设置**属性**
- 属性可以在元素中添加**附加信息**
- 属性一般描述于**开始标签**
- 属性总是以名称/值对的形式出现，**比如：name="value"**。

属性实例：

HTML 链接由 <a> 标签定义。链接的地址在 **href 属性**中指定：

![](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240218164607934.png)

下面列出了适用于大多数 HTML 元素的属性：

![](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240218164712054.png)

### 标题  注释

- HTML 标题（Heading）

​	是通过 <h1> - <h6> 标签进行定义的。

​	-<h1> 定义最大的标题。-<h6>定义最小的标题。

注：确保将 HTML 标题 标签只用于标题。不要仅仅是为了生成**粗体**或**大号**的文本而使用标题。

![](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240218165118124.png)

- HTML 注释

  可以将注释插入 HTML 代码中，这样可以提高其可读性，使代码更易被人理解。浏览器会忽略注释，也不会显示它们。

  注释写法如下:

![](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240218165328233.png)

### 段落 换行

- HTML 段落

​	段落是通过 <p> 标签定义的。

![](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240218165522861.png)

- 换行

![](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240218170027954.png)

### HTML 文本格式化

![](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240218170044884.png)

- HTML 文本格式化的常用标签

![]()![image-20240218170203109](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240218170203109.png)

- HTML "计算机输出" 标签

![](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240218170251623.png)

- HTML 引文, 引用, 及标签定义

![](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240218170318647.png)

### HTML 链接

- HTML 使用超级链接与网络上的另一个文档相连。

​	HTML中的链接是一种用于在不同网页之间导航的元素。

​	链接通常用于将一个网页与另一个网页或资源（如文档、图像、音频文件等）相关联。

​	链接允许用户在浏览网页时单击文本或图像来跳转到其他位置，从而实现网页之间的互联。

#### HTML 超链接

- HTML使用标签 **<a>** 来设置超文本链接。

- 超链接可以是一个字，一个词，或者一组词，也可以是一幅图像，您可以点击这些内容来跳转到新的文档或者当前文档中的某个部分。当您把鼠标指针移动到网页中的某个链接上时，箭头会变为一只小手。

在标签 **<a>** 中使用了 **href** 属性来描述链接的地址。

默认情况下，链接将以以下形式出现在浏览器中：

- 一个未访问过的链接显示为<u>蓝色字体</u>并带有下划线。
- 访问过的链接显示为紫色并带有下划线。
- 点击链接时，链接显示为红色并带有下划线。

![](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240218170808372.png)

#### HTML 链接语法

以下是 HTML 中创建链接的基本语法和属性：`<a>` 元素：创建链接的主要HTML元素是`<a>`（锚）元素。`<a>`元素具有以下属性：

- `href`：指定链接目标的URL，这是链接的最重要属性。可以是另一个网页的URL、文件的URL或其他资源的URL。
- `target`（可选）：指定链接如何在浏览器中打开。常见的值包括 `_blank`（在新标签或窗口中打开链接）和 `_self`（在当前标签或窗口中打开链接）。
- `title`（可选）：提供链接的额外信息，通常在鼠标悬停在链接上时显示为工具提示。
- `rel`（可选）：指定与链接目标的关系，如 nofollow、noopener 等。

链接的 HTML 代码很简单，它类似这样：

![](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240218170920208.png)

href 属性描述了链接的目标。

**实例**如下：

![](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240218170953441.png)

上面这行代码显示为：[访问菜鸟教程](https://www.runoob.com/)

点击这个超链接会把用户带到菜鸟教程的首页。

**提示:** *"链接文本"* 不必一定是文本。图片或其他 HTML 元素都可以成为链接。

- **文本链接：**最常见的链接类型是文本链接，它使用 <a> 元素将一段文本转化为可点击的链接，例如：

![](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240218171148739.png)

- **图像链接：**您还可以使用图像作为链接。在这种情况下，<a> 元素包围着 <img> 元素。例如：

![](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240218171210115.png)

- **锚点链接：**除了链接到其他网页外，您还可以在同一页面内创建内部链接，这称为锚点链接。要创建锚点链接，需要在目标位置使用 <a> 元素定义一个标记，并使用#符号引用该标记。例如：

![](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240218171232113.png)

- **下载链接：**如果您希望链接用于下载文件而不是导航到另一个网页，可以使用 download 属性。例如：

![](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240218171256384.png)

#### HTML 链接 - target 属性

使用 target 属性，你可以定义被链接的文档在何处显示。

下面的这行会在新窗口打开文档

![](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240218171705473.png)

#### HTML 链接- id 属性

id 属性可用于创建一个 HTML 文档书签。

**提示:** 书签不会以任何特殊方式显示，即在 HTML 页面中是不显示的，所以对于读者来说是隐藏的。

**实例**

在HTML文档中插入ID:

![](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240218171751313.png)

### HTML 头部

#### HTML < head> 元素

< head> 元素包含了所有的头部标签元素。在 < head>元素中你可以插入脚本（scripts）, 样式文件（CSS），及各种meta信息。

可以添加在头部区域的元素标签为: <title>, <style>, <meta>, <link>, <script>, <noscript> 和 <base>。

#### HTML < title> 元素

- < title> 标签定义了不同文档的标题。

​	< title> 在 HTML/XHTML 文档中是必需的。

< title> 元素:

- 定义了浏览器工具栏的标题
- 当网页添加到收藏夹时，显示在收藏夹中的标题
- 显示在搜索引擎结果页面的标题

#### HTML < base> 元素

< base> 标签描述了基本的链接地址/链接目标，该标签作为HTML文档中所有的链接标签的默认链接:

![](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240219212641200.png)

#### HTML < link> 元素

< link> 标签定义了文档与外部资源之间的关系。

< link> 标签通常用于链接到样式表:

![](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240219212717946.png)

#### HTML < style> 元素

< style> 标签定义了HTML文档的样式文件引用地址.

在< style> 元素中你也可以直接添加样式来渲染 HTML 文档:

![](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240219212754689.png)

#### HTML < meta> 元素

meta标签描述了一些基本的元数据。

< meta> 标签提供了元数据.元数据也不显示在页面上，但会被浏览器解析。

META 元素通常用于指定网页的描述，关键词，文件的最后修改时间，作者，和其他元数据。

元数据可以使用于浏览器（如何显示内容或重新加载页面），搜索引擎（关键词），或其他Web服务。

< meta> 一般放置于 < head> 区域

- < meta> 标签- 使用实例

![](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240219212903313.png)

#### HTML < script> 元素

< script>标签用于加载脚本文件，如： JavaScript。

< script> 元素在以后的章节中会详细描述。

#### 小结

![](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240219213012159.png)

### HTML 图像

**HTML 图像- 图像标签（ <img>）和源属性（Src）**

在 HTML 中，图像由<img> 标签定义。

<img> 是空标签，意思是说，它只包含属性，并且没有闭合标签。

要在页面上显示图像，你需要使用**<u>源属性（src</u>）**。src 指 "source"。源属性的值是图像的 URL 地址。

**定义图像的语法是：**

<img src="url" alt="some_text">

<u>**URL 指存储图像的位置**</u>。如果名为 "pulpit.jpg" 的图像位于 www.runoob.com 的 images 目录中，那么其 URL 为 [http://www.runoob.com/images/pulpit.jpg](https://www.runoob.com/images/pulpit.jpg)。

浏览器将图像显示在文档中图像标签出现的地方。如果你将图像标签置于两个段落之间，那么浏览器会首先显示第一个段落，然后显示图片，最后显示第二段。

------

#### HTML 图像- Alt属性

alt 属性用来为图像定义一串预备的可替换的文本。

替换文本属性的值是用户定义的。

<img src="boat.gif" alt="Big Boat">

在浏览器无法载入图像时，替换文本属性告诉读者她们失去的信息。此时，浏览器将显示这个替代性的文本而不是图像。为页面上的图像都加上替换文本属性是个好习惯，这样有助于更好的显示信息，并且对于那些使用纯文本浏览器的人来说是非常有用的。

------

#### HTML 图像- 设置图像的高度与宽度

height（高度） 与 width（宽度）属性用于设置图像的高度与宽度。

属性值默认单位为像素:

<img src="pulpit.jpg" alt="Pulpit rock" width="304" height="228">

**提示:** 指定图像的高度和宽度是一个很好的习惯。如果图像指定了高度宽度，页面加载时就会保留指定的尺寸。如果没有指定图片的大小，加载页面时有可能会破坏HTML页面的整体布局。

------

#### 基本的注意事项 - 有用的提示：

**注意:** 假如某个 HTML 文件包含十个图像，那么为了正确显示这个页面，需要加载 11 个文件。加载图片是需要时间的，所以我们的建议是：慎用图片。

**注意:** 加载页面时，要注意插入页面图像的路径，如果不能正确设置图像的位置，浏览器无法加载图片，图像标签就会显示一个破碎的图片。

### HTML 表格

#### tr th td

HTML 表格由 **<table>** 标签来定义。

HTML 表格是一种用于展示结构化数据的标记语言元素。

每个表格均有若干行（由 **<tr>** 标签定义），每行被分割为若干单元格（由 **<td>** 标签定义），表格可以包含标题行（**<th>**）用于定义列的标题。

- **tr**：tr 是 table row 的缩写，表示表格的一行。
- **th**：th 是 table header的缩写，表示表格的表头单元格。
- **td**：td 是 table data 的缩写，表示表格的数据单元格。

数据单元格可以包含文本、图片、列表、段落、表单、水平线、表格等等。

**HTML 表格生成器**：https://www.jyshare.com/front-end/7688/

以下是一个简单的 HTML 表格实例:

![](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240219221850954.png)

以上的表格实例代码中，<table> 元素表示整个表格，它包含两个主要部分：<thead> 和 <tbody>。

- **<thead > 用于定义表格的标题部分:** 在 <thead > 中，使用 <th > 元素定义列的标题，以上实例中列标题分别为"列标题1"，"列标题2"和"列标题3"。
- **<tbody > 用于定义表格的主体部分:** 在 <tbody > 中，使用 <tr > 元素定义行，并在每行中使用 <td > 元素定义单元格数据，以上实例中有两行数据，每行包含三个单元格。



通过使用 **<th >** 元素定义列标题，可以使其在表格中以粗体显示，与普通单元格区分开来。

HTML 表格还可以具有其他部分，如 <tfoot > （表格页脚）和 <caption > （表格标题），<tfoot > 可用于在表格的底部定义摘要、统计信息等内容。 <caption > 可用于为整个表格定义标题。

HTML 表格还支持合并单元格和跨行/跨列的操作，以及其他样式和属性的应用，以满足各种需求。

我们也可以使用 CSS 来进一步自定义表格的样式和外观。

![](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240219222129541.png)

#### **HTML 表格和边框属性**

如果不定义边框属性，表格将不显示边框。有时这很有用，但是大多数时候，我们希望显示边框。

使用边框属性来显示一个带有边框的表格：只需加上 boardr=“1”，如下：

![](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240219222339905.png)

#### HTML 表格表头

表格的表头使用 <th> 标签进行定义。

大多数浏览器会把表头显示为**<u>粗体居中</u>**的文本：(还是蛮实用的)

![image-20240219222523520](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240219222523520.png)

#### 小结

![image-20240219222602730](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240219222602730.png)

### HTML 列表

HTML 支持：（下面这种表达就是有序列表）

1. 无序
2. 有序
3. 定义列表

#### HTML无序列表

无序列表是一个项目的列表，此列项目使用粗体圆点（典型的小黑圆圈）进行标记。

无序列表使用 <ul> 标签。每个列表项始于 <li> 标签。

![image-20240220085241093](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240220085241093.png)

#### HTML 有序列表

同样，有序列表也是一列项目，列表项目使用数字进行标记。 有序列表始于 <ol> 标签。每个列表项始于 <li> 标签。

列表项使用数字来标记。（start=“12”可以不写，这样就从1起始）

![image-20240220085452906](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240220085452906.png)

#### HTML 自定义列表

自定义列表不仅仅是一列项目，而是**项目**及其**注释**的组合。

自定义列表以 <dl> 标签开始。每个自定义列表项以 <dt> 开始。每个自定义列表项的定义以 <dd> 开始。

- **dl**表示列表的起始和结束
- **dt**表示**项目**的起始和结束
- **dd**表示**注释**的起始和结束

例如：

![image-20240220085750378](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240220085750378.png)

又如：

![image-20240220090027101](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240220090027101.png)

#### 小结

![image-20240220090113056](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240220090113056.png)

### HTML 区块

- 大多数 HTML 元素被定义为**块级元素**或**内联元素**。

#### HTML 区块元素

块级元素在浏览器显示时，通常会以新行来开始（和结束）。

实例: <h1>, <p>, <ul>, <table>

#### HTML 内联元素

内联元素在显示时通常不会以新行开始。

实例: <b>, <td>, <a>, <img>

#### HTML <div> 元素

HTML <div> 元素是块级元素，它可用于组合其他 HTML 元素的容器。

< div> 元素没有特定的含义。除此之外，由于它属于块级元素，浏览器会在其前后显示折行。

如果与 CSS 一同使用，< div> 元素可用于对大的内容块设置样式属性。

< div> 元素的另一个常见的用途是<u>文档布局</u>。它**取代**了使用表格定义布局的老式方法。*使用 < table> 元素进行文档布局不是表格的正确用法。< table> 元素的作用是显示表格化的数据。*

#### HTML <span> 元素

HTML <span> 元素是内联元素，可用作文本的容器

<span> 元素也没有特定的含义。

当与 CSS 一同使用时，<span> 元素可用于为部分文本设置样式属性。

#### 小结

![image-20240220090516938](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240220090516938.png)

### HTML 布局

- 网站布局

大多数网站会把内容安排到多个列中（就像杂志或报纸那样）。

大多数网站可以使用 <div> 或者 <table> 元素来创建多列。CSS 用于对元素进行定位，或者为页面创建背景以及色彩丰富的外观。

- 注：虽然我们可以使用**HTML table**标签来设计出漂亮的布局，但是table标签是不建议作为布局工具使用的 - 表格不是布局工具。

**HTML 布局 - 使用<div> 元素**

div 元素是用于分组 HTML 元素的块级元素。

下面的例子使用五个 div 元素来创建多列布局：

![image-20240220090953758](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240220090953758.png)

上面的 HTML 代码会产生如下结果：

![image-20240220091053172](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240220091053172.png)

**HTML 布局 - 有用的提示**

**Tip:** 使用 CSS 最大的好处是，如果把 CSS 代码存放到外部样式表中，那么站点会更易于维护。通过编辑单一的文件，就可以改变所有页面的布局。如需学习更多有关 CSS 的知识，请访问我们的[CSS 教程](https://www.runoob.com/css/css-tutorial.html)。

**Tip:** 由于创建高级的布局非常耗时，使用模板是一个快速的选项。通过搜索引擎可以找到很多免费的网站模板（您可以使用这些预先构建好的网站布局，并优化它们）。

**小结**

![image-20240220091231290](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240220091231290.png)

### HTML 表单

HTML 表单用于收集用户的输入信息。

HTML 表单表示文档中的一个区域，此区域包含交互控件，将用户收集到的信息发送到 Web 服务器。

HTML 表单通常包含各种输入字段、复选框、单选按钮、下拉列表等元素。

以下是一个简单的HTML表单的例子：

- `<form>` 元素用于创建表单，`action` 属性定义了表单数据提交的目标 URL，`method` 属性定义了提交数据的 HTTP 方法（这里使用的是 "post"）。
- `<label>` 元素用于为表单元素添加标签，提高可访问性。
- `<input>` 元素是最常用的表单元素之一，它可以创建文本输入框、密码框、单选按钮、复选框等。`type` 属性定义了输入框的类型，`id` 属性用于关联 `<label>` 元素，`name` 属性用于标识表单字段。
- `<select>` 元素用于创建下拉列表，而 `<option>` 元素用于定义下拉列表中的选项。

#### 创建表单

表单是一个包含表单元素的区域。

表单元素是允许用户在表单中输入内容，比如：文本域（textarea）、下拉列表（select）、单选框（radio-buttons）、复选框（checkbox） 等等。

我们可以使用 **<form>** 标签来创建表单:

![image-20240220092219145](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240220092219145.png)

#### 输入类型

多数情况下被用到的表单标签是输入标签 **<input>**。

输入类型是由 **type** 属性定义。

接下来我们介绍几种常用的输入类型。

- 文本域（Text Fields）
- 密码字段
- 单选按钮（Radio Buttons）
- 复选框（Checkboxes）
- 提交按钮(Submit)

##### 1.文本域

文本域通过 <input type="text"> 标签来设定，当用户要在表单中键入字母、数字等内容时，就会用到文本域。

![image-20240220093001820](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240220093001820.png)

注意:表单本身并不可见。同时，在大多数浏览器中，文本域的默认宽度是 **20** **个字符**。

##### 2.密码字段

密码字段通过标签 **<input type="password">** 来定义:

![image-20240220093127837](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240220093127837.png)

注意：密码字段字符不会明文显示，而是以星号 ***** 或圆点 **.** 替代。

##### 3.单选按钮

**<input type="radio">** 标签定义了表单的单选框选项:

![image-20240220093225723](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240220093225723.png)

##### 4.复选框

**<input type="checkbox">** 定义了复选框。

![image-20240220093307411](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240220093307411.png)

复选框可以选取一个或多个选项

##### 5.提交按钮

- **<input type="submit">** 定义了提交按钮。

- 当用户单击确认按钮时，表单的内容会被传送到服务器。表单的动作属性 **action** 定义了服务端的文件名。

**action** 属性会对接收到的用户输入数据进行相关的处理:

![image-20240220093343114](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240220093343114.png)

假如在上面的文本框内键入几个字母，然后点击确认按钮，那么输入数据会传送到 **html_form_action.php** 文件，该页面将显示出输入的结果。

以上实例中有一个 method 属性，它用于定义表单数据的提交方式，可以是以下值：

- **post**：指的是 HTTP POST 方法，表单数据会包含在表单体内然后发送给服务器，用于提交敏感数据，如用户名与密码等。
- **get**：默认值，指的是 HTTP GET 方法，表单数据会附加在 **action** 属性的 URL 中，并以 **?**作为分隔符，一般用于不敏感信息，如分页等。例如：https://www.runoob.com/?page=1，这里的 page=1 就是 get 方法提交的数据。

### HTML 框架

**iframe语法:**

![image-20240220094120999](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240220094120999.png)

该URL指向不同的网页。

#### iframe - 设置高度与宽度

height 和 width 属性用来定义iframe标签的高度与宽度。

属性默认以像素为单位, 但可以指定其按比例显示 (如："80%")。

![image-20240220094213430](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240220094213430.png)

#### iframe - 移除边框

frameborder 属性用于定义iframe表示是否显示边框。

设置属性值为 "0" 移除iframe的边框:

#### ![image-20240220094231021](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240220094231021.png)使用 iframe 来显示目标链接页面

iframe 可以显示一个目标链接的页面

目标链接的属性必须使用 iframe 的属性，如下实例:

![image-20240220094313937](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240220094313937.png)

批注：这里第一行定义了name=“iframe_a",便于第二行用target=”iframe_a" 从而使链接与框架相联系

#### 小结

### ![image-20240220094543362](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240220094543362.png)HTML 颜色

HTML 颜色由红色、绿色、蓝色混合而成。

#### 三元素

HTML 颜色由一个**十六进制符号**来定义，这个符号由红色、绿色和蓝色的值组成（RGB）。

每种颜色的最小值是0（十六进制：#00）。最大值是255（十六进制：#FF）。

这个表格给出了由三种颜色混合而成的具体效果：

![image-20240220094931955](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240220094931955.png)

#### 颜色名

目前所有浏览器都支持以下颜色名：

- 141个颜色名称是在HTML和CSS颜色规范定义的（17标准颜色，再加124）。下表列出了所有颜色的值，包括十六进制值。
- **提示:** 17标准颜色：黑色，蓝色，水，紫红色，灰色，绿色，石灰，栗色，海军，橄榄，橙，紫，红，白，银，蓝绿色，黄色。点击其中一个颜色名称（或一个十六进制值)就可以查看与不同文字颜色搭配的背景颜色。

#### 颜色值

- 颜色值由十六进制来表示红、绿、蓝（RGB）。

- 每个颜色的最低值为 0(十六进制为 00)，最高值为 255(十六进制为FF)。

- 十六进制值的写法为 # 号后跟三个或六个十六进制字符。

- 三位数表示法为：#RGB，转换为6位数表示为：#RRGGBB。

### HTML 脚本

#### HTML <script> 标签

< script> 标签用于定义客户端脚本，比如 JavaScript。

< script> 元素既可包含脚本语句，也可通过 src 属性指向外部脚本文件。

JavaScript 最常用于图片操作、表单验证以及内容动态更新。

下面的脚本会向浏览器输出"Hello World!"：

![image-20240220102106870](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240220102106870.png)

#### HTML<noscript> 标签

< noscript> 标签提供无法使用脚本时的替代内容，比方在浏览器禁用脚本时，或浏览器不支持客户端脚本时。

< noscript>元素可包含普通 HTML 页面的 body 元素中能够找到的所有元素。

只有在浏览器不支持脚本或者禁用脚本时，才会显示 < noscript> 元素中的内容：

![image-20240220102133050](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240220102133050.png)

#### 小结

![image-20240220102219237](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240220102219237.png)

### HTML 字符实体

HTML 中的预留字符必须被替换为字符实体。

一些在键盘上找不到的字符也可以使用字符实体来替换。

#### HTML 实体

在 HTML 中，某些字符是预留的。

在 HTML 中不能使用小于号（<）和大于号（>），这是因为浏览器会误认为它们是标签。

如果希望正确地显示预留字符，我们必须在 HTML 源代码中使用字符实体（character entities）。 字符实体类似这样：

&*entity_name*;

或

&#*entity_number*;

如需显示小于号，我们必须这样写：![image-20240220102550887](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240220102550887.png)

![Remark](https://www.runoob.com/images/lamp.gif)**提示：** 使用实体名而不是数字的好处是，名称易于记忆。不过坏处是，浏览器也许并不支持所有实体名称（对实体数字的支持却很好）。

#### 不间断空格(Non-breaking Space)

HTML 中的常用字符实体是不间断空格(&nbsp;)。

浏览器总是会截短 HTML 页面中的空格。如果您在文本中写 10 个空格，在显示该页面之前，浏览器会删除它们中的 9 个。如需在页面中增加空格的数量，您需要使用 &nbsp; 字符实体。

#### 结合音标符

发音符号是加到字母上的一个"glyph(字形)"。

一些变音符号, 如 尖音符 ( ̀) 和 抑音符 ( ́) 。

变音符号可以出现字母的上面和下面，或者字母里面，或者两个字母间。

变音符号可以与字母、数字字符的组合来使用。

以下是一些实例:

![image-20240220102643229](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240220102643229.png)

### HTML URL

- **URL**统一资源定位器(Uniform Resource Locators)

- URL 是一个网页地址。

- URL可以由字母组成，如"runoob.com"，或互联网协议（IP）地址： 192.68.20.50。大多数人进入网站使用网站域名来访问，因为 名字比数字更容易记住。

#### URL - 统一资源定位器

Web浏览器通过URL从Web服务器请求页面。

当您点击 HTML 页面中的某个链接时，对应的 <a> 标签指向万维网上的一个地址。

一个统一资源定位器(URL) 用于定位万维网上的文档。

一个网页地址实例: http://www.runoob.com/html/html-tutorial.html 语法规则:

**scheme`://`host.domain`:`port`/`path`/`filename**

说明:

- scheme - 定义因特网服务的类型。最常见的类型是 http
- host - 定义域主机（http 的默认主机是 www）
- domain - 定义因特网域名，比如 runoob.com
- :port - 定义主机上的端口号（http 的默认端口号是 80）
- path - 定义服务器上的路径（如果省略，则文档必须位于网站的根目录中）。
- filename - 定义文档/资源的名称

#### 常见的 URL Scheme

以下是一些URL scheme：

![image-20240220102946979](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240220102946979.png)

#### URL 字符编码

URL 只能使用 [ASCII 字符集](https://www.runoob.com/tags/html-ascii.html).

来通过因特网进行发送。由于 URL 常常会包含 ASCII 集合之外的字符，URL 必须转换为有效的 ASCII 格式。

URL 编码使用 "%" 其后跟随两位的十六进制数来替换非 ASCII 字符。

URL 不能包含空格。URL 编码通常使用 + 来替换空格。

#### URL 编码实例

![image-20240220103020481](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240220103020481.png)

### HTML 速查列表

![image-20240220103310220](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240220103310220.png)

## 二.CSS

### 简介

什么是 **CSS**?

- CSS 指层叠样式表 (**C**ascading **S**tyle **S**heets)
- 样式定义**如何显示** HTML 元素
- 样式通常存储在**样式表**中
- 把样式添加到 HTML 4.0 中，是为了**解决内容与表现分离的问题**
- **外部样式表**可以极大提高工作效率
- 外部样式表通常存储在 **CSS 文件**中
- 多个样式定义可**层叠**为一个

**CSS 实例**

- CSS 规则由两个主要的部分构成：选择器，以及一条或多条声明:

![img](https://www.runoob.com/wp-content/uploads/2013/07/632877C9-2462-41D6-BD0E-F7317E4C42AC.jpg)

选择器通常是我们需要改变样式的 HTML 元素。

每条声明由一个属性和一个值组成。

属性（property）是我们希望设置的样式属性（style attribute）。每个属性有一个值。属性和值被冒号分开。

- CSS声明总是以分号 **;** 结束，声明总以大括号 **{}** 括起来:

```
p {color:red;text-align:center;}
```

#### CSS 注释

注释是用来解释你的代码，并且可以随意编辑它，浏览器会忽略它。

CSS注释以 **/\*** 开始, 以 ***/** 结束, 实例如下:

![image-20240223094416190](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223094416190.png)

### CSS id 和 class

#### id 选择器

id 选择器可以为标有特定 id 的 HTML 元素指定特定的样式。

- HTML元素以id属性来设置id选择器,CSS 中 id 选择器以 "#" 来定义。

以下的样式规则应用于元素属性 id="para1":

![image-20240223094459032](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223094459032.png)

#### class 选择器

class 选择器用于描述**一组元素**的样式，class 选择器有别于id选择器，class可以在**多个元素**中使用。

class 选择器在 HTML 中以 class 属性表示, 在 CSS 中，类选择器以一个**点 . 号**显示：

在以下的例子中，所有拥有 center 类的 HTML 元素均为居中。

![image-20240223094648491](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223094648491.png)

注：类名的第一个字符不能使用数字！它无法在 Mozilla 或 Firefox 中起作用。

### CSS 创建样式

当读到一个样式表时，浏览器会根据它来格式化 HTML 文档。

------

**如何插入样式表**

插入样式表的方法有三种:

- 外部样式表(External style sheet)
- 内部样式表(Internal style sheet)
- 内联样式(Inline style)

#### 外部样式表

当样式需要应用于很多页面时，外部样式表将是理想的选择。在使用外部样式表的情况下，你可以通过改变一个文件来改变整个站点的外观。每个页面使用 <link> 标签链接到样式表。 <link> 标签在（文档的）头部：

![image-20240223094827340](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223094827340.png)

浏览器会从文件 mystyle.css 中读到样式声明，并根据它来格式文档。

外部样式表可以在任何文本编辑器中进行编辑。文件不能包含任何的 html 标签。样式表应该以 .css 扩展名进行保存。下面是一个样式表文件的例子：

![image-20240223094839935](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223094839935.png)

#### 内部样式表

当单个文档需要特殊的样式时，就应该使用内部样式表。你可以使用 <style> 标签在文档头部定义内部样式表，就像这样:

![image-20240223094914195](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223094914195.png)

#### 内联样式

由于要将表现和内容混杂在一起，内联样式会损失掉样式表的许多优势。请慎用这种方法，例如当样式仅需要在一个元素上应用一次时。

要使用内联样式，你需要在相关的标签内使用样式（style）属性。Style 属性可以包含任何 CSS 属性。本例展示如何改变段落的颜色和左外边距：

![image-20240223094937527](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223094937527.png)

#### 多重样式优先级

样式表允许以多种方式规定样式信息。样式可以规定在单个的 HTML 元素中，在 HTML 页的头元素中，或在一个外部的 CSS 文件中。甚至可以在同一个 HTML 文档内部引用多个外部样式表。

一般情况下，优先级如下：

**（内联样式）Inline style > （内部样式）Internal style sheet >（外部样式）External style sheet > 浏览器默认样式**

### CSS 文本格式

#### **文本颜色**

颜色属性被用来设置文字的颜色。

颜色是通过CSS最经常的指定：

- 颜色的名称 - 如: **red**
- 十六进制值 - 如: **＃FF0000**
- 一个RGB值 - 如: **RGB(255,0,0)**

![image-20240223095050513](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223095050513.png)

#### 文本的对齐方式

文本排列属性是用来设置文本的水平对齐方式。

文本可居中或对齐到左或右,两端对齐.

当text-align设置为"justify"，每一行被展开为宽度相等，左，右外边距是对齐（如杂志和报纸）。

![image-20240223095117120](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223095117120.png)

#### 文本修饰

text-decoration 属性用来设置或删除文本的装饰。

从设计的角度看 text-decoration属性主要是用来删除链接的下划线：

![image-20240223095132062](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223095132062.png)

也可以这样装饰文字：

![image-20240223095146072](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223095146072.png)

#### 文本转换

文本转换属性是用来指定在一个文本中的大写和小写字母。

可用于所有字句变成大写或小写字母，或每个单词的首字母大写。

![image-20240223095205401](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223095205401.png)

#### 文本缩进

文本缩进属性是用来指定文本的第一行的缩进。

![image-20240223095221576](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223095221576.png)

#### 字体样式

主要是用于指定斜体文字的字体样式属性。

- 正常 - 正常显示文本
- 斜体 - 以斜体字显示的文字
- 倾斜的文字 - 文字向一边倾斜

![image-20240223095320229](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223095320229.png)

### CSS 链接

链接的样式，可以用任何CSS属性（如颜色，字体，背景等）。

特别的链接，可以有不同的样式，这取决于他们是什么状态。

这四个链接状态是：

- a:link - 正常，未访问过的链接
- a:visited - 用户已访问过的链接
- a:hover - 当用户鼠标放在链接上时
- a:active - 链接被点击的那一刻

![image-20240223095343875](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223095343875.png)

#### 文本修饰

text-decoration 属性主要用于删除链接中的下划线：

![image-20240223095414424](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223095414424.png)

#### 背景颜色

背景颜色属性指定链接背景色：

![image-20240223095447683](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223095447683.png)

### CSS 列表

CSS 列表属性作用如下：

- 设置不同的列表项标记为无序列表
- 设置不同的列表项标记为有序列表
- 设置列表项标记为图像

#### **无序列表如下所示:**

- Coffee
- Tea
- Coca Cola

#### **有序列表如下所示:**

1. Coffee
2. Tea
3. Coca Cola

### CSS 表格

使用 CSS 可以使 HTML 表格更美观。

#### 表格边框

指定CSS表格边框，使用border属性。

下面的例子指定了一个表格的Th和TD元素的黑色边框：

![image-20240223095650993](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223095650993.png)

![image-20240223095700755](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223095700755.png)

#### 折叠边框

border-collapse 属性设置表格的边框是否被折叠成一个单一的边框或隔开：

![image-20240223095722722](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223095722722.png)

![image-20240223095730361](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223095730361.png)

#### 表格宽度和高度

Width和height属性定义表格的宽度和高度。

下面的例子是设置100％的宽度，50像素的th元素的高度的表格：

![image-20240223095800174](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223095800174.png)

![image-20240223095808605](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223095808605.png)

#### 表格文字对齐

表格中的文本对齐和垂直对齐属性。

text-align属性设置水平对齐方式，向左，右，或中心：

![image-20240223095909297](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223095909297.png)

![image-20240223095917559](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223095917559.png)

#### 表格填充

如需控制边框和表格内容之间的间距，应使用td和th元素的填充属性：

![image-20240223095950407](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223095950407.png)

#### 表格颜色

下面的例子指定边框的颜色，和th元素的文本和背景颜色：

![image-20240223100016831](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223100016831.png)

## 三.JavaScript

### 简介

**JavaScript** 是 web 开发人员必须学习的 3 门语言中的一门：

1. **HTML** 定义了网页的内容
2. **CSS** 描述了网页的布局
3. **JavaScript** 控制了网页的行为

---------

#### 1.输出

JavaScript 没有任何打印或者输出的函数。

- 在 HTML **输出**中可使用 **document.write**

**注**：如果在文档加载后使用该方法，则会覆盖整个文档！

JavaScript 还可以通过不同的方式来输出数据：

- 使用 **document.write()** 方法将内容写到 HTML 文档中。
- 使用 **window.alert()** 弹出警告框。
- 使用 **innerHTML** 写入到 HTML 元素。
- 使用 **console.log()** 写入到浏览器的控制台。

#### 2.改变 HTML 内容

使用 JavaScript 来处理 HTML 内容是非常强大的功能。

![image-20240222203843759](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222203843759.png)

![image-20240222204059642](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222204059642.png)

![image-20240222204255172](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222204255172.png)

通过id=“demo”找到对应元素，再改变元素内容。

- 这里用到了<u>x.innerHTML="Hello JavaScript!";</u>来改变元素内容

#### 3.改变 HTML 图像/样式

改变 HTML 元素的样式，属于改变 HTML 属性的变种。

![image-20240222204315747](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222204315747.png)

![image-20240222204413082](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222204413082.png)

![image-20240222204420704](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222204420704.png)

与上例类似，先找到目标元素，然后通过不同的方式改变其样式。

- 这里用到了<u>x.style.color="#ff0000";</u> 来改变元素颜色

#### 4.验证输入

JavaScript 还可以用于验证用户的输入，具体操作与下文的正则有关

```html
if(isNaN(x)||x.replace(/(^\s*)|(\s*$)/g,"")==""){    alert("不是数字"); }
```

### 常规用法

- HTML 中的 Javascript 脚本代码**必须**位于 **<script>** 与 **</script>** 标签之间。

- Javascript 脚本代码可被放置在 HTML 页面的 **<body>** 和 **<head>** 部分中。

#### < script> 标签

当我们要在 HTML 页面中插入 JavaScript，就得使用 < script> 标签。

< script> 和 </ script> 会告诉 JavaScript 在何处**开始**和**结束**。

< script> 和 < /script> 之间的代码行包含了 JavaScript。

#### 在 < head> 或者 < body> 的JavaScript

我们可以在 HTML 文档中放入不限数量的脚本。

- 脚本可位于 HTML 的 <body> 或 <head> 部分中，或者同时存在于两个部分中。

- 通常的做法是把函数放入 <head> 部分中，或者放在页面底部。这样就可以把它们安置到同一处位置，不会干扰页面的内容。

##### < head> 中的 JavaScript 函数

在本例中，我们把一个 JavaScript 函数放置到 HTML 页面的 <head> 部分。

该函数会在点击按钮时被调用：

![image-20240222205702637](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222205702637.png)

##### < body> 中的 JavaScript 函数

在本例中，我们把一个 JavaScript 函数放置到 HTML 页面的 <body> 部分。

该函数会在点击按钮时被调用：

![image-20240222205851462](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222205851462.png)

#### 外部的 JavaScript

当然了，我们也可以把脚本保存到外部文件中。外部文件通常包含被多个网页使用的代码。

- 外部 JavaScript 文件的文件扩展名是 .js。

- 如需使用外部文件，请在 <script> 标签的 "src" 属性中设置该 .js 文件：

![image-20240222210001502](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222210001502.png)

我们可以将脚本放置于 < head> 或者 < body>中，放在 < script> 标签中的脚本与外部引用的脚本运行效果完全一致。

myScript.js 文件代码如下：

```javascript
function myFunction()
{
    document.getElementById("demo").innerHTML="我的第一个 JavaScript 函数";
}
```

**注**：外部脚本不能包含 < script> 标签。

### **基础概念**

#### 函数（Function）

函数是可复用的代码块，可以一次编写，反复运行，从而节省了大量的重复代码。

函数的格式包括了关键字 `function` 、一个函数名、一对小括号定义了一个函数。随后是一对花括号（`{ }`）。花括号内部是调用函数时要运行的所有代码。

```javascript
function the_name_of_function() {
  your code;
}
```

#### 事件（Event）

理想中，我们希望在点击某个按钮时调用某个函数，为此，我们需要使用事件。**事件就是浏览器中发生的事儿**，比如点击按钮、加载页面、播放视频，等等，我们可以通过调用代码来响应事件。侦听事件发生的结构称为**事件监听器**（Event Listener），响应事件触发而运行的代码块被称为**事件处理器**（Event Handler）。

#### 对象和方法

##### 对象（Object）

在JavaScript中，一切都是对象。对象是一种复合数据类型(类似C语言的结构体)，它可以包含**属性和方法，由逗号分隔开**。例如：

```javascript
// 定义一个对象
const person = {
  // 属性
  name: "John",
  age: 30,
  // 方法
  greet: function() {
    console.log("Hello, my name is " + this.name);
  }
};
```

点符号（`.`）来访问对象的属性和其他方法，例如：

```
PLAINTEXT
person.greet(); // 调用对象的方法
```

属性是对象的特征或数据是任何JavaScript数据类型，包括字符串、数字、布尔值、数组、甚至其他对象。

##### 方法（method）

与对象关联的**函数**。方法是在对象上定义的，它可以访问对象的属性和其他方法，并执行特定的操作。是对象能够执行的操作或行为。可通过浏览器的JavaScript 控制台操作浏览器对象

##### 函数与方法的差别

1. 归属关系：**方法是与对象关联的函数**。它们通常是在对象的上下文中定义的，并且可以访问对象的属性和其他方法。方法是对象的行为或操作。**函数是独立的代码块**，不依赖于特定的对象。它们可以在任何地方定义和调用，而不需要依赖于对象。

2. 调用方式：**方法通过对象来调用。它们使用对象名和方法名的结合形式进行调用**，例如 `objectName.methodName()`。方法的调用是基于对象的，因此方法可以使用对象的属性和其他方法。**函数可以直接通过函数名进行调用**，例如 `functionName()`。函数的调用是独立的，不依赖于特定的对象。

3. 参数传递：**方法通常将对象本身作为第一个参数传递给方法（通常称为 `this` 或 `self`）**，以便在方法内部访问对象的属性和其他方法。方法可以接受其他参数作为输入。函数可以接受任意数量的参数，并且可以通过参数来接收外部值。

   例：

   ```javascript
   const person = {
     name: "Wells",
     greet: function() {
       console.log("Hello, my name is " + this.name); //使用this作为对象本身
     },
   };
   
   person.greet(); // 输出 "Hello, my name is Wells"
   ```

4. 定义方式：方法是在对象或类的定义中声明的。它们可以使用对象字面量语法或类的方法定义语法进行定义。函数可以在全局范围内或其他函数内部进行定义。它们可以使用函数声明语法或函数表达式语法进行定义。

#### 运算符（Operator）

JavaScript 运算符允许我们执行比较、做数学运算、连接字符串等等。

#### 算术运算符

| 运算符 | 描述         |
| ------ | ------------ |
| +      | 加法         |
| -      | 减法         |
| *      | 乘法         |
| **     | 幂           |
| /      | 除法         |
| %      | 取模（余数） |
| ++     | 自增         |
| –      | 自减         |

- 自增和自减运算符放置在变量前和变量后与区别（与C语言类似）

  1. 前置自增/自减运算符会先对变量进行自增或自减操作，然后返回更新后的值。
  2. 后置自增/自减运算符会先返回变量的原始值，然后再对变量进行自增或自减操作。

- 运算符用于把文本值或字符串变量加起来（连接起来）。

  例如：

  ```javascript
  txt1="What a very";
  txt2="nice day";
  txt3=txt1+txt2;
  ```

  则`txt3`为`What a verynice day`

- 如果数字与字符串相加，此时数字会被认为是字符串，返回字符串

  例如

  ```javascript
  z="Hello"+666;
  ```

  则`z`为`Hello666`

#### 赋值运算符

赋值运算符用于给 JavaScript 变量赋值。

| 运算符 | 例子 | 等同于         |
| ------ | ---- | -------------- |
| =      | x=y  | （将y赋值给x） |
| +=     | x+=y | x=x+y          |
| -=     | x-=y | x=x-y          |
| *=     | x*=y | x=x*y          |
| /=     | x/=y | x=x/y          |
| %=     | x%=y | x=x%y          |

#### 比较运算符

比较运算符在逻辑语句中使用，以测定变量或值是否相等。

以x=5为例：

| 运算符 | 描述                                               | 比较    | 返回值  |
| ------ | -------------------------------------------------- | ------- | ------- |
| ==     | 等于(类型不等时会进行转化)                         | x==8    | *false* |
|        |                                                    | x==5    | *true*  |
|        |                                                    | x==”5”  | *true*  |
| ===    | 严格等于（值和类型均相等）                         | x===”5” | *false* |
|        |                                                    | x===5   | *true*  |
| !=     | 不等于                                             | x!=8    | *true*  |
|        |                                                    | x!=”5”  | *false* |
| !==    | 严格不等于（值和类型有一个不相等，或两个都不相等） | x!==”5” | *true*  |
|        |                                                    | x!==5   | *false* |
| >      | 大于                                               | x>8     | *false* |
| <      | 小于                                               | x<8     | *true*  |
| >=     | 大于或等于                                         | x>=8    | *false* |
| <=     | 小于或等于                                         | x<=8    | *true*  |

严格的版本往往导致更少的错误，建议使用这些严格的版本。

#### 逻辑运算符

逻辑运算符用于测定变量或值之间的逻辑。

| 运算符 | 描述                |
| ------ | ------------------- |
| &&     | and（同时成立为真） |
| \|\|   | or（一个成立为真）  |
| !      | not                 |

#### 条件（三元）运算符

条件元素运算符把两个结果中其中一个符合运算逻辑的值返回。

```javascript
? :
(condition ? if True : if False)
```

### JavaScript 语法

#### 字母大小写

JavaScript 对**大小写**是敏感的!!!

- 当编写 JavaScript 语句时，一定要记得查看是否关闭大小写切换键。

例如：

- 函数 **getElementById** 与 **getElementbyID** 是不同的。

- 同样，变量 **myVariable** 与 **MyVariable** 也是不同的。

#### 字面量

在编程语言中，一般固定值称为**字面量**，如 3.14。

- **数字（Number）字面量** 可以是整数或者是小数，或者是科学计数(e)。
- **字符串（String）字面量** 可以使用单引号或双引号:

![image-20240222211905064](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222211905064.png)

- **表达式字面量**用于计算：

![image-20240222211932948](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222211932948.png)

- **数组（Array）字面量** 定义一个数组：

![image-20240222212008943](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222212008943.png)

- **对象（Object）字面量** 定义一个对象：

![image-20240222212017116](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222212017116.png)

- **函数（Function）字面量** 定义一个函数：

![image-20240222212032523](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222212032523.png)

#### 变量

在编程语言中，**变量**用于<u>存储数据值</u>。

JavaScript 使用关键字 **var** 来**定义变量**， 使用等号来为变量赋值：

![image-20240222212111038](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222212111038.png)

**Tip**

- 变量可以通过变量名访问。在指令式语言中，变量通常是可变的。字面量是一个恒定的值。

- 变量是一个**名称**。字面量是一个**值**。

- 变量是用于存储信息的"容器"。

----------

**变量**

  与代数一样，JavaScript 变量可用于存放值（比如 x=5）和表达式（比如 z=x+y）。

  变量可以使用短名称（比如 x 和 y），也可以使用描述性更好的名称（比如 age, sum, totalvolume）。

  - 变量必须以字母开头
  - 变量也能以 $ 和 _ 符号开头（不过我们不推荐这么做）
  - 变量名称对大小写敏感（y 和 Y 是不同的变量）

  **注**： JavaScript **语句**和 JavaScript **变量**都对**大小写**敏感。

#### 操作符

JavaScript使用 **算术运算符** 来计算值:

![image-20240222212238312](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222212238312.png)

JavaScript使用**赋值运算符**给变量赋值：

![image-20240222212249907](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222212249907.png)

JavaScript语言有多种类型的运算符：

![image-20240222212304467](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222212304467.png)

#### 关键字

JavaScript 关键字用于标识要执行的操作。

和其他任何编程语言一样，JavaScript 保留了一些关键字为自己所用。

**var** 关键字告诉浏览器创建一个新的变量：

![image-20240222212547680](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222212547680.png)

以下是 JavaScript 中最重要的保留关键字（按字母顺序）：

| abstract | else       | instanceof | super        |
| -------- | ---------- | ---------- | ------------ |
|          |            |            |              |
| boolean  | enum       | int        | switch       |
|          |            |            |              |
| break    | export     | interface  | synchronized |
|          |            |            |              |
| byte     | extends    | let        | this         |
|          |            |            |              |
| case     | false      | long       | throw        |
|          |            |            |              |
| catch    | final      | native     | throws       |
|          |            |            |              |
| char     | finally    | new        | transient    |
|          |            |            |              |
| class    | float      | null       | true         |
|          |            |            |              |
| const    | for        | package    | try          |
|          |            |            |              |
| continue | function   | private    | typeof       |
|          |            |            |              |
| debugger | goto       | protected  | var          |
|          |            |            |              |
| default  | if         | public     | void         |
|          |            |            |              |
| delete   | implements | return     | volatile     |
|          |            |            |              |
| do       | import     | short      | while        |
|          |            |            |              |
| double   | in         | static     | with         |

### JavaScript 语句

JavaScript 语句向浏览器发出的命令。语句的作用是告诉浏览器该做什么。

----------

#### 语句

JavaScript 语句是发给浏览器的命令。

- 这些命令的作用是告诉浏览器要做的事情。

- 下面的 JavaScript 语句向 id="demo" 的 HTML 元素输出文本 "你好 Dolly" ：

![image-20240222212755919](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222212755919.png)

#### 分号

分号用于分隔 JavaScript 语句。

- 通常我们在每条可执行的语句结尾添加分号。

- 使用分号的另一用处是在一行中编写多条语句。

例如：

```
a = 5;
b = 6;
c = a + b;
```

也可以这么写:

```
a = 5; b = 6; c = a + b;
```

#### 代码

JavaScript 代码是 JavaScript 语句的序列。

- 浏览器按照编写顺序依次执行每条语句。

本例向网页输出一个标题和两个段落：

![image-20240222213027663](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222213027663.png)

#### 代码块

JavaScript 可以分批地组合起来。

- 代码块以左花括号开始，以右花括号结束。

- 代码块的作用是一并地执行语句序列。

本例向网页输出一个标题和两个段落：

![image-20240222213150720](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222213150720.png)

而这个其实就是函数的运用

#### 空格

JavaScript 会忽略多余的空格。

- 可以向脚本添加空格，来提高其可读性。

因此下面的两行代码是等效的：

```
var person="runoob";
```

```
var person = "runoob";
```

#### 折行

我们可以在文本字符串中使用**反斜杠**<u>对**代码行**进行换行</u>。

例如：

![image-20240222213445751](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222213445751.png)

运行结果：

![image-20240222213453168](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222213453168.png)

### JavaScript 注释

JavaScript 不会执行注释。

我们可以添加注释来对 JavaScript 进行解释，或者提高代码的可读性。

#### 单行注释

- 单行注释以 **//** 开头。

本例用单行注释来解释代码：

![image-20240222213649770](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222213649770.png)

#### 多行注释

多行注释以 **/\*** 开始，以 ***/** 结尾。

下面的例子使用多行注释来解释代码：

![image-20240222213716802](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222213716802.png)

#### 可在行末使用注释充当说明

在下面的例子中，我们把注释放到代码行的结尾处：

![image-20240222213832011](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222213832011.png)



### JavaScript 数据类型

**值类型(基本类型)**：字符串（String）、数字(Number)、布尔(Boolean)、空（Null）、未定义（Undefined）、Symbol。

**引用数据类型（对象类型）**：对象(Object)、数组(Array)、函数(Function)，还有两个特殊的对象：正则（RegExp）和日期（Date）。

![img](https://www.runoob.com/wp-content/uploads/2013/08/Javascript-DataType.png)

**注：**Symbol 是 ES6 引入了一种新的原始数据类型，表示独一无二的值。

**JavaScript 拥有动态类型**

JavaScript 拥有<u>动态类型</u>。这意味着**相同的变量**可用作**不同的类型**：

![image-20240222214226094](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222214226094.png)

这点非常的神奇，此外 变量的数据类型可以使用 **typeof** 操作符来查看：

![image-20240222214312276](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222214312276.png)

#### 数字

avaScript 只有一种数字类型。

- 数字可以带小数点，也可以不带

![image-20240222214715053](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222214715053.png)

- 极大或极小的数字可以通过科学（指数）计数法来书写：

![image-20240222214721302](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222214721302.png)

#### 字符串

字符串是存储字符（比如 "Bill Gates"）的变量。

字符串可以是引号中的任意文本：

- 可以使用单引号或双引号；
- 可以在字符串中使用引号，只要不匹配包围字符串的引号即可：

![image-20240222214619837](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222214619837.png)

##### 字符串长度

可以使用内置属性 **length** 来计算字符串的长度：

![image-20240222221342909](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222221342909.png)

#### 布尔

布尔（逻辑）只能有两个值：true 或 false。

![image-20240222214739812](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222214739812.png)

#### 数组

下面的代码创建名为 cars 的数组：

```
var cars=new Array();
cars[0]="Saab";
cars[1]="Volvo";
cars[2]="BMW";
```

也可以这样写：


```
var cars=new Array("Saab","Volvo","BMW");
```

还可以这样写：

```
var cars=["Saab","Volvo","BMW"];
```

注：数组下标是基于零的，所以第一个项目是 [0]，第二个是 [1]，以此类推.

#### 对象

对象由花括号分隔。在括号内部，对象的属性以名称和值对的形式 (name : value) 来定义。属性由逗号分隔：

![image-20240222215049400](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222215049400.png)

上面例子中的对象 (person) 有三个属性：firstname、lastname 以及 id。

空格和折行无关紧要。声明可横跨多行：

![image-20240222215100553](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222215100553.png)

对象属性有两种寻址方式：

![image-20240222215114359](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222215114359.png)

#### Undefined 和 Null

Undefined 这个值表示变量不含有值。

可以通过将变量的值设置为 null 来清空变量。

![image-20240222215421234](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222215421234.png)

#### 声明变量类型

声明新变量时，我们可以使用关键词 "new" 来声明其类型：

![image-20240222215445085](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222215445085.png)

注：由于JavaScript 变量均为对象，所以每声明一个变量时，就创建了一个新的对象。

### JavaScript 对象

JavaScript 对象是拥有**属性**和**方法**的数据。

- 对象也是一个变量，但对象可以包含多个值（多个变量），每个值以 **name:value** 对呈现。

#### 对象定义

可以使用字符来定义和创建 JavaScript 对象:

![image-20240222215701639](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222215701639.png)

定义 JavaScript 对象可以跨越多行，空格跟换行不是必须的：

![image-20240222215715968](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222215715968.png)

#### 对象属性

可以说 "JavaScript **对象**是**变量**的容器"。

- 可以理解成对象可以包含多个值（多个变量），每个值以 **name:value** 对呈现。

----------

但是，我们通常认为 "JavaScript **对象**是**键值对**的容器"。

- 键值对通常写法为 **name : value** (键与值以冒号分割)。

- 键值对在 JavaScript 对象通常称为 **对象属性**。

##### 访问对象属性

你可以通过两种方式访问对象属性:

![image-20240222215939959](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222215939959.png)

或者：

![image-20240222215951854](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222215951854.png)

#### 对象方法

对象的方法定义了一个函数，并作为对象的属性存储。

- 对象方法通过添加 () 调用 (作为一个函数)。

该实例访问了 person 对象的 fullName() 方法:

![image-20240222220036649](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222220036649.png)

##### 访问对象方法

我们可以使用以下语法创建对象方法：

![image-20240222220110203](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222220110203.png)

并可以使用以下语法访问对象方法：

![image-20240222220125476](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222220125476.png)

通常 fullName() 是作为 person 对象的一个方法， fullName 是作为一个属性。

如果使用 fullName 属性，不添加 **()**, 它会返回函数的定义！

### JavaScript 函数

函数是由事件驱动的或者当它被调用时执行的可重复使用的**代码块**。

#### 函数语法

函数就是包裹在花括号中的代码块，前面使用了**关键词** **function**：

```
function functionname()
{
    // 执行代码
}
```

当调用该函数时，会执行函数内的代码。

#### 调用带参数的函数

在调用函数时，我们可以向其传递值，这些值被称为参数。

- 这些参数可以在函数中使用。

- 可以发送任意多的参数，由逗号 (,) 分隔：

```
myFunction(argument1,argument2)
```

声明函数时，把参数作为变量来声明：

```
function myFunction(var1,var2)
{
代码
}
```

变量和参数必须以一致的顺序出现。第一个变量就是第一个被传递的参数的给定的值，以此类推。

![image-20240222220414745](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222220414745.png)

函数使得代码变得更加灵活，当我们使用不同的参数调用函数是，就会给出不同的信息：

![image-20240222220541298](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222220541298.png)

上面的例子会提示 "Welcome Harry Potter, the Wizard" 或 "Welcome Bob, the Builder"。

#### 带有返回值的函数

有时，我们会希望函数将值返回调用它的地方。

通过使用 return 语句就可以实现。

在使用 return 语句时，函数会停止执行，并返回指定的值。

````
function myFunction()
{
    var x=5;
    return x;
}
````

上面的函数会返回值 5。

**注意：** 整个 JavaScript 并不会停止执行，仅仅是函数。JavaScript 将继续执行代码，从调用函数的地方。

函数调用将被返回值取代：

````````
var myVar=myFunction();
````````

myVar 变量的值是 5，也就是函数 "myFunction()" 所返回的值。

即使不把它保存为变量，也可以使用返回值：

````
document.getElementById("demo").innerHTML=myFunction();
````

"demo" 元素的 innerHTML 将成为 5，也就是函数 "myFunction()" 所返回的值。

### JavaScript 作用域

作用域是可访问变量的集合。

#### 局部作用域

变量在函数内声明，变量为局部变量，具有局部作用域。

局部变量：只能在函数内部访问。

![image-20240222220909828](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222220909828.png)

因为局部变量只作用于函数内，所以不同的函数可以使用相同名称的变量。

局部变量在函数开始执行时创建，函数执行完后局部变量会自动销毁。

#### 全局变量

变量在函数外定义，即为全局变量。

全局变量有 **全局作用域**: 网页中所有脚本和函数均可使用。 

![image-20240222220936915](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222220936915.png)

- **!!!**  **如果变量在函数内没有声明（<u>没有使用 var 关键字</u>），该变量为全局变量。**

以下实例中 carName 在函数内，但是为全局变量。

![image-20240222221043860](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240222221043860.png)

### JavaScript 事件

HTML 事件是发生在 HTML 元素上的事情:可以是浏览器行为，也可以是用户行为。

以下是 HTML 事件的实例：

- HTML 页面完成加载
- HTML input 字段改变时
- HTML 按钮被点击

在事件触发时 JavaScript 可以执行一些代码:

- HTML 事件属性可以直接执行 JavaScript 代码
- HTML 事件属性可以调用 JavaScript 函数
- 可以为 HTML 元素指定自己的事件处理程序
- 可以阻止事件的发生。
- 等等 ...

下面是一些常见的HTML事件的列表:

| 事件        | 描述                                 |
| :---------- | :----------------------------------- |
| onchange    | HTML 元素改变                        |
| onclick     | 用户点击 HTML 元素                   |
| onmouseover | 鼠标指针移动到指定的元素上时发生     |
| onmouseout  | 用户从一个 HTML 元素上移开鼠标时发生 |
| onkeydown   | 用户按下键盘按键                     |
| onload      | 浏览器已完成页面的加载               |

### JavaScript 条件语句

在 JavaScript 中，我们可使用以下条件语句：

- **if 语句** - 只有当指定条件为 true 时，使用该语句来执行代码
- **if...else 语句** - 当条件为 true 时执行代码，当条件为 false 时执行其他代码
- **if...else if....else 语句**- 使用该语句来选择多个代码块之一来执行
- **switch 语句** - 使用该语句来选择多个代码块之一来执行

#### if 语句

只有当指定条件为 true 时，该语句才会执行代码。

```
if (*condition*)
{
  *当条件为 true 时执行的代码*
}
```

![image-20240223083745214](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223083745214.png)

#### if...else 语句

使用 if....else 语句在条件为 true 时执行代码，在条件为 false 时执行其他代码。

```
if (condition)
{
    当条件为 true 时执行的代码
}
else
{
    当条件不为 true 时执行的代码
}
```

![image-20240223083828148](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223083828148.png)

#### if...else if...else 语句

使用 if....else if...else 语句来选择多个代码块之一来执行。

```
if (condition1)
{
    当条件 1 为 true 时执行的代码
}
else if (condition2)
{
    当条件 2 为 true 时执行的代码
}
else
{
  当条件 1 和 条件 2 都不为 true 时执行的代码
}
```

![image-20240223083902599](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223083902599.png)

**注：以上用法与C语言类似**

### JavaScript switch 语句

switch 语句用于基于不同的条件来执行不同的动作。

- 使用 switch 语句来选择要执行的多个代码块之一。

```
switch(n)
{
    case 1:
        执行代码块 1
        break;
    case 2:
        执行代码块 2
        break;
    default:
        与 case 1 和 case 2 不同时执行的代码
}
```

#### default 关键词

使用 default 关键词来规定匹配不存在时做的事情：

![image-20240223092019707](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223092019707.png)

### JavaScript for 循环

循环可以将代码块执行指定的次数。

![image-20240223092106515](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223092106515.png)

使用for循环

```javascript
for (var i=0;i<cars.length;i++)
{ 
    document.write(cars[i] + "<br>");
}
```

**不同类型的循环**

JavaScript 支持不同类型的循环：

- **for** - 循环代码块一定的次数
- **for/in** - 循环遍历对象的属性
- **while** - 当指定的条件为 true 时循环指定的代码块
- **do/while** - 同样当指定的条件为 true 时循环指定的代码块

#### for循环

下面是 for 循环的语法：

```
for (语句 1; 语句 2; 语句 3)
{
    被执行的代码块
}
```

- **语句 1** （代码块）开始前执行
- **语句 2** 定义运行循环（代码块）的条件
- **语句 3** 在循环（代码块）已被执行之后执行

#### For/In 循环

JavaScript for/in 语句循环遍历对象的属性：

![image-20240223092420074](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223092420074.png)

#### While 循环

while 循环会在指定条件为真时循环执行代码块。语法如下：

```
while (条件)
{
    需要执行的代码
}
```

**实例**

本例中的循环将继续运行，只要变量 i 小于 5：

![image-20240223092514700](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223092514700.png)

#### do/while 循环

do/while 循环是 while 循环的变体。该循环会在检查条件是否为真之前执行一次代码块，然后如果条件为真的话，就会重复这个循环。

语法如下：

```
do
{
    需要执行的代码
}
while (条件);
```

**实例**

下面的例子使用 do/while 循环。该循环至少会执行一次，即使条件为 false 它也会执行一次，因为代码块会在条件被测试前执行：

![image-20240223092607173](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223092607173.png)

### JavaScript typeof, null, 和 undefined

#### typeof 操作符

我们可以用 typeof 操作符来检测变量的数据类型。

![image-20240223092731118](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223092731118.png)

#### null

在 JavaScript 中 null 表示 "什么都没有"。

null是一个只有一个值的特殊类型。表示一个空对象引用。

**注**：用 typeof 检测 null 返回是**object**。

#### undefined

在 JavaScript 中, **undefined** 是一个没有设置值的变量。

**typeof** 一个没有值的变量会返回 **undefined**。

#### undefined 和 null 的区别

![image-20240223092831120](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223092831120.png)

### JavaScript 类型转换

**数据类型**

在 JavaScript 中有 6 种不同的数据类型：

- string
- number
- boolean
- object
- function
- symbol

3 种对象类型：

- Object
- Date
- Array

2 个不包含任何值的数据类型：

- null
- undefined

#### 将数字转换为字符串

全局方法 **String()** 可以将数字转换为字符串。

该方法可用于任何类型的数字，字母，变量，表达式：

![image-20240223093123042](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223093123042.png)

Number 方法 **toString()** 也是有同样的效果。

![image-20240223093140225](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223093140225.png)

#### 将布尔值转换为字符串

全局方法 **String()** 可以将布尔值转换为字符串。

![image-20240223093203349](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223093203349.png)

Boolean 方法 **toString()** 也有相同的效果。

![image-20240223093214953](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223093214953.png)

#### 将日期转换为字符串

Date() 返回字符串。

![image-20240223093234062](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223093234062.png)

全局方法 String() 可以将日期对象转换为字符串。

![image-20240223093245990](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223093245990.png)

Date 方法 **toString()** 也有相同的效果。

![image-20240223093259862](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223093259862.png)

#### 将字符串转换为数字

全局方法 **Number()** 可以将字符串转换为数字。

字符串包含数字(如 "3.14") 转换为数字 (如 3.14).

空字符串转换为 0。

其他的字符串会转换为 NaN (不是个数字)。

![image-20240223093317411](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223093317411.png)

#### 一元运算符 +

**Operator +** 可用于将变量转换为数字：

![image-20240223093337514](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223093337514.png)

**注**：如果变量不能转换，它仍然会是一个数字，但值为 **NaN** ！！！(不是一个数字):

![image-20240223093409721](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223093409721.png)

#### 将布尔值转换为数字

全局方法 **Number()** 可将布尔值转换为数字。

![image-20240223093425605](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223093425605.png)

#### 将日期转换为数字

全局方法 **Number()** 可将日期转换为数字。

![image-20240223093451871](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223093451871.png)

日期方法 **getTime()** 也有相同的效果。

![image-20240223093504906](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223093504906.png)

## 四.URL与HTTP

### URL

先来简单了解一下URL，**URL**就是统一资源定位器(**U**niform **R**esource **L**ocators)的简称，URL 是一个网页地址。

- URL可以由字母组成，如"runoob.com"，或互联网协议（IP）地址： 192.68.20.50。
- 大多数人进入网站使用网站域名来访问，因为 名字比数字更容易记住。

当我们点击 HTML 页面中的某个链接时，对应的 <a> 标签指向万维网上的一个地址。

- 而一个统一资源定位器(URL) 用于定位万维网上的文档。

- 一个网页地址实例: http://www.runoob.com/html/html-tutorial.html 语法规则:

```
scheme://host.domain:port/path/filename
```

说明:

- scheme - 定义因特网服务的类型。最常见的类型是 http
- host - 定义域主机（http 的默认主机是 www）
- domain - 定义因特网域名，比如 runoob.com
- :port - 定义主机上的端口号（http 的默认端口号是 80）
- path - 定义服务器上的路径（如果省略，则文档必须位于网站的根目录中）。
- filename - 定义文档/资源的名称

### HTTP

- HTTP 协议是 Hyper Text Transfer Protocol（超文本传输协议）的缩写，是用于从万维网（ WWW:World Wide Web ）服务器传输超文本到本地浏览器的传送协议。
- HTTP 是一个基于 TCP/IP 通信协议来传递数据（HTML 文件、图片文件、查询结果等）。
- HTTPS 协议是 HyperText Transfer Protocol Secure（超文本传输安全协议）的缩写，是一种通过计算机网络进行安全通信的传输协议。
- HTTPS 经由 HTTP 进行通信，但利用 SSL/TLS 来加密数据包，HTTPS 开发的主要目的，是提供对网站服务器的身份认证，保护交换资料的隐私与完整性。
- HTTP 的 URL 是由 **http://** 起始与默认使用端口 **80**，而 HTTPS 的 URL 则是由 **https://** 起始与默认使用端口**443**。

#### HTTP 工作原理

HTTP 协议工作于客户端-服务端架构上。

- 浏览器作为 HTTP 客户端通过 URL 向 HTTP 服务端即 WEB 服务器发送所有请求。

- Web 服务器有：Apache 服务器，IIS 服务器（Internet Information Services）等。

Web 服务器根据接收到的请求后，向客户端发送响应信息。

- HTTP 默认端口号为 **80**，但是你也可以改为 **8080** 或者其他端口。

#### **HTTP 三点注意事项：**

- HTTP 是**无连接**：无连接的含义是限制每次连接只处理一个请求，服务器处理完客户的请求，并收到客户的应答后，即断开连接，采用这种方式可以<u>节省传输时间</u>。
- HTTP 是**媒体独立**的：这意味着，只要客户端和服务器知道如何处理的数据内容，任何类型的数据都可以通过HTTP发送，客户端以及服务器指定使用适合的 MIME-type 内容类型。
- HTTP 是**无状态**：HTTP 协议是无状态协议，无状态是指协议对于事务处理没有记忆能力，缺少状态意味着如果后续处理需要前面的信息，则它必须重传，这样可能导致每次连接传送的数据量增大，另一方面，在服务器不需要先前信息时它的应答就较快。

以下图表展示了 HTTP 协议通信流程：

![cgiarch](https://www.runoob.com/wp-content/uploads/2013/11/cgiarch.gif)

#### HTTP 消息结构

*HTTP是基于客户端/服务端（C/S）的架构模型，通过一个可靠的链接来交换信息，是一个无状态的请求/响应协议。*

*一个HTTP"客户端"是一个应用程序（Web浏览器或其他任何客户端），通过连接到服务器达到向服务器发送一个或多个HTTP的请求的目的。*

*一个HTTP"服务器"同样也是一个应用程序（通常是一个Web服务，如Apache Web服务器或IIS服务器等），通过接收客户端的请求并向客户端发送HTTP响应数据。*

*HTTP使用统一资源标识符（Uniform Resource Identifiers, URI）来传输数据和建立连接。*

*一旦建立连接后，数据消息就通过类似Internet邮件所使用的格式[RFC5322]和多用途Internet邮件扩展（MIME）[RFC2045]来传送。*

- **客户端请求消息**

客户端发送一个HTTP请求到服务器的请求消息包括以下格式：请求行（request line）、请求头部（header）、空行和请求数据四个部分组成，下图给出了请求报文的一般格式。

![img](https://www.runoob.com/wp-content/uploads/2013/11/2012072810301161.png)

- **服务器响应消息**

HTTP响应也由四个部分组成，分别是：状态行、消息报头、空行和响应正文。

![img](https://www.runoob.com/wp-content/uploads/2013/11/httpmessage.jpg)

**实例**

下面实例是一点典型的使用GET来传递数据的实例：

客户端请求：

![image-20240223152307256](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223152307256.png)

服务端响应:

![image-20240223152324244](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223152324244.png)

输出结果：

![image-20240223152335680](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223152335680.png)

#### HTTP 请求方法

根据 HTTP 标准，HTTP 请求可以使用多种请求方法。

HTTP1.0 定义了三种请求方法： **GET**, **POST** 和 HEAD 方法。

HTTP1.1 新增了六种请求方法：OPTIONS、PUT、PATCH、DELETE、TRACE 和 CONNECT 方法。

| 序号 | 方法     | 描述                                                         |
| :--- | :------- | :----------------------------------------------------------- |
| 1    | **GET**  | 请求指定的页面信息，并返回实体主体。                         |
| 2    | HEAD     | 类似于 GET 请求，只不过返回的响应中没有具体的内容，用于获取报头 |
| 3    | **POST** | 向指定资源提交数据进行处理请求（例如提交表单或者上传文件）。数据被包含在请求体中。POST 请求可能会导致新的资源的建立和/或已有资源的修改。 |
| 4    | PUT      | 从客户端向服务器传送的数据取代指定的文档的内容。             |
| 5    | DELETE   | 请求服务器删除指定的页面。                                   |
| 6    | CONNECT  | HTTP/1.1 协议中预留给能够将连接改为管道方式的代理服务器。    |
| 7    | OPTIONS  | 允许客户端查看服务器的性能。                                 |
| 8    | TRACE    | 回显服务器收到的请求，主要用于测试或诊断。                   |
| 9    | PATCH    | 是对 PUT 方法的补充，用来对已知资源进行局部更新 。           |

#### HTTPS 作用

HTTPS 的主要作用是在不安全的网络上创建一个安全信道，并可在使用适当的加密包和服务器证书可被验证且可被信任时，对窃听和中间人攻击提供合理的防护。

HTTPS 的信任基于预先安装在操作系统中的证书颁发机构（CA）。

因此，与一个网站之间的 HTTPS 连线仅在这些情况下可被信任：

- 浏览器正确地实现了 HTTPS 且操作系统中安装了正确且受信任的证书颁发机构；
- 证书颁发机构仅信任合法的网站；
- 被访问的网站提供了一个有效的证书，也就是说它是一个由操作系统信任的证书颁发机构签发的（大部分浏览器会对无效的证书发出警告）；
- 该证书正确地验证了被访问的网站（例如，访问 [https://www.runoob.com](https://www.runoob.com/) 时收到了签发给 www.runoob.com 而不是其它域名的证书）；
- 此协议的加密层（SSL/TLS）能够有效地提供认证和高强度的加密。

## 五.Linux命令

### Linux 用户管理

Linux系统是一个多用户多任务的分时操作系统，任何一个要使用系统资源的用户，都必须首先向系统管理员申请一个账号，然后以这个账号的身份进入系统。

用户的账号一方面可以帮助系统管理员对使用系统的用户进行跟踪，并控制他们对系统资源的访问；另一方面也可以帮助用户组织文件，并为用户提供安全性保护。

每个用户账号都拥有一个唯一的用户名和各自的口令。

用户在登录时键入正确的用户名和口令后，就能够进入系统和自己的主目录。

实现用户账号的管理，要完成的工作主要有如下几个方面：

- 用户账号的添加、删除与修改。
- 用户口令的管理。
- 用户组的管理。

#### 1、添加新的用户账号使用useradd命令，其语法如下：

```
useradd 选项 用户名
```

参数说明：

- 选项:

  - -c comment 指定一段注释性描述。
  - -d 目录 指定用户主目录，如果此目录不存在，则同时使用-m选项，可以创建主目录。
  - -g 用户组 指定用户所属的用户组。
  - -G 用户组，用户组 指定用户所属的附加组。
  - -s Shell文件 指定用户的登录Shell。
  - -u 用户号 指定用户的用户号，如果同时有-o选项，则可以重复使用其他用户的标识号。

- 用户名:

  指定新账号的登录名。

**实例1**

```
# useradd –d  /home/sam -m sam
```

此命令创建了一个用户sam，其中-d和-m选项用来为登录名sam产生一个主目录 /home/sam（/home为默认的用户主目录所在的父目录）。

**实例2**

```
# useradd -s /bin/sh -g group –G adm,root gem
```

此命令新建了一个用户gem，该用户的登录Shell是 `/bin/sh`，它属于group用户组，同时又属于adm和root用户组，其中group用户组是其主组。

这里可能新建组：`#groupadd group及groupadd adm`

增加用户账号就是在/etc/passwd文件中为新用户增加一条记录，同时更新其他系统文件如/etc/shadow, /etc/group等。

Linux提供了集成的系统管理工具userconf，它可以用来对用户账号进行统一管理。

#### 2、删除帐号

如果一个用户的账号不再使用，可以从系统中删除。删除用户账号就是要将/etc/passwd等系统文件中的该用户记录删除，必要时还删除用户的主目录。

删除一个已有的用户账号使用`userdel`命令，其格式如下：

```
userdel 选项 用户名
```

常用的选项是 **-r**，它的作用是把用户的主目录一起删除。

例如：

```
# userdel -r sam
```

此命令删除用户sam在系统文件中（主要是/etc/passwd, /etc/shadow, /etc/group等）的记录，同时删除用户的主目录。

#### 3、修改帐号

修改用户账号就是根据实际情况更改用户的有关属性，如用户号、主目录、用户组、登录Shell等。

修改已有用户的信息使用`usermod`命令，其格式如下：

```
usermod 选项 用户名
```

常用的选项包括`-c, -d, -m, -g, -G, -s, -u以及-o等`，这些选项的意义与`useradd`命令中的选项一样，可以为用户指定新的资源值。

另外，有些系统可以使用选项：-l 新用户名

这个选项指定一个新的账号，即将原来的用户名改为新的用户名。

例如：

```
# usermod -s /bin/ksh -d /home/z –g developer sam
```

此命令将用户sam的登录Shell修改为ksh，主目录改为/home/z，用户组改为developer。

#### 4、用户口令的管理

用户管理的一项重要内容是用户口令的管理。用户账号刚创建时没有口令，但是被系统锁定，无法使用，必须为其指定口令后才可以使用，即使是指定空口令。

指定和修改用户口令的Shell命令是`passwd`。超级用户可以为自己和其他用户指定口令，普通用户只能用它修改自己的口令。命令的格式为：

```
passwd 选项 用户名
```

可使用的选项：

- -l 锁定口令，即禁用账号。
- -u 口令解锁。
- -d 使账号无口令。
- -f 强迫用户下次登录时修改口令。

如果默认用户名，则修改当前用户的口令。

例如，假设当前用户是sam，则下面的命令修改该用户自己的口令：

```
$ passwd 
Old password:****** 
New password:******* 
Re-enter new password:*******
```

如果是超级用户，可以用下列形式指定任何用户的口令：

```
# passwd sam 
New password:******* 
Re-enter new password:*******
```

普通用户修改自己的口令时，passwd命令会先询问原口令，验证后再要求用户输入两遍新口令，如果两次输入的口令一致，则将这个口令指定给用户；而超级用户为用户指定口令时，就不需要知道原口令。

为了系统安全起见，用户应该选择比较复杂的口令，例如最好使用8位长的口令，口令中包含有大写、小写字母和数字，并且应该与姓名、生日等不相同。

为用户指定空口令时，执行下列形式的命令：

```
# passwd -d sam
```

此命令将用户 sam 的口令删除，这样用户 sam 下一次登录时，系统就不再允许该用户登录了。

passwd 命令还可以用 -l(lock) 选项锁定某一用户，使其不能登录，例如：

```
# passwd -l sam
```

### Linux系统用户组的管理

每个用户都有一个用户组，系统可以对一个用户组中的所有用户进行集中管理。不同Linux 系统对用户组的规定有所不同，如Linux下的用户属于与它同名的用户组，这个用户组在创建用户时同时创建。

用户组的管理涉及用户组的添加、删除和修改。组的增加、删除和修改实际上就是对/etc/group文件的更新。

#### 1、增加一个新的用户组使用groupadd命令。其格式如下：

```
groupadd 选项 用户组
```

可以使用的选项有：

- -g GID 指定新用户组的组标识号（GID）。
- -o 一般与-g选项同时使用，表示新用户组的GID可以与系统已有用户组的GID相同。

**实例1：**

```
# groupadd group1
```

此命令向系统中增加了一个新组group1，新组的组标识号是在当前已有的最大组标识号的基础上加1。

**实例2：**

```
# groupadd -g 101 group2
```

此命令向系统中增加了一个新组group2，同时指定新组的组标识号是101。

#### 2、如果要删除一个已有的用户组，使用groupdel命令，其格式如下：

```
groupdel 用户组
```

例如：

```
# groupdel group1
```

此命令从系统中删除组group1。

#### 3、修改用户组的属性使用groupmod命令。其语法如下：

```
groupmod 选项 用户组
```

常用的选项有：

- -g GID 为用户组指定新的组标识号。
- -o 与-g选项同时使用，用户组的新GID可以与系统已有用户组的GID相同。
- -n新用户组 将用户组的名字改为新名字

**实例1：**

```
# groupmod -g 102 group2
```

此命令将组group2的组标识号修改为102。

**实例2：**

```
# groupmod –g 10000 -n group3 group2
```

此命令将组group2的标识号改为10000，组名修改为group3。

#### 4、如果一个用户同时属于多个用户组，那么用户可以在用户组之间切换，以便具有其他用户组的权限。

用户可以在登录后，使用命令newgrp切换到其他用户组，这个命令的参数就是目的用户组。例如：

```
$ newgrp root
```

这条命令将当前用户切换到root用户组，前提条件是root用户组确实是该用户的主组或附加组。类似于用户账号的管理，用户组的管理也可以通过集成的系统管理工具来完成。

### Linux 系统目录结构

登录系统后，在当前命令窗口下输入命令：

```
 ls / 
```

会看到如下图所示:

![img](https://www.runoob.com/wp-content/uploads/2014/06/4_20.png)

树状目录结构：

![img](https://www.runoob.com/wp-content/uploads/2014/06/d0c50-linux2bfile2bsystem2bhierarchy.jpg)

以下是对这些目录的解释：

- **/bin**：
  bin 是 Binaries (二进制文件) 的缩写, 这个目录存放着最经常使用的命令。

- **/boot：**
  这里存放的是启动 Linux 时使用的一些核心文件，包括一些连接文件以及镜像文件。

- **/dev ：**
  dev 是 Device(设备) 的缩写, 该目录下存放的是 Linux 的外部设备，在 Linux 中访问设备的方式和访问文件的方式是相同的。

- **/etc：**
  etc 是 Etcetera(等等) 的缩写,这个目录用来存放所有的系统管理所需要的配置文件和子目录。

- **/home**：
  用户的主目录，在 Linux 中，每个用户都有一个自己的目录，一般该目录名是以用户的账号命名的，如上图中的 alice、bob 和 eve。

- **/lib**：
  lib 是 Library(库) 的缩写这个目录里存放着系统最基本的动态连接共享库，其作用类似于 Windows 里的 DLL 文件。几乎所有的应用程序都需要用到这些共享库。

- **/lost+found**：
  这个目录一般情况下是空的，当系统非法关机后，这里就存放了一些文件。

- **/media**：
  linux 系统会自动识别一些设备，例如U盘、光驱等等，当识别后，Linux 会把识别的设备挂载到这个目录下。

- **/mnt**：
  系统提供该目录是为了让用户临时挂载别的文件系统的，我们可以将光驱挂载在 /mnt/ 上，然后进入该目录就可以查看光驱里的内容了。

- **/opt**：
  opt 是 optional(可选) 的缩写，这是给主机额外安装软件所摆放的目录。比如你安装一个ORACLE数据库则就可以放到这个目录下。默认是空的。

- **/proc**：
  proc 是 Processes(进程) 的缩写，/proc 是一种伪文件系统（也即虚拟文件系统），存储的是当前内核运行状态的一系列特殊文件，这个目录是一个虚拟的目录，它是系统内存的映射，我们可以通过直接访问这个目录来获取系统信息。
  这个目录的内容不在硬盘上而是在内存里，我们也可以直接修改里面的某些文件，比如可以通过下面的命令来屏蔽主机的ping命令，使别人无法ping你的机器：

  ```
  echo 1 > /proc/sys/net/ipv4/icmp_echo_ignore_all
  ```

- **/root**：
  该目录为系统管理员，也称作超级权限者的用户主目录。

- **/sbin**：
  s 就是 Super User 的意思，是 Superuser Binaries (超级用户的二进制文件) 的缩写，这里存放的是系统管理员使用的系统管理程序。

- **/selinux**：
   这个目录是 Redhat/CentOS 所特有的目录，Selinux 是一个安全机制，类似于 windows 的防火墙，但是这套机制比较复杂，这个目录就是存放selinux相关的文件的。

- **/srv**：
   该目录存放一些服务启动之后需要提取的数据。

- **/sys**：

  这是 Linux2.6 内核的一个很大的变化。该目录下安装了 2.6 内核中新出现的一个文件系统 sysfs 。

  sysfs 文件系统集成了下面3种文件系统的信息：针对进程信息的 proc 文件系统、针对设备的 devfs 文件系统以及针对伪终端的 devpts 文件系统。

  该文件系统是内核设备树的一个直观反映。

  当一个内核对象被创建的时候，对应的文件和目录也在内核对象子系统中被创建。

- **/tmp**：
  tmp 是 temporary(临时) 的缩写这个目录是用来存放一些临时文件的。

- **/usr**：
   usr 是 unix shared resources(共享资源) 的缩写，这是一个非常重要的目录，用户的很多应用程序和文件都放在这个目录下，类似于 windows 下的 program files 目录。

- **/usr/bin：**
  系统用户使用的应用程序。

- **/usr/sbin：**
  超级用户使用的比较高级的管理程序和系统守护程序。

- **/usr/src：**
  内核源代码默认的放置目录。

- **/var**：
  var 是 variable(变量) 的缩写，这个目录中存放着在不断扩充着的东西，我们习惯将那些经常被修改的目录放在这个目录下。包括各种日志文件。

- **/run**：
  是一个临时文件系统，存储系统启动以来的信息。当系统重启时，这个目录下的文件应该被删掉或清除。如果你的系统上有 /var/run 目录，应该让它指向 run。

在 Linux 系统中，有几个目录是比较重要的，平时需要注意不要误删除或者随意更改内部文件。

**/etc**： 上边也提到了，这个是系统中的配置文件，如果你更改了该目录下的某个文件可能会导致系统不能启动。

**/bin, /sbin, /usr/bin, /usr/sbin**: 这是系统预设的执行文件的放置目录，比如 **ls** 就是在 **/bin/ls** 目录下的。

值得提出的是 **/bin**、**/usr/bin** 是给系统用户使用的指令（除 root 外的通用用户），而/sbin, /usr/sbin 则是给 root 使用的指令。

**/var**： 这是一个非常重要的目录，系统上跑了很多程序，那么每个程序都会有相应的日志产生，而这些日志就被记录到这个目录下，具体在 /var/log 目录下，另外 mail 的预设放置也是在这里。

### 处理目录的常用命令

最后，让我们来看看几个常见的处理目录的命令吧：

- ls（英文全拼：list files）: 列出目录及文件名
- cd（英文全拼：change directory）：切换目录
- pwd（英文全拼：print work directory）：显示目前的目录
- mkdir（英文全拼：make directory）：创建一个新的目录
- rmdir（英文全拼：remove directory）：删除一个空的目录
- cp（英文全拼：copy file）: 复制文件或目录
- rm（英文全拼：remove）: 删除文件或目录
- mv（英文全拼：move file）: 移动文件与目录，或修改文件与目录的名称

#### ls (列出目录)

在Linux系统当中， ls 命令可能是最常被运行的。

语法：

![image-20240223185453707](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223185453707.png)

选项与参数：

- **-a** ：全部的文件，连同隐藏文件( 开头为 . 的文件) 一起列出来(常用)
- **-d** ：仅列出目录本身，而不是列出目录内的文件数据(常用)
- **-l** ：长数据串列出，包含文件的属性与权限等等数据；(常用)

将目录下的所有文件列出来(含属性与隐藏档)

![image-20240223185746474](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223185746474.png)

#### cd (切换目录)

cd是Change Directory的缩写，这是用来变换工作目录的命令。

语法：

![image-20240223185534747](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223185534747.png)

![image-20240223185546011](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223185546011.png)

#### pwd (显示目前所在的目录)

pwd 是 **P**rint **W**orking **D**irectory 的缩写，也就是显示目前所在目录的命令。

![image-20240223185623155](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223185623155.png)

选项与参数：

- **-P** ：显示出确实的路径，而非使用链接 (link) 路径。

实例：单纯显示出目前的工作目录：

![image-20240223185639347](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223185639347.png)

实例显示出实际的工作目录，而非链接档本身的目录名而已。

![image-20240223185811352](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223185811352.png)

#### mkdir (创建新目录)

如果想要创建新的目录的话，那么就使用mkdir (make directory)吧。

语法：

![image-20240223185835803](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223185835803.png)

选项与参数：

- -m ：配置文件的权限喔！直接配置，不需要看默认权限 (umask) 的脸色～
- -p ：帮助你直接将所需要的目录(包含上一级目录)递归创建起来！

实例：请到/tmp底下尝试创建数个新目录看看：

![image-20240223185848207](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223185848207.png)

加了这个 -p 的选项，可以自行帮你创建多层目录！

实例：创建权限为 **rwx--x--x** 的目录。

![image-20240223190733343](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223190733343.png)

上面的权限部分，如果没有加上 -m 来强制配置属性，系统会使用默认属性。

如果我们使用 -m ，如上例我们给予 -m 711 来给予新的目录 drwx--x--x 的权限。

#### rmdir (删除空的目录)

语法：

![image-20240223190748835](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223190748835.png)

选项与参数：

- **-p ：**从该目录起，一次删除多级空目录

删除 runoob 目录

![image-20240223190759975](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223190759975.png)

将 mkdir 实例中创建的目录(/tmp 底下)删除掉！

![image-20240223190812683](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223190812683.png)

利用 -p 这个选项，立刻就可以将 test1/test2/test3/test4 一次删除。

不过要注意的是，这个 rmdir 仅能删除空的目录，你可以使用 rm 命令来删除非空目录。

#### cp (复制文件或目录)

cp 即拷贝文件和目录。

语法:

![image-20240223190839932](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223190839932.png)

选项与参数：

- **-a：**相当於 -pdr 的意思，至於 pdr 请参考下列说明；(常用)
- **-d：**若来源档为链接档的属性(link file)，则复制链接档属性而非文件本身；
- **-f：**为强制(force)的意思，若目标文件已经存在且无法开启，则移除后再尝试一次；
- **-i：**若目标档(destination)已经存在时，在覆盖时会先询问动作的进行(常用)
- **-l：**进行硬式链接(hard link)的链接档创建，而非复制文件本身；
- **-p：**连同文件的属性一起复制过去，而非使用默认属性(备份常用)；
- **-r：**递归持续复制，用於目录的复制行为；(常用)
- **-s：**复制成为符号链接档 (symbolic link)，亦即『捷径』文件；
- **-u：**若 destination 比 source 旧才升级 destination ！

用 root 身份，将 root 目录下的 .bashrc 复制到 /tmp 下，并命名为 bashrc

![image-20240223190857930](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223190857930.png)

#### rm (移除文件或目录)

语法：

![image-20240223190909295](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223190909295.png)

选项与参数：

- -f ：就是 force 的意思，忽略不存在的文件，不会出现警告信息；
- -i ：互动模式，在删除前会询问使用者是否动作
- -r ：递归删除啊！最常用在目录的删除了！这是非常危险的选项！！！
- 

将刚刚在 cp 的实例中创建的 bashrc 删除掉！

![image-20240223190920060](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223190920060.png)

如果加上 -i 的选项就会主动询问喔，避免你删除到错误的档名！

#### mv (移动文件与目录，或修改名称)

语法：

![image-20240223190932844](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223190932844.png)

选项与参数：

- -f ：force 强制的意思，如果目标文件已经存在，不会询问而直接覆盖；
- -i ：若目标文件 (destination) 已经存在时，就会询问是否覆盖！
- -u ：若目标文件已经存在，且 source 比较新，才会升级 (update)

复制一文件，创建一目录，将文件移动到目录中

![image-20240223190945775](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223190945775.png)

将刚刚的目录名称更名为 mvtest2：

![image-20240223191009767](C:\Users\30323\AppData\Roaming\Typora\typora-user-images\image-20240223191009767.png)
