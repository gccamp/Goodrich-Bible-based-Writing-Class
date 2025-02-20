###作者：猛犸


> “人生有很多坑，完全可以单脚一跃而过；可是大多数人，却偏偏要绕个大圈子。”

> “对未知事物的恐惧，几乎是本能的反应吧？”
> 
> ——[《Markdown 操作用户反馈》](http://www.jianshu.com/p/3a39ba00f6f3)，沐沐周

## 0 说明

0. 不要恐慌，不要恐慌，不要恐慌。

1. 本教程是为[王佩](http://www.jianshu.com/u/neLruC)在[简书](http://www.jianshu.com/)开设的[《好中文的样子》](http://www.jianshu.com/p/d409bb2b5d6c)课程而撰写。该课程鼓励作者使用 Markdown 写作。

2. 为什么要学习和使用 Markdown？如果你想要流畅表达想法，不想在键盘和鼠标之间频繁切换而中断思路；如果你想让你的文稿可以在任何地方打开；想让你的文稿一次排版，到处可用；想让排版更快；需要和其他人一起协同写作或翻译——那么你应该试试看 Markdown。

3. 本文的目标读者，是习惯以 Microsoft Office、Pages、WPS 或 LibraOffice 为写作编辑软件，较少或从未使用过 Markdown 的计算机用户。

4. 本文假设读者拥有一定计算机使用能力，足以完成网络搜索、浏览、文档写作与编辑等任务。

5. 本文将会尝试解释一些概念。这些解释可能会帮助读者更容易地理解，但未必精准。

6. 互联网上已经有大量 Markdown 相关资料，本文将会在“6 扩展阅读”部分给出一些扩展阅读材料。

7. 做是最好的学。我们需要一个可以快速上手的Markdown 编辑器，它应该可以实时预览。建议现在点击[作业部落](https://www.zybuluo.com/mdeditor)，并且在阅读本文时随时尝试。

## 1 Markdown 概述

Markdown 是一种轻量级标记语言。它是一种标准、一种语言，而非特定的软件；所以我们一般说“Markdown 编辑器”，而不说“Markdown 软件”。

- “轻量级”：是指结构简单，容易记忆也容易上手。
- “标记语言”：是指它会通过一些特定符号来实现特定功能；而这些符号会直接写在文字当中。我们将会在“**4 Markdown 语法**”部分详细描述这些符号。

Markdown 语言的设计目标是让人们“使用易读易写的纯文本格式编写文档，并且可以转换成其他格式。”

- “纯文本格式”：是指可以用最简单的文档编辑器打开的格式，例如 Windows 上的“记事本”、Mac 上的“TextEdit”，或一些 Linux 发行版上的“gedit”。
- 一般来说，纯文本格式文件的扩展名是“.txt”，这是最通用的文档文件格式，所有文本编辑器都能打开。
-  Markdown 文档的扩展名是“.md”或“.markdown”，一般建议使用“.md”。
- “转换成其他格式”：Markdown 格式可以轻松地转化成日常使用的大部分文档格式，包括但不限于.doc .html .pdf 等。

Markdown 最重要的设计是可读性。撰写 Markdown 不是为了让机器更容易读取，而是为了让人能够轻松阅读。

Markdown 已经获得了许多网站的支持，并且成为了 Github、Reddit 等著名社区的标准。

## 2 Markdown 与 Microsoft Word 的对比

在这一部分，将从以下几个方面，对比 Markdown 和 Microsoft Word 。

通用程度：

- Markdown 的 .md 格式：所有的文本编辑器都可以编辑。在“**3 支持 Markdown 的编辑器**”中列出了常见工具。
- Word 的 .doc 或 .docx 格式：只有 Microsoft Word、 LibraOffice、WPS 等几种软件能够编辑。

学习难度：

- Markdown：几分钟就可以学会常用语法。
- Word：“大部分人只用到了 Word 不到 5% 的功能。”看看书店里的教程数量和厚度就知道。

可读性：

- Markdown 文档：可读性强，文本中的符号基本不会影响阅读。
- Word 文档：如果你有 Word 的话，还不错；若是你没有，强行打开 Word 文档就只能看到一堆乱码。

转换成其他格式：

- Markdown：可以很容易地转换成多种格式的文档，当然也包括 .doc 或 .docx。
- Word ：除了“另存为”对话框中提供的格式之外，只能寻找其他工具来帮助转换。

管理不同版本：

- Markdown：可以使用通行的版本管理工具管理不同版本，可以避免编辑时多份不同版本内容冲突或丢失。
- Word：通常的做法，是在 Word 文档文件名后面加上一串数字，来手工管理版本。

协作：

- Markdown：可以使用 Github 等协同工具，多人同时或不同时编辑。
- Word：一份文档传来传去，同一时间只能由一个人修改。

最重要的区别在于， Word 本质上是一个排版软件而非写作支持软件，大量按钮和菜单让人们很难专注于写作本身。

而 Markdown 是种纯粹而优美的写作工具，只是兼顾排版而已。

## 3 支持 Markdown 的编辑器

### Windows

推荐 [Sublime Text 3](https://www.sublimetext.com/3)，强大优雅的编辑器。

[MarkdownPad](http://markdownpad.com/)，一款可以直接预览排版效果的编辑器。

### Mac

推荐 [Ulysess](https://www.ulyssesapp.com/)，专注写作的编辑器，功能强大，体验一流。

[Macdown](https://macdown.uranusjr.com/)，可以预览排版效果。

### Linux

推荐 [VIM](http://www.vim.org/)，编辑器之神。当然，[Emacs](https://www.gnu.org/software/emacs/)是神的编辑器。

[ReText](https://sourceforge.net/projects/retext/)，也可以预览。

### Web

推荐[简书](www.jianshu.com)，有 Markdown 写作/预览模式。

[作业部落](https://www.zybuluo.com/mdeditor)，功能强大的 Markdown 编辑器。

### 与其他常用工具配合

在 Firefox 浏览器上，推荐插件 [It’s All Text!](https://addons.mozilla.org/en-US/firefox/addon/its-all-text/)，可以将网页上的文本框转化为 Markdown 编辑器。

在和 Evernote 配合使用时，推荐使用[马克飞象](https://maxiang.io/)。

### 扩展阅读

[《好用的 Markdown 编辑器一览》](http://www.williamlong.info/archives/4319.html)

欢迎补充，随时更新。

## 4 Markdown 语法

现在可以在[作业部落](https://www.zybuluo.com/mdeditor)的左侧窗口中试试看了。无需注册，直接开始输入文字就好。

### 要事第一

首先需要注意：在 Markdown 中另起一段时，需要多敲一次回车键，来在段落之间添加一个空行。这是与其他常见文档格式的不同之处。

这是因为，在一些 Markdown 解释器中，会把相邻的两行合并成同一个段落。

例如，当我们这样书写时：

**这是第一段。**
**这是第二段。**

实际上看到的效果是这样：

**这是第一段。这是第二段。**

虽然并非所有 Markdown 解释器都会用同样的解释方式，但是为了避免出错，还是多敲一次回车来添加一个空行吧。

### 标题

Markdown 中，只需要在文本前面加上“#”，就会被认为是加了一个标题。同理，你还可以增加二级、三级、四级、五级标题和六级标题，只需要增加“#” 即可。例如：

\# 一级标题

\#\# 二级标题

\#\## 三级标题

\#\### 四级标题

\#\#### 五级标题

\#\##### 六级标题

**实际显示的效果是这样的（在不同的环境下显示效果可能会有差异）：**

# 一级标题

## 二级标题

### 三级标题

#### 四级标题

##### 五级标题

###### 六级标题

### 列表

当你要罗列一些内容时，列表是很有用的工具。为了说明哪些条目属于这个列表，我们需要引入“项目标记”。

列表项目标记通常放在段落开头，后面要跟着一个空格。列表的各个条目之间可以不留空行。

若列表中的条目没有特定顺序时，可以使用 **无序列表**。加号“+”或减号“-”都可以作为列表标记，后面要跟一个空格。例如：

\- Red

\- Green

\- Blue

或者

\+ Red

\+ Green

\+ Blue


**实际显示的效果都是这样的（在不同的环境下显示效果可能会有差异）：**

- Red
- Green
- Blue

若想在段落前加上数字序号，就需要用到**有序列表**了。使用数字、一个英文句号和一个空格即可。例如：

1\. Red

2\. Green

3\. Blue

**实际显示的效果是这样的（在不同的环境下显示效果可能会有差异）：**

1. Red
2. Green
3. Blue

### 图片

Markdown 中可以插入图片，只需要感叹号、方括号和圆括号即可。例如：

\!\[Alt text](/path/to/img.jpg)

一个英文感叹号 “!” 后紧跟方括号，里面可以写这张图片的说明；再紧跟一对圆括号，里面写这张图片的网址。例如：

\!\[吃面条](http://upload-images.jianshu.io/upload\_images/19107-4a17a25a90d42a5e.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

**实际显示的效果是这样的（在不同的环境下显示效果可能会有差异）：**

![吃面条](http://upload-images.jianshu.io/upload_images/19107-4a17a25a90d42a5e.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

当然，在圆括号里填上这张图片的本地路径也可以。“本地路径”是这个图片文件在你计算机中存储的位置，一般可以在文件浏览器的地址栏里看到它，类似“C:/My Documents/picture.jpg”，或者“UserMyNameHomeDesktoppicture.jpg”的样子。

### 链接

在文档中插入连接的语法和插入图片的语法很像，只是少了最前面的英文感叹号"!"。

在方括号写下链接文字，圆括号写下网址即可。例如：

\[好中文的样子](http://www.jianshu.com/p/d409bb2b5d6c)

**实际显示的效果是这样的（在不同的环境下显示效果可能会有差异）：**

[好中文的样子](http://www.jianshu.com/p/d409bb2b5d6c)

### 引用

可以使用"\>" 标记来引用其他人的言论、书籍或报纸的内容。只需要在段落的第一行最前面加上 \> 即可：

\> ”每位作者都应该学习 Markdown。” ——王佩

**实际显示的效果是这样的（在不同的环境下显示效果可能会有差异）：**

> ”每位作者都应该学习 Markdown。” ——王佩 

引用可以嵌套，只要根据层次的不同，加上不同数量的 \> 即可：

\> 这是第一级引用。


\>\> 这是第二级引用。


\> 现在回到第一级引用。

**实际显示的效果是这样的（在不同的环境下显示效果可能会有差异）：**

> 这是第一级引用。

> > 这是第二级引用。

> 现在回到第一级引用。

在引用的区域内，也可以使用其他的 Markdown 语法，包括标题、列表等：

\> ## 这是一个标题。

\> 1. 这是第一行列表项。

\> 2. 这是第二行列表项。

**实际显示的效果是这样的（在不同的环境下显示效果可能会有差异）：**

> ## 这是一个标题。

> 1. 这是第一行列表项。

> 2. 这是第二行列表项。

### 强调

在Markdown中，可以使用 \* 和 \_ 来表示*斜体*和**加粗**。需要注意的是，“_”是下划线而非减号“-”。

在需要_斜体_的文本左右各加一个“*”或“_” ：

\*吹吹那热风，听听那冷雨，看哪，好中文的样子。\* 

\_吹吹那热风，听听那冷雨，看哪，好中文的样子。\_ 

**实际显示的效果是这样的（在不同的环境下显示效果可能会有差异）：**

*吹吹那热风，听听那冷雨，看哪，好中文的样子。* 

_吹吹那热风，听听那冷雨，看哪，好中文的样子。_ 

在需要**加粗**的文本左右各加两个“*”或“_” ：

\*\*吹吹那热风，听听那冷雨，看哪，好中文的样子。\*\* 

\_\_吹吹那热风，听听那冷雨，看哪，好中文的样子。\_\_ 

**实际显示的效果是这样的（在不同的环境下显示效果可能会有差异）：**

**吹吹那热风，听听那冷雨，看哪，好中文的样子。** 

__吹吹那热风，听听那冷雨，看哪，好中文的样子。__ 

### 分割线

在 Markdown 中，可以用分隔线来将内容分成不同区域。

只需要三个短横"-"即可。例如：

\---

**实际显示的效果是这样的（在不同的环境下显示效果可能会有差异）：**

---

## 5 常见问题

Q： 我该去哪里下载 Markdown 软件？

A： Markdown 是一种标准而非软件，任何支持 Markdown 语法的编辑器都可以使用，无论是何种操作系统、哪类设备。请看“3 支持 Markdown 的编辑器”，或者问问 Google。

---- --

Q： 为什么我按说明写了标记，但是没法正常显示？

A： 很可能是你误把中文标点当成了英文标点。在 Markdown 中使用标点符号作为标记时，要使用英文标点符号。没关系，人们总会犯这种小错误。

---- ---

Q： 为什么我写了正确的标记，但是在编辑窗口中看不到任何效果？

A： 许多 Markdown 编辑器都不是所见即所得的——“所见即所得”是指你对格式的修改会马上反映在屏幕上，就像 Word 那样。如果你的编辑器没有没有实时预览功能，就不会看到格式的变化。[Macdown](https://macdown.uranusjr.com/)和[简书](www.jianshu.com) 都支持实时预览，你需要先打开这个功能，才能看到这些格式标记的效果。

-----

Q： Markdown 可以排版表格吗？

A： 可以，如果你熟练的话，排版表格也会很快。表格的语法请见“[Markdown 语法说明（简体中文版）](http://wowubuntu.com/markdown/)”。

---- -

Q： Markdown可以排版数学公式吗？

A： 可以。只要有相应的扩展，Markdown 可以支持LaTeX 公式、甚至画流程图和甘特图。

-----

Q： 标题效果和加粗有区别吗？

A： 看似没有，其实还是有的。这涉及到如何解释 Markdown 标记的问题，一般和 CSS 有关。更多信息，请看“**6 扩展阅读**”部分。

-----

Q： 加图片时，无 IT 背景人士一般会采用从桌面拖拽的方式。Markdown 支持拖拽吗？

A： 拖拽图片插入文档或上传到网站，不是 Markdown 语法本身的内容。不过有些网站和 Markdown 编辑器支持拖拽方式，例如 [Ulysess](https://www.ulyssesapp.com/) 和 [简书](www.jianshu.com) 。

-----

Q： Markdown 正文可以调整字号吗？

A： 同样和解释 Markdown 标记的方式有关。更多信息，请看“**6 扩展阅读**”部分。

----

Q： Markdown 段落开头不能空两格，看着很难受啊。有办法解决吗？

A： 办法嘛……若是在自己机器上的 Markdown 编辑器中，也许你可以修改 CSS。若是在 [简书] 之类网站上，可能只能手工在每段开始前手工添加五个“\&nbsp;”了。记得，是“\&nbsp;”，最后的分号也是有必要的哦~

## 6 扩展阅读

更多关于 Markdown 语法或工具的内容，可以参考：

- [Markdown 语法说明（简体中文版）](http://wowubuntu.com/markdown/)
- [献给写作者的 Markdown 新手指南](http://www.jianshu.com/p/q81RER)
-  Markdown 是定义文章逻辑结构，而非定义样式的。一般来说，Markdown 最终呈现出的样式，是由对应的层叠样式表（CSS）所定义的。如果想要自己调整出想要的样式，可以从 CSS 开始。这里有一份 CSS 教程：[《CSS 入门教程》](https://developer.mozilla.org/zh-CN/docs/Web/Guide/CSS/Getting_started)

不断扩充中，欢迎补充。

-----

本文是[《好中文的样子》](http://www.jianshu.com/p/d409bb2b5d6c)课程 G056组小组协作作业的衍生作品。

计划共有三篇。截止20170219：

1. Markdown 新手手册（本文）
2. Git 新手手册（撰写中）
3. GitHub 新手手册（未开始）

更多内容，请关注专题[《GC4WPS03E05-番外》](http://www.jianshu.com/c/d6c41203c8d7)

撰写：[叶猛犸](http://www.jianshu.com/u/jsB5Kx)
其他贡献者：[Zoom.Quiet](http://www.jianshu.com/u/3908d6bf439d)，[粒粒如一](http://www.jianshu.com/u/1313ab3fdbec)， [迷妹乔小喵](http://www.jianshu.com/u/863ba0c40078)，[玛雅蓝](http://www.jianshu.com/u/8fMnfE)
