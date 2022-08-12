## Apache RocketMQ 2022 中国开发者社区月会记录
----
URL: https://shimo.im/docs/RC6vJCtHh3qWWYXd

2022-08-11
----
#### 会议主题：
RocketMQ中国开发者社区月会-08
#### 会议时间
2022/08/11 19:30-20:30 (GMT+08:00) 中国标准时间 - 北京

点击链接入会，或添加至会议列表：
https://meeting.tencent.com/dm/JATRrZAZGM6y

#腾讯会议：675-392-234

手机一键拨号入会
+8675536550000,,675392234 (中国大陆)
+85230018898,,,2,675392234 (中国香港)

根据您的位置拨号
+8675536550000 (中国大陆)
+85230018898 (中国香港)

复制该信息，打开手机腾讯会议即可参与

主持人：丁磊
Attendee:

#### 议题&纪要
RocketMQ 定时消息分享， by 季俊涛  

RocketMQ rsqldb 新功能演示  by 倪泽  repo： https://github.com/alibaba/rsqldb

RocketMQ Client 5.0版本demo。by 艾阳坤  https://github.com/apache/rocketmq-clients

RocketMQ Schema registry社区任务分享 by 许奕斌  https://github.com/apache/rocketmq/wiki/RIP-42-Support-Schema-Registry

#### 待办事项
- 整理压测的文档， 摸底timerlog的性能， 压测结果通过邮件形式，在原RIP上回复Dev邮件列表，在PR上同步更新。@季俊涛
- 基于readme文档演示成功，汇总剩余任务并发布到社区 @倪泽
- 任务拆解后提交issue，包括SchemaStorageInfo（与序列化协议相关的存储，多协议支持(json,protobuf，thrift等),生态任务关联 @许奕斌
- 对齐kafka schema的ReferenceBy，支持一个schema与多个subject的绑定/解绑, @张鑫认领

