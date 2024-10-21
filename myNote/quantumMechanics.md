# 量子力学
## 角动量耦合
设有两个角动量分别为$s_1,s_2$，则其总角动量满足$|s_1-s_2|\leq s\leq |s_1+s_2|$，角动量z分量满足$m_s\leq s$。
## 解本征值
* 在量子力学中我们通常通过对角化一个物理量的本征矩阵来求其本征值。这个过程如下：
$det(A-\lambda I)=0$
## 一些重要的对易关系
* 角动量量子数 $[L_x,L_y]=i\hbar L_z$,$[L_z,L,x]=i\hbar L_y$,$[Ly,Lx]=-i\hbar L_z$,$[L_y,L_z]=i\hbar L_x$
* w位置-动量：$[\hat{x},\hat{p}]=i\hbar$
* $[\hat{A},\hat{B}\hat{C}]=[\hat{A},\hat{B}]\hat{C}+\hat{B}[\hat{A},\hat{C}]$


## 有限深方势阱
折射与投射：
$\phi(x)=Ae^{ikx}+Be^{-ikx},x\leq-a$
$\phi(x)=something,-a\leq x\leq a$
$\phi(x)=Ce^{ikx},x\geq a$
这部分的题目往往通过极限情况来排除。比如当势阱深度为0时粒子折射率为0 等等。

## 质能关系和德布罗意假设
* $E=h\nu$ or $E=\hbar\omega$ or $E=\frac{h c}{\lambda}$ E是粒子的能量，h是普朗克常数，$\nu$是波的频率，$\omega$是波的角频率
* $\lambda=\frac{h}{p}$ $\lambda$是波长，h是普朗克常数，p是粒子的动量
* $p=\hbar k$ k是波数

## 无限深方势阱
* 能级 $E_n= \frac{n^2 \pi^2 \hbar^2}{2mL^2}$

## delta函数
* $\delta(x_1-x_2)$ 当$x_1=x_2$时函数的值趋近于无穷大，其他时候函数值为0
* $\delta(x)$ 当$x=0$时函数的值趋近于无穷大，其他时候函数值为0

## 微扰论
* 一阶微扰修正：$\Delta E_n^{(1)}=\braket{\psi_n|v(x)|\psi_n}$
