

### html基础

#### 基础标签

- 结构

  ```html
  <!DOCTYPE html>
  <html>
  <head>
  <body>
  <p> </p>
  </body>
  </head>
  </html>
  ```

  ​


- 标题

  ```html
  <h1></h1>
  <h2></h2>
  ```

- 段落

  ```html
  <p></p>
  ```

- 链接

  ```html
  <a href="url……"></a>
  <a href="url……" target="_blank"></a>    //target属性设置为_blank链接将在新窗口打开
  <a id="" href="url……"></a>
  ```

- 图像

  ```html
  <img src="路径or软链" width="" height=""/>
  <img src="路径or软链" alt="">   //替换文本属性告诉读者她们失去的信息
  ```

- 换行

  ```html
  <br>

  ```

- 水平线

  ```html
  <hr>
  ```

- 注释

  ```html
  <!-- 这是一个注释 -->
  ```

  ​

- 表格

  ```html
  <table>
  <tr>
  <th>……,……,……</th>                 //表头
  </tr>    
  <tr>
  <td>……,……,……</td>
  </tr>
  ……
  <tr>
  <td>……,……,……</td>
  </tr>
  </table>

    <ul>                                      //内嵌列表
      <li></li>
      <li></li>
      <li></li>
     </ul>
  ```



|标签|描述|
|-|-|
|<table>|定义表格|
|<th>|定义表格的表头|
|<tr>|定义表格的行|
|<td>|定义表格单元|
|<caption>|定义表格标题|
|<colgroup>|定义表格列的组|
|<col>|定义用于表格列的属性|
|<thead>|定义表格的页眉|
|<tbody>|定义表格的主体|
|<tfoot>|定义表格的页脚|

- 列表

  ```html
  <!DOCTYPE html>
  <html>
  <head> 
  <meta charset="utf-8"> 
  <title>菜鸟教程(runoob.com)</title> 
  </head>
  <body>

  <h4>嵌套列表：</h4>
  <ul>
    <li>Coffee</li>
    <li>Tea
      <ul>
        <li>Black tea</li>
        <li>Green tea</li>
      </ul>
    </li>
    <li>Milk</li>
  </ul>

  </body>
  </html>
  ```

  ​

|标签|描述|
|-|-|
|<ol>|定义有序列表|
|<ul>|定义无序列表|
|<li>|	定义列表项|
|<dl>|定义列表|
|<dt>|自定义列表项目|
|<dd>|定义自定列表项的描述|

- 区块标签

  ```html
  <div></div>
  <span></span>
  ```

  ​

- 表单

  ```html
  <form></form>
  ```

- 框架

  ```html
  <iframe src="URL"></iframe>
  ```

  ​


#### html字符实体

参考[html实体参考手册](http://www.runoob.com/tags/ref-entities.html)

#### html插件

- object：定义了在 HTML 文档中嵌入的对象,用于插入对象 (例如在网页中嵌入 Java 小程序, PDF 阅读器, Flash 播放器)

- 同样可用于包含HTML文件.

  ```html
  <object width="400" height="50" data="bookmark.swf"></object>
  <object width="100%" height="500px" data="snippet.html"></object>
  <object data="audi.jpeg"></object>  //插入图片

  ```

- embed:表示一个 HTML Embed 对象,已经出现很长一段时间了，但是在 HTML5 前并未被详细说明，该元素在 HTML 5 页面上会被验证，在 HTML 4 上不会.

  ```html
  <embed width="400" height="50" src="bookmark.swf">
  <embed width="100%" height="500px" src="snippet.html">
  <embed src="audi.jpeg">
  ```

  ​


#### html属性

|属性|描述|
|-|-|
|class|为html元素定义一个或多个类名（classname）(类名从样式文件引入)|
|id|定义元素的唯一id|
|style|规定元素的行内样式（inline style）|
|title|描述了元素的额外信息 (作为工具条使用)|

#### 字体样式


```html
<b>加粗文本</b>
<i>斜体文本</i>
<code>电脑自动输出</code>
<sub> 下标</sub> 
<sup> 上标</sup>
```

#### 元素标签

- title:定义了文档的标题

```html
<title></title>
```



- base: 述了基本的链接地址/链接目标，该标签作为HTML文档中所有的链接标签的默认链接

```html
<head>

<base href="http://www.runoob.com/images/" target="_blank">

</head>

```







- link:定义了文档与外部资源之间的关系,用于链接到样式表

```html
<head>

<link rel="stylesheet" type="text/css" href="mystyle.css">

</head>

```




- style:定义了HTML文档的样式文件引用地址,也可以直接添加样式来渲染 HTML 文档

```html
<head>
<style type="text/css">
body {background-color:yellow}
p {color:blue}
</style>
</head>
```

- meta:描述了一些基本的元数据,元数据也不显示在页面上，但会被浏览器解析,通常用于指定网页的描述，关键词，文件的最后修改时间，作者，和其他元数据,可以使用于浏览器（如何显示内容或重新加载页面），搜索引擎（关键词），或其他Web服务。<meta> 一般放置于 <head> 区域

  实例1：为搜索引擎定义关键词:

```html

<meta name="keywords" content="HTML, CSS, XML, XHTML, JavaScript">

```

​	实例2：为网页定义描述内容:

```html
<meta name="description" content="免费 Web & 编程 教程">
```

​	实例3：定义网页作者:

```html
<meta name="author" content="Runoob">
```

​	实例4：每30秒钟刷新当前页面:

```html
<meta http-equiv="refresh" content="30">
```

- script:用于加载脚本文件，如： JavaScript


