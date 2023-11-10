# 1d Schrodinger's Equation with Potential δ(x)
$\delta$
势下的一维定态薛定谔方程：
$$-\frac{\hbar^2}{2m} \frac{d^2}{dx^2} \psi(x)-V_0  \delta(x) \psi(x) = E \psi(x)$$
对其进行傅里叶变换，并设
$F[\psi(x)]=F(\omega)$,得到：
$$\frac{\omega^2 \hbar^2}{2m}F(\omega)-V_0\psi(0)=EF(\omega)$$
解得:
$$F(\omega)=\frac{2mV_0 \psi(0)}{\hbar^2}\times \frac{1}{\omega^2-\frac{2mE}{\hbar^2}}$$
根据傅里叶逆变换有：
$$\psi(x) = \frac{1}{2\pi}\int_{-\infty}^{\infty}\frac{2mV_0 \psi(0)}{\hbar^2}\times \frac{e^{i\omega x}}{\omega^2-\frac{2mE}{\hbar^2}}d\omega$$
整理得到：
$$\psi(x) = \frac{mV_0\psi(0)}{\pi\hbar^2}\int_{-\infty}^{\infty}\frac{e^{i\omega x}}{\omega^2-\frac{2mE}{\hbar^2}}d\omega$$
若
$E<0$，则解得波函数为束缚态波函数，令
$g(\omega)=\frac{e^{i\omega x}}{\omega^2-\frac{2mE}{\hbar^2}}$,利用留数定理可得：
$$I=\int_{-\infty}^{\infty}\frac{e^{i\omega x}}{\omega^2-\frac{2mE}{\hbar^2}}d\omega=2\pi i\sum_{上半平面}Res\ g(\omega_{i})$$
$g(\omega)$
在上半平面存在一阶极点
$\omega=\frac{\sqrt{-2mE}}{\hbar}i$,求得该点留数为：
$$Res\ g(\omega_{0})=\frac{\hbar e^{-\frac{\sqrt{-2mE}}{\hbar}x}}{\sqrt{-2mE}i}$$
则所求波函数即为：
$$\psi(x)=\frac{mV_0\psi(0)}{\hbar\sqrt{-2mE}}e^{-\frac{\sqrt{-2mE}}{\hbar}x}$$
根据波函数在
$x=0$的连续条件，求得
$E=-\frac{mV_{0}^2}{2\hbar^2}$，结合波函数的归一化条件以及束缚态波函数宇称的要求，解得束缚态波函数：
$$
\psi(x)=\frac{\sqrt{mV_0}}{\hbar}e^\frac{-2\sqrt{-2mE}}{\hbar}x\ \ \ \ \ \ \ \ \ \ \ x>0\\
\psi(x)=\frac{\sqrt{mV_0}}{\hbar}e^\frac{-2\sqrt{2mE}}{\hbar}x\ \ \ \ \ \ \ \ \ \ \ \ \ x<0