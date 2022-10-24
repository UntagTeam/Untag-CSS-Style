# Untag CSS Style

Untag CSS Style 是由于 [Untag](https://utgd.net) 提供的 CSS 样式文件。

Untag 的主题色是亮黄色（#ffd600），希望这一抹靓丽的黄色，能够给你带来愉悦的阅读体验。

## 使用

本仓库中 [untag-style.css](./untag-style.css) 可以直接下载并使用在任意位置。

你需要在你的网页中引入这个 CSS 文件：

``` html
<head>
    <!-- ... -->
    <link rel="stylesheet" href="../untag-style.css">
    <!-- ... -->
</head>
```

接下来需要将 "markdown-body" 作为内容标签的 class，例如：

``` html
<article class="markdown-body">
    <h2>标题</h2>
    <p>正文内容</p>
</article>
```

这样就完成了！

## 参考

- 示例文件 index.html 是基于 [github-markdown-css 仓库](https://github.com/sindresorhus/github-markdown-css/edit/main/index.html) 中的 HTML 示例文档进行少量修改的版本。

- 部分参考了 Apple 阅读模式中的 CSS 样式。

## LICENSE

[GPL-3.0](./LICENSE)
