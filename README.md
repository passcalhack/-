# 云

IaaS指提供系统（可以自己选）或者储存空间之类的硬件，软件要自己手动装；PaaS提供软件/框架（可以自己选）；SaaS只能使用开发好的软件（卖软件本身）；BaaS一般类似于非关系数据库，但各家不通用，有时还有一些其它东西。

## 其他人的集合

* https://github.com/ripienaar/free-for-dev
* https://github.com/AchoArnold/discount-for-student-dev
* https://github.com/qinghuaiorg/free-for-dev-zh 很久没更新了
* https://github.com/vincenthou/free-for-china-dev 很久没更新了
* https://github.com/ivmm/Student-resources
* https://www.freeforstudents.org/
* https://github.com/255kb/stack-on-a-budget
* https://github.com/Ibexoft/awesome-startup-tools-list
* https://www.cokemine.com/

## Paas

* https://www.heroku.com/ java go py docker
* https://www.pythonanywhere.com/ 限制非常多，几乎就和虚拟主机差不多了，免费账户不允许访问白名单之外的网站。但好歹能提供一个自动https的web app
* https://cloud.google.com/appengine/docs/ 标准环境有一点储存空间和流量，柔性环境(.NET)必须启用结算，且现在标准环境要启用一个API，也要求绑卡
* https://fly.io/docs/pricing/ docker
* https://m3o.com/ go
* https://anvil.works/ py，前端Drag and Drop UI，后端和数据储存用的是该网站的库
* https://www.kintohub.com/ node go py java php docker 免费3个实例但内存32MB？添加信用卡后每月免费$5
* https://clustered.com/pricing 现在只免费14天，永久免费的plan还没出
* https://www.ibm.com/cn-zh/cloud/free Lite版无需信用卡，Cloud Foundry 256M内存，还有对象储存、Db2、翻译；https://51.ruyo.net/12065.html
* https://www.clever-cloud.com/en/pricing 看介绍送20€，但应该只会送一次，可以用4个月

### .net

* https://appharbor.com 看起来比较好，支持3.1
* https://www.gearhost.com/ 看起来比较好，支持3.1。还支持PHP7和node
* https://www.aspify.com/en/webhosting/aspnet-freehosting/ 100MB硬盘100MB数据库，支持Core
* https://freeasphosting.net/ 看起来不怎么样，虽然写了免费，但是整个网站都在说学习
* https://somee.com/ 被墙了，且IP被封了

## 云端空间/IDE？

* https://www.tutorialspoint.com/codingground.htm http://codepad.org/ https://ideone.com/ https://coliru.stacked-crooked.com/ https://wandbox.org/ 无需登录，能执行许多语言，但只能说能运行代码，根本称不上IDE
* https://cloudstudio.net 原版VSC，服务器在上海，每日限时两小时
* https://che.openshift.io/dashboard/ 之前是codenvy；现在是魔改VSC，速度和完成度都还不错，但不支持扩展
* https://www.gitpod.io/ 有免费版；专业版在学生包里免费6个月
* https://colab.research.google.com/ 在线jupyter notebook，宣传说有免费gpu额度，国内无法直接打开
* https://aistudio.baidu.com
* https://code.xueersi.com/ide/code/1 只有C++，很简陋
* https://tianchi.aliyun.com/notebook-ai/home jupyter lab，有免费gpu，能连续运行8小时，5G空间
* https://www.kaggle.com notebook，验证电话后有免费gpu和外网，能连续运行9小时，有编程教程
* https://repl.it/ 有免费版；专业版在学生包里免费3个月
* https://deepnote.com jupyter notebook，免费额度750小时，5G空间
* https://next.tech/ 学生包中有
* https://www.kesci.com/ 国产，jupyter notebook和大数据

### 前端在线IDE

* https://codepen.io/
* https://stackblitz.com/
* https://jsfiddle.net/ 我这里打开非常慢
* https://codesandbox.io/
* https://trinket.io/
* https://bit.dev/
* https://jsbin.com

## 数据库

* https://db4free.net/ mysql 200M
* https://www.freemysqlhosting.net/ mysql 5.5，5MB，每周会收到要手动操作来延期的邮件
* https://mlab.com/ https://www.mongodb.com/pricing 500MB；后者学生包中有
* https://app.redislabs.com/ redis，30M
* https://www.elephantsql.com/plans.html pg
* https://remotemysql.com/ mysql 100M

## BaaS

* https://bmob.cn/
* https://leancloud.cn/pricing/
* https://firebase.google.cn/pricing 用处：https://zhuanlan.zhihu.com/p/95334890
* https://www.zhihu.com/question/34124789/answer/72495188
* https://maxleap.cn/s/web/zh_cn/devcenter-pricing.html
* https://www.8base.com GraphQL
* https://www.deta.sh/

## 也许可用的IaaS

* https://www.litespeedtech.com/experience-litespeed-for-free 一个月有效？需要姓名，电话，邮箱，地址
* https://open.iot.10086.cn/cloud/introduction/cloud-server OneNET移动的，MQ、对象储存、可视化、CI都有一定的免费额度
* https://cloud.tencent.com/act/free 腾讯云，个人验证后有一些可以长期免费使用；现在容器内测，本身是免费的，其它服务收费；云函数公测暂时免费
* https://activity.xinruiyun.cn/free/ 新睿云，发个广告可以免费用一个月的ECS
* https://www.oracle.com/cn/cloud/free/ 体验文章：https://51.ruyo.net/14138.html 不支持prepaid card
* https://51.ruyo.net/14583.html Azure
* https://www.atlantic.net/ 免费12个月，需要信用卡
* euserv，德国的，只有IPV6，亲测确实可以，但硬盘很慢

## Managed K8S

* https://okteto.com/pricing 免费版2CPU，4G内存，10G储存。刚注册送一个月pro，不付款自动降到免费版。免费版24小时不活动就sleep。原意是为开发者日常开发使用的
* https://www.openshift.com/products/online/ 每60天清除
* https://usekrucible.com 一个月能用25小时，自己分配
* https://kubernauts.sh/ 免费版有1CPU，1G内存；申请注册后什么邮件也没收到也没有登录的地方
* https://labs.play-with-k8s.com/ 好像每天只有四小时；https://labs.play-with-docker.com/
* zarvis.ai staroid.com 网页都用的是Google的服务器，无法直接访问
* https://kubesail.com/ 停止免费版了，不过还是能作为管理平台
* https://devspace.cloud/ 好像只是客户端或者管理平台
* 挂了的：k8spin.cloud tryk8s.com

## Serverless/Node Paas（无状态的api）

* https://glitch.com/
* https://workers.cloudflare.com/
* https://vercel.com/ node go py
* https://pipedream.com/
* https://keen.io/
* https://www.openode.io/pricing
* https://runkit.com
* https://www.cloud66.com/node/ 免费一个月
* https://www.jexia.com/

## 静态网页托管（必须要能自动更新）

* https://surge.sh/
* https://www.netlify.com/
* https://render.com/
* https://cloudcannon.com
* https://tiiny.host 只能存活7天？

## 未分类

* https://help.aliyun.com/document_detail/54301.html#Free FaaS 有一点免费额度
* https://github-students.educationhost.co.uk/ 免费一年
* https://www.cokemine.com/goormide.html
