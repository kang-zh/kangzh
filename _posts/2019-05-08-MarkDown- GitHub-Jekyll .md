---
layout: post
title:  助力输出， MarkDown + GitHub + Jekyll  有轻功
date: 2019-05-08
description: 
categories: 
tags: [tool, selfedu]
---





<blockquote class="blockquote-center">作品和作品的差别，源于卡片。<br>人和人的差异，垒于习惯。</blockquote>




最近复盘，发现这大半年如有神助，几乎每月发布一个作品或项目，拿下个人探索路上一个又一个[小里程碑](#jump)。



相较过往，这输出密集程度算是突飞猛进。不禁好奇为何如此。得益于一群良师益友，叫我见贤思齐？可之前他们就在呀。因为工作节奏没有前两年紧张？或许，但光多点时间肯定不够。

思来想去，发现主要区别源于去年 9 月——那会儿我已有良好读写习惯打底，又幸运习得一套新的输出习惯，难怪如虎添翼。

好东西我向来不独自掖着。加之最近卡片写作、卡片大法传播越广，南辕北辙的输出姿势越多，体胖（pan）如我都看不下去了，撸起袖子就想……

说干就干！

咳，优雅习惯推介会，现在开始~
<!-- more -->

## 升级输出习惯

如果看过 [《卡片级输入输出工具，我选 WorkFlowy 》](https://www.kangzh.com/workflowy) 这篇文章，你应该知道若想畅快输出作品，为何卡片层级重要，以及如何挑选卡片工具。甚至你已尝试我推荐的方法，借 WorkFlowy 优化工作生活。

过去几年那套方法的确令我受益匪浅。但去年夏天，我工作情感生活状况频出，仅靠原有输出习惯，越来越不能满足诉求：

脑海中闪过无数思绪、观察，无论是为了记住还是为了忘记，都想及时捕捉，从大脑工作记忆（[working memory](https://en.wikipedia.org/wiki/Working_memory)）内存切换到外部载体；线上与人交流，输入界面常不友好，我喜欢到 MarkDown 编辑器里写好再发出，每次思考写哪、存否、存哪、命名也挺麻烦；打出不错内容未来要调取复用，再去对话界面搜寻实在繁琐，想不起在哪儿发布、意外丢失聊天记录更是徒增烦恼……

贪心如我，还想有个地儿作「[一个人的微博](https://www.yangzhiping.com/psy/quiet.html)」，同我[「品味（savoring）」生活](https://www.yangzhiping.com/psy/savoring-10.html)，或分担难过失意等当下不宜为熟人知的时光。不仅积累个人故事，录下欣然成长的自己，还能倒逼写作练习——毕竟不是私人笔记，不由得照顾读者观感琢磨文字嘛。

于是，我开始摸索更舒畅的输出姿势。结合已有的「 WorkFlowy 酝酿 + MarkDown 书写/编辑 + GitHub 托管/发布 」工作流，优化后的理想情况当如此：


- **想写就写**。无论沟通发言、朋友圈状态、写作练手，还是观察反思、日记灵感，只要想写，打开即写，不必纠结存否、存哪、命名。
- **方便检索调取，及时取用**。
  - 时间维度：三年五年甚至十年后，依然可以调取；积累三年五年甚至十年后，搜索加载依然快。
  - 空间维度：在不同电脑切换，比如工作电脑和个人电脑上，都能随时调取和更新。在移动设备也能调取并更新更好，不行也无妨，毕竟多数时候我电脑随身。
- **可作「一个人的微博」，方便积累个人故事及练习写作**。这需要内容发布后可修改，才不阻断「慢改」；鲜有广告，也不会被强推内容，没啥噪音分散注意力；支持 MarkDown ，可平滑接入原有读写发布工作流；可设置自由设定访问权限，比如分享给特定朋友或公开访问。

需求列完，眼瞅这坑我心里特没底，灌了两桶酸奶仍不见底……

好在倒腾俩月，终把坑填——

## MarkDown + GitHub + Jekyll  有轻功

庞杂需求如上，只靠一款工具难以满足。摸索再三，这套组合拳最得我心：

- **有目录视图、支持文件管理的 MarkDown 编辑器**：MWeb
- **云端同步工具**：GitHub
- **一个人的微博**：Jekyll 

工具不稀奇，关键在用法。领会要点，再依已有习惯自选趁手工具，更是妙哉。

### 以「周」为单位记忆外部化

**日常以「周」为单位新建 MarkDown 文档，这周任何想写的内容，都写在当周文档里**。文档命名也省心，`文档类别代号+年月+周数`即可，比如这是我养成这个习惯至今的记录：

	Mur1709w37.md Mur1711w45.md Mur1801w01.md Mur1802w09.md Mur1804w17.md Mur1806w25.md
	Mur1709w38.md Mur1711w46.md Mur1801w02.md Mur1803w10.md Mur1804w18.md Mur1806w26.md
	Mur1709w39.md Mur1711w47.md Mur1801w03.md Mur1803w11.md Mur1805w19.md Mur1807w27.md
	Mur1710w40.md Mur1711w48.md Mur1801w04.md Mur1803w12.md Mur1805w20.md Mur1807w28.md
	Mur1710w41.md Mur1712w49.md Mur1801w05.md Mur1803w13.md Mur1805w21.md Mur1807w29.md
	Mur1710w42.md Mur1712w50.md Mur1802w06.md Mur1804w14.md Mur1805w22.md
	Mur1710w43.md Mur1712w51.md Mur1802w07.md Mur1804w15.md Mur1806w23.md
	Mur1710w44.md Mur1712w52.md Mur1802w08.md Mur1804w16.md Mur1806w24.md

**文档里，按天划分组块**，时间是一级标题，正文概要作二级标题，**按时间倒序排列**。如此便可凭目录栏随心跳转，快速修改已有内容：

![mwebtoc3.png](https://raw.githubusercontent.com/kang-zh/yunimage/master/blog/mwebtoc3.png)


为了区分内容类型以便查找复用，我还建了套标记规则，加在内容概要之前，一目了然各条状态：

- `0`：未发出
- `1`：已发出、已使用
- `-1`：已发布后又修改，但还未同步更新到发布界面（由于我习惯多次修改，改后不会马上更新到发布界面，而是等个一两天没什么还想改的再更新，所以需要这个标记提醒自己）
- `0-`：尚未发布，但有价值，适合继续修改以备未来使用

如此，写意来临，便可立马打出 `## 0` 而后开写，方便时再加标题。甚至一天忙完，该 commit 到 GitHub 私有库，才把当天各标题补上。
<br>

如果你像我一样懒，还可借这仨技巧能省则省：

1. 一级标题所需的「当天时间」，用输入法自带的当前时间。比如在搜狗拼音输入 `sj` ，候选项就会出现当前时间，选择即可输入。如此，不仅可作一级组块区分标记，还可记录当天遐思何时开始：

	![mwebtricks1.gif](https://raw.githubusercontent.com/kang-zh/yunimage/master/blog/mwebtricks1.gif)

	对了，当天时间最好选全 ASCII 字符的表达方式，不带汉字，未来若想跑个脚本分析也省心。比如我习惯晨间日记，可借此分析某阶段早上何时进入状态。



2. `## 0` 等常用字符，使用 aText 这类工具设置缩写规则，比如 `;0 == ## 0` ，简化输入流程。当天遐思的同步到 GitHub 所用的 commit message，当然也设缩写，比如 `uft == update for today` ：

	![mwebtricks3.gif](https://raw.githubusercontent.com/kang-zh/yunimage/master/blog/mwebtricks3.gif)

3. 其它 MarkDown 标记比如 `#` ，以及各视图切换等常用操作，用 [MWeb 快捷键](http://ishanshan.zoomquiet.top/share/mwebtricks7.png)简化输入流程。

![mwebtricks4.gif](https://raw.githubusercontent.com/kang-zh/yunimage/master/blog/mwebtricks4.gif)

这样下来，每周文档只含字符，图像影音托管给七牛云，单个文档即使万字，也就十来 k 。如此这般，该文档常开也不费劲儿，我想写的现在就写;-)

还有啥优势？**轻盈省心、数据在自己手里，若想保持此输出习惯，十年百年不在话下**。

### 用「一个人的微博」促进快写慢改


记忆外部化搞定，该填贪心挖的坑。


多方测试，我发现 GitHub +  Jekyll  最适合作「一个人的微博」。不信你瞅 [https://www.kangzh.com](https://www.kangzh.com]) ？

不仅版式优雅，需求还都满足：

- 内容发 markdown 编辑后直接同步；布后可修改 ，GitHub desktop 自动识别文件修改，一键提交，OK！
- 没有广告，自己的博客怎样都行
- 支持 MarkDown 
- 自适应各种平台（电脑、平板、手机……）

或许还有更合适的，但**最优解可遇不可求，找到满意解，先跑起来再说**：）


跑了大半年，发现不但好使，还有意外收获：我总是发布后，才很快想到要修改哪里。如果说以周为单位想写就写的「记忆外部化」习惯利于「快写」，那发到「一个人的微博」这套习惯，无疑加速了我练习「慢改」。而**「快写慢改」，正是调和人类自主心智（[Autonomous Mind](http://www.keithstanovich.com/Site/Research_on_Reasoning_files/Stanovich_Two_MInds.pdf)）和算法心智（[Algorithmic Mind](http://www.keithstanovich.com/Site/Research_on_Reasoning_files/Stanovich_Two_MInds.pdf)）、创造动人作品的最佳范式**啊！


从此，我便沉浸在这样舒爽的输出习惯中自拔不能：当周 MarkDown 文档常开，随时记忆外部化。那些需要发布的，就贴到对应渠道发出。如果想到要修改，就在 MarkDown 编辑器里改好，再更新到对应渠道。每天 commit 同步到 GitHub 一次；若有值得保存的版本对比，则改动后立即 commit 一次留备后用。



## 小结

作品和作品的差别，源于卡片。人和人的差异，垒于习惯。一切皆时间的函数，时间最可怕的是复利效应。


<br> 

---


PS.

1. 此文转载自 [卡片助力输出， MarkDown + GitHub + LOFTER 有轻功](https://ishanshan.im/selfedu/tool/HbOutputOwetoCards) ；原文博客很久未维护，图片已经不显示，转此留存。且有增删改部分以适合本人需求。


## CHANGELOG
- 190502 LOFTER（简单易操作；版式各方面不支持自定，偏重社交，相对自建博客还是不够清爽） 替换为 Jekyll  
- 181231 增加 Windows MarkDown 编辑器推荐（[Typora](https://typora.io/)），把开头内容移到附录
- 180720 和 MWeb 开发者确认目录视图调整方案后，修改 MWeb 推荐说明
- 180717 根据反馈增补内容，强调增进作品质、量的关键，在以「周」为单位记忆外部化，并用「一个人的微博」促进快写慢改，而非具体哪个 App
- 180716 优化样式和表达
- 180715 累计快写慢改近 50h 终于发布
- 180707 创建
