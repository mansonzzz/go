# HTML基础

> HTML:一门用于定义内容结构的标记语言

## HTML文档详解

通过一个栗子来引入：

```html
<!-- index.html -->

<!DOCTYPE html> <!-- 文档类型，用于保证文档正常读取 -->
<html> <!-- 根元素 -->
  <head> <!-- 文档配置信息（元数据），包括文档的标题，引用的文档样式和脚本等 -->
    <meta charset="utf-8">
    <title>测试页面</title>
  </head>
  <body> <!-- 包含期望让用户在访问页面时看到的内容 -->
    <h1>Mozilla 酷毙了</h1>
    <img src="images/firefox-icon.png" alt="测试图片">
    <p>Mozilla 是一个全球社区，这里聚集着来自五湖四海的</p>
    <ul> <!-- 无序列表  <ol>:有序列表 -->
        <li>技术人员</li>
        <li>思考者</li>
        <li>建造者</li>
    </ul>
    <p>我们致力于让 Internet 保持活力</p>
    <a href="https://www.mozilla.org/zh-CN/about/manifesto/">Mozilla宣言</a> <!-- 链接 -->
  </body>
</html>
```

