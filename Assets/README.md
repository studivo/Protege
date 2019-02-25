# Agora real-time voice call plugin

*其他语言版本： [简体中文](README.zh.md)*

Agora real-time voice call plugin helps you quickly implement real-time voice call in Unity3D games.

Agora real-time voice call plugin contains the following folders：

- Plugins This is a necessary part of integrating Agora real-time voice call plugin, including library files that implement the core functions of Android and IOS voice.

- Scripts This is a necessary part of integrating Agora real-time voice call plugin, including api interface file for integrating Agora real-time voice call plugin. The main api interface file is the AgoraGamingRtcEngine.cs.

- Editor (alternative)This scripts helps you to link some ios system libraries that ios plugin depend on when integrating Unity3D IOS.

- TestScene.unity This is a simple example scenario for real-time voice calls.

- TestSceneScript.cs This is the script file which the sample scenario TestScene.unity depends, and you can refer to this for simple integration.


## Run the sample program
First, sign up your account at [Agora.io sign up] (https://dashboard.agora.io/cn/signup/), and create your own project to get the AppID. Fill in the AppID in TestSceneScript.cs

```
private static string appId = "YOUR APP ID";
```

Choose Build Settings and add the TestScene.unity scene to the compilation, select the compilation platform (Android or IOS), and click Build.

Make sure microphone and Camera permissions are provided before running.


## Integrate Agora real-time voice call plugin

1: Put the Plugins folder under the Assets folder to your project's Assets folder.

2: Put the Scripts folder under the Assets folder to your project's Assets folder。

3: Call api in AgoraGamingRtcEngine.cs.


## Demo Scene Running environment
* Unity 2018 +

## Agora Voice Call Plugin Support Unity version
* Unity 5.5 +

## Contact us

- See the complete API documentation[Document Center](https://docs.agora.io/cn/).
- If you have problems in integration, you can ask for help in here[Developer Center](https://dev.agora.io/cn/).
- If you have pre-sale consultation questions, you can call 400 632 6626 or join the official QQ group 12742516 to ask for help.
- If you need after-sales technical support, you can submit a work order at [Agora Dashboard] (https://dashboard.agora.io)
- If a bug is found, welcome to submit it [issue](https://github.com/AgoraIO/Hello-Unity3D-Agora/issues)

## Code permission

The MIT License (MIT).
