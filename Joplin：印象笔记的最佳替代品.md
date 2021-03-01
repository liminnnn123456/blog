---
tags: 作品存档
name: Joplin：印象笔记的最佳替代品
about: 软件,Joplin
type: 稿件
status: 已存档
date: 2021-02-06
---

# Joplin：印象笔记的最佳替代品


[TOC]


作者：如山清

> 注：本文的所有参考文献和软件下载链接，均附在文后。需要时请自取。

笔记类的软件我们已经介绍过了很多，以至于我已经没有办法对其进行一个合理的分类，不过这里我还是尝试着根据不同的需求分一下类。在之后我们还会再出一篇对笔记软件进行大总结的文章。

- 注重排版效果
  - MS Word
  - OneNote
- 注重层级结构
  - 幕布
  - iThoughts
- 具有双向链接功能
  - Obsidian
  - Wikidpad
- 简洁记录
  - Flomo
- 注重剪藏
  - 印象笔记

而本期要介绍的Joplin就是对印象笔记进行替代的软件，也就是以收集和剪藏文章为目的的笔记软件。

## 为什么选择Joplin而不是印象笔记

我们上面介绍的软件中，有一类是比较特殊的。那就是Wikidpad和Obsidian，这两款软件实际上都受到了曾经的“自由软件运动”（free software movement）的影响（其中的“free”意指“freedom”，而非免费）。其中Wikidpad是纯粹的开源软件（open-source software）。顾名思义，即“开放源代码的软件”。软件的源代码也就是软件最为核心的部分，源代码的开放意味着用户可以对于软件本身进行修改和传播，同时也意味着所有人可以对这些源代码进行学习。而软件的所最重视的“知识产权”就是源代码，也因此，“自由软件”运动在实质上是一种带有左翼色彩、反对知识产权制度的社会运动。

