# Anyboard_Retro_HW

![test](https://github.com/sunhaoqin/Anyboard_Retro_HW/blob/master/AnyBoard_Retro.jpg)

这是一个基于esp32的开源掌机项目，fork自odroid-go。

修改了扩展部分电路，以及充放电部分的电路。同时重新做了layout，采用分体式设计（核心板，扩展板，按键板，屏幕板四部分）。当不需要

作为游戏机时，可以拔下手柄换上其他的电路。

这么做是因为我觉得它不应该仅仅被当作一款掌机，事实上它是一个TF卡，喇叭，电池，屏幕，按键，wifi的集合体。这么多的部件，足够做出

很多有意思的制作了。

固件完全兼容odroid-go，所以如果使用时有任何问题，可以参考：
https://wiki.odroid.com/odroid_go/odroid_go
