---
title: Hexo添加自定义网页
date: 2019-10-09 19:37:58
tags: Hexo
categories: 教程
---
自定义CV。
<!-- more -->
## 新建page
```
hexo new page CV
```

## 更新html
将source目录下生成的index.md改为index.html，然后进行编写。

## 跳过渲染
> 编写完成后，在index.html文件头部添加如下命令：

```
---
layout: false
---
```

## 完成
```
执行hexo g、hexo s查看效果。
```