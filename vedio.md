---
title: 实验教学实例和视频
layout: page
hero_height: is-fullwidth
show_sidebar: false
---

### 本实验视频为《无线网络技术》(第4版，清华大学出版社，2020)的配套实验教学视频，目前已完成37项实验，还将不断更新，敬请期待。

##### 1. 构建无线网络实验环境

<p style="text-indent:2em;text-align:justify;margin-bottom:2px;word-break:break-all;">本实验为无线网络实验环境构建，是进行后续实验的基础。本实验系统的实测实验利用实验箱内各器件和PC进行，NS2仿真实验是在树莓派中运行，Contiki实测及仿真实验是在PC机中运行。通过将已制作好的系统镜像文件wnt-ns2与wnt-contiki导入树莓派和虚拟机， 搭建完整的无线网络实验环境。</p>
<p style="text-indent:2em;text-align:justify;margin-bottom:2px;word-break:break-all;">点击链接可看完整视频演示，原始长视频约6分钟。</p>
<p style="text-indent:2em;text-align:justify;margin-bottom:2px;word-break:break-all;">视频链接：<span><a href="https://v.qq.com/x/page/j0527akmica.html"><u>https://v.qq.com/x/page/j0527akmica.html/</u></a></span></p>
<p style="text-indent:2em;text-align:justify;margin-bottom:2px;word-break:break-all;">百度云下载链接：<span><a href="https://pan.baidu.com/s/1MQheLQNsSO_Aa_2sFrlYaw"><u>https://pan.baidu.com/s/1MQheLQNsSO_Aa_2sFrlYaw/</u></a></span>密码：i9e5</p>

<div>
<div style="text-align:center">
    <img src="https://0nil0.github.io/img/ex1.jpg"  width="250" height="250">
</div>
    <p style="text-align:center;">构建无线网络实验环境</p>
</div>

##### 2. 无线网络环境RSSI测量实验

<p style="text-indent:2em;text-align:justify;margin-bottom:2px;word-break:break-all;">本实验分2个部分。基础实验部分利用作者课题组开发的软件测量不同环境下WiFi的RSSI值，观察环境变化对RSSI值的影响。扩展实验部分则是对ZigBee网络RSSI值的测量，向两个CC2530节点中烧录对应代码，以观测环境变化对ZigBee网络RSSI值的影响。</p>
<p style="text-indent:2em;text-align:justify;margin-bottom:2px;word-break:break-all;">点击链接可看完整视频演示，原始长视频约8分钟。</p>
<p style="text-indent:2em;text-align:justify;margin-bottom:2px;word-break:break-all;">视频链接：<span><a href="https://v.qq.com/x/page/d0540vnb7y4.html"><u>https://v.qq.com/x/page/d0540vnb7y4.html/</u></a></span></p>
<p style="text-indent:2em;text-align:justify;margin-bottom:2px;word-break:break-all;">百度云下载链接：<span><a href="https://pan.baidu.com/s/1R7WNqFfwPzxtZ-yIWC5x0w"><u>https://pan.baidu.com/s/1R7WNqFfwPzxtZ-yIWC5x0w/</u></a></span>密码：62b0</p>
<div>
<div style="text-align:center">
<img src="https://0nil0.github.io/img/ex2-1.png"  width="250" height="250">
<img src="https://0nil0.github.io/img/ex2-2.png"  width="250" height="250">
</div>
    <p style="text-align:center;">无线网络环境RSSI测量实验</p>
</div>

##### 3.  无线局域网组网和管理实验

<p style="text-indent:2em;text-align:justify;margin-bottom:2px;word-break:break-all;">本实验分2个部分。基础实验部分首先配置无线路由器(包括SSID/密码/信道/DHCP等)，以此组建无线局域网；再利用inSSIDer软件测量不同信道下WiFi信号的稳定性，并可更换到较为空闲的的信道。</p>
<p style="text-indent:2em;text-align:justify;margin-bottom:2px;word-break:break-all;">扩展实验中利用IPerf软件测量信道较繁忙和较空闲情况下的网络传输速率。在服务器上监听3个客户端，客户端同时向服务器传输数据，以此测量每条数据流的传输速率以及总传输带宽。</p>
<p style="text-indent:2em;text-align:justify;margin-bottom:2px;word-break:break-all;">点击链接可看完整视频演示，原始长视频约9分钟。</p>
<p style="text-indent:2em;text-align:justify;margin-bottom:2px;word-break:break-all;">视频链接：<span><a href="https://v.qq.com/x/page/a0540s6p1sh.html"><u>https://v.qq.com/x/page/a0540s6p1sh.html/</u></a></span></p>
<p style="text-indent:2em;text-align:justify;margin-bottom:2px;word-break:break-all;">百度云下载链接：<span><a href="https://pan.baidu.com/s/1mW6kWV5OSLzv2_xnVp004g"><u>https://pan.baidu.com/s/1mW6kWV5OSLzv2_xnVp004g/</u></a></span>密码：6xa2</p>

