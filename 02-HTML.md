# 超文本标记语言

## 什么是HTML

官方文档参考w3.org

## HTML的结构

```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8" />
  <title style="color: #3498db;">页面标题</title>
</head>
<body>

</body>
</html>
```

### 标签tag

标签以“`<`​”开始，以“`>`​”结束，

#### 起始标签

<title>文档标题</title>

#### 结束标签

结束标签中含有“`/`​”，

### 元素element

元素由起始标签、内容和结束标签构成，是HTML的基本单位。

<title>文档标题</title>

#### 属性

​`<meta charset="UTF-8">`​中的charset就是meta的属性之一。属性可自定义。

#### 值

​`<meta charset="UTF-8">`​中=号后的内容，即`"UTF-8"`​就是属性对应的值。

## 常用元素

### 块、行内元素

块级(block)元素，在语义上默认会换行的元素。如标题h1-h6、段落p等

行内(inline)元素，语义上出现在内容中间的元素。如图片img、表情符号等

### 列表元素

有序列表ol、无序列表ul、列表项li

### 逻辑区块

分区元素div

### 文本语义元素

超链接a

### 嵌入内容元素

图片img、内嵌框架iframe、矢量图形svg

### 表格元素

表格table、表头th、行tr、单元格td

### 表单元素

表单form、标签label、输入框input、按钮button、选择框select
