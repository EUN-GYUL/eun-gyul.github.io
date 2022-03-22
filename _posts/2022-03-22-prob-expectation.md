---
layout: single
title:  "Expectation"
categories: probabilty
tags : probabilty
toc : true
---

---

# Expectation

## Definition

$$
\begin{array}{lllllllll}
\mbox{Discrete}&EX&=&\displaystyle\sum_x x * P(X=x)\\
\mbox{Continuous}&EX&=&\displaystyle\int_{-\infty}^{\infty} x f(x)dx\\
\end{array}
$$

## Properties of Expectation

### Expectation as a linear operator

$$
\begin{eqnarray}
(1) &&\quad\displaystyle \mathbb{E}(X+Y) =\mathbb{E}(X) + \mathbb{E}(Y) \\
(2) &&\quad\displaystyle \mathbb{E}(aX) = a\mathbb{E}(X) \\
(3) &&\quad\displaystyle \mathbb{E}(a) = a
\end{eqnarray}
$$

### Change of variable

$$
\begin{eqnarray}
(4) &&\quad\displaystyle \mathbb{E}[g(X)] =\sum_{x_i}g(x_i)p_{x_i} \\
(5) &&\quad\displaystyle \mathbb{E}[g(X, Y)] =\sum_{x_i}\sum_{y_j}g(x_i,y_j)p_{x_i},_{y_j}
\end{eqnarray}
$$

### Product of independent random variables

$$
\begin{array} {llllllll}
(6) &&\quad\displaystyle \mathbb{E}[XY] =\mathbb{E}[X]\mathbb{E}[Y] &&\mbox{if $X$ and $Y$ are independent} \\
(7) &&\quad\displaystyle \mathbb{E}g[X]h[Y] =\mathbb{E}[g(X)]\mathbb{E}[h(Y)] &&\mbox{if $X$ and $Y$ are independent} \\
\end{array}
$$



### Cauchy-Schwartz inequality

$$
\begin{eqnarray}
(8)&&\quad\displaystyle \mathbb{E}|XY|\le (\mathbb{E}X^2)^{1/2}(\mathbb{E}Y^2)^{1/2}\nonumber
\end{eqnarray}
$$










