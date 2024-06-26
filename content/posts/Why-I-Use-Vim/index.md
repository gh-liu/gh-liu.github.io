---
title : 'Why I Use Vim'
date: 2021-12-15T11:38:19Z
draft : true
isCJKLanguage : true
categories:
- Development
tags:
- vim
enableComment : true
---

Vim是一个文本编辑器。

设想你在编辑一段文字的时候，你需要`定位`到想要编辑的地方，`选择`想要编辑的范围，然后`输入`文字；

那为了提高效率，就需要`快速定位`，`精准选择`，`准确输入`；

Vim提供一种不使用鼠标的高效编辑文本的方式！

## 不同模式

vim有着不同的模式，比如 Insert 模式，进行文字的输入与修改，`输入什么字符，即显示什么字符`；

又比如 Visual 模式，当选择文字的时候，自动进入此模式，又可以细分成三种模式：`字符character, 行line, 块block`，针对不同的场景对文字进行选择进而操作；

还有Normal 模式，在这个模式下，`字符都有其特殊意义`，比如在文本内快速移动、对文字进行操作；

还有 Command 模式，在这个模式下，可以`执行相关命令或代码`，对符合条件的文本进行操作；

## 文本编辑

### 文本对象

在Vim中，文本对象(text objects)是一个定义的文本区域，可以作为一个单元进行选择、操作。

词、句、段落、被引号包裹的、被括号包裹的等等，都是文本对象；

文字符合一定规则的，都可以成为文本对象；

### 文本操作

Normal模式下，`字符都有其特殊意义`：比如d删除，c修改，r替换等，可以配合文本对象比如字w，dw删除一个词；

#### 寄存器

提供多个寄存器，保存被操作的文本；

### 历史编辑记录

u 撤销上一次修改；

Ctrl-r 重做上一次撤销的修改；

### 搜索、替换

使用 / 或 ? 进入搜索模式；

使用 :s 进行命令行模式，且使用s替换命令

## 快速移动

### 移动光标

还是Normal模式下，`字符都有其特殊意义`：

比如：hjkl对应左下上右；

又比如f向前到某个一字符，F向后到某个一字符等；

当然，w也可以表示相前移动一个词；

### 标记位置

使用mark，小写字母a-z标记当前文件，大写字母A-Z标记全局文件；

## Buffer, Window, Tab

文件被读取后，就是一个Buffer；

Window 起到视窗的作用，用来查看 Buffer，一个 Buffer 可以在多个Window被查看；

Tab是多个Window的组合；

## 可编程

vimscript

## 插件生态

丰富的插件生态
