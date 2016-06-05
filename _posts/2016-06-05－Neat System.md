---
title:  "OS简约系统的建构"
header:
  teaser: "https://farm5.staticflickr.com/4076/4940499208_b79b77fb0a_z.jpg"
categories: 
  - tech
tags:

# OS简约系统的建构

## 简约系统的优势（An Neat System）

* 简约
* 安静：便于注意力集中
* 稳定
* 高效
* 贴心

## 如何优化系统
优化系统有两种方式，即重装系统和优化系统。优化原则就是尽可能少的工具，尽可能熟练地运用。也就是说，用最少的工具，解决最多的问题。

* 重装系统：一般都是在系统“行将就木”的时候才会考虑重装，感觉重装一次系统太麻烦了。
* **优化再优化**

  优化的方式，是通过做减法（删减同类软件）和做加法（尝试新的优化工具）来尝试优化和完善自己常用的系统。

### 最佳应用软件清单

    * Chrome 浏览器：公司 Win 系统和自己的 Mac 系统下的常用浏览器
    * 终端：iTerm（Mac 系统），优化和扩展
    * 编辑器：TextMate、Sublime Text
    * Dropbox：云存储平台(国内访问好像有问题？)

* Dropbox 的优势（AZ老师强力推荐的存储工具）
    * 云存储
    * 全平台
    * 自动同步
    * 增量同步
    * 协同编辑
    * 扩展度高

* Dropbox 扩展应用
    * IFTTT: 在 Instagram 点赞照片后，自动保存
    * Day One ：日记 app 类应用，手机下载了一个，不过只用过一次。
    * 1Password ：
    * MWeb
    * TextExpander
    * Kindle 文件自动推送

* Git/ GitHub Desktop
* Evernote：
* Everything （公司的电脑 Win 系统，已经安装，找文件确实很方便）
* Spotlight ：Mac 下查找文件（命名规范，标题）
* Clover ／Finder： 任务管理器，集成式窗口，与Chrome 标签页操作类似，自由推拽，固定标签。群组功能
* 7-Zip／ The Unarchiver（与Win 系统下的文件传输，降低乱码概率）
* F.lux: 调节屏幕色温。日落时色温偏红


## 如何重塑系统

多探索，多尝试。工具不在多，而在于精，符合自己的使用情境，提高工作和学习效率。

常用工具，尽可能熟悉其功能。比如我个人工作中常用的 office 软件，其中 

### 图片处理工具
* Preview 和 Picasa ：用于简单的修改，剪切、压缩和转换格式
* Pixelmator、Affinity Designer、 Autodesk Pixlr、PS：高级修改；照片的修改；专业作图
* Sketch ： 图标修改


### Homebrew 是个什么鬼？
Homebrew 是Linux／Mac 下的**套件管理工具**，它提供大量优秀的应用软件包的分发下载，只不过它的渠道是通过命令行工具来进行检索于获取。Homebrew 的优势在于：

* 依存于系统既有的库，减少空间占用和冗余
* 使用 Git 进行管理和更新
* 定制容易
* 管理便捷

安装要求

* Mac OS
* Xcode CLI
* Git    

安装 Homebrew 流程

配置 Ruby Git （OS自带）

Xcode CLI 工具
`$ xcode-select --install`

通过 ruby 命令安装 Homebrew
`$ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" `

命令集

更新`$ brew update`

搜索所有存在的软件包 `brew search package_name`

安装 `brew install package_name`

列出已安装软件包 `brew list`

查看已安装软件包集相应版本 `brew list --versions`

删除 `brew remove package_name`

**Homebrew cask**类似于一个开源的 App Store。添加 Caskroom／Cask 库并安装 Homebrew-Cask: `$ brew install caskroom/cask/brew-cask

在 Cask 存在的优质应用列表（留待以后再慢慢研究）

效率：iterm2 Alfred sublime－text textexpander textmate

整合：dropbox Evernote anki 1password virtualbox

网络：google－chrome firefox thunder

查看：piscasa mplayerx skitch

通讯：Skype QQ


## 如何更高效地搜索（Google 搜索）

关键词：匹配的搜索内容和场景

### 搜索技巧
限定网站：
site:xxx.com +keyword

限定搜索结果：用形容词限定搜索结果

排除搜索：keyword －排除的内容

文件格式搜索：filetype:pdf/word/ppt/jpg/gif+keyword

多重搜索

自定义搜索引擎


[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/






    
