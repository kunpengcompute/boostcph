# **BoostCPH**项目介绍

1.1 概述

BoostCPH 云手机套件包含Kbox云手机容器、指令流引擎、视频流引擎核心能力等组件，利用ARM指令集同构优势，支持移动应用无损上云，帮助客户和伙伴实现云手机极致的性能和业务体验。

1.2 架构图

![img](https://www.hikunpeng.com/doc_center/source/zh/kunpengcps/cpturbokit/videostreamengine/figure/zh-cn_image_0000002479923868.png)

云手机 是基于ARM服务器虚拟出的带有AOSP （Android Open Source Project，安卓开放源代码项目）系统的虚拟手机服务。简而言之，云手机=ARM服务器+Android OS。您可以远程实时控制云手机，实现Android APP的云端运行；也可以基于云手机的基础算力，高效搭建应用，如云游戏、移动办公、直播互娱等场景。

1.3 社区主页

[BoostCPH 云手机套件-鲲鹏BoostKit-鲲鹏社区](https://www.hikunpeng.com/boostkit/boost-x/cph)

# 特性介绍

| 特性名称      | 特性介绍                                                     | 仓库地址                          |
| ------------- | ------------------------------------------------------------ | --------------------------------- |
| Kbox云手机    | Kbox云手机容器是鲲鹏BoostKit云手机Turbo套件的重要组成部分，是实现Android应用运行的基础软件。它将AOSP 系统直接运行在容器内，实现GPS、加速度传感器、陀螺仪、IMEI、Wi-Fi等外设硬件的数据Mock功能，以及Gralloc&HWComposor模块，确保AOSP系统可以正常启动运行。 | [Kbox-patches](https://gitcode.com/boostkit/Kbox-patches |
| vmi视频流引擎 | 端云协同引擎 顾名思义可以分为端侧和云侧两个部分：云侧运行于服务器上；端侧一般为云手机APK，可以被安装在用户的Android手机上，用于和云侧进行交互，进而对Kbox容器进行正常的操作。 | [vmi](https://gitcode.com/boostkit/vmi)  |

# 关于社区

提供社区治理架构、SIG组织运作章程、参与贡献、邮件订阅、社媒联系方式等公共模块内容简介和指引

# 贡献、建议与交流

欢迎大家为社区做贡献，如果使用过程中有任何问题/建议，或者需要反馈特性需求和bug报告，可以提交[Issues]( https://gitcode.com/boostkit/community/blob/master/docs/contributor/issue-submit.md)联系我们，具体贡献方法可参考[这里](https://gitcode.com/boostkit/community/blob/master/docs/contributor/contributing.md)。同时也欢迎大家在[讨论专区](https://gitcode.com/boostkit/community/discussions)展开讨论交流。感谢您的支持。

# LICENSE

本项目文档适用CC-BY 4.0许可证，具体参见文件[LICENSE](LICENSE)文件。