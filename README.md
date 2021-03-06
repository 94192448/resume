#  **简历**

## 个人信息

姓 名：张山海 <br>
手机： 18811413070 <br>
性 别： 男<br>
出生日期： 1989年11月30日 <br>
居 住 地： 北京-海淀区<br>
工作年限：5年<br>
qq：707582070<br>
户 口： 河北唐山<br>
求职意向<br>
到岗时间： 近期到岗<br>
希望行业： 互联网/电子商务/移动互联网<br>
目标地点： 北京<br><br>
期望薪水： 25k-30k/月<br>
目标职能： 架构师、高级工程师<br>




## 教育经历

2009.09 - 2012.06  河北工业大学 计算机网络

## 工作经验

#### 掌游天下
2015.11 - 2016.12：<br><br>
所属行业： 手游、互联网广告<br>
部门：玉米广告，自主广告研发平台<br>
公司简介：
> - 公司以手游为主。广告是游戏变现的一种方式。
- 广告部门分为 聚合广告和**自主研发**。



#### 北京灵动创新有限公司
时间：2015.01 - 2015.10 <br>
所属行业：邮件营销、互联网广告<br>
部门：技术部<br>
公司简介：
> - 大量发送营销邮件，触发邮件的平台。
- 该平台已经长达7年。日发送量达千万封。
- 公司产品，主要为第三方发送email，比如神州租车，大麦网等等。平台发送能力达每日千万，一个c网网段作为发送ip，email地址单表数量生成环境大约2亿。所发送邮件都是正规邮件，正规签名。绝无恶意发送垃圾邮件。邮件类型大体为促销邮件。例如大麦的门票促销。



#### 北京维旺明科技有限公司
时间：2012.07 - 2015.01<br>
所属行业：互联网新闻app<br>
部门：服务器组<br>
公司简介：
> 公司已在线阅读杂志，在线阅读咨询为主。
在APP上投放合约广告，已到达变现目的。当时统计已有8千万在线用户。
[viva畅读app地址](https://itunes.apple.com/cn/app/id402641844)

## 项目经历

### 互联网广告平台
时间：2015.11 - 2016.12<br>
担任角色： 主程序员<br>
项目描述：
> - 自主研发为：sdk -> adserver->adexchange->dsp/api/
- 直投dsp自主研发为：sdk -> adserver->adexchange->直投dsp

本人职责：
>-  adserver 和dsp的 开发和线上运维 工作。
- 每天日均2亿次请求，4000万 曝光。每天日均2亿次请求，4000万 曝光。
- 晚间高峰期，保证99%的请求都能得到相应。

具体工作内容：
- 0.负责 ssp和dsp 的广告投放机
- 1.ssp平台，对现有已经离职团队留下的平台进行重写，优化性能
- 2.ssp对接sdk，**定义开发接口**。
- 3.根据 openrtb协议对接adx
- 4.ssp 支持常见的广告形式（原生，banner，插屏，开屏，视频）
- 5.ssp使用redis，存储广告 请求，上报pv，点击等信息，确保 顺序，在线初步防止作弊行为。
- 6.dsp 直投 ，将广告库在redis 内做**倒排索引**完成 **基础定向**。
- 7.**频次控制**，实时超量下线。排期上下线。
- 8.**平滑投放**功能。使用redis计数器，将 广告平滑的投放出去，避免前期投放过多后期下线。
- 9.使用**elasticsearch** 进行第三方物料分析。用于统计举报数量，屏蔽低俗图片
- 10.日常线上运维，使用awk，查找日志。
- 11.改造项目，将非maven改成maven，jenkins建设使系统自动化编译部署，大大节省开发时间
- 12.api 项目，对接三方广告接口api，返回给adx（dsp功能）
- 13.优化ssp系统性能，使用**guava**缓存，分析性能瓶颈代码，优化代码，jmeter显示系统性能提高将近10倍。
- 14.使用guava，在内存中统计 超时率，每分钟调整策略，限制流量 防止 对接 第三方api项目  因为http请求阻塞导致 性能下降。


### edm 平台

时间：2015.01 - 2015.10<br>
担任角色： 主程序员<br>
项目介绍
> 大量发送营销邮件，触发邮件的平台。edm平台。

责任描述
> - 在将近十年的，经手很多人，十多个项目中，修复bug，完善系统。
- Guava作为内存缓存。Redis作为外部缓存和部分存储。
- 使用**storm**，binlog，将2亿email地址导入到elastisearch中。打开点
- 击等回调第三方回调地址。
- 使用线程池，redis队列，通过比较复杂的调度将打开点击等回馈信息确
- 保100%的回调给第三方。保100%的回调给第三方。

### 服务器端 初中级开发

时间：2012.07 - 2015.01 <br>

项目介绍
> - 杂志，资讯（cms），爬虫，广告，接口，客户端。
- 蜘蛛抓取指定网站文章，图集入库，使用fudannlp对文章进行打标签。对标签分类管理，对文章修改。
- 文章根据标签走，标签根据表情包走，用户订阅标签包，根据标签包，下发文章给客户端。

责任描述
>-  管理面板的开发：调整文章，标注/过滤关键词，管理关键词，搜索词语，标签包运营等。
- 网页抽取正文工具。
- 编辑使用工具开发。
- 图片源抓取蜘蛛。
- 使用**dubbo**，开发查询文章，类目等接口服务给接口工程师。
- 合约广告系统开发。


## 个人技能
sql优化等，python，go等语言了解基本语法<br>
了解 devops，chatops

## 职业目标
- 想在计算机，互联网行业长期发展。希望从事互联网，移动互联网，计算广告等 后端工作
- 走架构师 技术路线。

##特长

自学能力还好，喜欢新型的东西，喜欢研究。最近在学习使用spring cloud 开发微服务

##对公司/团队的 要求和 期望

要求：
互联网公司，不加班（8*5工作）

期望：
公司有优秀的文化和 工程师文化开发文化，能够做到重复的事情不手动处理。需求，开发，测试 ，运维 流程完备的团队

技术栈 期望
spring mvc，jpa，go，git，jenkins，docker，slack，chatops，devops

## 业余作品
[网络收藏夹](http://100000p.com)
[开发api](http://github.com/zhangshanhai/readthis-api)
