We deal here with a d dimensional solid model and consider $N$ quantised phonon modes with linear dispersion $\omega=ck$. Using periodic b.c., one may derive the following expression for the average energy:
$$
	\braket{E}=\sum_{0}^{\infty} \hbar \omega \left(\frac{1}{2}+n_{B}(\beta \hbar \omega))\right) 
$$
Passing from mode summation to integration over the momentum space, we inrodcuce the [[density of states]] (see the expression for [[hypersphere surface area]] $S_{d}(r)$) $g(\varepsilon)$ as follows:
$$
     g(\varepsilon)=\frac{dN(\varepsilon)}{d\varepsilon}=M\left(\frac{L}{2\pi}\right)^d\frac{S_{d}\left(k(\varepsilon))\right)}{d_{k}{\varepsilon} }=M\left(\frac{L}{2\pi}\frac{1}{c}\right)^d\frac{\pi^{d/2}d}{\Gamma\left(\frac{n}{2}+1\right)}\varepsilon^{d-1}
$$
The parameter $M$ stands here for the number of phonon modes per single wavevector $k$.
This allows to rewrite the expresion for the mean energy in a general fashion (here $z=\beta\varepsilon$):
$$
\braket{E}=\int_{0}^{\infty} \, g(\varepsilon )\varepsilon \left(\frac{1}{2}+n_{B}(\beta\varepsilon)\right)d\varepsilon = M\frac{V}{(2\pi c)^d\beta^{d+1}}\frac{\pi^{d/2}d}{\Gamma\left(\frac{n}{2}+1\right)}\int_{0}^{\infty} n_{B}(z) z^{d}  \, dz + T-\text{independent terms}    
$$
Heat capacity per site is given by the derivative of this expression:
$$
c=\frac{1}{N}\frac{ \partial \braket{E}{}  }{ \partial T }=-\frac{\beta^2}{N}\frac{ \partial \braket{ E }  }{ \partial \beta }= \frac{M(d+1)V}{(2\pi c)^d\beta^{d}}\frac{\pi^{d/2}d}{\Gamma\left(\frac{n}{2}+1\right)}\int_{0}^{\infty} \frac{z^d}{e^z-1}  \, dz
$$
The integral may be shown to be given by the [[Dzeta function]]:

$$
c=\frac{1}{N}\frac{ \partial \braket{E}{}  }{ \partial T }=-\frac{\beta^2}{N}\frac{ \partial \braket{ E }  }{ \partial \beta }= \frac{M(d+1)V}{N(2\pi c)^d\beta^{d}}\frac{\pi^{d/2}d}{\Gamma\left(\frac{n}{2}+1\right)}\left(\frac{\pi^4}{15}\right)
$$
For 3D solid with $d=3$ ($n$ stands for concentration, $M=3$ accounts for one longitudinal and 2 transverse modes):
$$
c= \frac{4\times{3}}{n(2\pi c)^3\beta^{3}}\frac{3\pi^{3/2}}{\Gamma\left(\frac{5}{2}\right)}\left(\frac{\pi^4}{15}\right)=\frac{12
}{n(2\pi c)^3\beta^{3}}\frac{3\pi^{3/2}}{\frac{3}{4}\sqrt{ \pi }}\left(\frac{\pi^4}{15}\right)=\frac{2\pi^2}{5n c^3}T^3.
$$
This reproduces the correct $c\sim T^3$ dependence. However, the Dulong-Petite law is not a high-temperature limit for this model.
