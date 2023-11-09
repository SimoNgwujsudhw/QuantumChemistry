# About Analytic Function
题干：已知
$f(z) = u(x,y) + iv(x,y)$ 在复平面上解析，且
$$u=x^3+6x^2y-3xy^2-2y^3,f(0)=0$$
求
$f(z)$解析式

已知 $C-R$ 条件：
$$\frac{\partial u}{\partial x}=\frac{\partial v}{\partial y};\frac{\partial u}{\partial y}=-\frac{\partial v}{\partial x}$$
根据初值条件
$f(0)=0$可知：
$$v=3x^2y+6xy^2-y^3-2x^3$$
$$f(z)=(x^3+6x^2y-3xy^2-2y^3)+i (3x^2y+6xy^2-y^3-2x^3)$$
看不出
$f(z)$的显式表达，令
$z=x+iy$,有
$x=z-iy$，代入
$f(z)$
$$f(z)=(1-2i)(z-iy)^3+(6y+3yi)y(z-iy)^2+(6i-3)y^2(z-iy)-(2+i)y^3$$
可以预期最后表达式含
$y$的项都会被消除，最后算得：
$$f(z)=(1-2i)z^3$$
