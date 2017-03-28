---
title: GitHub Pages + Hexo搭建个人博客
date: 2017-02-07 14:42:59
categories:
- 技术
- github

tags:
- 博客
- 技术
- github

---
新年第一天上班，没啥太多工作，于是心血来潮用GitHub Pages + Hexo搭建了个人博客。网上有好多帖子可以参考，由于大家经验和语言表达的不同，我还是看了一大圈资料才弄好，下面我分享下步骤。

<!-- more -->

### 1、Hexo框架
[快速、简洁且高效的博客框架Hexo](https://hexo.io/zh-cn/)，有中文文档，跟着步骤来。

### 2、NexT主题
[精于心，简于形NexT](http://theme-next.iissnan.com/)，还有中文文档，一步一步来。貌似这是网上评论最好的博客主题。
### 问题
总体来说就是这么简单，在windows下我没发现什么问题，但在Mac下发现没有wget，[https://www.zhihu.com/question/19863831](https://www.zhihu.com/question/19863831)这里有回答。
还有就是多个电脑共同维护时的问题，知乎里有个哥们思路很好：**一个分支用来存放Hexo生成的网站原始的文件，另一个分支用来存放生成的静态网页。**这是知乎回答链接[https://www.zhihu.com/question/21193762](https://www.zhihu.com/question/21193762)