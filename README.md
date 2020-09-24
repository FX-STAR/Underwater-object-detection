# URPC 2020 水下目标检测算法赛二等奖 

![](./img/water_banner04.jpg)

## 整体方案：

- Cascade RCNN 检测算法
- 骨干网： resnetxt101_64d
- DCN
- SycBN
- GC模块
- Label smoothing
- SoftNMS

## 数据增强：

- Mixup
- Cutmix
- RandomRotate90
- Autoaugment

## 部署方法：

- 多尺度测试（no flip，翻转测试耗时）
- Pytorch DDP

## 队伍名：baseline
<div align="center"><img src="./img/rank.png"></div>