# Guía 3

1.  El agua de un lago de zonas templadas puede dividirse en estratos térmicos. Cerca de la superficie el agua es tibia y liviana (epilimnion) y en el fondo más fría y densa (hipolimnion). Lo mismo sucede en reactores químicos. Ambas capas están separadas, aproximadamente, por un plano conocido por thermocline, donde la derivada segunda de la temperatura respecto de la profundidad se hace cero (o la derivada primera tiene su máximo). A esta profundidad el flujo de calor de la superficie al fondo de la capa se puede calcular con la ley de Fourier, $J = -k\frac{dT}{dz}$. Dados los datos de la tabla siguiente, correspondientes a la temperatura del líquido de un reactor en función de la profundidad y usando el método de splines, realice un ajuste de la temperatura en función de la profundidad y de su derivada. Encuentre la posición aproximada de la thermocline y calcule el flujo de calor a través de la interfaz (tome $k = 0.01\;cal(s\;cm\;^\circ C)$)

    | $z\;[m]$              | 0 | 0.5 | 1.0 | 1.5 | 2.0 | 2.5 | 3.0 |
    | :---------------- | :---- | :---- | :---- | :---- | :---- | :---- | :---- |
    | $T\;[^\circ C]$        | 70 | 68 | 55 | 22 | 13 | 11 | 10 |
