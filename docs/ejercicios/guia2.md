# Guía 2

1.  Se tiene el siguiente sistema de ecuaciones:

    $$ 2x_1 + 3x_2 = 2 $$
    $$ -3x_1+ x_2  = 3 $$
    
    Resuélvalo y represente el resultado gráficamente.
    
1.  Se tiene una barra de $1\;m$ de longitud, con sus extremos a $40^\circ C$ y $20^\circ C$. Cuando dicho medio se encuentra a una temperatura de $100^\circ C$, la barra pierde calor por convección natural con un coeficiente de convección $h_0 = 5 \frac{W}{m^2 ^\circ C}$. Considere un conjunto de puntos equiespaciados ${x_i}_{i=1,...,N}$, con $x_1$ y $x_N$ en los extremos de la barra. El estado estacionario de la misma (cuando la temperatura ya no cambia en su interior) puede resolverse numéricamente mediante el siguiente sistema de ecuaciones:

    $$ T_1 = 40 $$
    $$ -T_{i-1} + (2+h'\Delta x^2)T_i - T_{i+1} = h'\Delta x^2 T_a,\; i=2,...,N-1 $$
    $$ T_N = 20 $$
    
    Resuelva el perfil de temperaturas para $N=3,5,10,15$.

1.  Encontrar las raíces de la función $f(x) = e^{-x} -x utilizando los métodos de bisección, falsa posición, secante y Newton-Raphson. En los dos primeros tome como intervalo inicial $[0,1]$, para el método de la secante use $x_0=1$ y $x_{-1}=0$ y para el de Newton-Raphson $x_0=0$. Grafique el error en función del número de iteraciones. Analice los resultados.
