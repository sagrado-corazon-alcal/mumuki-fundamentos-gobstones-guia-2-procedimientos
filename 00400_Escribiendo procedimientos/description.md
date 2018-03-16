Formalicemos un poco: a la acción de crear un procedimiento nuevo la conocemos como **definición** o **declaración**, y eso nos lleva a introducir nuevos elementos sintácticos (o sea, cosas que podemos escribir en nuestro programa):

- la palabra reservada `procedure`, que indica que vamos a definir un procedimiento nuevo;
- un nombre que represente lo que nuestro procedimiento va a hacer, el cual **tiene que empezar sí o sí con mayúsculas**. Algo importante: **los paréntesis del final son necesarios**, más adelante veremos por qué;
- un **bloque de código**, que va a ser lo que se ejecute cada vez que **invoquemos** a nuestro procedimiento. Este bloque empieza con una llave de apertura (`{`) y termina con una de finalización (`}`), similar a lo que ya hacíamos para el `program`.

> Veamos si lo entendiste: escribí un procedimiento `Poner3Rojas` que ponga 3 bolitas rojas y un `program` que lo use.