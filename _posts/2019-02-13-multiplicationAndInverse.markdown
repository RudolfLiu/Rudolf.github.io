---
layout: post
title: "矩阵乘法和逆"
description: "A quick demo of Simple Texture theme's code highlighting features"
categories: [linear-algebra]
tags: [linear-algebra]
redirect_from:
  - /2019/02/13/
---

* Kramdown table of contents
{:toc .toc}

cccccccccccccccccccccccccc

$$
\begin{align*}
  A\cdot B = C
\end{align*}
$$

$$
\begin{align*}
  & \phi(x,y) = \phi \left(\sum_{i=1}^n x_ie_i, \sum_{j=1}^n y_je_j \right)
  = \sum_{i=1}^n \sum_{j=1}^n x_i y_j \phi(e_i, e_j) = \\
  & (x_1, \ldots, x_n) \left( \begin{array}{ccc}
      \phi(e_1, e_1) & \cdots & \phi(e_1, e_n) \\
      \vdots & \ddots & \vdots \\
      \phi(e_n, e_1) & \cdots & \phi(e_n, e_n)
    \end{array} \right)
  \left( \begin{array}{c}
      y_1 \\
      \vdots \\
      y_n
    \end{array} \right)
\end{align*}
$$

心累

1. A行乘B列
2. A的列向量的线性组合
3. B的行向量的线性组合
4. A列乘B行
5. 分块乘法
