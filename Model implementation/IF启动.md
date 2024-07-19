#无感启动 #FOC 
首先明确 IF 启动的架构图。
![[Pasted image 20240708110529.png]]
从图中可以看出使用IF 启动需要给定电机运行的角度，并且给定Iqref 和Idref，送到电流环PI，再经过反Park，最后到SVPWM发波给电机。
