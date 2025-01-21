# 今天把昨天的内容，老师把正确的答案给出来了，做一个对比。发现区别是在语言表达上的区别。自己的更加偏向于自然语言，老师的是做程序语言直接表达。

## 1."HTML 是什么?它有什么用?" 

HTML就是用一种超文本标记语言（可以说是某一种计算机能读懂的语言）来描述我们我们日常生活中看到的网页

## 2.=="HTML 文件的基本结构是什么样的?"== 

基础结构是由一个文档说明作为最开始的标记，这样不同的浏览器可以直接识别是哪个版本的HTML。然后完整的HTML页面由头部元素，和内容界面组成。

head里面包含了文档的一些基础数据，比如utf-8（应该是meta元素，这些给全文一些基础的通用概念），还有title，即说明整个文档的的标题，

内容界面就是body 版块，body元素里面就包含了我们平时看到网页的呈现的部分

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>网页标题</title>
</head>
<body>
    <h1>这是网页内容</h1>
    <p>这是一个段落</p >
</body>
</html>

## 3.=="常用的 HTML 标签有哪些?怎么用?" "==

常见的标签主要是标题的标签，段落的标签，图片、链接的标签，有序列表和无序列表。

这里面有单标签和双标签。图片和链接的标签后面一般都会有属性。

```
<h1>一级标题</h1>
<h2>二级标题</h2>
<h3>三级标题</h3>
<h4>四级标题</h4>
<h5>五级标题</h5>
<h6>六级标题</h6>
<p>这是一个段落</p>
<a href="https://www.example.com">这是一个链接</a>
<img src="image.jpg" alt="图片描述">


<!-- 标题标签 h1最大，h6最小 -->
<h1>一级标题</h1>
<h2>二级标题</h2>

<!-- 段落标签 -->
<p>这是一个段落</p >

<!-- 加粗和斜体 -->
<strong>加粗文字</strong>
<em>斜体文字</em>

<!-- 换行 -->
<br>

<!-- 水平线 -->
<hr>
```

## 4."如何在 HTML 中插入图片和链接?" 

<img src="url" alt="some_text">

就是img这个标签是空标签，所以一定会在后面用src这个源属性来找图片的位置（url），后面那个alt是替换文本的属性，相当于是如果图片加载不出来，就会用另外一个方式来提醒

![1737466911600](H:\微信文件\WeChat Files\wxid_wqs36adrwvzm21\FileStorage\Temp\1737466911600.png)

![1737467067726](H:\微信文件\WeChat Files\wxid_wqs36adrwvzm21\FileStorage\Temp\1737467067726.png)

## ==5."什么是语义化标签?为什么要使用它们?"== 

语义化标签就是有意思的标签，比如常用的img，table，form这些词一看就知道他的内容是啥。就是为了更改描述的更清楚，大家统一一个默认的语言规则来沟通

![1737467032119](H:\微信文件\WeChat Files\wxid_wqs36adrwvzm21\FileStorage\Temp\1737467032119.png)

