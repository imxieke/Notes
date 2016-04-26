---
title: 小书匠ppt使用示例
tags: 小书匠, presentation
preview_previewType: presentation
---

# 小书匠ppt使用示例

----

## 幻灯片

1. #### 幻灯片背景
1. #### 水平幻灯片
2. #### 垂直幻灯片
3. #### 片段

----

### 幻灯片背景
``` html
<!-- .slide: data-background="#ff0000" -->
```
支持颜色，图片，视频做为背景

----



#### **颜色幻灯片背景**

--

<!-- .slide: data-background="img/zen/3.jpg" -->

#### **图片幻灯片背景**

----


### 水平幻灯片

语法：
```
----
```
**注意前后都需要空一行**


----

### 垂直幻灯片

语法：
```
--
```
**注意前后都需要空一行**

----

垂直幻灯片1

--

垂直幻灯片２

----

### 片段

语法:
``` html
<!-- .element: class="fragment" data-fragment-index="1" -->
```
扩展样式：

``` html
<!-- .element: class="fragment>>== grow==<<" data-fragment-index="1" -->
```

`grow`, `shrink`, `roll-in`, `fade-out`, `current-visible`, `highlight-current-blue`, `highlight-red`, `highlight-green`, `highlight-blue`

----

1. 片段１
2. 片段２
3. 片段３
4. 片段４
5. 片段５
6. 片段６
7. 片段７
8. 片段８
9. 片段９
10. 片段１０
11. 片段１１

----

## 转场动画

1. 动画转场
2. 转场速度
3. 背景动画转场

----

### 动画转场
```html
<!-- .slide: data-transition="zoom"-->
```

支持的动画
`none`, `fade`, `slide`, `convex`, `concave`, `zoom`

----



#### 无动画转场

--

<!-- .slide: data-transition="fade"-->

#### fade动画转场

--

<!-- .slide: data-transition="slide" -->

#### slide动画转场

--

<!-- .slide: data-transition="convex"-->

#### convex动画转场

--

<!-- .slide: data-transition="concave"-->

#### concave动画转场

--

<!-- .slide: data-transition="zoom"-->

#### zoom动画转场

----

### 转场速度
``` html
<!-- .slide: data-transition-speed="fast"-->
```
支持的参数有: `default`, `fast`, `slow`

----

#### 默认转场速度

--

<!-- .slide: data-transition-speed="slow"-->

#### slow转场速度

--

<!-- .slide: data-transition-speed="fast"-->

#### fast转场速度

----

### 背景动画转场
``` html
<!-- .slide: data-background-transition="zoom"-->
```

支持的动画
`none`, `fade`, `slide`, `convex`, `concave`, `zoom`

----



#### convex背景动画转场

--

<!-- .slide: data-background="#4d7e65" data-background-transition="concave"-->

#### concave背景动画转场

--

<!-- .slide: data-background="#4d7e65" data-background-transition="zoom"-->

#### zoom背景动画转场

--

<!-- .slide: data-background="#4d7e65" data-background-transition="slide"-->

#### slide背景动画转场

----

#### 组合模式动画转场

--

<!-- .slide: data-background="#ff0000" data-transition="zoom" data-transition-speed="fast"-->

zoom, fast

--

<!-- .slide: data-background="img/zen/3.jpg" data-background-transition="concave" data-transition="slide" data-transition-speed="slow"-->

concave, slide, slow

--


<!-- .slide: data-background="#03c8cb" data-background-transition="fade" data-transition="convex" data-transition-speed="default"-->

fade, convex, default

----

谢谢观赏
