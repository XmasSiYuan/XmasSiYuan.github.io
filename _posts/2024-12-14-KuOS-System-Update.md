---
layout:     post
title:      "KuOS 更新日志 #1"
subtitle:   "少许更新"
date:       2024/12/14 23：54
author:     "SiYuan"
header-img: "img/first blog-bg.jpg"
tags:
    - KuOS System Update log
---

更新内容:

1.更换了开始菜单和通知中心关闭判断,不再有延迟了.

2.增加了窗囗活动应用判断,解决了关闭按钮有时会不正确显示.

3.开始菜单和通知中心增加了元素.

已知bugs:

1.锁屏按钮仍不起作用.

2.对于更新内容第二点,实际上在更新窗口活动应用时,如果鼠标是直接拖动窗囗而不是单点,会导致更新活动失败,造成包括在内所有元素不会随窗囗移动,后面会修复.

其他：

音乐应用ui已确认,功能应该能一一做出来,但以最后成品为效.


![KuOS Music](http://image.nekoyuan.top/KuOS%20sys%20up%20%231-1.jpg?e=1734245251&token=jdmgvnOEWOVLAMPa56Splm4ApG83KOE-bGXBZ94i:3AOEdN1rztufYYUUgfkESa3aK3o=)
