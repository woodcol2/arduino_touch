# 一机多头可编程点击器

## 程序功能

J1~J10为按一下按键后点住屏，再按一下按键不点,jok为每秒20次点击，按一下按键后变为不点，再按一下又为每秒20次

## 说明：

这个代码的功能是,

J1~J10,jok为按一下按键后点住屏，再按一下按键不点

jok为每秒20次点击，按一下按键后变为不点，再按一下又为每秒20次


## 注意

这个代码使用了一个第三方的多线程SCoop库，这个库使用简单，使用这个库的主要原因是为了把按键实时检测和点击头延时停顿分开，以做到点击头点击的同时不影响程序对按键的检测（因为没有使用arduino的外部中断来处理按键）

使用的时候要把lib目录下的文件夹复制到arduio的库目录下。这个目录一般是在arduino的libraries目录下，这里放了所有的第三方arduino库.

doc目录下有放一个pdf的板子使用注意说明

## 点击头购买地址:

https://fengmm521.taobao.com

## SCoop多线程库地址：

https://github.com/fabriceo/SCoop

在这里查看SCoop库的使用方法，作者有放一个pdf教程在项目目录下

实际请使用下边路径下的库

https://github.com/woodcol/arduino_touch/tree/master/lib