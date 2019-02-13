# YSBase
常用的一些基类

## 环境
swift4.2、iOS9.0

## 使用步骤 
1、导入框架

```swift
pod 'YSBase'
```

2、导入命名空间

```swift
import YSBase
```

## 说明
目前只抽取了6个基类：

控制器：YSBaseCollectionVC、YSBaseTabBarC、YSBaseTableVC、YSBaseVC

Cell：YSBaseCell_tbv、YSBaseCell_colv

都特别简单，看名字就知道是什么意思，具体的API也特别简单，直接进入文件查看，然后调用即可，不再做过多陈述。

注意：所有基类deinit的时候，已经做了移除通知的功能，子类无需再移除---NotificationCenter.default.removeObserver(self)
