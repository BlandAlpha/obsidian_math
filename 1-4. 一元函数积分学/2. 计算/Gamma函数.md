---
属性: 拓展概念
上一层级: 
tags:
---

$\Gamma$ 函数有时候在 [[反常积分的计算]] 时有奇效。

## 定义

如果需要计算的是 $e^{x}$ ，则用第一条；如果是 $e^{x^{2}}$ 则用第二条。

$$\Gamma (\alpha) = \int^{+\infty}_{0} x^{\alpha-1} e^{-x} \mathrm{d}x$$

令 $x=t^{2}$ 得：

$$\Gamma (\alpha) = 2 \int^{+\infty}_{0} t^{2\alpha-1} e^{-t^{2}} \mathrm{d}t ~ (x,t>0)$$

> [!info] 
> $e^{-t^{2}}$ 是 [[#高斯曲线]] 。

## 递推式

$$\Gamma (\alpha) = \int^{+\infty}_{0} x^{\alpha-1} e^{-x} \mathrm{d}x$$

$$\Gamma (\alpha - 1) = \int^{+\infty}_{0} x^{\alpha} e^{-x} \mathrm{d}x = \alpha \Gamma(\alpha)$$

### 若 $x$ 为整数

后一项是前一项的 $\alpha$ 倍，即 $\Gamma (\alpha - 1) = \alpha \Gamma(\alpha)$ ，所以找第一项：

$$\Gamma (1) = 1$$

$$\Rightarrow~ \Gamma (2) = 1,~ \Gamma (3) = 2 \cdot 1 ,~ \Gamma (4) = 3 \cdot 2 \cdot 1  ~\cdots$$

$$\Rightarrow \Gamma (n+1) = n!$$

### 若 $x$ 为分数

$$\Gamma \left(\frac{1}{2}\right) = \sqrt{\pi}$$

> [!info] 
> 可用下方 [[#高斯曲线]] 面积证明。

$$\Rightarrow \Gamma \left(\frac{5}{2}\right)= \frac{3}{2} \cdot \frac{1}{2} \cdot \Gamma \left(\frac{1}{2}\right)= \frac{3}{4} \sqrt{\pi}$$

## 定义域

> [!question] 
> $\Gamma$ 函数的定义域？
>
> 让 $\Gamma$ 函数**收敛**的 $x$ 的取值

---

## 高斯曲线

$$y = e^{t^{2}}$$

曲线下围成的面积为 $\sqrt{\pi}$ ，一半为 $\frac{\sqrt{\pi}}{2}$ 。

![gaussian curve](assets/gaussian_curve.png)

> [!note] 
> 
> 证明详见 `二重积分 p255`