---
title: 第一章 函数 极限 连续
date: 2022/11/17 14:00:00
categories:
- [学习笔记, 高等数学]
tags:
- 学习笔记
- 高等数学
math: true
mermaid: true
quiz: true
password: 852456llp
message: 请输入密码：
---
# 函数 极限 连续
## 1 函数
### 1.1 函数概念以及常见函数

1. `复合函数`
:::info
复合函数需要保证交集不为空集
:::
2. `反函数`
:::info
1. 不是所有函数都有反函数
2. 单调函数一定有反函数，反之则不一定，例如分段函数
3. $f^{-1}[f(x)]=f[f^{-1}(x)]=x$
:::
3. `初等函数`：幂函数、指数函数、对数函数、三角函数以及反三角函数统称为几本初等函数
[三角函数]{.label .info}
:::info
[定义域]{.label .warning}
$$\begin {array}{c}
tanx,x \in Z,x\neq k\pi + \dfrac\pi2 \\
cotx,x \in Z,x\neq k\pi
\end {array}$$
:::
4. `极限`
:::info
1. 极限 $lim_{x\rightarrow\infty}f(x)$ 存在的充分必要条件是极限$lim_{x\rightarrow-\infty}f(x)$与$lim_{x\rightarrow+\infty}f(x)$存在且相等。
2. 极限$lim_{x\rightarrow x_0}f(x)$ 存在的充分必要条件是左极限$lim_{x\rightarrow x_0^-}f(x)$与$lim_{x\rightarrow x_0^+}f(x)$存在且相等。
:::
5.`极限的性质`
:::info
1. 有界性：
   如果数列$\{x_n\}$收敛，那么数列$\{x_n\}$一定有界。无界函数一定发散，但发散数列不一定无界。
   如果$lim_{x\rightarrow x_0}f(x)$存在，则$f(x)$在$x_0$某去心领域有界（局部有界）。
2. 保号性：
3. 极值与无穷小之间的关系：
:::
1. `极限的存在准则`
:::info
1.
:::
