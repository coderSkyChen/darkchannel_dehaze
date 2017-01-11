# darkchannel_dehaze
- 根据CVPR2009 BestPaper论文：何等人的《Single Image Haze Removal Using Dark Channel Prior》 
- 使用C++,基于**opencv2.4.10** 实现暗通道去雾算法
- 具体参见我的博客： [暗通道去雾算法的C++实现与优化](http://coderskychen.cn/2015/12/11/%E6%9A%97%E9%80%9A%E9%81%93%E5%8E%BB%E9%9B%BE%E7%AE%97%E6%B3%95%E7%9A%84C-%E5%AE%9E%E7%8E%B0%E4%B8%8E%E4%BC%98%E5%8C%96%EF%BC%88%E4%B8%80%EF%BC%89/)
- 考虑到涉密性，暂不公布源码，只开放了打包后的EXE文件，以供测试。

# 一、效果展示：
## 1

![pic1](/samples/1.png)
## 2

![pic2](/samples/2.png)
## 3

![pic3](/samples/3.png)

# 二、使用：
## 安装
`$ git clone https://github.com/coderSkyChen/darkchannel_dehaze`
## 应用
运行平台限制于:**windows**
包含两个文件：
- hazeremove.exe
- test.png

执行exe文件即可获得test.png去雾后的结果图：res.png。
