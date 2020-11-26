# 信息流，计算广告学习资料

信息流广告学习资料，包括简介，业务流程，工程架构，数据平台，算法策略与相关网站。

## 一、概览

[深入浅出解析信息流广告](http://www.woshipm.com/operate/591859.html)
> 
 
[互联网智能广告系统简易流程与架构](https://mp.weixin.qq.com/s?__biz=MjM5ODYxMDA5OQ==&mid=2651960148&idx=1&sn=7c8a2d789fb20981355e49c3defe0229)
> 
 
## 二、广告业务

[计算广告中主要模块、策略及其场景（上）](http://www.woshipm.com/pd/2167128.html)
> 
 
[计算广告中主要模块、策略及其场景（下）](http://www.woshipm.com/pd/2348709.html)
> 
 
#### 公式拆解

[一个平台怎么提升广告收入](https://work.tengblog.com/2018/12/18/guanggao/)
> 
 
#### AB试验

[实验引爆用户增长：A/B测试最佳实践](http://www.woshipm.com/data-analysis/1656851.html)
> 
 
## 三、工程架构

#### 概览

典型的程序化广告系统。

[广告系统的平台架构与交互流程](https://zhuanlan.zhihu.com/p/103386845)
> 
 
[解密商业化广告投放平台技术架构](https://www.infoq.cn/article/ymvabqb6lqxubb9ywrig) 
> 阿里智能营销平台分享，商业化广告投放平台技术架构，包括服务化、数据传输分发、广告投放引擎、计费、海量数据实时报表

[如何构建日请求数十亿次高性能高可用广告系统：微博广告架构解密](https://blog.51cto.com/14977574/2547259)
> 

[广告系统架构解密](https://jishuin.proginn.com/p/763bfbd2b5fb) 
> 

[微博广告策略工程架构体系演进](https://www.infoq.cn/article/qif3hlwoabpxvcp2jblg)
> 分享微博广告工程架构的建设经验。

[阿里淘外商业化广告工程架构实践](https://www.infoq.cn/article/e8vbkqsyvaxbxyjdmlfy)
> 阿里创新事业群智能营销平台在如何构建高性能、高可用、高效率，低成本的广告系统架构方面所做的诸多工作及实践经验。

#### 投放系统设计

投放系统实现。

[优酷 DSP 广告投放系统架构实践](https://mp.weixin.qq.com/s?__biz=MzU1NTMyOTI4Mw==&mid=2247495736&idx=1&sn=080c985a2e373e04496bce5db3cb1069&chksm=fbd74254cca0cb42324938685381d67217f3cb14cb6da64576cac58238264605b5f7e64d34a6&scene=21)
> 
 
#### 运营后台设计

CMS运营后台实现。

#### 检索平台设计

检索平台实现。

[广告引擎如何做到在0.1s内返回广告信息](https://time.geekbang.org/column/article/235336)
> 
 
[美团广告实时索引的设计与实现](https://tech.meituan.com/2018/05/11/adp-rtidx-ls.html)
> 
 
[广告索引设计](http://fatfei.com/2019/10/23/%E5%B9%BF%E5%91%8A%E7%B4%A2%E5%BC%95%E8%AE%BE%E8%AE%A1/)
> 
 

#### AB实验平台

AB试验平台实现。

[美团点评效果广告实验配置平台的设计与实现](https://tech.meituan.com/2019/11/28/advertising-performance-experiment-configuration-platform.html)
> 
 
[微博广告分层实验平台 (Faraday) 架构实践](https://www.6aiq.com/article/1536148957368)
> 
 

#### 广告计费系统

广告计费系统。

[蘑菇街广告计费系统架构设计](https://kuaibao.qq.com/s/20190410AZOL4W00?refer=spider)
> 
 

#### 账务管理中心

账务管理中心。


## 四、数据平台

数据平台主要解决两方面的问题。

[广告大数据平台核心架构设计](https://cloud.tencent.com/developer/news/225100)
> 
 
#### OLTP数据库

OLTP场景，包括广告库、创意库、会员库、广告产品库、广告策略库等，这些都存储在MySQL中，数据规模较大的广告库和创意库，按照广告主ID Hash做分库分表。

#### OLAP场景

OLAP场景，涉及到非常多的报表，聚合维度多，单表的记录数可能达到百亿级别，底层采用HDFS和HBase存储。


## 五、算法策略

[美团在O2O场景下的广告营销](https://tech.meituan.com/2018/08/16/meituan-o2o-advertising.html)

[阿里妈妈品牌广告中的 NLP 算法实践](https://zhuanlan.zhihu.com/p/84206297)
> 自言语言处理优化广告投放策略

[OCPC 广告算法在凤凰新媒体的实践探索](https://zhuanlan.zhihu.com/p/105175064)
> 成本优化


[互联网广告CTR预估新算法：基于神经网络的DeepFM原理解读](https://cloud.tencent.com/developer/article/1348233) 
> 成本优化

#### 点击率预估

[点击率预测综述 ( 上篇）](https://cloud.tencent.com/developer/article/1005051)
> 点击率预测

#### 推荐算法

[美团DSP广告策略实践](https://tech.meituan.com/2017/05/05/mt-dsp.html)
>

[爱奇艺效果广告的个性化探索与实践](https://www.infoq.cn/article/YYcQH7GF3oV8jMT96Vyl)
> 爱奇艺效果广告个性化方面的思考与实践，聚焦广告排序算法


## 六、产品实例

#### 阿里妈妈
> 阿里电商场景的变现平台
[阿里妈妈广告](https://www.yuque.com/alixman/alimama) 

[语雀搜索阿里妈妈知识库](https://www.yuque.com/search?p=1&q=%E9%98%BF%E9%87%8C%E5%A6%88%E5%A6%88&type=book)


#### 阿里智能营销平台
> 属于阿里创新事业群，主要流量构成包括：神马搜索、UC 浏览器、UC 头条、优酷、阿里云 OS 以及手机厂商、网盟第三方流量等。

## 七、开源项目

[https://github.com/opendsp](https://github.com/opendsp)
> 
 
[https://www.oschina.net/p/openmediation](https://www.oschina.net/p/openmediation)
> 
 
[https://github.com/shpilu/cloriSearch](https://github.com/shpilu/cloriSearch)
> 解决常规业务开发中的策略检索与在线广告匹配问题


[https://github.com/mJackie/RecSys](https://github.com/mJackie/RecSys)
> 推荐系统/计算广告/机器学习/CTR预估资料汇总


[https://github.com/wzhe06/Ad-papers](https://github.com/wzhe06/Ad-papers)
> 计算广告论文、学习资料、业界分享

[https://github.com/wnzhang/rtb-papers](https://github.com/wnzhang/rtb-papers)
> Paper Collection of Real-Time Bidding


## 七、书籍课程

#### 广告基础

[计算广告干货整理](https://blog.csdn.net/a819825294/article/details/53540245)
> 

[《Google 广告高阶优化（第3版）》](https://book.douban.com/subject/26609399/)
> 
 
[搜索引擎广告的机制设计理论与实践](https://book.douban.com/subject/5353670/)
> 拍卖理论在搜索广告竞价中的应用

#### 工程技术

[《被算法操控的生活》](https://book.douban.com/subject/34927752/)
> 
 
[《计算广告》](https://www.douban.com/people/53952698/)
> 
 
[《程序化广告实战》](https://book.douban.com/subject/27114728/)
> 
 
[《程序化广告：精准投放实用手册》](https://book.douban.com/subject/27180590//)
> 
 

#### 商业化运营

[《信息流广告实战》](https://book.douban.com/subject/35052614/)
> 
 
#### 广告优化
[广告数据定量分析](https://book.douban.com/subject/34782444/)
> 
 
#### 视频课程

[计算广告学](https://study.163.com/course/courseMain.htm?courseId=321007) 
> 
 

## 八、相关网站

#### 数据报告

[CNZZ-UDplus](udplus.umeng.com)
> 
 
[微博数据中心](data.weibo.com/datacenter/recommendapp)
> 
 
[艾瑞网](http://report.iresearch.cn/)
> 
 
[易观数据](http://www.199it.com/)
> 
 

#### 统计工具

[百度统计](tongji.baidu.com)
> 
 
[腾讯统计](ta.qq.com)
> 
 
[友盟](http://www.umeng.com/)
> 
 
[秒针](http://www.miaozhen.com/)
> 
 
[AdMaster](http://www.admaster.com.cn/)
> 
 
#### 学习资源
[App Growing](https://appgrowing.cn/)
> 
 
[http://www.nielsen.com/cn/zh.html](尼尔森)
> 
 
[ptengine](http://www.ptengine.cn/)
> 
 
[腾讯社交广告](https://e.qq.com/ads/)
> 
 
[腾讯大学营销学院](daxue.qq.com/mkt)
> 
 
[360营销学院](yingxiao.360.cn) 
> 发布360搜索营销行业案例和知识

[艾奇学院](www.27sem.com)
> 在线信息流学习网站，视频，干货文章，资料齐全


