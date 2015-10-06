# CNode
======================

CNode-iOS 是采用 Swift 开发的cnodejs.org社区客户端

*现在仅仅开发了一小部分功能*

> 关于我，欢迎关注  
> 博客：[Jianying.Li](http://jianying.li)
> 微信：[lijy91]()

#编译环境
XCode 7+
iOS 8+
Swift 2.0

# 运行
本项目使用CocoaPods管理第三方库
 
安装项目依赖的库 
```
$pod install --verbose
```

打开CNode.xcworkspace

# 项目说明
## 
```
.
├── LICENSE
├── CNode
│   ├── APIs                        // API
│   ├── AppDelegate.swift
│   ├── Assets.xcassets
│   ├── Base.lproj
│   ├── Controllers
│   ├── Extensions
│   ├── Info.plist
│   ├── Models
│   ├── CNode-Bridging-Header.h
│   ├── Resources
│   ├── Utils
│   └── Views
│       └── Cells
├── CNode.xcodeproj
├── CNode.xcworkspace
├── Podfile
├── Podfile.lock
├── Pods
└── README.md
```


# License

    Copyright (C) 2015 JianyingLi

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