#### 会议视频
[RocketMQ中国开发者社区月会-08](https://meeting.tencent.com/v2/cloud-record/share?id=961b5dde-c503-47d7-a389-2fdbc67a614c&from=3)


2022-06-16
----

#### 会议主题
Apache RocketMQ中国开发者社区月会-06

#### 会议时间
2022/06/16 19:30-20:30 (GMT+08:00) 中国标准时间 - 北京

点击链接入会，或添加至会议列表：
https://meeting.tencent.com/dm/9oMtmXPS1l74

#腾讯会议：801-980-783

手机一键拨号入会
+8675536550000,,801980783# (中国大陆)
+85230018898,,,2,801980783# (中国香港)

根据您的位置拨号
+8675536550000 (中国大陆)
+85230018898 (中国香港)

复制该信息，打开手机腾讯会议即可参与

主持人：丁磊

#### 议题&纪要

- 月会/周会制度讨论，Sig兴趣小组梳理讨论， by 丁磊 https://shimo.im/docs/1d3aV8ggE0s4Kjqg

- RocketMQ Schema设计分析  by 王帆https://shimo.im/docs/Ee32MWDG1WFmKRA2

- 发布推广4.9.4 LTS 版本。

- RIP-41: RocketMQ增加 E2E 测试能力及daily build release 能力 by 月伢(章源辰) https://shimo.im/docs/pmkxQEOZmDiLwdAN

- RocketMQ Streaming 基于compact topic 存储优化 by 倪泽 -- 建议放到下次 streams SIG 月会

2022-04-28
-----

### 会议主题
Apache RocketMQ 月会 2022-04-28

#### 会议时间
2022/04/28 19:30-20:30 (GMT+08:00) 中国标准时间 - 北京
#### 会议链接

点击链接入会，或添加至会议列表：
https://meeting.tencent.com/dm/WECHezjBto3b

#腾讯会议：774-354-698

复制该信息，打开手机腾讯会议即可参与

主持人：刘涛
Attendee:
124 人
#### 议题&纪要:

RocketMQ Compaction Topic design share  by 刘涛

定期发布 LTS 版本，讨论 LTS 版本 bug 修复，pr 提交策略（待disscuss，VOTE）。by 杜恒

推荐在有较大变动或者架构升级时发布LTS 版本，LTS 支持周期为 18 个月。

比如发布 4.9.x LTS 版本（LTS），后续会交替发布 4.9.x 版本或者4.10.x 甚至 5.x 版本，在保证新功能快速迭代的同时，LTS 版本能够保证bug fix 被及时合入。
RIP 状态更新

RIP-32 Slave Acting Master Mode和 RIP-34 Support quorum write and adaptive degradation in master-slave architecture 分享（如果前面时间太长就下次再找时间分享） by 通融

rocketmq-streams 增加一些 good first issue


2022-03-10
-----
#### 会议主题
Apache RocketMQ 双周会 2022-03-10
#### 会议时间
2022/03/10 19:30-8:30 (GMT+08:00) 中国标准时间 - 北京
#### 会议链接：
![image](https://user-images.githubusercontent.com/16487356/184300951-e89e10f8-82dc-496d-81bc-c8322792f2c9.png)

主持人：周波
Attendee:
杜恒、周波 等 56 人
#### 议题&纪要:
1. 存储计算分离及多协议支持 RIP design share by 牟羽
  - RIP文档：https://shimo.im/docs/gXqmeEPYgdUw5bqo
  - 讨论列表：https://lists.apache.org/thread/moyf812h7hshj3h9nsdx076xzdq29x8f

2. 新的统一 APIs 规范 by 艾阳坤
  RIP 文档：https://shimo.im/docs/m5kv92OeRRU8olqX
3. 讨论 RocketMQ 如何参加今年的GSoC, 大家可以争当 mentor by 余洲
  https://community.apache.org/gsoc.html
4. rocketmq connect 发展 周波
    https://shimo.im/docs/25q5MmEMb4hOWEqD/ 



2022-02-17
----
#### 会议主题：
Apache RocketMQ 双周会 2022-02-17
#### 会议时间：
2022/02/17 19:00-20:00 (GMT+08:00) 中国标准时间 - 北京
#### 会议链接：
主持人：杜恒
Attendee:
杜恒、金融通、老胡、于雨、张阳、李伟 等 41 人
#### 议题&纪要:
1.[RIP-31] Support RocketMQ BrokerContainer Design Share 
  - 设计文档：https://shimo.im/docs/xxY3QDqYvj6G6Gk9
  - 大家当更关心的重点在于是否会带来运维难度的上升，需要近一步说明。
  - @阿帆 会发起一个单broker，多commitlog 的RIP，需要与 RIP-30 compact topic 统一来看。

2. 项目整体及独立 SIG 双周会开发者会议制度讨论 
  - 后续会有各个sig 的maintainer 来组织定期会议（周会或者月会），maintainer 负责三件事情：
    - 搜集本 SIG 大家比较关注的问题或者是希望增加的特性。
    - 拆分任务，组织月会跟进 ISSUE，PR 完成，推动迭代。
    - 吸引更多开发者，共同完善SIG 对应的特性。
  - 当前的SIG maintainer，希望参与贡献或者有问题反馈可以在群里面找到对应同学：
    - ACL：孙玺，高扬
    - connect：周波，老胡
    - operator：张策，小伟
    - exporter，厚道，小伟
    - broker container：好名字，张策

3. go语言实现request- reply接口
  go client 社区里面新加，已经增加issue
4. dobbogo集成rocketmq 作为传输层
   在dubbogo 社区里面拆分任务，包括 go 语言完善以及集成
5. RocketMQ summit 
  https://mp.weixin.qq.com/s/NVaqUOT-BBaFX6V78kXwdw 欢迎申报议题或者成为sponsor，希望成为sponsor 的公司同学可以联系杜恒，不需要钱，只需要提供logo，协助进行议题筛选。

6. rocketmq exporter迁移到broker上 李伟
  周五 exporter 会议上讨论了，暂时先不迁移
7. 4.9.3  Release 时间安排 - 王帆
  已经在走发版本流程。

