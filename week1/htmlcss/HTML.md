## HTML定义
HTML（超文本标记语言——HyperText Markup Language）

**HTML & CSS & Javascript关系**

**HTML**：网页的内容和基本布局

**CSS**：网页的表现与展示效果

**Javascript**：网页的功能与行为

## 在线编辑工具
- [JSBin](http://jsbin.com/?html,js,output)
- [Thimble](https://thimble.mozilla.org/zh-CN/)

## HTML基础介绍
### HTML元素
![HTML 元素](/images/html-element.png)

#### 嵌套元素

#### 块级元素和内联元素
**块级元素**：在页面中以块的形式展现 —— 相对与其前面的内容它会出现在新的一行，其后的内容也会被挤到下一行展现

**内联元素**：通常出现在块级元素中并包裹文档内容的一小部分

一个以block形式展现的块级元素不会被嵌套进内联元素中，但可以嵌套在其它块级元素中。

**默认浏览器有默认的展示元素的CSS样式**

#### 空元素
只有一个标签，通常用来在此元素所在位置插入/嵌入一些东西

## HTML文档
```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="author" content="Du Juan">
    <meta name="description" content="...">
    <title>My test page</title>
  </head>
  <body>
    <p>This is my page</p>
  </body>
</html>
``` 

`meta`: 元数据

指定包含关于页面内容的关键字可能或让你的页面在搜索引擎的相关的搜索出现得更多(SEO)。
