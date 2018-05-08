No recordas la sintaxis (como se escribe un procedimiento)? No te preocupes, es normal ya que recién estamos empezando. Mirá como ejemplo este procedimiento que mueve el cabezal tres veces hacía el norte y el programa que lo usa:

```gobstones
procedure Mover5VecesHaciaElNorte() {
  Mover(Norte)
  Mover(Norte)
  Mover(Norte)
  Mover(Norte)
  Mover(Norte)
}

program {
  Mover5VecesHaciaElNorte()   
}
```