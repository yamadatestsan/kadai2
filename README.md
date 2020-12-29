# kadai2
This is a kadai2 repository.

コードは授業で作成したROSプログラミングをそのまま使用しています。

# 使い方
以下の(1)~(4)の手順で動作します

(1)$ cd catkin_ws/src/mypkg を行い, $ git cloneでリポジトリを複製する。
https://github.com/yamadatestsan/kadai2.git

(2)$ roscore & を別ターミナルで実行

(3)$ rosrun mypkg twice.py を(1)のターミナルで入力

(4)$ rostopic echo /twice を別ターミナルで実行し, 二倍になった数字が端末上に表示される。
