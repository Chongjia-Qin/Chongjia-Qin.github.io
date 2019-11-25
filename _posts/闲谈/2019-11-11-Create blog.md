---
title: "Create your own blog"
subtitle: "如何创建自己的博客"
layout: post
author: "Chongjia Qin"
header-style: text

tags:
  - 闲谈
---
其实想要搭建自己的博客想法已经萌芽很久了...今天他终于来了！
如果你也想和我一样拥有一个属于自己的博客，那我们就开始吧！搭建博客非常简单，只要你完成以下步骤，你也可以拥有属于自己的博客！
### 第一步：登录Github（假设你已经有了账号） ###
#### 1.1 创建一个仓库 ####
登录之后，你会看到这个按钮
![](/img/create my blog/1.jpg)
点击之后你会看到下面内容
![](/img/create my blog/2.png)
第一个红线是要创建的仓库的名称，这里要注意格式：用户名.github.io，例如我的用户名是Chongjia-qin，那么这里仓库名就需要填入Chongjia-qin.github.io
第二个红圈表示是否需要创建一个README文件，这里我们就不创建了，因为我们下面会用到Jekyll为我们提供的模板里面有。
#### 1.2 创建完后 ####
![](/img/create my blog/3.png)
这里显示的URL，就是当前仓库的远程地址，可用于clone或者push。
现在github的工作就准备完成了90%，还剩下SSH公钥没配置，后面会提到。
### 第二步：安装git+Jekyll ###
#### 2.1 下载安装git ####
地址在这里：[https://git-scm.com/download/win](https://git-scm.com/download/win)
安装完git点击后鼠标右键应该会出现下面两个选项
![](/img/create my blog/4.png)
#### 2.2 安装ruby ####
下载链接：[https://rubyinstaller.org/downloads/](https://rubyinstaller.org/downloads/)
![](/img/create my blog/5.png)
