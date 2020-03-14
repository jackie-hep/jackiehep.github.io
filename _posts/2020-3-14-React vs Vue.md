---
layout:     post
title:      Vue和React之比较
subtitle:   一些主要特性的对比
date:       2020-03-13
author:     PengHe
header-img: img/post-bg-rwd.jpg
catalog: true
categories: Tech
tags:
   - React
   - Vue

---

#### 两者比较

&sup1;是否使用模板来构建应用

Vue使用模板构建应用，将标记放入HTML文件中是Vue应用的默认选项。而React应用会避开模板，要求使用JS（依赖JSX和ES6)创建DOM。对新手而言，模板更容易理解，将功能和布局分离了，但这样要求比较了解所有扩展的HTML语法，而React的渲染函数就只需要了解标准的HTML和JS即可，也便于调试。

&sup2;简单性

在Vue中可以随意改变状态，而在React中需使用API来变更它。React会区分当前和先前状态，从而知道何时以及如何在DOM中渲染。当应用状态改变时，Vue和React都会构建一个虚拟的DOM并同步真实的DOM。

&sup3;适用场景

Vue上手更快（基于模板），但基于模板很容易出现难以发现的运行时错误，难以测试，并且不容易重构和解耦。而React的组件化思想构成，使得代码容易重用和测试。Vue虽然也有组件系统，但相比React显得孱弱了些，所以React应该是大型应用必备的。

**所以个人更倾向于React,且reactnative在react基础上容易掌握。**
