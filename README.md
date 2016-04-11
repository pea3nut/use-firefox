# 为什么要学习使用Firefox？

网页浏览器已经成为现在上网中娱乐办公必备的软件，如果能有一个称心如意的浏览器，那么对于工作和生活的帮助无疑是极大的。在国内，有多种网页浏览器可以选择。不严谨的说，大部分国产浏览器实际上是将其他浏览器**原创**浏览器内核进行二次开发，然后打包发布的，而截止到2015年，还在维护使用的浏览器（内核）仅包括

- 谷歌浏览器 —— Chrome
- 苹果系列浏览器 —— Safari
- 火狐浏览器 —— Firefox
- 微软系列浏览器 —— IE & Edga

Opera浏览器已经将内核换为Chrome内核（Blink）了，而国产浏览器大部分是Chrome+IE双内核。

那么，如果把上面的浏览器必做出行工具，那么差不多就应该是

- 国产浏览器 —— 方便的自动挡车
- Chrome —— 手动挡跑车
- Firefox —— 复杂的改装车

针对一般用户而言，使用国产浏览器可以快速的上手，几乎无需任何配置就可以完成大部分工作，但不会用的很舒服。而Firefox则正相反，如果不进行配置直接使用会有很多的不便，但是如何经过精心的配置，那么会用的非常舒服。

如果你喜欢DIY，想要打造一个“属于”自己的浏览器，那么，Firefox绝对是你的不二之选。

当然，想要配置Firefox也是有一定难度的，不过不要紧，本文会慢慢的帮助你一点点配置好属于你“自己”的Firefox。

# 关于本文

本篇文章会从头开始详细介绍如何使用Firefox（火狐浏览器），帮助新人轻松的从0开始一点点打造一个“属于自己”的强大浏览器。

因为本文原作者水平不高，可能无法充分的介绍出Firefox的威力，欢迎其他的Firefox爱好者一同帮忙完善此文，将我们心爱的Firefox推广给更多的人去使用。

> 一款产品的良心，不在于它对于大部分用户的态度，而是取决于它是否照顾到某一小部分人。

# 安装篇

Firefox有多种版本，首先我们需要选择一款适合自己的版本。

目前针对国内Windows用户来说，除了Mozilla官方提供的版本（国际版），我们还可以选择谋智火狐针对国内环境的优化版的Firefox（中国版）。

- 国际版：https://www.mozilla.org/en-US/firefox/all/
- 中国版：http://www.firefox.com.cn/download/

## 选择国际版还是中国版

### 关于谋智网络

> 成立于2005年3月4日，是Mozilla在中国北京的全资**子公司**，负责Mozilla在华的本地化营销、社区活动和赞助活动

> 北京谋智网络技术有限公司（英语：Beijing Mozilla Online Ltd），又称谋智中国或谋智网络，是一个帮助Mozilla基金会在中国推广和部署其产品的公司。

> 和Mozilla公司类似地，谋智中国是一个由非盈利慈善事业机构（Mozilla基金会）出资创办的商业性公司。


—— 来自维基百科[谋智中国](https://zh.wikipedia.org/wiki/%E8%B0%8B%E6%99%BA%E4%B8%AD%E5%9B%BD)、[Mozilla基金會](https://zh.wikipedia.org/wiki/Mozilla基金會)

所以说，中国版Firefox并不是个人的二次修改版，而是属于Mozilla官方的产品，不必担心某些安全问题。

### 中国版Firefox的缺点

中国版Firefox缺点并不大，据笔者所知，最明显的一点莫过于没有64位的Firefox。如果你选择中国版Firefox，就只能用32位版本的Firefox了。不过这影响并不大，32位的中国版Firefox可以在64位的系统中正常工作。

还有一些其他的小瑕疵，比如到双11购物狂欢节的时候可能会强制添加一个某宝的书签。

### 中国版Firefox的优点

谋智火狐为了帮助Firefox适应中国环境对Firefox做了很多人性化的修改，如中国版特有的许多插件。据笔者所知，最明显的一点莫过于“同步”功能：由于中国大陆独有的防火墙，在访问海外IP时会有诸多问题。因此，谋智公司在国内搭建了一个用于同步的服务器来解决这个问题，并且你也可以随时切换成国际版的同步。

关于缺点，64版本的问题影响也是比较小的，32位的Firefox几乎不会遇到性能的瓶颈，而强制添加的情况也很少出现（一年1次左右），并不会影响正常的使用。

### 关于选择的建议

如果在语言方面没有什么障碍的话，建议选择中国版的Firefox。对比那些微不足道的中国版Firefox的缺点，谋智中国专为国内上网环境订制的Firefox各种便利明显要更为实惠一些。

## 关于ESR版（延长支持版）

Firefox一共有3钟更新通道，分别是：

1. 开发版（更新最快，最不稳定）
2. 正式版
3. 稳定版（更新最慢，最稳当）

其中非开发人员不建议选择开发版的Firefox，更新频率太快且不稳定。而正式版（又称曙光版）则是Mozilla默认提供下载的版本，也是本文推荐下载的版本，但是如果在你的工作或生活中浏览器占据一个非常重要的位置，那么你可以选择ESR版。

> 延长支持版本（Extended Support Release, 简称“ESR”）是 Mozilla 专门为那些无法或不愿每隔六周就升级一次的企业打造。Firefox ESR 版的升级周期为 42 周，而普通 Firefox 的升级周期为 6 周。
> —— 引用自[Firefox 火狐浏览器 延长支持版](http://www.firefox.com.cn/download/#download-esr)

- 中国版ESR：http://www.firefox.com.cn/download/#download-esr
- 国际版ESR：https://www.mozilla.org/en-US/firefox/organizations/all/

## 针对 XP SP2 及更早版本的用户

针对 Windows XP SP2 及更早版本的用户，最新版本的Firefox可能无法在你的电脑上正常工作，在各个下载页面可以找到Mozilla针对 Windows XP SP2 及更早版本用户推出的Firefox。

请留意下载页面的文字：

![中国版Firefox低版本入口](img/for-xpuser-firefoxdownload-china.png)

## 其他资料

- 国际版Firefox大全（Mozilla FTP）：http://ftp.mozilla.org/pub/firefox/releases/

# 配置篇

# 插件篇