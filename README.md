

## About
这个github仓库，是`eqgrp-free-file.tar.xz` 的免费解压版本， 源文件由“The Shadow Brokers”黑客组织放出。 加密的拍卖版本可以在网上找到和下载。 

Firewall 这个文件夹包含了所有的源文件。 listing.txt则是所有文件的清单。  

This repository contains the decrypted and decompressed contents of the `eqgrp-free-file.tar.xz` file released by "The Shadow Brokers". The contents are supposedly a free sample of the files exfiltrated from the [Equation Group](https://en.wikipedia.org/wiki/Equation_Group), a notorious, highly-sophisticated cyber attack group.

The Shadow Brokers have opened an auction to sell off the remaining files, although the legitimacy of the auction is widely disputed. See the original auction announcement here: https://theshadowbrokers.tumblr.com/post/148871184165/equation-group-cyber-weapons-auction

Only files in the [`Firewall`](Firewall) directory are from the archive. [`listing.txt`](listing.txt) shows a list of all the files in the original archive, along with their file date and timestamps.

## Disclaimers
声明
这个仓库作为“The Shadow Broker”组织的所声称的事实的检验， 同时给那些想学习nb入侵技术的安全爱好者提供研究。 本人不对可能产生的任何后果负责。 

这些源文件和代码不属于我。 代码的作者的版权也不得而知。 如果我的行为侵犯了版权， 请通知我， 我会及时从仓库移除这些代码。 

This repository is provided as an educational resource to researchers wanting to validate the claims of the Shadow Brokers, as well as anyone wanting to study code potentially originating from a powerful threat actor. Needless to say, this repository may contain extremely malicious code, and I (@nneonneo) disclaim any responsibility for what may happen with your use or misuse of this software.

The code does *not* belong to me, but the author of the code is unknown and is very unlikely to step up to enforce any copyright claims. Nevertheless, if takedown is warranted I will gladly remove the repository.


free-file的文件主要涉及的内容是针对防火墙的扫描器、漏洞利用框架等等:
- BLATSTING -- 穷举爆破
- EXPLOITS -- 漏洞利用代码
- OPS -- 攻击操作控制工具包
- SCRIPTS -- 脚本资源引用库
- TOOLS -- 辅助工具包(编码转换、IP格式转换、加密解密装换等等)

有安全团队分析了相关的文件。 感兴趣的可以看一下。 

[8月19日：Shadow-Brokers所泄露文件的介绍、技术分析（上）](http://bobao.360.cn/learning/detail/2970.html)

大家可以重点关注下SecondDate相关的代码和工具,美国国安局在巴基斯坦和黎巴嫩的行动中曾使用过这个工具

[网络报道- 斯诺登：美国网络战争“武器库”被袭击](http://www.ithome.com/html/it/251065.htm)

有安全爱好者对eqgrp的相关文件做了深度分析和测试

[NSA（美国国安局）泄漏文件深度分析（PART 1）](http://www.freebuf.com/news/topnews/112447.html)

国外黑客对目录的解析

[Equation Group Firewall Operations Catalogue](https://musalbas.com/2016/08/16/equation-group-firewall-operations-catalogue.html

天融信产品的相关漏洞利用

[NSA方程式组织（Equation Group）泄露的天融信产品漏洞分析（一）](http://www.freebuf.com/articles/system/112482.html)

e安全对各模块的功能分析

[美国NSA“方程式组织”使用的黑客工具列表及功能解释](http://www.easyaq.org/info/infoLink/970229833.shtml)

分析\eqgrp-free-file\Firewall\EXPLOITS\EXBA的思路、搭建漏洞环境的过程和利用条件测试
[Cisco SNMP RCE漏洞复现过程](http://www.freebuf.com/vuls/112589.html?utm_source=tuicool&utm_medium=referral)

[方程式再曝0day漏洞：超84万思科设备受影响](http://www.freebuf.com/news/115118.html)
