# DemoProject
一个包含[DemoCollection](https://github.com/JWBlueLiu/DemoCollection)和[Android官方Demo](https://github.com/JWBlueLiu/DemoProject/tree/master)的工程

# 介绍
##### **平时的Demo存储仓库**
&emsp;&emsp; * [DemoCollection](https://github.com/JWBlueLiu/DemoCollection)
##### **Android官方Demo**
&emsp;&emsp; * [ApiDemos](https://github.com/JWBlueLiu/DemoProject/tree/master/ApiDemos)

&emsp;&emsp; * [Support4Demos](https://github.com/JWBlueLiu/DemoProject/tree/master/Support4Demos)

&emsp;&emsp; * [Support7Demos](https://github.com/JWBlueLiu/DemoProject/tree/master/Support7Demos)

&emsp;&emsp; * [Support13Demos](https://github.com/JWBlueLiu/DemoProject/tree/master/Support13Demos)

&emsp;&emsp; * [SupportAppNavigation](https://github.com/JWBlueLiu/DemoProject/tree/master/SupportAppNavigation)

&emsp;&emsp; * [SupportDesign](https://github.com/JWBlueLiu/DemoProject/tree/master/SupportDesign)

&emsp;&emsp; * [SupportLeanbackDemos](https://github.com/JWBlueLiu/DemoProject/tree/master/SupportLeanbackDemos)

&emsp;&emsp; * [SupportLeanbackShowcase](https://github.com/JWBlueLiu/DemoProject/tree/master/SupportLeanbackShowcase)

&emsp;&emsp; * [SupportPercentDemos](https://github.com/JWBlueLiu/DemoProject/tree/master/SupportPercentDemos)

&emsp;&emsp; * [SupportPreferenceDemos](https://github.com/JWBlueLiu/DemoProject/tree/master/SupportPreferenceDemos)

&emsp;&emsp; * [SupportTransitionDemos](https://github.com/JWBlueLiu/DemoProject/tree/master/SupportTransitionDemos)

&emsp;&emsp; * [SupportVectorDrawable:animated](https://github.com/JWBlueLiu/DemoProject/tree/master/SupportTransitionDemos/animated)

&emsp;&emsp; * [SupportVectorDrawable:static](https://github.com/JWBlueLiu/DemoProject/tree/master/SupportTransitionDemos/static)

based on [Revision 25.2.0](https://developer.android.com/topic/libraries/support-library/revisions.html?hl=zh-cn#25-2-0)

# git submodule

[DemoCollection](https://github.com/JWBlueLiu/DemoCollection)在此项目中使用`git submodule`进行管理
GitSubmodule快速入门:

```shell
git submodule init
git submodule update
```

在项目中使用引入Library:

```shell
git submodule add xxxx(你需要的git库)
git submodule update
```

更新所有module:

```shell
git submodule foreach git pull origin master
```
关于[GitSubmodule详细使用](http://ntop001.github.io/2014/05/29/Git-Submodule/)