<div>
<div style="text-align:center">
    <img src="https://0nil0.github.io/img/ex3_1.png"  width="250" height="250">
    <img src="https://0nil0.github.io/img/ex3_2.png"  width="250" height="250">
</div>
    <p style="text-align:center;">无线局域网组网和管理实验</p>
</div>

##### 4. 无线局域网信号测量软件开发实验

<p style="text-indent:2em;text-align:justify;margin-bottom:2px;word-break:break-all;">本实验在Windows环境下自主开发一个无线局域网信号测量软件。该软件通过C++调用Winpcap网络开发包，对WiFi数据进行捕获，储存至临时文件。随后在Java环境下，通过内置表格类JTable和开源图表绘制类库JFreeChart，对临时文件中的数据进行展示和图形化分析。</p>
<p style="text-indent:2em;text-align:justify;margin-bottom:2px;word-break:break-all;">点击链接可看完整视频演示，原始长视频约7分钟</p>
<p style="text-indent:2em;text-align:justify;margin-bottom:2px;word-break:break-all;">视频链接：<span><a href="https://v.qq.com/x/page/z054062yn2w.html"><u>https://v.qq.com/x/page/z054062yn2w.html/</u></a></span></p>
<p style="text-indent:2em;text-align:justify;margin-bottom:2px;word-break:break-all;">百度云下载链接：<span><a href="https://pan.baidu.com/s/13NLkE4DWB0elEWQHRuY9Rg"><u>https://pan.baidu.com/s/13NLkE4DWB0elEWQHRuY9Rg/</u></a></span>密码：ijqi</p>

<div>
<div style="text-align:center">
    <img src="https://0nil0.github.io/img/ex4.png"  width="250" height="250">
</div>
    <p style="text-align:center;">无线局域网信号测量软件开发实验</p>
</div>

##### 5. 无线局域网数据分组分析

<p style="text-indent:2em;text-align:justify;margin-bottom:2px;word-break:break-all;">本实验分别在Windows和Linux系统下使用Wireshark捕获无线局域网数据包进行分析，并介绍了在Linux系统下Kismet软件的使用，实验结果以数据和图形方式显示，读者可自行进行分析。</p>
<p style="text-indent:2em;text-align:justify;margin-bottom:2px;word-break:break-all;">点击链接可看完整视频演示，原始长视频约4分钟。</p>
<p style="text-indent:2em;text-align:justify;margin-bottom:2px;word-break:break-all;">视频链接：<span><a href="https://v.qq.com/x/page/o0540f7maw8.html"><u>https://v.qq.com/x/page/o0540f7maw8.html/</u></a></span></p>
<p style="text-indent:2em;text-align:justify;margin-bottom:2px;word-break:break-all;">百度云下载链接：<span><a href="https://pan.baidu.com/s/1Uwk8t8qGXJJGHsD_Nj7XpA"><u>https://pan.baidu.com/s/1Uwk8t8qGXJJGHsD_Nj7XpA/</u></a></span>密码：oepu</p>

<div>
<div style="text-align:center">
    <img src="https://0nil0.github.io/img/ex5.png"  width="250" height="250">
</div>
    <p style="text-align:center;">无线局域网数据分组分析</p>
</div>

##### 6. 无线局域网数据分组分析软件开发实验

<p style="text-indent:2em;text-align:justify;margin-bottom:2px;word-break:break-all;">本实验在Windows环境下，利用Winpcap网络开发组件，实现了一个无线局域网数据分组分析软件，界面类似WireShark。该软件能够对无线局域网的数据分组进行捕获，并可进一步分析其协议类型以及下层帧的构成。读者可通过本实验开发流程，熟悉网络抓包原理，了解报文格式和功能。</p>
<p style="text-indent:2em;text-align:justify;margin-bottom:2px;word-break:break-all;">点击链接可看完整视频演示，原始长视频约16分钟。</p>
<p style="text-indent:2em;text-align:justify;margin-bottom:2px;word-break:break-all;">视频链接：<span><a href="https://v.qq.com/x/page/q0540j7xqeq.html"><u>https://v.qq.com/x/page/q0540j7xqeq.html/</u></a></span></p>
<p style="text-indent:2em;text-align:justify;margin-bottom:2px;word-break:break-all;">百度云下载链接：<span><a href="https://pan.baidu.com/s/15m3mmA-EXuen6A_stnwKLA"><u>https://pan.baidu.com/s/15m3mmA-EXuen6A_stnwKLA/</u></a></span>密码：l9kj</p>

<div>
<div style="text-align:center">
    <img src="https://0nil0.github.io/img/ex6.png"  width="250" height="250">
</div>
    <p style="text-align:center;">无线局域网数据分组分析软件开发实验</p>
</div>