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

$$\Gamma (\alpha) = 2 \int^{+\infty}_{0} t^{2\alpha-1} e^{-t^{2}} \mathrm{d}x ~ (x,t>0)$$

## 递推式

$$\Gamma (\alpha) = \int^{+\infty}_{0} x^{\alpha-1} e^{-x} \mathrm{d}x$$

$$\Gamma (\alpha - 1) = \int^{+\infty}_{0} x^{\alpha} e^{-x} \mathrm{d}x = \alpha \Gamma(\alpha)$$

### $x$ 为整数

后一项是前一项的 $\alpha$ 倍，即 $\Gamma (\alpha - 1) = \alpha \Gamma(\alpha)$ ，所以找第一项：

$$\Gamma (1) = 1 ~\Rightarrow~ \Gamma (2) = 1,~ \Gamma (3) = 2 \cdot 1 ,~ \Gamma (4) = 3 \cdot 2 \cdot 1  ~\cdots$$

$$\Rightarrow \Gamma (n+1) = n!$$

### $x$