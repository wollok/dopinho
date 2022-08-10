Tito pesa 70 kilos. Se dedida a hacer actividad física, pero las bebidas que consume le afectan su rendimiento

Pero tiene la gran ventaja de que cada bebida que toma _reemplaza_ a la sustancia anterior. Hoy modelaremos tres bebidas:

* **Whisky**: el whisky provoca sueño, mareo y jaquecas. Un deportista con whisky en su sistema tiene un rendimiento de 0.9 elevado a la dosis consumida, en centímetros cúbicos.
* **Tereré**: el tereré es diurético, laxante y estimulante del rendimiento. Un deportista con tereré en su sistema tiene un rendimiento de 0.1 por cada centímetro cúbico de dosis. Sin embargo, nunca rinde menos que 1.
* **Cianuro**: el cianuro no favorece al rendimiento, sino que el deportista, luego de consumirlo queda como muerto, llenos de abulia y de marasmo. Con cianuro, el rendimiento es siempre 0.

> 1. Hacer que Tito tome cierta cantidad de una bebida, con el mensaje `consumir(cantidad, bebida)`
> 2. Conocer la velocidad de Tito, mediante el mensaje `velocidad()`.

La velocidad de Tito (en m/s) se calcula como el rendimiento de la sustancia por la inercia base de Tito (490 kg*m/s) dividido su peso.

**¡No vale guardarse la velocidad!**

