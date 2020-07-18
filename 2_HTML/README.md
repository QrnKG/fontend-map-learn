# HTML

## 基础

### 概念

超文本标记语言 (英语：**H**yper**t**ext **M**arkup **L**anguage，简称：HTML ) 是一种用来结构化 Web 网页及其内容的标记语言。

### 页面结构

```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>测试页面</title>
  </head>
  <body>
    <p class="editor-note">我的猫咪脾气<strong>爆</strong>:)</p>
    <img src="images/firefox-icon.png" alt="测试图片">
  </body>
</html>
```

- `<!DOCTYPE html>`---- 文档类型。早期，`DOCTYPE`用来链接一些 HTML 编写规则，比如自动查错之而立。如今作用有限，仅用于保证文档正常读取。
- `<html></html>` ---- `<html>`元素。该元素包含整个页面的内容，也称作根元素。
- `<head></head>` ---- `<head>`元素。该元素的内容对用户不可见，其中包含例如面向搜索引擎的搜索关键字（keywords）、页面描述(meta 元信息)、CSS 样式表和字符编码声明等。
  - `<meta charset="utf-8">` ---- 该元素指定文档使用 UTF-8 字符编码 ，UTF-8 包括绝大多数人类已知语言的字符。基本上 UTF-8 可以处理任何文本内容，还可以避免以后出现某些问题，没有理由再选用其他编码
  - `<title></title>` ----`<title>` 元素。该元素设置页面的标题，显示在浏览器标签页上，也作为收藏网页的描述文字。
- `<body></body>` ---- `<body>` 元素。该元素包含期望让用户在访问页面时看到的内容，包括文本、图像、视频、游戏、可播放的音轨或其他内容。

#### 元素详解

##### 元素，嵌套元素

```
    <p class="editor-note">我是例子<strong>大写</strong>:)</p>
```

- `<p>` ---- 开始标签
- `</p>`---- 结束标签
- `class='editor-note'`---- 属性
- `我是例子<strong>大写</strong>:)` ---- 内容
- 整体为一个**元素**
  - `<strong>大写</strong>`---- 嵌套元素

#### 空元素

```
    <img src="images/firefox-icon.png" alt="测试图片">
```
并没有 `</img>` 结束标签

---

- [html](https://juejin.im/post/5ed1c2cae51d45784635a50d?utm_source=gold_browser_extension#comment)
- [html 基础 MDN](https://developer.mozilla.org/zh-CN/docs/Learn/Getting_started_with_the_web/HTML_basics)
