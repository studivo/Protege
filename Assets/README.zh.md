# Agora real-time voice call plugin

*Read this in other languages: [English](README.md)*

Agora 实时语音插件帮助您在 Unity3D 游戏中快速实现实时音频通话。

在 Agora 实时语音插件中包含以下几个文件夹：

- Plugins （必须部分）这是集成 Agora 实时语音插件的必须的部分，包含了实现 Android 和 IOS 语音的核心功能的库文件。

- Scripts （必须部分）这是您集成 Agora 语音的 API 接口文件，主要的 API 接口就在 AgoraGamingRtcEngine.cs 文件中。

- Editor （辅助部分）这里的脚本帮助您在集成 Unity3D IOS 时链接一些插件所依赖的 IOS 系统库。

- TestScene.unity 这是一个简单的实现了实时语音的 Demo 场景。

- TestSceneScript.cs 这是需要绑定到 TestScene.unity 场景中的一个简单的脚本文件，里面有简单的集成实时语音 API 的流程。


## 运行示例程序
首先在 [Agora.io 注册](https://dashboard.agora.io/cn/signup/) 注册账号，并创建自己的测试项目，获取到 AppID。将 AppID 填写进 TestSceneScript.cs

```
private static string appId = "YOUR APP ID";
```

在 Unity3D Build Settings 中将 TestScene.unity 场景添加到编译中，然后选择编译平台 （Android 或者 IOS)，最后点击 Build 。

运行前请确认已经提供了麦克风和 Camera 权限。


## 集成 Agora SDK 插件

1: 将 Plugins 文件夹放入您项目的 Assets 文件夹下。

2: 将 Scripts 文件夹放入您项目的 Assets 文件夹下。

3: 调用 AgoraGamingRtcEngine.cs 接口文件的 API。

## Demo Scene 运行环境
* Unity 2018 +

## Agora Voice Call Plugin 支持的 Unity 版本
* Unity 5.5 +

## 联系我们

- 完整的 API 文档见 [文档中心](https://docs.agora.io/cn/)
- 如果在集成中遇到问题, 你可以到 [开发者社区](https://dev.agora.io/cn/) 提问
- 如果有售前咨询问题, 可以拨打 400 632 6626，或加入官方Q群 12742516 提问
- 如果需要售后技术支持, 你可以在 [Agora Dashboard](https://dashboard.agora.io) 提交工单
- 如果发现了示例代码的bug, 欢迎提交 [issue](https://github.com/AgoraIO/Hello-Unity3D-Agora/issues)

## 代码许可

The MIT License (MIT).
