# 下肢外骨骼概念设计展示

Lower-limb exoskeleton concept showcase · Maintained by [Genius-two](https://github.com/Genius-two)

面向老年人日常活动辅助的髋膝四主动自由度外骨骼概念设计。这里展示结构思路与动作示意，便于交流和项目汇报。

## 结构概览

![下肢外骨骼结构标注图](https://github.com/Genius-two/lower-limb-exoskeleton-showcase/releases/download/showcase-20261111/structure-overview.png)

- 左右髋关节和左右膝关节分别驱动，膝采用固定单轴旋转。
- 电机与减速器集成驱动，腿杆采用可调长度结构。
- 腰部、左右大腿和左右小腿设置穿戴固定接口。
- 大腿和小腿预留惯性传感器位置。
- 本方案没有机械踝、足板、轮子或自带座椅；起坐任务使用外部椅子。

## 六类动作展示

| 场景 | 视频 |
|---|---|
| 平地行走 | [观看视频](https://github.com/Genius-two/lower-limb-exoskeleton-showcase/releases/download/showcase-20261111/Concept_Walking.mp4) |
| 上楼 | [观看视频](https://github.com/Genius-two/lower-limb-exoskeleton-showcase/releases/download/showcase-20261111/Concept_StepUp.mp4) |
| 下楼 | [观看视频](https://github.com/Genius-two/lower-limb-exoskeleton-showcase/releases/download/showcase-20261111/Concept_StepDown.mp4) |
| 起立 | [观看视频](https://github.com/Genius-two/lower-limb-exoskeleton-showcase/releases/download/showcase-20261111/Concept_SitToStand.mp4) |
| 坐下 | [观看视频](https://github.com/Genius-two/lower-limb-exoskeleton-showcase/releases/download/showcase-20261111/Concept_StandToSit.mp4) |
| 康复动作示意 | [观看视频](https://github.com/Genius-two/lower-limb-exoskeleton-showcase/releases/download/showcase-20261111/Concept_Rehab_Concept.mp4) |

点击文件可查看或下载；GitHub未直接播放时，可下载到本地播放器观看。康复视频只是关节重复屈伸的工程示意，不代表经过临床验证的训练方案。

## 设计状态与限制

目前完成的是CAD概念结构与规定动作展示。尚未完成样机制造、结构强度与疲劳验证、实际带载驱动、温升、电池续航或真实穿戴测试。

动画使用规定轨迹，不能证明人体平衡、真实足地接触或康复效果。可调结构仍需检查不同尺寸组合的干涉与人体对轴。本资料不能直接作为供老人穿戴训练的成品设计。

## 资料范围与使用说明

本展示页只包含介绍、结构图与六段演示视频，不提供可编辑CAD、装配源文件、详细尺寸参数、制造图纸或运动输入数据。

本项目未授予开源许可证或额外的商用、再分发、改编授权；GitHub平台条款允许的行为及适用法律规定的权利除外。转载图文或视频、进一步使用设计前，请联系维护者确认授权及署名。此说明不会改变第三方材料原有权利。

署名与维护账号为Genius-two，不代表声明全部部件、方法或参考数据均为独立原创。

## 外部参考

- 电机外形与接口参考：[ENCOS官方产品页](https://www.encos.cn/productinfo/55373.html?templateId=6217)。厂家原始CAD与手册不在本展示页分发。
- 步行和楼梯动作参考：[Lencioni等，Scientific Data，2019](https://www.nature.com/articles/s41597-019-0323-z)。双侧动作包含工程相位构造，不是完整实测双侧步态。
- 起坐动作参考：[Reznick等，Scientific Data，2021](https://www.nature.com/articles/s41597-021-01057-9)及[数据入口](https://locolab.robotics.umich.edu/data.html)。参考对象不等同于目标老年人群。
- 康复动作是工程示意。原始动作数据库不随本展示页分发。
