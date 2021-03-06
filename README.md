SpainAppProto
=============

项目原型，用于展示：

* 如何使用swift第三方库，比如[Alamofire](https://github.com/Alamofire/Alamofire)等
* 如何使用objc第三方库，比如[SDWebImage](https://github.com/rs/SDWebImage)等
* 基于NSNotificationCenter的ViewController调度方式
* 首页使用AutoLayout的基于手势的动画原型

## 如何在Xcode下跑起来

先clone项目。

然后，在项目根目录下执行：
```
  git submodule update --init --recursive
```
之后，应该可以正常把项目跑起来。

## 使用的第三方库

如下：

* [Snappy](https://github.com/Masonry/Snappy) 简化autolayout代码的库
* [Alamofire](https://github.com/Alamofire/Alamofire) HTTP网络库，[AFNetworking](https://github.com/AFNetworking/AFNetworking)作者写的
* [SDWebImage](https://github.com/rs/SDWebImage) 图片加载，objc项目，通过头文件bridge方式供swift使用
