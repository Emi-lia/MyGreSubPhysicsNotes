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
* 对于有限深三维势阱来说，有三个n，即$n_x,n_y,n_z$，基态代表所有的n都是1，第一激发态代表一个n是2两个n是1，第二激发态代表两个n是2一个n是1.

## 谐振子
* 一维能级 $E_n=\hbar\omega(n+\frac{1}{2})$
* 三维能级 $E_n=\hbar\omega(n+\frac{3}{2})$

## delta函数
* $\delta(x_1-x_2)$ 当$x_1=x_2$时函数的值趋近于无穷大，其他时候函数值为0
* $\delta(x)$ 当$x=0$时函数的值趋近于无穷大，其他时候函数值为0

## 微扰论
* 一阶微扰修正：$\Delta E_n^{(1)}=\braket{\psi_n|v(x)|\psi_n}$
## 角动量
$$L^2=l(l+1)\hbar^2$$

## 自旋
自旋是一种内禀的角动量，其大小用自旋量子数s来表示，对于自旋s的粒子，其角动量平方满足一下关系式:
$$S^2=s(s+1)\hbar^2$$
## 自旋分量与泡利矩阵
$\hat{s_x}=\frac{\hbar}{2}\delta_x$,$\hat{s_y}=\frac{\hbar}{2}\delta_y$,$\hat{s_z}=\frac{\hbar}{2}\delta_z$
泡利矩阵的具体形式题目中一般会给出来
### 两个自旋1/2的粒子耦合
* 三重态：总自旋（s=1），有三种自旋态 $|1,1>,|1,0>,|1,-1>$
* 单重态：总自旋（s=0），只有一种自旋态 $|0,0>$

## 时间演化
时间演化算符：$U(t)=exp(-\frac{iHt}{\hbar})$
含时间演化的波函数：$\ket{\psi(t)}=exp(-\frac{i\alpha S\cdot B t}{\hbar})\ket{\psi(t=0)}$

