# A-Frame介绍
## 目录
[TOC]
## 1 什么是A-Frame？
![A-Frame logo](./img/aframe-logo.jpg)
[A-Frame][aframe]是由[Mozilla][mozilla]旗下的VR团队[MozVR][mozvr]推出的一个开源框架，使开发者不必学习复杂的3D绘图标准WebGL，就能够轻松完成3D或VR网页的制作。
A-Frame的使用简单到什么程度呢？只要在网页文件中加入以下一行代码，就可以将A-Frame组件集成到网页中，通过使用熟悉的HTML代码方式，便可以方便地进行3D和VR内容的开发。
```xml
<script src="https://aframe.io/releases/0.2.0/aframe.min.js"></script>
```
## 2 A-Frame能做什么？
下面用几个A-Frame应用的实例来给你一个直观的感受。
### [动态UI](./examples/showcase/anime-UI)
[![anime-ui](./img/anime-ui.jpg)](./examples/showcase/anime-UI)
### [动画](./examples/animation/generic-logo)
[![generic-logo](./img/generic-logo.jpg)](./examples/animation/generic-logo)
### [组合](./examples/showcase/composite)
[![composite](./img/composite.jpg)](./examples/showcase/composite)
### [弯曲的图像](./examples/showcase/curved-mockups)
[![curved-mockups](./img/curved-mockups.jpg)](./examples/showcase/curved-mockups)
### [动态光源](./examples/showcase/dynamic-lights)
[![dynamic-lights](./img/dynamic-lights.jpg)](./examples/showcase/dynamic-lights)
### [3D模型-模拟购物](./examples/showcase/shopping)
[![shopping](./img/shopping.jpg)](./examples/showcase/shopping)
### [虚拟场景](./examples/test/geometry-gallery)
[![geometry-gallery](./img/geometry-gallery.jpg)](./examples/test/geometry-gallery)
### [光标交互](./examples/test/cursor)
[![cursor](./img/cursor.jpg)](./examples/test/cursor)
### [播放全景图](./examples/boilerplate/panorama)
[![panorama](./img/panorama.jpg)](./examples/boilerplate/panorama)
### [播放全景视频](./examples/boilerplate/360-video)
[![360-video](./img/360-video.jpg)](./examples/boilerplate/360-video)

## 3 A-Frame的特点

## 4 A-Frame的学习和使用
### 4.1 helloworld
下面是一个简单的A-Frame的helloworld例子，在一个VR场景中，放置了一个球体，长方体，圆柱体，平面，和一个背景。
```xml
<html>
  <head>
    <script src="https://aframe.io/releases/0.2.0/aframe.min.js"></script>
  </head>
  <body>
    <a-scene>
      <a-sphere position="0 1.25 -1" radius="1.25" color="#EF2D5E"></a-sphere>
      <a-box position="-1 0.5 1" rotation="0 45 0" width="1" height="1" depth="1"  color="#4CC3D9"></a-box>
      <a-cylinder position="1 0.75 1" radius="0.5" height="1.5" color="#FFC65D"></a-cylinder>
      <a-plane rotation="-90 0 0" width="4" height="4" color="#7BC8A4"></a-plane>
      <a-sky color="#ECECEC"></a-sky>
    </a-scene>
  </body>
</html>
```
以上代码的实际效果如下图所示。([点击查看helloworld网页](./examples/boilerplate/hello-world/))
![helloworld](./img/helloworld.jpg)

[aframe]: https://aframe.io
[awesome]: https://github.com/aframevr/awesome-aframe
[mozilla]: https://developer.mozilla.org
[mozvr]: http://mozvr.com
[slack]: https://aframevr-slack.herokuapp.com/
[three]: http://threejs.org/
[webvr]: http://mozvr.com/#start