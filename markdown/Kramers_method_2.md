### Метод Крамера

с определителем матрицы системы $\Delta$, отличным от нуля, решение записывается в виде:
vmatrix
$$
x_i = \dfrac{1}{\Delta}
 \begin{vmatrix}
  a_{11} & \cdots & a_{1,i-1} & b_1 & a_{1,i+1} & \cdots & a_{1n} \\\\
  a_{21} & \cdots & a_{2,i-1} & b_2 & a_{2,i+1} & \cdots & a_{2n} \\\\
  \vdots & \ddots & \vdots & \vdots & \vdots & \ddots & \vdots  \\\\
  a_{n-1,1} & \cdots & a_{n-1,i-1} & b_{n-1} & a_{n-1,i+1} & \cdots & a_{n-1,n} \\\\
  a_{n1} & \cdots & a_{n,i-1} & b_1 & a_{n,i+1} & \cdots & a_{nn} 
 \end{vmatrix}
$$