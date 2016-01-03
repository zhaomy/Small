# Small [中文介绍](#zh_CN)
A small framework to split app into small parts.

[![License Apache2.0](https://img.shields.io/hexpm/l/plug.svg)][license]

# Features
* **Perfect built-in**
  - All plugins are support to build in host application.
* **Highly transparent**
  - The plugin codings (code, layout, etc.) are as same as a single application.
  - Support plugin debuging just like a completion application.
* **Ultimate slicing**
  - Splits out any shared codes and resources from plugins.
* **Seamless connection**
  - The host, native app bundle, native web bundle, online web page and any custom bundle can launch and pass parameters to each other with a simple uri.
* **Cross platforms**
  - Until now, we support android, iOS and html5 plugins. In addition, they can communicate with each other by an uniform javascript interface.

# Documentation
The development details and the code principles are on [Small Wiki][wiki].

# License
Apache License 2.0

# <a name="zh_CN">中文介绍</a>
## 功能
* **完美内置**
  - 所有插件支持内置于宿主包中
* **高度透明**
  - 插件编码、布局编写方式与独立应用开发无异
  - 插件代码调试与整包开发无异
* **极致剪裁**
  - 对插件分离所有一切能分离的公共代码、资源
* **无缝链接**
  - 通过设定URI，宿主、本地化应用插件、本地化web插件、在线网页，以及任何自定义的插件之间能够相互调起与传递参数
* **跨平台**
  - 目前已支持安卓、iOS以及html5插件。并且三者之间可以通过同一套javascript接口进行通信。

## 文档
开发细节、代码原理见 [Small Wiki][wiki]

[wiki]: https://github.com/wequick/Small/wiki
[license]: https://raw.githubusercontent.com/wequick/Small/master/LICENSE