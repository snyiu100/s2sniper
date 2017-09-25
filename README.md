# s2sniper:针对struts2漏洞的检测工具

//声明：此工具只能用于教育学习和安全检测，不得用于非法用途，此工具引发的一切非法后果皆与本人无关！

## 0x00 简介:<br>
这是一款针对struts2的漏洞检测工具，目前支持检测045，046，048，并且可以继续添加，可批量，可自定义线程数。

## 0x01 功能描述：<br>
1.单url检测。<br>
2.批量url检测。<br>
3.命令执行。<br>
4.程序执行日志记录。<br>

## 0x02 使用方法：<br>
python s2sniper.py -h<br>
单url直接输出结果，批量的结果保存在result文件夹。

## 0x03 效果图：<br>
使用帮助：<br>
![s2sniper0](https://github.com/theLSA/s2sniper/raw/master/demo/s2sniper0.png)
<br>批量检测：<br>
![s2sniper1](https://github.com/theLSA/s2sniper/raw/master/demo/s2sniper1.png)
<br>单url检测：<br>
![s2sniper2](https://github.com/theLSA/s2sniper/raw/master/demo/s2sniper2.png)
<br>命令执行：<br>
![s2sniper3](https://github.com/theLSA/s2sniper/raw/master/demo/s2sniper3.png)

## 0x04 结语：

简单的小工具，后续会不断完善，欢迎大家反馈bug和建议！<br>

我的博客：http://www.lsablog.com<br>

gmail: lsasguge@gmail.com

qq: 2894400469

## 20170924更新------------------------------------------

1.新增052，053检测，这两漏洞本地demo测试可用，但是实际环境可能要修改相关参数，否则误报率较大

2.修复网站无响应程序卡死的Bug

ps:测试url要加上http://或https://以防止出现异常或误报

本程序参考了一些大神的开源作品，在此表示感谢！








