# WCplus

## 介绍
本项目旨在逆向WCplus源码，并提供相关license生成算法，相关讨论见 https://www.v2ex.com/t/551219 原项目介绍如下：

> 在超过两千万的公众号中，假如每个公众号平均发文1000篇，合计500亿篇文章，每个中国人能分到36篇。这些文章在提供大量资讯、信息、知识的同时，已经渗透到了各行各业。其中，互联网、教育、金融的内容最多。细细深挖，总能发现鲜为人知的信息差，如果你了解公开情报分析Open Source Intelligence的原则，微信公众号的数据一定不能错过。
> 只要有一个微信账号，任何一个公众号的内容都可以查看，但是你真的会看吗？真的能看懂吗？真的有时间看吗？请承认，总有那么一小撮人，深谙这些方法和技巧，他们的思维方式和信息渠道完全吊打挤在同一条地铁中的其他人。不管是印刷术、互联网还是微信公众号实际上都加剧了信息不对称，请务必笃信这一点。
> WCplus提供了较大规模数据采集、存储管理，以及即将推出的搜索和AI数据分析，旨在进一步加剧这种信息不对称，强者更强，弱者自得安逸。WCplus没有没荡平信息不对称的远大抱负，专注为少部分人提供更先进的武器，洋枪洋炮对大刀长矛 。

更多原项目的详情与使用指南请参考：https://shimo.im/docs/dA7ejdOQuPwo7NZV/read


## 运行 WCplus
WCplus 没有原版打包程度高，所以无法实现一键运行，但是运行依然很简单，只需三步简单配置即可

### 依赖
WCplus 依赖 Python3 运行，请先安装 Python ，最好是 python 3.6 。

### 安装Python依赖
`pip3 install -r requirements.txt`

### 安装MongoDB
// TODO:

### 运行
`python3 main.py`

以上就是运行 WCplus 所需的所有步骤

## 生成证书
如果你想要使用原版exe程序（[下载](https://github.com/fuckwonderfulsuccess/WCplus/releases)），可以使用license generator生成一个license.ca授权文件，按照使用说明配置即可。license generator使用方式为：
```
python3 license_generator.py 标识码
```

## 其他声明
本人没有太多时间参与源代码的维护工作，不能保证所有 issue 都能在短时间内得到解决
