# HCSDKtoRTMP

## 介绍
因海康nvr使用rtsp转封装为rtmp流会存在带宽限制，无法满足项目需求。故而通过海康sdk二次开发捕获码流数据，将捕获到的ps流转封装为rtmp推到nginx服务中。

## 项目完成功能
可以参考rtsp转封装rtmp实现web端播放的开源项目：[https://gitee.com/banmajio/RTSPtoRTMP](https://gitee.com/banmajio/RTSPtoRTMP)
与该项目功能一致。
该项目的出现仅仅是为了解决rtsp历史回放的问题。

## 新增的一些特性
1.增加断线重连机制
2.完善服务稳定性，解决内存溢出OOM的问题
3.增加播放器断线重连功能
4.增加Linux环境下部署的配置

## 2020-11-17 新增功能
1.抓图接口
2.倍速播放（0.25；0.5；1；2；4；8；16）
3.回放暂停与恢复
4.下载指定时间内的录像文件
5.查询指定时间点内的nvr录像文件列表
6.回放拖动进度条（正在开发中...）

## 注意
### 考虑到开发成本，该项目暂时不开源，后期视情况而定。有需要完整项目的朋友可以通过QQ：1402325991；vx：banmajio 联系！
### 项目实现思路参考CSDN博客：[海康sdk捕获码流数据通过JavaCV推成rtmp流的实现思路(PS流转封装RTMP)](https://blog.csdn.net/weixin_40777510/article/details/105840823)


