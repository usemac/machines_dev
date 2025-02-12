# Diseño de las dimensiones de la máquina

Según {cite}`pellegrino16` el máximo par se puede aproximar como

$$
\tau_e = 2 \sigma V_r
$$ (eq:tau_sigma)

donde $V_r$ es el volumen del rotor, y $\sigma$ es el esfuerzo de corte. En la siguiente tabla se pueden encontrar algunos valores típicos de $\sigma$,

![table_3p1_shear_stress.png](figs/table_3p1_shear_stress.png)


Los parámetros de entrada pueden ser varios. Por ejemplo la potencia mecánica nominal ($P_n$) y la velocidad nominal ($\Omega_n$), que se relacionan con el par ($T_n$) según:

$$
\begin{aligned}
P_n = \Omega_n T_n
\end{aligned}
$$

En el siguiente ejemplo se supone que se conocen $P_n$ y $\Omega_n$ con lo que se obtiene $T_n$. Si se supone un valor de $\sigma$ típico, con {eq}`eq:tau_sigma`, se puede obtener un valor aproximado de volumen de rotor, $V_r$. 

Una vez obtenido el volumen se debe determinar el diámetro ($D_r$) y la longitud del rotor ($L_r$).

$$
V_r = L_r \pi \left(\frac{D_r}{2}\right)^2
$$ (eq:Vr_L_D)

En el ejemplo se supondrá que la longitud es conocida.