---
layout: post
title: "Learn Jekyll"
description: ""
category: jekyll
tags: [jekyll]
---

## Jekyll 学习笔记

###  一. Jekyll简介

Jekyll([官网](https://jekyllrb.com/docs/)，[官网翻译](https://jekyllcn.com/))是一种轻量级用于生成静态站点内容的软件，目前它多被用于撰写个人博客，和它类似的还有[hexo](https://hexo.io/)和[hugo](https://gohugo.io/)。

---

### 二. Jekyll的安装

Jekyll本身是用Ruby语言编写，需要先安装Ruby的开发环境。通过以下几步来完成Jekyll的安装:

#### 1.安装Ruby

去Ruby的[官网](https://www.ruby-lang.org/en/downloads/), 根据不同的操作系统选择合适的安装包进行安装。官网比较推荐在Linux平台进行安装。如果是在Windows上安装的话，安装过程中，要**勾选所有的**，默认只勾选前两项。

```ruby
安装后通过查看版本来确认安装成功:
ruby -v
ruby 2.6.3p62 (2019-04-16 revision 67580) [x64-mingw32]
```

#### 2. 安装RubyGems

>The RubyGems software allows you to easily download, install, and use ruby software packages on your system. The software package is called a “gem” which contains a packaged Ruby application or library.
>
>Gems can be used to extend or modify functionality in Ruby applications. Commonly they’re used to distribute reusable functionality that is shared with other Rubyists for use in their applications and libraries. Some gems provide command line utilities to help automate tasks and speed up your work.

RubyGems是Ruby的包管理器，它会将Ruby的应用程序打包的一个Gem里，在**最新版本的Ruby安装程序中，已经包含了RubyGems**。

**Gem又是什么鬼?** Gem是封装起来的Ruby应用程序或代码库，可以理解为Java中已经JDK自带的库。

```ruby
安装后通过查看版本来确认安装成功:
gem -v
3.0.3
```

有一个默认的sources，用于下载更新，sources默认的地址是国外，速度非常慢，需要替换成国内的sources。

```ruby
gem sources --add https://gems.ruby-china.com/ --remove https://rubygems.org/
```

#### 3. 安装Jekyll

```ruby
安装命令: gem install jekyll
安装后通过查看版本来确认安装成功:
jekyll -v
jekyll 3.8.6
```

#### 4. 安装Bundler(可选，但强烈建议安装)

>Bundler provides a consistent environment for Ruby projects by tracking and installing the exact gems and versions that are needed.
>

Bundler是一个可以批量执行gem的工具。它的存在是为了解决安装Gem时软件之间的版本冲突。


```ruby
安装命令: gem install bundler
安装后通过查看版本来确认安装成功:
bundler -v
Bundler version 2.0.2
```

#### 5. 启动Jekyll





---


### 三. Jekyll的使用





---
###### 参考:

[整理Ruby相关的各种概念（rvm, gem, bundle, rake, rails等）](https://henter.me/post/ruby-rvm-gem-rake-bundle-rails.html)

[RubyGems维基百科](https://zh.wikipedia.org/wiki/RubyGems#)

[Ruby的Gem是什么](https://blog.csdn.net/guyue35/article/details/54898439)

[Bundler官网](https://bundler.io/)

[RubyGems官网](https://rubygems.org/?locale=zh-CN)











