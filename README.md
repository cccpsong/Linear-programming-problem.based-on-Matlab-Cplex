线性规划问题，Matlab+Yalmip+Cplex，Ilog/Cplex，从入门开始....<br>
==

欢迎大家批评指正，又cai又爱玩  

问题一，问题描述<br>
--
1.某工厂在计划期内要安排生产桌子（table)、椅子（chair），已知生产单位产品所需的设备台时及A，B两种原材料的消耗量，如表1所示。该工厂每生产一张桌子获利2元，每生产一件椅子获利3元，问如何安排生产获利最大？

|                |  资源约束表  |              |              |
| ------------- | ------------- |              |              |
| 设备台时  | 桌子/张 | 桌子/张 |
| 原材料A  | 1 |               |              |
| 原材料B  | 4 |               |              |


 |          | 资源约束表  |          | 
| ---- | ----- | ------  | ------  |
 |        |   桌子/张  |   桌子/张  |  合计  |
 |设备台时 |      1    |      2     |   8   |
 |原材料A  |     4     |      0     | 16kg |
 |原材料B  |      0    |      4     | 12kg |