![自由软件，自由社会](https://i.loli.net/2021/02/05/xNpmuB7TvLtRgnW.png)

但之后自由软件运动发生了分裂，其中一派将自由软件重新诠释成了“开源软件”。在这个意义上，开源软件算是自由软件运动的一个遗产，即便有许多自由软件运动的支持者认为这实质上是一种背叛。不过开源软件却更多走入了主流视野，至今仍是互联网精神的一种代表。

开源软件给当今的互联网留下了众多丰硕的成果，其中最为著名的应该要数Linux系统和Android移动操作系统。而我们之前推荐的Wikidpad也于2005年开始成为了开源软件，它的最后一次更新是在2018年，直到2020年类似的软件又吸引了商业公司的注意，它算是填补了一个小众需求相当长的一段时间。

自由软件运动强调用户需要对软件完全控制，因为“如果用户没有控制程序，那么程序就在控制用户。”。但是互联网的发展到今天，除了专有软件之外，商业企业也有了更多的方式来剥夺用户对于程序的控制权。我们不得不使用相同的社交媒体，却缺乏替代品。我们也不得不每时每刻接受审查，甚至对此麻木。我们还默许商业公司出卖我们自身的隐私谋利，却毫无办法。棱镜计划的存在也证实我们的信息正在被大规模的搜集和滥用。

当然，人们也有着不断收回控制权的努力。Linux系统使得人们有了商业公司操作系统之外的选择。Mastodon使得人们可以搭建分布式的社交媒体，而Joplin则正是一款开源的笔记软件。

关于印象笔记的槽点，我大概可以说一整期，不过那并没有什么意义。印象笔记的功能并不丰富，而它的编辑器也是祖传的难用（如果好用就不会出现马克飞象这种东西了），关键还存在隐私和审查的风险（某朋友为此直接搬迁到国际版去了）。在这种状况下，实际上Joplin与印象笔记的最大区别就是用户对于数据的完全掌控。

在这点上，Joplin与Obsidian的有相像之处。虽然Obsidian并非开源软件，但是对于个人用户完全免费，且个人用户的数据永远不会被Obsidian所掌控（因为你不使用它提供的云服务），且Obsidian只不过是一个编辑器而已，你的文件完全可以使用其他更好用的编辑器去打开和编辑。这些特点也都是Joplin具有的。当然，二者相同的是，如果你想多端同步的话，你需要自己使用同步云盘等方式（当然这并不难）。

印象笔记最为好用的功能其实就是剪藏（我相信大多数人还是不会长时间在那么难用的编辑器上写文字的），但Joplin在这方面并不弱于印象笔记。同时我们还可以使用一些插件来让剪藏有更好的体验。

![Joplin各平台客户端](https://i.loli.net/2021/02/05/BOqJUMtbPEHce4o.jpg)

## Joplin的基本使用

### 1.Joplin的界面

如果你常年使用印象笔记的话，那么对于Joplin的界面也一定有一种熟悉感，因为差别并不大。

![印象笔记截图](https://i.loli.net/2021/02/05/I9s5prqTu26KZen.png)

![Joplin截图](https://i.loli.net/2021/02/05/HXfQoFKBOknwSlP.png)

没错，都是熟悉的三栏设计，最左边的一栏是笔记本和标签，中间一栏是笔记列表，右边占比最大的一栏是编辑器。不过这里就已经可以展示出2个区别，Joplin没有回收站，同时它的标签不是多级设计，所以在使用的时候推荐使用“1级标签/2级标签/3级标签”这样使用，如果想提高标签的优先级，可以在前面加数字或者字母。

### 2.Joplin的文件结构

为了之后使用的方便，我们先介绍一下Joplin笔记是如何储存的，这样更便于我们之后的使用。

我们可以通过“工具-选项-通用选项”，看到我们的笔记储存在什么位置（这个位置在选项中是不能修改的，但是有其他方法，具体可见附录1）。我们复制这个位置到系统文件管理器打开。

![image-20210205153735922](https://i.loli.net/2021/02/05/PDY7GgW9cfzdtsI.png)

我们可以看到笔记储存的文件结构。一级目录中的txt文件似乎是一些运行记录，我们不用看。sqlite文件是软件的数据库文件，也不用管。而templates文件夹是储存模板的地方，我们之后制作好的模板要放在这里。而resource则是储存笔记的附件（尤其是图片一类的东西）。而两个以“edit”打头的MD文件，就是我现在在Joplin正在编辑的文件。这个文件是因为我使用外部编辑器来编辑笔记而临时生成的。（后文会讲使用外部编辑器编辑）

![image-20210205154239662](https://i.loli.net/2021/02/05/ACaUShdqmQHeJpj.png)

当我们打开笔记的属性的时候，我们可以看到笔记的一串ID，而这个ID就是储存的文件名，你凭借这个ID是可以直接在系统的文件资源管理器中搜索到源文件的。

![image-20210205165228224](https://i.loli.net/2021/02/05/cfhyN6H8UxnldWj.png)

所以本质上，Joplin只是一些有结构的文件的集合，以及一个可以浏览和修改文件的编辑器。而这些文件本身都可以脱离这个编辑器存在。

### 3.模板的使用

我们在介绍印象笔记的那一期中，制作了很多方便使用的模板。当然因为Markdown对于表格的支持并不好，我们在Joplin的模板也没有必要以表格的形式制作（印象笔记模板做成表格很大程度上也是因为它的编辑器很糟糕）。

那么我们就以本期文章的“写作计划”为例，制作一个模板。本期文章的写作计划大致如下：

![image-20210205170203899](https://i.loli.net/2021/02/05/gFweXuqQUjbzncv.png)

既然每个写作计划我们都会有这些部分，那么我们就将这些内容做成模板。

![image-20210205170537653](https://i.loli.net/2021/02/05/N8MfXDzV1LGOjHC.png)

然后我们选择“文件-模板-打开模板目录”。

![image-20210205170613680](https://i.loli.net/2021/02/05/rz1AuVRE2X7BFUq.png)

然后我们会发现，其实打开的这个文件目录，其实就是之前笔记储存目录中的templates文件夹。然后我们在其中创建要给MD文件，将之前模板的Markdown代码复制进去保存。模板就算是创建成功了。

![image-20210205170938727](https://i.loli.net/2021/02/05/aomgnvOTJRkb8C9.png)

当我们新建一个笔记之后，准备使用时，选择“文件-模板——插入模板”，然后选择对应模板使用即可。

![image-20210205171120284](https://i.loli.net/2021/02/05/gNRMGfuk7iBVHUh.png)

### 4.笔记的导入和导出

Joplin笔记主要支持导入Markdown、Joplin文件和印象笔记导出文件。所以从印象笔记向Joplin搬迁是极为容易的事情。

![image-20210205171336005](https://i.loli.net/2021/02/05/HRtFeTXLvaE6zKU.png)

导出则支持导出Joplin自身可以导入的文件、Markdown、html和PDF文件。不过因为它的PDF文件的渲染效果不够好，并不推荐。

## Joplin的进阶使用

不过写到这里，Joplin除了有开源软件的情怀之外，似乎对比印象笔记全都是劣势。要说印象笔记的编辑器不好用，Joplin的编辑器也不过就好了一点点而已。Joplin也不过就是一个只有基本功能的笔记软件而已。

而接下来的部分，才是本文的重点：如何更好更舒适地使用Joplin。

### 1.更好的编辑器：Typora

![](https://i.loli.net/2021/02/05/AMNhCGx49cXu7rO.png)

Joplin最让人舒适的地方莫过于它可以使用外部编辑器来进行编辑。而这里向大家推荐的Markdown编辑器就是Typora。

Typora是一款免费、简单，并且可以实时预览的Markdown编辑器。并且支持Mac OS、Windows和Linux三个平台。在我们安装完成这款软件之后，我们就可以使用它对Joplin的笔记进行编辑了。

#### 1.1 使用方式

当我们打开一篇笔记之后，我们可以点击工具栏上方的“切换外部编辑器”的标志。或者按快捷键crtl+E。

![image-20210205173153968](https://i.loli.net/2021/02/05/8vkBnywbg79NDLs.png)

当我们编辑完成时，先在Typora中进行保存，然后关闭文档。再在Joplin中点击“停止”。

![image-20210205173338264](https://i.loli.net/2021/02/05/QlL7B4Uvn3g6XZs.png)

#### 1.2 使用技巧1：更舒适的界面

我先向大家展示一下我的Typora编辑器的编辑界面。这样可以更加直观地反映出差别有多大。

![image-20210205173603808](https://i.loli.net/2021/02/05/wPaf7IcEh1BsgWy.png)

首先，为了让编辑界面更美观，我加载了GitHub一位热心网友制作的主题CSS（Flora，下载链接在文后）。使得中文渲染效果也十分出色（尤其是字体上）。当然你相关的主题还有很多很多（如果你懂一些CSS的话，你甚至可以自己做一个），你完全可以在Themes Gallery找一款你喜欢的。

![image-20210205174753746](https://i.loli.net/2021/02/05/8PQUyYR4eKSnGh9.png)

然后我们再修改一些Typora的设置，使得编辑器更易于使用。

1. **自动保存**，这是最重要的一步：“偏好设置-通用-自动保存”，一定要把自动保存勾选上。防止你没有保存文件，突然电脑关机，然后丢失了一下午的工作。如果你已经丢失了的话，你可以在这里点击“恢复未保存的草稿”，说不定它还存在那里。
2. **一体化窗口样式**：“偏好设置-外观-窗口样式-一体化”，如果你使用过Mac系统，可能最印象深刻的就是其一体化窗口的沉浸感，使用这种设置也能在Windows上有相同的体验（同时推荐把Windows最底部的任务栏设置为自动隐藏）。
3. **打字机模式和专注模式**：所谓打字机模式就是你光标所在的段落会居中显示，感觉就如同传统打字机一样，打完一行纸张就会向上拉一行，这个模式快捷键F9即可。而专注模式则是让你正在编辑段落之外的段落都降低亮度，使得当前编辑的段落更突出，减少了视觉干扰。这两种模式都会让写作的过程更有沉浸感。

#### 1.3 使用技巧2：图床

Markdown是一种十分简介的标记语言，但是它有一个很重要的问题，就是对图片进行保存的问题。一般而言，Word文档会直接将图片包含在同一个文件内，而html会将图片统一归入一个文件夹，在现实的时候再引用。但是Markdown本质上仍然是纯文本的形式的，图片并不能直接包含在MD的文件内，所以通常而言有两种处理方法：

1. 将图片转化成文本的形式，即将一张图片转换为Base64编码，然后以文本的形式储存。这种方式的好处在于不怕图片丢失，坏处在于影响Markdown编写时的体验，因为转换成Base64编码的图片在编辑时显示的是一段极长的代码。

![image-20210205220636509](https://i.loli.net/2021/02/05/Bnhs7dpc4IYuGXV.png)

以上图为例，图片转化成Base64编码，使得整个文本基本没法编辑，因为这一张图片的编码比文章正文还长。

2. 从某个地方引用图片。一般也可以分为两种：
   1. 一种是本地的，即引用你本地储存的图片所在的地址（相对地址或者绝对地址）。但这样的问题就在于，如果你哪天不小心在电脑上把图片删了，那文档上也不可能再显示图片了。此外，如果你直接给朋友发MD文件，他也是看不到MD文件中所引用的图片的。
   2. 另一种就是引用一个网络地址。当然你可以直接复制图片的网址，但还是那个问题，就是这些网址你也不知道什么时候关门，所以也存在风险。此外，你自己的截图之类的也得找个网站传一下才能引用。这个时候，专门用来存放图片的网站就出现了，这就是**图床**。

这里不介绍更多了。直接说效果和方法。最后效果就是在Typora中粘贴一张图片，它就会自动上传到图床服务器，并转化成Markdown标记语言。

方法是采用PicGo+SMMS图床的方式。需要做的准备是安装PicGo，并且注册SMMS。

打开SMMS的网址（https://sm.ms/），“User-Register”，进行注册。

![image-20210205222401308](https://i.loli.net/2021/02/05/zNVP16RkU4mjFil.png)

注册并且登录之后，“User-Dashboard”，然后“API Token”，将其中的Secret Token（令牌）的内容复制下来。

![image-20210205222625165](https://i.loli.net/2021/02/05/LU3QqiywPM6a9fl.png)

打开PicGo，然后选择SMMS，将复制的令牌粘贴进去。

![image-20210205222804465](https://i.loli.net/2021/02/05/cfROU7128VokSGD.png)

然后，我们对Typora进行设置。“偏好设置-图像”，将“插入图片时”的选项改为“上传图片”，然后给“对本地位置的图片应用上述规则”和“对网络位置的图片应用上述规则”都进行勾选。

之后，对“上传服务设定”进行修改，“上传服务”改成“PicGo（app）”，“PicGo路径”改为你安装PicGo的路径。这个设置的意思是，当需要上传图片的时候，它会根据这个路径去把PicGo软件打开。

![image-20210205222910570](https://i.loli.net/2021/02/05/vuS4Ef9ngycMszL.png)

如果你不知道PicGo安装在哪里的话，可以选择快捷方式后右键，在属性中查看它的安装路径。

![image-20210205223300338](https://i.loli.net/2021/02/05/83y9fF27bHBKwvt.png)

之后复制到Typroa的图片都会自动上传图床了。如果偶尔上传失败，点击图片右键，再次上传即可。



### 2.更好的剪藏：简悦

Joplin有一个还算不错的剪藏插件，支持Firefox和Chrome浏览器。但是我个人还是认为体验并不足够。

我这里更推荐一款国产浏览器插件：简悦。

![img](https://camo.githubusercontent.com/b2e7cd0a790bf089aec41ed395bbcd1792cde4f9f438eb8ae520a6017da9f72f/687474703a2f2f73722e6b737269612e636e2f6c6f676f2532306269676765722e706e67)

简悦本身在不同平台都有，它是我最近用过的功能最为强大的阅读和剪藏插件了。具体的配置方式我放到文后了，这里只举一个使用例。

比如我们看到了这么一篇文章，想要剪藏。

![image-20210205224935504](https://i.loli.net/2021/02/05/2LsMGEK1IWr3Rof.png)



我们将这篇文章的链接复制到Chrome浏览器中，然后在网页上单击右键，选择“简悦-阅读模式”。

![image-20210205225146423](https://i.loli.net/2021/02/05/Nx9qzFgUTJQiXu5.png)

然后将鼠标放在屏幕右下角的三个点上，在弹出的菜单中选择“动作-保存到Joplin”（需要你先配置好，配置教程网址在文后）。然后我们切换回Joplin，就能看到一个很清爽干净的Markdown文档呈现在这里。

![image-20210205225404750](https://i.loli.net/2021/02/05/5pEKwgPXeWVlUNF.png)

当然，除此之外你还可以使用另外两种方法剪藏。“导出为Markdown”和“导出为离线Markdown”，前者就是把网页转化成MD文档，同时也会把图片也一起下载下来。而后者就如我们前面所说，图片是通过Base 64转化成了代码，所以导出的最后文件就是一个单独的MD文件。这两种都可以导入到Joplin中。

![image-20210205225514747](https://i.loli.net/2021/02/05/JUC4zVFYPujelfm.png)

### 3.更好的云同步：坚果云

我们在介绍Obsidian的时候就介绍过用坚果云进行同步，不过Joplin的同步方式有一些不同。不过这里篇幅有限，我也没有必要重复造轮子，如果有兴趣的话，直接使用坚果云的官方教程吧，链接我也放在文后了。

使用坚果云的原因也很简单，主流的国外主流的同步盘都被墙了，国内的同步盘坚果云算是最方便使用的。通过坚果云，Joplin凭借着多平台的客户端，就完全可以相互进行同步了。

![image-20210205230927824](https://i.loli.net/2021/02/05/5I3vJARbty4Smjr.png)

## 总结

本期文章就是使用这一整个流程的工具写就的，这其实也不是介绍单一的工具了。就像Typora其实完全可以单独拎出来写一期。但是如果既然工具之间相互能够更好的配合，就没有必要将他们割裂开来。我们专栏也同样，许多内容（有些是技术的、有些是工具的、有些是方法论的）会混杂在一期，即使我们不能很明白清楚地解释出来，我们也尽力为大家提供更多了解的途径。

毕竟介绍的工具总会过时，但是你也总是可以凭借这些知识打造更高效率的工作流。

## 附录1：一些可能存在的使用问题以及教程

1. Joplin默认文件储存位置的修改方法：[CSDN：修改joplin默认笔记存储位置](https://blog.csdn.net/lc315yuhuofei/article/details/106217087)，这个教程方法是正确有效的，但是使用时要把其中的代码的中文引号替换成英文引号。
2. Github上的文件下载，是在右边栏的Releases上。
3. Typora主题Flora的下载地址：[typora-theme-flora: A theme that looks as beautiful as flora.](https://github.com/wnanbei/typora-theme-flora)
4. Typora Themes Gallery：[Themes Gallery — Typora](https://theme.typora.io/)
5. 现在使用一些插件直接保存的离线Markdown就是使用的这种方法：[用 Base64 编码插入 Markdown 图片](https://www.jxtxzzw.com/archives/1700)
6. PicGo的下载地址：[PicGo: 一个用于快速上传图片并获取图片 URL 链接的工具](https://github.com/Molunerfinn/PicGo)
7. SMMS主页：[sm.ms](https://sm.ms/)
8. Joplin的剪藏插件下载地址：[Firefox扩展]([Joplin Web Clipper – Get this Extension for 🦊 Firefox (en-US) (mozilla.org)](https://addons.mozilla.org/en-US/firefox/addon/joplin-web-clipper/))；[Joplin Web Clipper - Chrome 网上应用店 (google.com)](https://chrome.google.com/webstore/detail/joplin-web-clipper/alofnhikmmkdbbbgpnglcpdollgjjfek)。Chrome的插件也是可以添加到Win10自带的Edge浏览器的。

9. 简悦的主页：[简悦1.0 - SimpRead：让你瞬间进入沉浸式阅读的扩展，还原阅读的本质，提升你的阅读体验](https://github.com/Kenshin/simpread)
10. 简悦的Joplin配置方法：[简悦-进阶功能](http://ksria.com/simpread/docs/#/Joplin)
11. Joplin使用坚果云同步的配置方法：[如何使用WebDAV关联坚果云与Joplin?](https://help.jianguoyun.com/?p=5633)

## 附录2：参考资料

1. 关于开源软件的介绍：[Red Hat：开源是什么？](https://www.redhat.com/zh/topics/open-source/what-is-open-source)
2. 关于自由软件运动，可以参考这本书：[Richard M. Stallman：自由软件，自由社会（第三版）](https://book.huihoo.com/free-software-free-society/index.html)
3. Wikidpad主页：[WikidPad is a Wiki-like notebook for storing your thoughts, ideas, todo lists, contacts, or anything else you can think of to write down.](http://wikidpad.sourceforge.net/)
4. Joplin主页：[Joplin: An open source note taking and to-do application with synchronisation capabilities](https://joplinapp.org/)，可以在这里下载各个平台的软件版本。
5. Typora主页：[Typora — a markdown editor, markdown reader.](https://typora.io/)
6. PicGo说明文档：[PicGo-指南](https://picgo.github.io/PicGo-Doc/zh/guide/#%E5%90%AC%E8%AF%B4%E4%BD%A0%E4%B9%9F%E6%83%B3%E7%94%A8picgo)
