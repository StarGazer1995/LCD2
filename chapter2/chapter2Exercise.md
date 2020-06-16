# Problem 1
## Problem a
If we choose $p, \dot{p}, \theta, and \ \dot{\theta}$ as the state vector, and we assume that:
$$
x_1 = p\\
x_2 = \dot{p}\\
x_3 = \theta\\
x_4 = \dot{\theta}
$$
The whole system could be written as:
$$
\begin{aligned}
\dot{x_1} &= x_2\\
\dot{x_2} &= \frac{x_4^2mLsinx_3-\frac{3}{4}mgsinx_3cosx_3+u}{M+m-\frac{3}{4}mgcos^2x_3}\\
\dot{x_3} &= x_4\\
\dot{x_4} &=\frac{\frac{3g}{4L}(M+m)sinx_3-\frac{3m}{4}x_4^2sinx_3cosx_3-\frac{3u}{4L}cosx_3}{M+m-\frac{3}{4}mcos^2x_3}\\
y &= x_1
\end{aligned}
$$

## Prblem b
If we assume the system is in stable:
$$
\dot{x_4}=0
$$
Then, the equations could be derived:
$$
\dot{x_{20}} = \frac{u_0}{(M+m)}\\
x_{30} = \frac{u_0}{(M+m)g}
$$