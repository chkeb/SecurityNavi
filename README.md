网址：https://urdr-gungnir.github.io/tools/#

# 前言

我想开这个项目的目地是，让新手、安全从业者，在刚刚涉及某一领域的时候，想找工具，但是不知道用什么，或者根本不知道有哪些比较好的工具。

结合之前的经历，我觉得，存在一个误区，很多安全导航是尽可能全，或者把知名的东西列出，这样造成大家认识知道这个工具好，所以认为这个导航好，如果大家不知道这个工具，大家就不知道导航给的好不好，而不是因为导航给了这个工具，这个工具肯定是好的，我就是想做这个事。

所以，我想结合自己经历，去完善这一部分。

# SecurityNavi

一个安全导航，包括安全工具、安全学习资料

我不想把冗余的大量工具都列出来，没啥意义，我想把我觉得各个方向真的能用到的、好用的工具列出来，供大家使用。

往往新手也会面对很多工具的抉择，我列出的工具虽然不一定保证最适合你，但是它一定在某一领域有优于其他工具的地方，用它绝对不会太拉跨。

学习资料也是我自己学习、看过的，所以至少不会浪费大家时间。

也可以推荐给我工具，直接提Issue就可以。

# 目前收录

## 安全工具

---

`信息收集`

|                         工具                         |                             介绍                             |
| :--------------------------------------------------: | :----------------------------------------------------------: |
|   [ARL](https://github.com/TophantTechnology/ARL)    |     一站式资产探测，包含域名、IP、指纹、文件泄露等等。。     |
| [OneForAll](https://github.com/shmilylty/OneForAll)  |           OneForAll是一款功能强大的子域名收集工具            |
|   [JSFinder](https://github.com/Threezh1/JSFinder)   | 目前比较成熟的js接口收集工具，我们可以通过它去收集一些藏在js中的有用接口 |
|  [ehole](https://github.com/EdgeSecurityTeam/EHole)  |    ehole是一款较全的系统指纹探测工具，其中的指纹库很不错     |
| [dirsearch](https://github.com/maurosoria/dirsearch) |                   扫目录嘎嘎强，字典很强大                   |
|     [dumpall](https://github.com/0xHJK/dumpall)      |      .git/.svn/.DS_Store泄漏和目录列出，一个工具完成了       |

---

`漏洞检测及利用`

|                             工具                             |                             介绍                             |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
|     [nuclei](https://github.com/projectdiscovery/nuclei)     | 基于YAML的漏洞扫描仪。我认为是目前开源漏扫工具中最出色的（我用过的）。 |
| [JNDI-Injection-Exploit](https://github.com/welk1n/JNDI-Injection-Exploit) |         JNDI注入测试工具(star最多的，还是比较好用的)         |
|      [ysoserial](https://github.com/frohoff/ysoserial)       |   构造java的反序列化payload毫无疑问是它，有着全面的利用链    |

---

`代码审计`

|                    工具                    |                          介绍                          |
| :----------------------------------------: | :----------------------------------------------------: |
| [CodeQL](https://github.com/github/codeql) | 很有未来的语义代码分析引擎，代码审计神器，批量挖洞yyds |

---

`Webshell管理工具`

|                             工具                             |                           介绍                            |
| :----------------------------------------------------------: | :-------------------------------------------------------: |
| [Godzilla【哥斯拉】](https://github.com/BeichenDream/Godzilla) |    号称shell均可绕过市面所有静态查杀、WAF,自带众多插件    |
|   [Behinder【冰蝎】](https://github.com/rebeyond/Behinder)   | 多采用加密传输,可Java内存马注入、支持多种Web容器、反向DMZ |

---

`安全多功能平台`

|                   工具                    |                             介绍                             |
| :---------------------------------------: | :----------------------------------------------------------: |
| [Yakit](https://github.com/yaklang/yakit) | 一站式安全工具，包括burpsuite的功能，还能进行漏扫等等其他操作，可用性很强 |



## 安全学习

---

`Web安全学习资料`

|                             资料                             |                             介绍                             |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| [Web安全学习笔记](https://websec.readthedocs.io/zh/latest/)  | Web安全较为系统的学习手册，内容不够深入，但是他比较全、系统，还是适合新手。 |
|               [JavaSec](https://javasec.org/)                | java Web安全的手册，我学习java安全，也是跟着这个手册，再向外扩展。 |
| [JavaThings [java安全漫谈]](https://github.com/phith0n/JavaThings) |     p牛的，学java安全看看会有很多收获，不过要收费入圈子      |

---

`安全社区`

|                     资料                     |                             介绍                             |
| :------------------------------------------: | :----------------------------------------------------------: |
|      [先知社区](https://xz.aliyun.com/)      |  阿里的安全社区，虽然看起来简陋，但是有很多原创高水平文章。  |
|  [seebug-paper](https://paper.seebug.org/)   | 知道创宇的高水平paper，有很多不错的文章，而且各类都有，扩展眼界。 |
|      [跳跳糖社区](https://tttang.com/)       |                 几乎都是高水平的文章，很不错                 |
|     [吾爱破解](https://www.52pojie.cn/)      |       经典且庞大的破解社区，破解软件什么的在这都能发现       |
| [Security Search](http://helosec.com/search) |    安全搜索引擎，专注安全搜索。(不是社区，但是我放在这了)    |

## 漏洞

---

`漏洞库`

|                             名称                             |                         介绍                          |
| :----------------------------------------------------------: | :---------------------------------------------------: |
|             [Peiqi文库](http://wiki.peiqi.tech/)             | 最著名的基于docker的漏洞靶场，一键化搭建真实漏洞环境  |
| [白阁文库](https://wiki.bylibrary.cn/%E6%BC%8F%E6%B4%9E%E5%BA%93/01-CMS%E6%BC%8F%E6%B4%9E/ActiveMQ/ActiveMQ%E4%BB%BB%E6%84%8F%E6%96%87%E4%BB%B6%E4%B8%8A%E4%BC%A0%E6%BC%8F%E6%B4%9E/) |    基于docker的IOT漏洞靶场，一键化搭建真实漏洞环境    |
|            [阿里云漏洞库](https://47.101.61.67/)             |                    阿里云的漏洞库                     |
|          [exploit-db](https://www.exploit-db.com/)           |                    国际知名漏洞库                     |
| [Windows提权EXP搜索](http://blog.neargle.com/win-powerup-exp-index/#) | Windows提权EXP在线搜索工具，在内网渗透很方便找提权exp |

---

`真实漏洞靶场`

|                         名称                          |                         介绍                         |
| :---------------------------------------------------: | :--------------------------------------------------: |
|      [vulhub](https://github.com/vulhub/vulhub)       | 最著名的基于docker的漏洞靶场，一键化搭建真实漏洞环境 |
| [IOT-vulhub](https://github.com/firmianay/IoT-vulhub) |   基于docker的IOT漏洞靶场，一键化搭建真实漏洞环境    |
|      [Vulfocus](http://vulfocus.io/#/dashboard)       |      白帽汇的靶场，内置不少真实环境，更加方便了      |

