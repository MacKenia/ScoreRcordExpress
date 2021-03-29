# ScoreRcordExpress
## A program for quick score recording

 [![GitHub](https://img.shields.io/github/license/MacKenia/ScoreRcordExpress)](https://github.com/MacKenia/ScoreRcordExpress/blob/main/LICENSE)

在统计同学成绩时，还在为不断地翻找名字，不断翻找作业本吗？这个项目帮你解决了将作业本上的成绩录入Excel表格的复杂操作。

## 起源：

Excel表格会将回车后面的信息自动录入到下一个格子中，于是诞生了这个程序

## 使用方法：

1.下载release[![GitHub release (by tag)](https://img.shields.io/github/downloads/MacKenia/ScoreRcordExpress/1.1/total?color=%23&label=Donwload%20V2)](https://github.com/MacKenia/ScoreRcordExpress/releases/download/1.1/ScoreRcordExpress.zip)中的压缩包

2.使用g++编译或者vs等编译器编译ScoreRcord.cpp后生成exe文件

3.检查Excel中的学生名字的简拼是否有相同的，若有请自行在名字中加一个字区分

4.将Excel名单粘贴到name.txt备用

![s-s-copy](https://github.com/MacKenia/ScoreRcordExpress/blob/main/img/s-copy.gif)

5.运行生成的exe文件

![s-s-copy](https://github.com/MacKenia/ScoreRcordExpress/blob/main/img/s-input.gif)

6.程序运行结束之后会生成名为score.txt的文件，其中便是已经拍好顺序的成绩，全选粘贴到Excel表格中的成绩栏即可

![s-s-copy](https://github.com/MacKenia/ScoreRcordExpress/blob/main/img/s-paste.gif)

## 注意：由于本程序使用的是GBK2312编码版本较老，有些字的首拼无法识别，可联系我定制版本或者自己修改源代码或者采用同音字替换！
