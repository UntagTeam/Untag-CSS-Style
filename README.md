# Untag CSS Style

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)  [![Untag](https://img.shields.io/badge/Website-Untag-ffd600)](https://utgd.net)  

Untag CSS Style 是由 [Untag](https://utgd.net) 提供的 CSS 样式文件，对中文排版支持良好。

Untag 的主题色是亮黄色（#ffd600），希望这一抹靓丽的黄色，能够给你带来愉悦的阅读体验。

## 预览

![整体样式](https://cdn.utgd.net/assets/uploads/2022/12/FG-282205-n.png)

![局部样式](https://cdn.utgd.net/assets/uploads/2022/12/FG-282206-C.png)

## 下载

本仓库中 [Untag-Style.css](./Untag-Style.css) 可以直接下载并使用在任意位置。

## 使用

你需要在你的网页中引入这个 CSS 文件：

``` html
<head>
    <!-- ... -->
    <link rel="stylesheet" href="../Untag-Style.css">
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

- 部分参考了 Apple 阅读模式的 CSS 样式。

## LICENSE

[GPL-3.0](./LICENSE)
