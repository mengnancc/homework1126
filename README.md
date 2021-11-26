# Homework1126
Second homework

## 实现功能及方法
* 改进了血条和子弹数的UI
* ![](https://github.com/mengnancc/homework1126/blob/main/begin.PNG) 
* 添加`RadialForce`扔手雷并炸开敌人（按G）<br> 
* ![](https://github.com/mengnancc/homework1126/blob/main/shoulei.png) 
* 使用`Spotlight`实现了枪支加手电的功能（按F）
* 使用`导航网格边界体积`实现了敌人指定区域自动追踪
* ![](https://github.com/mengnancc/homework1126/blob/main/zhuizong.PNG) 
* 增加了射击 静止 奔跑（按shift） 跳跃（按空格）等动画（基本上都是基于`分层骨骼`实现），包括敌人的攻击行走动画<br>
* ![](https://github.com/mengnancc/homework1126/blob/main/movement.png) 
* 新增了一个摄像机Actor加上`混合视图目标`实现了机瞄功能（鼠标右键）<br>
* ![](https://github.com/mengnancc/homework1126/blob/main/jimiao.png) 
* 枪械流光外形（基于`time`实现）我做了但是没有实装在player身上，可以在project中的Content文件夹的Fp_weapon的网格体中找到<br>
* ![](https://github.com/mengnancc/homework1126/blob/main/gunskin.png) 
* 利用`Camerashake`功能实现后坐力与拟真晃动
* 如果这两天有空我会把第一，三人称视角切换功能实装

## 一些补充说明
* 由于之前我按照油管上基于模板做了一个移动靶，上了两周课回顾发现第一次确实做的很蠢，这回我从空模板开始做，所有的蓝图均为我自己书写，部分动画与贴图资源谷歌下载。<br>射击的靶子改成了僵尸，加入了伤害判定和生命值以及僵尸自动寻路功能，看起来像个游戏一点
* 虽然我做了跑步和射击的动画，但是我还没有将两者很好的结合到一起，边跑边射会很鬼畜，之后我会加紧打磨
* 缺少丢手雷的动画略显僵硬
* 缺少子弹偏移

