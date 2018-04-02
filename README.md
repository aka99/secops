# secops

只更新最近一次
git clone https://github.com/aka99/secops.git --depth=1


## 工具
### HTML/CSS
http://www.ibootstrap.cn/

### 开发工具
- [IntelliJ IDEA 简体中文专题教程](https://github.com/judasn/IntelliJ-IDEA-Tutorial)

### Python 
- [那些有趣/用的 Python 库](https://mp.weixin.qq.com/s/6wZTZmg59L-u8X7TR0_Pwg)

### 安全工具

Java 开发安全框架:
- Spring Security 
- Apache Shiro

[Spring Security DEMO & Guides](https://github.com/ChinaSilence/any-spring-security)
[Spring Boot 最佳实战，精致UI，丰富内容](Java 爬虫)

Dependency Check 第三方组件安全检查
`./dependency-check.sh --project "Web" -s ~/Downloads/S2-046-PoC-master/`

爬虫，代理服务:
- https://scrapinghub.com/crawlera/

静态扫描：
- https://github.com/scovetta/yasca


- [安全行业从业者自研开源工具清单](https://github.com/We5ter/Scanners-Box)
- [安全平台框架](https://github.com/martinzhou2015/SRCMS)
- [XSS跨站平台](https://github.com/imlrhui/xssplatform/tree/master/xssplatform)
- [攻防演练平台](https://github.com/710leo/ZVulDrill)
- [巡风系统](https://github.com/ysrc/xunfeng)


**SSHFS**  
目的：通过SSH映射远程服务器目录，进行文件扫描
步骤：
- 客户端何服务器安装 sshfs
- 客户端访问 密码认证 sshfs -o allow_other aka77@hd:/home/aka77/ /mnt/hd
- 客户端访问 证书认证 sshfs -o IdentityFile=~/.ssh/id_rsa aka77@jp:/home/aka77/ ~/jp

###  IRC Client for Macos
- LimeChat_2.42

Android
- BytecodeViewer Java Jar 代码查看，比jd-gui强

Spring Boot 入门
- [入门教程](https://github.com/ChaoZeyi/SpringBootLearning)
- [项目管理利器maven](http://www.imooc.com/learn/443)
- [Spring入门篇](http://www.imooc.com/learn/196)


https://github.com/ChaoZeyi/SpringBootLearning
安全技能： 
- sqlmap 、mitmproxy  BeEF 

Web安全标准：

- OWASP 
- WASC


GitHub 泄露监控系统/工具

- [Hawkeye](https://github.com/0xbug/Hawkeye) 泄露监控系统
- [gitrob](https://github.com/michenriksen/gitrob
) Ruby开发，支持通过postgresql数据库
- [weakfilescan](https://github.com/ring04h/weakfilescan
) Python开发，多线程，猪猪侠开发中文注释，个性化定制，需要beautifulsoup4,用于渗透人员在对网站进行网站渗透时查找敏感文件（配置文件、临时文件）、敏感目录，会首先爬取目标站点的三层目录资源，生成目录FUZZ和文件FUZZ
- [GitPrey](https://github.com/repoog/GitPrey
) Python开发，国人开发中文支持，用于企业搜索关键词，及时发现潜在的敏感信息，需要登录
- [GitMiner](https://github.com/UnkL4b/GitMiner
) Python开发，功能简单


社工库：

- http://cha.hx99.net
- http://163.donothackme.club/
- [社工库](http://s.70sec.com/)
- [邮箱库](http://email.70sec.com/)
- 163.donothackme.club/
- https://www.70sec.com/

## 主机安全

[驭龙 HIDS](https://github.com/ysrc/yulong-hids) 一款由 YSRC 开源的主机入侵检测系统


## 数据库安全

数据库中间件:

 - [美团DBProxy Github](https://github.com/Meituan-Dianping/DBProxy)  美团点评数据库中间件
 - [美团点评的DBProxy实践](https://tech.meituan.com/dbproxy-pr.html)
 - [美团点评数据库中间件DBProxy开源](https://tech.meituan.com/dbproxy-pr.html)
 - [Mysql Sniffer](https://github.com/Qihoo360/mysql-sniffer)
 
### Linux

Linux 

- [运维命令](http://www.brendangregg.com/Perf/linux_perf_tools_full.png)
- [运维命令2](http://www.brendangregg.com/Perf/linux_observability_tools.png)

http://opmk280rf.bkt.clouddn.com/6b3ef5f6d649b4c83183aeea39f2cb74.jpg


## 开发

[Developer How To Guide](https://software-security.sans.org/developer-how-to/)

- How To Fix SQL Injection 
- Cross-Site Scripting (XSS)
- Cross-Site Request Forgery (CSRF)

## 测试



静态扫描：
- [JAVA代码审计的一些Tips(附脚本)](https://mp.weixin.qq.com/s/josQv1X6YjsttZr1O32j2Q)
- [民生银行源代码安全研究与实践](http://www.talkwithtrend.com/Article/216897)
- [携程安全自动化测试之路](https://zhuanlan.zhihu.com/p/28115732)

测试社区：
- [测试社区](https://testerhome.com)

持续集成：
- [安全自动化扫描测试平台实现](https://testerhome.com/topics/10323)

# Sonar 测试框架

[SonarSource Rules]

**Plugins：**

[Dependency Check]
[ThreadFix] ：The ThreadFix plugin allows importing results from application security scanning tools, such as AppScan, WebInspect, Fortify, Checkmarx, BurpSuite and many others.

[ZAP]：Parses OWASP ZAP reports and imports results into SonarQube

Slack：Multiple independent plugins (with coincidentally identical plugin keys) exist to send SonarQube notifications to the specified Slack channel.


测试工具
- [开源工具](https://testerhome.com/opensource_projects)
- [Hitchhiker](http://doc.hitchhiker-api.com/cn/) 是一款开源的 Restful Api 测试工具，支持Schedule, 数据对比，压力测试，支持上传脚本定制请求，可以轻松部署到本地，和你的team成员一起管理Api


## 威胁情报

### 安全漏洞信息

CNVD：
- [关于开放CNVD漏洞信息批量获取方式的公告](http://www.cnvd.org.cn/webinfo/show/4128)

CVSS:
- [漏洞盒子中文CVSS](https://www.vulbox.com/cvss)

## 移动安全
### Android 安全

- [Xposed 给微信步数加上翅膀](https://mp.weixin.qq.com/s/HIxSDcWnXnCiNDpotozN3A)

### OWASP

- [owasp-mstg](https://github.com/OWASP/owasp-mstg) The Mobile Security Testing Guide (MSTG)

## 网络
IP
- [ip2region](https://github.com/lionsoul2014/ip2region) 准确率99.9%的ip地址定位库，0.0x毫秒级查询，数据库文件大小只有1.5M

## 文摘

### 安全测试
很用心的文章
- [很用心的安全文章收集](https://github.com/JnuSimba) 
- [微步安全分析和情报大会PPT](https://threatbook.cn/event/)

安全事件
- [黑客的滑铁卢——美国大断网全纪实](https://mp.weixin.qq.com/s/25f5gK0fXIr_UV9xROLX3w)
-

## 数据安全

治理：
- [数据安全](http://opmk280rf.bkt.clouddn.com/6b3ef5f6d649b4c83183aeea39f2cb74.jpg)


## 加密技术

Cryptographic Storage Cheat Sheet
- Key exchange: Diffie–Hellman key exchange with minimum 2048 bits
- Message Integrity: HMAC-SHA2
- Message Hash: SHA2 256 bits
- Assymetric encryption: RSA 2048 bits
- Symmetric-key algorithm: AES 128 bits
- Password Hashing: PBKDF2, Scrypt, Bcrypt

## 书籍

[《微服务：从设计到部署》中文版](https://github.com/DocsHome/microservices)

## 支付SDK
[支付SDK Java](https://github.com/Pay-Group/best-pay-sdk)
