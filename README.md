# `Face Hand Detection Unity`
---
### What does this project do?

This repository is a Unity3D Project that **`detects faces and hands in 2D/3D`**. 👍<br>
You can test this project on `Android` and `iOS`.<br>
### OR, just download <img width="25" src="https://i.imgur.com/e8wjusG.png"/> **Alchera** app from <img width="25" src="https://i.pinimg.com/originals/45/13/0a/45130a9d775c2aefcc124f96f69dbe9a.jpg"/> or <img width="25" src="http://mblogthumb4.phinf.naver.net/20150908_215/elimmedia_an_1441696061085odskM_PNG/1441288794_playstore.png?type=w2"/> for testing.

---
### What's in it?
|Face2DFacemark|Face3DSticker|Face3DAnimoji|
|:-:|:-:|:-:|
|![](https://media.giphy.com/media/Uov097lvdnXrq7cS5L/giphy.gif)|![](https://media.giphy.com/media/S6Z48wBxLRajZTzrfQ/giphy.gif)|![](https://media.giphy.com/media/eIaOn6eLvzBBIT4Uzf/giphy.gif)|

|Face3DMask|Hand2DSkeleton|Complex(face+hand)|
|:-:|:-:|:-:|
|![](https://media.giphy.com/media/WOHY3NvxNv6MFxAjxx/giphy.gif)|![](https://media.giphy.com/media/dsdRPOxwqMDDqX24sU/giphy.gif)|![](https://media.giphy.com/media/QBwRPVOlP2EIUsBSIR/giphy.gif)| 

---
<details>
  <summary>Open<h3>What is the scope of your application?<h3></summary>
  
> Device Orientation
> - [x] Portrait
> - [ ] Portrait Upside Down
> - [x] Landscape Right
> - [x] Landscape Left

> Camera
> - [x] Front Camera
> - [x] Rear Camera

> Platform
> - [x] Androidㅤ`ARMv7`, `ARM64`
> - [x] iOSㅤㅤㅤ`arm64`, `armv7`, `armv7s`
> - [ ] Windows Editorㅤ(If you want to use it, Please contact [Alchera](mailto:alchera@alcherinc.com))
> - [ ] MacOS Editorㅤㅤ(If you want to use it, Please contact [Alchera](mailto:alchera@alcherinc.com))

> Max detection count
> - [x] Unlimited. `The more, the slower.`
</details>


---
<details>
  <summary>Open<h3>How do I run the test?<h3></summary>
    
    Click image below to see Youtube tutorial.
[![Video Label](https://i.imgur.com/9dLzsm3.png)](https://www.youtube.com/watch?v=tSU9wG1huhU)<br>

> 1. **Clone** or **Download** this repository.

> 2. open it with **Unity3D**<br>
> we've tested with Unity3D version **`2019.2.13f`** `Universal RP`.<br>
> `Universal RP` is optional, but without setup, graphics can be broken as follows:<br>
> <img width="600" src="https://i.imgur.com/vNeZtmm.png"/><br>
> If you don't mind, it will work in the 2018 as well.

> 3. If you want to play with **`iOS`**. unzip [opencv2.framework](https://github.com/AlcheraInc/Face-Hand-Detection-Unity/releases/download/opencv2.framework/opencv2.framework.zip) to Assets/Alchera/Plugins/iOS<br>
> (It is too large for github push)<br>
> <img width="500" src="https://i.imgur.com/OLnMasu.png"/><br>
> Make sure the platform is checked with iOS.<br>

> 4. Set Unity3D settings.<br>
> `Window - Package Manager`<br>
> <img width="500" src="https://i.imgur.com/HbmbiEA.png"/><br>
> We use Universal RP 6.9.2<br><br>
> `File - Build Settings`<br>
> <img width="500" src="https://i.imgur.com/5VGvf8E.png"/><br>
> Place the `Splash`scene first and the `DemoUI`scene second.<br><br>
> `Edit - Project Settings - Graphics`<br>
> <img width="500" src="https://i.imgur.com/qalWxXS.png"/><br>
> Set `Scriptable Render PipelineAsset` to **`LightweightAsset`**. for `Universal RP`<br><br>
> `Edit - Project Settings - Player - Other Settings - iOS`<br>
> <img width="500" src="https://i.imgur.com/K83k8Sz.png"/><br>
> `Edit - Project Settings - Player - Other Settings - Android`<br>
> <img width="500" src="https://i.imgur.com/62GRibJ.png"/><br>

> 5. Build And Run.<br>
> build with `iOS` or `Android`. And see the **`magic :)`**
</details>


---
<details>
  <summary>Open<h3>I want to know more about sdk!<h3></summary>

Please check **`Assets/Alchera/AlcheraUnitySDK_Document_2020.1.0`** (English and Korean supported)<br>
OR, conctact [Alchera](mailto:alchera@alcherinc.com).
</details>

---
### Until when can I use it?

This SDK is available until **`2020/5/31`**. If you want to extend the deadline after the test, please contact [Alchera](mailto:alchera@alcherinc.com).<br>
You can play with this project. but if you want to distribute your project, please contact [Alchera](mailto:alchera@alcherinc.com).<br><br>

<p align="center">Copyright 2016. Alchera inc. All rights reserved.</p>
