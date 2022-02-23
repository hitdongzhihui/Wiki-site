---
title: Luwu Dynamics
toc: true
date: 2022-02-22 17:07:57
tags:
categories: 
---

欢迎来到Luwu Dynamics Wiki页面！

# Markdown
本Wiki站的文章可通过点击右上角的 **Edit** 按钮跳转到Github页面，对文章源文件进行编辑。源文件编辑使用的格式为Markdown。
编辑完成后请联系Github管理员，由Github管理员push到Git page上。

[中文Markdown官方教程](https://markdown.com.cn/ "中文Markdown官方教程")
建议在本地的Markdown编辑器上编辑好后复制/上传，写起来会方便些。


# 目录
本Wiki站的所有文章目录结构按照Github仓库中文章源文件目录结构编辑（如下图），在创建新文章时可直接跳转到Github创建源文件。
![Wiki目录](demo_category.jpg)
![源文件目录](demo_md_category.jpg)

# 创建文件
创建文件或文件夹时，请注意命名：Windows文件名不能包含下列任何字符 \/：*？“

创建.md文件后，请在文件中写入以下代码，并将`<文章标题>`修改为文章标题（否则无法在目录中显示），后续改动文章内容时不要删除改代码

`---`

`title: <文章标题>`

`toc: true`

`date: `

`tags:`

`categories:` 

`---`

# 图片
文章插入图片时，格式为

`![文字描述](图片路径)`

示例

`![Wiki目录](./demo_category.jpg)`

一篇文章的图片建议统一放在文章源文件同级文件夹中，文件夹命名需要与文章名一致
示例
![插入图片](./picture_demo.jpg)


