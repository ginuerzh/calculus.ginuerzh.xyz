+++
date = "2018-06-24T20:51:00+08:00"
title = "Decimal Fractions. Bases Other than Ten"
+++

It is possible that there are two different decimal representations of the same number; for example,

$$
1 = 0.99999\cdots = 1.00000\cdots.
$$

In our construction the integer \\(c_0\\) is determined uniquely by \\(x\\) unless \\(x\\) itself is an integer. In that case we could choose either \\(c_0 = x\\) or \\(c_0 = x - 1\\). Once a choice has been made the digit \\(c_1\\) is unique unless \\(x\\) is one of the new points subdividing \\(I_0\\) into ten equal parts. Continuing we find that \\(c_0\\) and all \\(c_k\\) are determined uniquely by \\(x\\) unless \\(x\\) occurs as a point of subdivision at some stage. If this should happen for the first time at the \\(n\\)th stage, then

$$
x = c_0 + \frac{1}{10} c_1 + \cdots + \frac{1}{10^n} c_n,
$$

where \\(c_1, c_2, \cdots, c_n\\) are digits and where \\(c_n > 0\\), since otherwise \\(x\\) would have been a point of subdivision at an earlier stage. It follows that \\(I\_{n+1}\\)is either the interval \\([x, x+\frac{1}{10^{n+1}}]\\) or the interval \\([x-\frac{1}{10^{n+1}}, x]\\). In the first case \\(x\\) will be the left-hand end point of all later intervals \\(I\_{n+2}, I\_{n+3}, \cdots\\), and in the second case, the right-hand end point. We are then led either to the decimal representation

$$
x = c_0 + 0.c_1c_2 \cdots c_n 000 \cdots
$$

or the representation

$$
x = c_0 + 0.c_1c_2 \cdots (c_n - 1)99999 \cdots.
$$