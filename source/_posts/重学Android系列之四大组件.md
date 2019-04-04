---
title: 重学Android系列之四大组件
date: 2019-04-02 15:47:34
tags: 重学Android
---
### 前言
做Android挺长时间了，期间没有太重视基础知识的积累，以此系列博客作为复习。

### Activity
Activity的4种状态：running / paused / stopped / killed
Activity的生命周期：onCreate() -> onStart() - > onResume() -> onPause() -> onStop() -> onDestroy()

<center>
<img src="../images/activity.gif">
<p style="text-algin:center">Android官网生命周期图</p>
</center>

* 启动Activity：onCreate() -> onStart() - > onResume()
* 点击Home回到主屏(Activity不可见)：onPause() -> onStop()
* 当再次回到原Activity：onRestart() -> onStart() - > onResume()
* 退出Activity：onPause() -> onStop() -> onDestroy()

Android进程优先级：前台 / 可见 / 服务 / 后台 / 空

### Service

### BroadcastReceiver

### ContentProvider

### 结束语