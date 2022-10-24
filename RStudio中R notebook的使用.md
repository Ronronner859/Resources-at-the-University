---
title: R notebook的使用
date: 2022-10-24 12:36:36
tags: "R"
categories: R
updated: 2022-10-24
description:  "集成开发环境R Studio"
comments: true
---

# RStudio中R notebook的使用

>Rnotebook官方文档：里面有关于R Markdown详细语法和基础操作。

RStudio中的NOTE BOOK主要界面如下：

![](https://img-blog.csdnimg.cn/f8ebf42caece4f1c9aefa66c2ff6f594.png#pic_center)

## 前提

学习R语言这门语言的时候，会用到集成开发环境R Studio，其中提供编写文档是用R notebook俗称R标记文档，能够快速的生成各种文档。其语法和 Markdown语法类似，主要内容看上面的链接即可。可以提前看看关于Markdown语法知识，是怎样通过Markdown来快速编写文档的。

再就是用过Typora的肯定已经很熟悉Markdown的操作，还有就是用hexo+githubpage搭建博客也是用的Markdown进行编写的，大差不差。

## Markdown语法链接

1. 菜鸟教程：[语法教程](https://www.runoob.com/markdown/md-image.html)
2. CSDN: [CSDN教程](https://blog.csdn.net/phunxm/article/details/49565427?_t_t_t=0.030726275473744513)
3. 起源看github: [Markdown起源](https://github.com/younghz/Markdown)

## R notebook的使用

### 操作流程

![](https://img-blog.csdnimg.cn/babe112286964ea9875cd5e0329eca05.png#pic_center)

图形界面：

![](https://img-blog.csdnimg.cn/8a194eaa0de64b2c9736510f101723fa.png#pic_center)

运行：

![](https://img-blog.csdnimg.cn/1b846c6cc4e940a586c5ad6bf47c4a2d.png#pic_center)

或者直接按：alt + shit + enter

### 基本使用

R Markdown在使用时需要安装一些程序包

```c
install.packages("rmarkdown") # 写rmarkdown必需的包
install.packages("knitr") # 导出文件必需的包
install.packages("tinytex") # TeX的轻量级发行版，用于PDF文件的导出
install.packages("rticles") # 配合中文导出PDF，有很多不同的文档模板可供使用
```

### 写作

R Studio下的R Markdown支持数学公式的实时预览，相当于本地Typora

详细看链接：

[R studio](http://rmarkdown.rstudio.com )