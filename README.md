线性规划问题，Matlab+Yalmip+Cplex，Ilog/Cplex，从入门开始....<br>
==

欢迎大家批评指正，又cai又爱玩  

问题一，问题描述<br>
--
1.某工厂在计划期内要安排生产桌子（table)、椅子（chair），已知生产单位产品所需的设备台时及A，B两种原材料的消耗量，如表1所示。该工厂每生产一张桌子获利2元，每生产一件椅子获利3元，问如何安排生产获利最大？

|    | 资源约束表 |    |   |
| ------------- | ------------- | ------------- | ------------- |
| Content Cell  | 桌子/张  | 椅子/张  | 合计  |
| 设备台时  | 1  | 2  | 8  |
| 原材料A  | 4  | 0  | 16 kg |
| 原材料B  | 0  | 4  | 12kg  |

建议自己写出他的数学模型，非常简单...<br>
$$
max z=2x_1+3x_2\
s.t.  x_z+2x_2<=8\
$$

$\hbar\frac
{\partial \psi}
{\partial t}
= \frac{-\hbar^2}{2m} \left(\frac{\partial^2}
{\partial x^2} + \frac{\partial^2}
{\partial y^2}+\frac{\partial^2}
{\partial z^2}
\right) \psi + V \psi$
