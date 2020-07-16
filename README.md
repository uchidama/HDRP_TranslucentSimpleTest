# HDRP_TranslucentSimpleTest
[![Image from Gyazo](https://i.gyazo.com/67278e9cf8b6431461956c9a05089f44.gif)](https://gyazo.com/67278e9cf8b6431461956c9a05089f44)  
HDRP Translucent Simple Test

# Memo
## 半透明の平面
<a href="https://gyazo.com/84a271e44aa005b28a8941bd4fe9cf0a"><img src="https://i.gyazo.com/84a271e44aa005b28a8941bd4fe9cf0a.png" alt="Image from Gyazo" width="320"/></a>  
マテリアルのSurface TypeをTransparentに設定。  
Surface InputsのBase ColorのA値を下げる。  

## 平面に対して反転したオブジェクト
同じオブジェクトを作って、位置、姿勢をVector3.Reflectで計算。    
[CubeRef.cs](https://github.com/uchidama/HDRP_TranslucentSimpleTest/blob/master/Assets/Scripts/CubeRef.cs)に実装が記述されている。  

# System requirements
- Unity 2019.4.4f1 or later

# License
[Unlicense](https://unlicense.org/)

# Reference material
- [Unity Documentation: Vector3.Reflect](https://docs.unity3d.com/ScriptReference/Vector3.Reflect.html)  
- [HDRPを使ってみる　その3](https://nopitech.com/2018/09/26/post-846/)

