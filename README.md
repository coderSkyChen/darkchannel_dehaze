# darkchannel_dehaze
- 根据CVPR2009 BestPaper论文：何等人的《Single Image Haze Removal Using Dark Channel Prior》 
- 使用C++,基于**opencv2.4.10** 实现暗通道去雾算法 
- 考虑到涉密性，暂不公布源码，只开放了打包后的EXE文件，以供测试。

# 一、效果展示：
## 1

![pic1](http://img.my.csdn.net/uploads/201612/17/1481971869_6910.png)
## 2

![pic2](http://img.my.csdn.net/uploads/201612/17/1481971870_7135.png)
## 3

![pic3](http://img.my.csdn.net/uploads/201612/17/1481971869_6910.png)

# 二、使用：
## 安装
`$ git clone: https://github.com/coderSkyChen/darkchannel_dehaze`
## 应用
运行平台限制于:**windows**
包含两个文件：
- hazeremove.exe
- test.png
执行exe文件即可获得test.png去雾后的结果图：res.png。
