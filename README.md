# Python 解密亿赛通加密文件

## 概述

很多小伙伴在看到亿赛通加密系统5.0的时候，想必非常头疼，Excel，word，PPT文件全部会被加密，打上一把黄色的锁（如下图），今天分享一下关于如何解密亿赛通加密系统文件。如何在本地电脑解密的方法！此方法需要使用到的工具是Python语言，用到的第三包有Django，项目运行前的环境配置，以下环境需你自己安装解决。

1. 安装好python安装包
   安装方法：https://www.python.org/ 官网下载exe文件，双击安装（注意python需要加入环境变量，具体方法可参考：https://mp.weixin.qq.com/s/99f1W0iS4BtdekaBpUaA_Q）	
2. 安装Django第三方包
   运行里搜索cmd,在弹出的黑框中输入pip insall Django
 

![亿赛通加密图片](./Image/Excel_decrypt.png) ![解密后图片](./Image/Excel_normal.png)


## 解密步骤
### 一、github下载源码到本地，并解压。
### 二、运行网站方法（推荐方法2）
	方法1：
	在电脑运行里输入cmd，弹出命令框，输入如下代码
	cd "代码所在的文件夹路径/Decrypt_Test"
	python manage.py runserver 127.0.0.1:8000
	方法2：
	直接双击 ‘运行网站-setup.cmd’文件即可
### 三、浏览器进入网址：http://127.0.0.1:8000/decrypt
浏览器输入网址后，如下图：选择需要解密的文件，点击上传并解密。解密后的文件默认存放在"D:\"根目录下。
	
 ![解密后图片](./Image/html_pic.png)

## 解密操作视频地址
[B站视频地址-亿赛通加密文件的解密方法](https://b23.tv/BV1Lh411275u)

## 关注公众号
欢迎大家关注公众号：Python利剑，公众号文章里面为大家详细介绍解密原理。

![公众号图片](./Image/QR_code.PNG)



