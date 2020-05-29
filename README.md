# react-native-troubleshooting
react-native各种问题以及解决方案

### @react-navigation/native@5 android 手势问题

问题描述：android开启手势功能，键盘弹起输入时，点击屏幕左边的位置会出现键盘收起又弹出的问题

> 解决方法1：关闭android手势功能

> 解决方法2：缩小手势的触发区域，可以通过设置`gestureResponseDistance`实现

### 慎用`overflow:"hidden"`
