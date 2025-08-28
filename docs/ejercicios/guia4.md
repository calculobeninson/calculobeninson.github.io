# Guía 4

1.  Evalúe, utilizando los métodos de Euler, de Heun y de Runge Kutta de cuarto orden, la ecuación diferencial:

    $$
      \frac{dy}{dx} = 4 e^{0.8x} - 0.5 y
    $$

    con la condición de contorno $y(0) = 2$, desde $x = 0$ hasta $x = 4$, con varios tamaños de paso. Compare la exactitud de los diferentes métodos con el resultado exacto en $x = 4$, $y=75.3389626$. Grafique este error en función del esfuerzo de cálculo realizado (cantidad de veces que tuvo que evaluar la función). Compare la soluciones numéricas obtenidas, $y(x)$, con la solución teórica:

    $$
      y(x) = \frac{4}{1.3}(e^{0.8x} - e^{-0.5x}) + 2 e^{-0.5x}
    $$
    
1.  Utilice el código desarrollado en el ejercicio anterior para resolver la ecuación del péndulo físico:

    $$
      m\;L\frac{d^2\Theta}{dt^2}+m\;g\;sen(\Theta)=0
    $$
    
    realizando el pasaje a un sistema de dos ecuaciones de primer orden acopladas. Compare el período de oscilación obtenido con el calculado para ángulos pequeños, que debe haber visto en Física 1, en función del ángulo de apartamiento inicial.
