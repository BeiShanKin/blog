---
title: UIViewController容器详解
tags: 
	- UIViewController
	- iOS
categories: iOS
---

这篇文章的主要目的就是搞清楚UIViewController.addChildViewController之后的影响，didMoveToParentViewController，willMoveToParentViewController等方法的用法和影响，还有不同容器Controller调用addChildViewController的不同影响等等问题，removeFromParentViewController会不会自动移除childVc的view