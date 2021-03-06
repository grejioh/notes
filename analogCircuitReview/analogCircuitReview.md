# 半导体器件
## 半导体基础知识
- 本征半导体
- N型和P型半导体
- 对于硅材料, 温度每上升8摄氏度, 本征半导体载流子浓度ni升高一倍; 对于锗材料, 大约温度升高12摄氏度, ni升高一倍
- 温度一定时 n\*p=常数

## PN结
### 异型半导体接触现象
- 浓度->扩散运动
- 电场->漂移运动
- 耗尽层(阻挡层)

### PN结单向导电特性
- 正向偏置 电源正极接P区, 负极接N区
- 外加电场削弱内建场, 阻挡层变窄, 扩散作用大于漂移作用, 多数载流子向对方区域扩散形成正向电流, 方向由P -> N
- 反向偏置 电源正极接N区, 负极接P区
- 外加电场与自建场方向相同, 增强了自建场, 使阻挡层变宽, 漂移作用大于扩散作用, 方向由N -> P
- 此处有一公式
### PN结的击穿
- 反向击穿电压UB

| 雪崩击穿   | 齐纳击穿   |
|------------|------------|
| 反向电压高 | 反向电压低 |
| 轻掺杂     | 重掺杂     |
| 正温度系数 | 负温度系数 |
| 7V以上     | 4V以下     |

- 4-7V时两种击穿都有, 6V时为零温度系数
- 反向击穿不一定就会损坏二极管

### PN结的电容效应
- 电压变化->电荷变化, 就反映出电容效应
1. 势垒电容CT
	- 阻挡层的空间电荷(不能移动的正负离子的电荷)
	- 外加电压使阻挡层变宽, 电荷量增加
	- 外加电压使阻挡层变窄, 电荷量减小
	- 阻挡层的电荷数随外加电压变化, 形成电容效应
	- 有一公式
	- 几pF~200pF, 变容二极管->压控可变电容器
2. 扩散电容CD
	- 扩散电容是PN结在正向电压时, 多数载流子在扩散过程中引起电荷积累而产生的
	- 正向电压增大, 扩散作用加强, 电荷量增加, 反之电荷量减少
	- CD正比于I

- 总结: PN结 Cj = CT + CD
- 正向偏置 扩散电容起主要作用
- 反响偏置 势垒电容起主要作用

### 半导体二极管
- P 阳极
- N 阴极

- 按材料分: 硅二极管, 锗二极管
- 按结构分:
	- 点接触型: 结电容小(阻抗小), 适合高频
	- 面接触型: 高功率?
	- 硅平面型: 集成电路

#### 二极管的特性
- 正向特性
	-	导通电压(门限电压, 死区电压) Uon
	- 硅管的Uon约为0.6~0.8V, 锗管的Uon约为0.1~0.3V
	- 可以认为电压正向电压U\<Uon时截止, U\>Uon时导通
- 反响特性
	- 反向电流数值很小, 基本不变, 称为反向饱和电流
	- 硅二极管nA级, 锗二极管uA级
	- 反向电压达到一定数值时反向电流急剧增加, 产生击穿
	- 普通二极管的反向击穿电压电压在几十伏以上
- 温度特性
	- 温度升高, 正向特性曲线向左移, 反向特性曲线向下移
	- 规律: 在室温附近, 在同一电流下, 温度每升高1摄氏度, 正向电压降减小2~2.5mV
	- 温度每升高10摄氏度, 反向电流增大一倍

#### 二极管的主要参数
- 最大整流电流I_F
- 最大反向工作电压U_R (为留有余地, 取击穿电压的一半作为U)
- 反向电流I_R 二极管未击穿时的反向电流值, 由少子构成, 受温度影响很大, 反映单向导电性
- 最高工作频率f_M 取决于结电容大小
- 二极管的直流电阻R_D = U_F/I_F 非线性
- 交流电阻r_d 工作点切线斜率的倒数 非线性; 可由PN结的电流方程求得r_d=U_T/I_D 约等于 26mV/I_DQ
- 同一工作点, 直流电阻大于交流电阻

### 稳压二极管
<++>

