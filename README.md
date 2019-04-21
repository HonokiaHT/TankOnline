# TankOnline
- 网络对战坦克小游戏
- 项目的基本介绍-[点击跳转到该博客地址](https://www.cnblogs.com/tanshaoshenghao/p/10708586.html)

## 本项目涉及的知识点
- 通过面向对象思想实现坦克, 子弹, 爆炸等
- 游戏中客户端与服务器之间的交互需要自定义应用层网络协议
- 多态在发送与解析应用层协议中的使用
- 在子弹击中坦克的逻辑中使用观察者模式


## 游戏启动
- 先启动服务器`TankServer`, 注意如果多台电脑测试, 开启服务器的电脑需要关闭防火墙.
- 然后启动`TankClient`客户端, 输入服务器所在IP地址, 如果在本机测试只需要填写默认的`127.0.0.1`

## 游戏中的操作
- W A S D 对应上下左右移动, J 键开火. 
- 死亡后可重新启动`TankClient`进入游戏. 

<html>
    <img src="https://www.cnblogs.com/images/cnblogs_com/tanshaoshenghao/1426602/o_tankFight.gif"/>
</html>
