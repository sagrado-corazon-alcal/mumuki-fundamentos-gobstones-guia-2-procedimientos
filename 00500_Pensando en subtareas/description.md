Bueno, ya sabemos cómo crear procedimientos, pero ¿por qué querríamos hacerlos?

Algunas posibles respuestas:

- para **simplificar código**, escribiendo una sola vez y en un solo lugar cosas que vamos a hacer muchas veces;
- para **escribir menos**, porque los programadores somos un poco vagos;
- para que el propósito de nuestro programa **sea más entendible para los humanos**, como vimos en el ejemplo de `DibujarCuadradoNegroDeLado3`. Para esto es fundamental **pensar buenos nombres**, que no sean muy largos (`DibujarUnCuadradoNegroDe3DeAnchoY3DeLargo`), ni demasiado cortos (`DibCuadNeg3`), y sobre todo que **dejen en claro qué efecto produce nuestro procedimiento**;
- para comunicar la **estrategia** que pensamos para resolver nuestro **problema**;
- y como consecuencia de todo esto: para **poder escribir programas más poderosos**.

En los siguientes ejercicios, vamos a escribir una versión mejorada de `DibujarCuadradoNegroDeLado3`, dividiendo cada parte del problema en procedimientos más pequeños. Para esto, vamos a plantear la siguiente **estrategia**: construir al cuadrado como tres líneas de tres bolitas, una encima de la otra. Se ve que vamos a necesitar un comando para dibujar una línea, así que arranquemos por ahí.

> Escribí un procedimiento `DibujarLineaNegra3` que, como su nombre lo indica, "dibuje una línea" poniendo 3 bolitas negras consecutivas hacia el Este.

**Nota:** De ahora en más, salvo que se indique lo contrario, el `program` lo armamos nosotros. Así que sólo tenés que escribir el procedimiento.