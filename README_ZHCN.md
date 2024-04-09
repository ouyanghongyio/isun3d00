md语法基本使用

## README.md

”-“  减号效果添加一个点在文本前面，如下面所示

- en [英语](README.md)
- zh [中文](README_ZHCN.md)

空行换行

“##” 符号代表二级标题，字号逐级递减
## 前言
“``” 符号(制表符)可以高亮，类似如下效果

`ligangxiaodian`是一个基于html,css搭建的静态导航网站，
只具有基本的展示功能，且不具备动态配置功能

”```“  三个指标符上下两行中间包括的文本会全部高亮，就是整个代码块高亮的效果 

```
代码快高亮
```

## 项目在线地址

“**” 或者 “__”  前后包括文本加粗

**项目在线演示地址**

__项目演示__

"[]" + ” () “，前面描述，后面跳转地址，超链接语法

[项目传送门](https://ouyanghongyio.github.io/ligangxiaodian/)

”*“ 或者 ”_“  前后包括文本斜体

*背景*

”~~“ 前后包括文本显示删除线

~~前期需要一个实体引流的方便页面，其实不重要~~

_目的_

"<u>" 和 </u> 前后包括文本下划线

<u>推广引流集中到网店销售</u>

”sup“ 和 ”/sup“  分别加 <> 前后包括文本上标

使用技术<sup>html,css</sup>

"sub" 和 "/sub"  分别加 <> 前后包括文本下标

功能<sub>商铺展示，商品展示，课程展示</sub>

”|“ 一行几个即生成几列表格表格，类似效果如下，有几列第二行需要 用 "|" 和 “---” 分成和第一行那么多列

“img src="url""” 前后加 <> 即可展示图片，效果如下

| index                                                                | store                                                                | goods                                                                | courses                                                              
|----------------------------------------------------------------------|----------------------------------------------------------------------|----------------------------------------------------------------------|----------------------------------------------------------------------|
| <img src="https://ouyanghongyio.github.io/ligangxiaodian/laba.png"/> | <img src="https://ouyanghongyio.github.io/ligangxiaodian/laba.png"/> | <img src="https://ouyanghongyio.github.io/ligangxiaodian/laba.png"/> | <img src="https://ouyanghongyio.github.io/ligangxiaodian/laba.png"/> 
| 第二行1                                                                 | 第二行2                                                                 | 第二行3                                                                 | 第二行4                                                                 |


##项目结构

“|” 和 “-” 可得到如下效果的树状结构图

📂  文件夹小图标

📄  文件小图标

配合使用可以更加直观的展示项目结构

```agsl
📂 ligangxiaodian
|-📂docs
|   |-📄index.html
|   |-laba.npg
|   |-📄store.html
|-📂idea
|-📄README.md
|-📄README_ZHCN.md

```

“!” 加 “[]” 加 “()”  可以得到超链接图片的效果

![喇叭图片](https://ouyanghongyio.github.io/ligangxiaodian/laba.png)