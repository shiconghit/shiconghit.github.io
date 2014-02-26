---
layout: post
title: 磁材表面缺陷视觉检测
categories: [图像处理]
tags: [尺寸 缺陷检测]
---

《磁材表面缺陷视觉检测方法》作为研究生毕业设计，主要用于解决磁材形变以及表面缺陷的在线检测。主要创新点为：提出了一种金子塔的边缘模板匹配方法，研究了磁材纹理的提取和滤波，以及缺陷区域的分割、缺陷的描述以及分类。最后对算法进行优化，一帧图像(1292*964)检测时间150ms以内，满足工业产品实时检测的要求。 [[论文链接]](http://wenku.baidu.com/view/781bb3c7aef8941ea76e055e.html)。

当时做的PPT，也一并放出来吧[链接](http://wenku.baidu.com/view/2ae3d5d5172ded630b1cb666.html)

---

主要一些性能指标

- 图像匹配时间在50ms;
- 尺寸测量以及表面测量的时间为80ms;
- 总共图像处理时间在150ms以内;
- 尺寸检测的精度可达到100um；面积检测误差在100像素面积以内;
- 重复检测误差小于1%;
- 连续稳定运行时间在5小时以上;
- 误检率小于2％;
- 支持检测磁材的种类达9种以上;

---

最后贴上一个视频，展示一下整个软件的运行情况。

<embed src="http://player.youku.com/player.php/sid/XNjc3ODU2NTY4/v.swf" allowFullScreen="true" quality="high" width="480" height="400" align="middle" allowScriptAccess="always" type="application/x-shockwave-flash"></embed>