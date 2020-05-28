# react-native-troubleshooting
react-native各种问题以及解决方案

### @react-navigation/native@5 android 手势问题

问题描述：android开启手势功能，键盘弹起输入时，点击屏幕左边的位置会出现键盘收起又弹出的问题

> 解决方法1：关闭android手势功能

> 解决方法2：缩小手势的触发区域，可以通过设置`gestureResponseDistance`实现

### [FlatList靠近屏幕底部的最后一个TextInput无法弹起键盘](https://github.com/facebook/react-native/issues/23916)

问题描述：keyboard dismisses automatically when focused on TextInput inside a Flatlist

> 解决方法：I think that setting FlatList.removeClippedSubviews to false might be a workaround for now.
