## robosys_kadai1
2018年　ロボットシステム学　第1回課題　16C1041　金子 歩

## ライセンス
This repository is licensed under the GPLv3 license, see LICENSE.

## 概要
与えた入力の数字(0~2)と同じ数のLEDが点灯します。  
0を入力すると全て消灯します。  

## 操作方法
    $ make  
    $ sudo insmod myled.ko  
    $ sudo chmod 666 /dev/myled0  
    $ echo [0∼2] > /dev/myled0  

## 動画URL(YouTube)
https://youtu.be/yLTzx_TwoPQ
