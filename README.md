<div align=center><img src="ScreenShot/JetChatSmall.png" width="934" height="168" /></div>

# JetChat
 Swift5.0编写的简仿微信聊天应用，完美支持表情键盘、单聊、群聊、本地消息会话缓存。<br>
 
[![platform](https://img.shields.io/badge/platform-iOS-blue.svg?style=plastic)](#)
[![languages](https://img.shields.io/badge/language-swift-blue.svg)](#) 
[![support](https://img.shields.io/badge/support-ios%208%2B-orange.svg)](#) 

 ### Examples
![image](https://github.com/tanagile/JetChat/blob/master/ScreenShot/JetChat.gif)

### 主要技术运用
- 聊天功能采用RxSwift+MVVM响应式架构设计，通过ViewModel合理过渡处理消息数据，减轻Controller层业务计算
- UITableView+FDTemplateLayoutCell实现cell高度自适应计算和缓存，提高列表滑动顺滑
- wcdb实现所有会话消息快速缓存
- SnapKit纯代码自动布局
- 后续开发完善中.....

### 主要实现功能
- 聊天室键盘控件封装处理，支持表情文字多行输入，支持iOS13
- 用户：添加好友，添加群，用户备注名称修改，本地实时同步
- 聊天：一对一单聊，一对多群聊，支持文字、视频、图片发送和转发，图片和视频浏览
- 会话：最近聊天会话记录，并按照最近时间排序列表展示
- 角标：单个会话未读消息数量展示，全部未读消息数量显示
- 清除：单个消息删除，退出群，删除好友，消息会话角标清除，记录删除
- 具体功能了解可以下载源码运行查看

### Tips
- 如果你有更好的建议和方案请在lssues提交

### Licensed under the MIT licens.
- 如果你对IM即时通讯感兴趣，或者该项目对你有一些帮助，希望可以给我点个🌟Star🌟，非常感谢<br>