![](H:\微信文件\WeChat Files\wxid_wqs36adrwvzm21\FileStorage\Temp\1737467113032.png

### 6."div 和 span 的区别是什么?什么时候用它们?" 

div是一个块级元素，比如说有一整个大块的内容，可以用这个div。span有是行内的元素，就是可以在一句话里面添加。使用的时候，其实div也可以当作span来用，但是div肯定是换行，span用在一句话里面能够强调这句话中的某一些内容。两个分工不同

![1737466933978](H:\微信文件\WeChat Files\wxid_wqs36adrwvzm21\FileStorage\Temp\1737466933978.png)



## ==1."什么是 HTML 列表?有几种类型?" 有序列表、无序列表和定义列表,它们各有特点和适用场景。==

有三个列表，有序，无序，自定义列表

理解起来也是字面意思，有序列表会使用数字来进行标记，无序列表会用一个. 点来标记。自定义也可以输入一个-来标识，看实际的需要。

<!-- 无序列表 -->

<ul>
    <li>苹果</li>
    <li>香蕉</li>
</ul>
<!-- 有序列表 -->

<ol>
    <li>第一步</li>
    <li>第二步</li>
</ol>

## 2."HTML5 新特性有哪些?带来了什么改变?" 

从1991年HTML开始，后面有HTML+，HTML2.0,HTML3.2,HTML4.01,XHTML1.0,HTML5，XHTML5这些不同的类型。目前听大家分享的，以及看不同的版本中的文档说明，一定是HTML5更简洁。然后引用一些语义化标签，大家读这个网页的时候也更加清楚。

其他的就是在表单，在网页中嵌入音频，视频，图像，存储等方面的功能优化。

## 1."如何创建表格?表格的结构是什么样的?" 

创建表格就用用表格标签，<table>,然后加上相关属性的其他标签。比如说有的有表头，有的是行的标签，有的是列的标签。

每个表格均有若干行（由 **<tr>** 标签定义），每行被分割为若干单元格（由 **<td>** 标签定义），表格可以包含标题行（**<th>**）用于定义列的标题。

- **tr**：tr 是 table row 的缩写，表示表格的一行。
- **td**：td 是 table data 的缩写，表示表格的数据单元格。
- **th**：th 是 table header的缩写，表示表格的表头单元格。

数据单元格可以包含文本、图片、列表、段落、表单、水平线、表格等等。

![1737466961165](H:\微信文件\WeChat Files\wxid_wqs36adrwvzm21\FileStorage\Temp\1737466961165.png)

![image-20250120221325072](C:\Users\10263\AppData\Roaming\Typora\typora-user-images\image-20250120221325072.png)

## ==2."HTML 表单是什么?如何收集用户输入?" 表单是收集用户信息的重要工具,包括文本框、按钮、复选框等多种输入方式。==

表单就是用于收集用户的信息，类似于图示的信息

![image-20250120222117675](C:\Users\10263\AppData\Roaming\Typora\typora-user-images\image-20250120222117675.png)

![1737467002251](H:\微信文件\WeChat Files\wxid_wqs36adrwvzm21\FileStorage\Temp\1737467002251.png)

## 3."如何在 HTML 中嵌入视频和音频?"

自己理解下来，可以用a元素插入链接的方式完成这个嵌入。但是视频和音频本身也有对应的标签。

音频：audio，视频：video（这个应该也是HTML5的新特性，不需要依赖其他的插件了） ，一般都会跟一个能够控制音量的，暂停开始，或者是进度条的一个控件。示例里面还有更多的一个标签，就是source。就是确保不同类型的音频/视频能够被识别到，也是被这个网页的浏览器能够兼容对应的内容。

## 4."如何让网页适应不同的设备屏幕?"

这个是自己在V0设计的时候的新体验，最开始的时候，一直以为只有是网页版的呈现，后来我了解了下，点F12，里面可以选择不同的设备类型，这个时候网页内容自动开始适应不同设备的屏幕。

在执行上，自己检索到一些指令。先po下html中的标签（这个里面也是涉及到meta元素，就是想起来老师说的一句话，用数据描述数据的元素）

 使用视口元标签（Viewport Meta Tag）

确保网页在移动设备上有正确的缩放比例，通过在HTML文档的 `<head>` 部分添加视口元标签：

```
<meta name="viewport" content="width=device-width, initial-scale=1">
```

这条语句告诉浏览器以设备的实际宽度为基准进行渲染，并设置初始缩放级别为1。 （也有其他的方式）

![1737467113032](H:\微信文件\WeChat Files\wxid_wqs36adrwvzm21\FileStorage\Temp\1737467113032.png)

## 5."SEO 友好的 HTML 结构是什么样的? 

这个问题还是要先清楚一下SEO是什么：SEO 是 "Search Engine Optimization"（搜索引擎优化）的缩写，它是一系列方法和技术，旨在提高网站在搜索引擎自然（非广告）搜索结果中的可见性和排名。SEO 的主要目标是增加来自搜索引擎的有机流量，从而提升网站的知名度和潜在客户或用户的数量。

我自己的理解就是怎么写好这个网页，让浏览器能够更好的抓到我的这个网站推送给到客户，以增加客户的注意力。

其实站在现在的学习基础上考虑下，就是标签要怎么分配，现在来看就是标题标签，还有head元素里面的meta的元素。还有url（对应的文件地址）的优化。

然后还有站在客户使用层面的解读，就是一些表单录入信息的方便性，读取段落文字中的各样列表是否简单易读。等等

## 6."如何调试 HTML?常见的错误有哪些?"

有人工审查，但是现在肯定用工具了。

常见的错误：我自己操作过程中，就是双标签的闭合，还有英文单词是否正确，还有大小写，中文状态以及英文状态下的标点符号的区别。还有在学标签嵌套的时候，可能也会搞混。还有游戏额字符实体的应用等。



常见的 HTML 错误包括:

标签闭合错误

忘记关闭标签,如 <div> 没有对应的 </div>
标签嵌套顺序错误,如 <p><span></p ></span>
自闭合标签使用错误,如 <img> 应该写成 < img />


属性语法错误

属性值缺少引号,如 <div class=container>
属性名重复使用
布尔属性语法错误,如 disabled="false"


标签使用不当

在不允许的位置使用某些标签,如 <div> 内直接放 <tr>
特定标签的父子关系错误,如 <ul> 下直接放 <div>
使用已废弃的标签或属性


ID 和类名错误

ID 重复使用(ID 必须唯一)
类名或 ID 命名不规范,如使用特殊字符


文档结构错误

缺少必要的文档声明 <!DOCTYPE html>
<head> 或 <body> 标签缺失或位置错误
字符编码设置错误或缺失