# Mi propuesta de mejora para la hoja de asistencia

https://docs.google.com/spreadsheets/d/1l1Agzfr3_j_U9nlYZBh4bTw83zf2vtDWvH3Q6HuETdw/edit?usp=sharing

### Cambios realizados:

1. Las fórmulas de cada clase se modificaron añadiendo otra condicional que incluya el caso de
que la fecha universal sea igual a la de una clase

   Fórmula resultante:
=Si($A$2= [fecha de la clase] ;1;Si($A$2> [fecha de la clase] ; 0; 2))

2. Añadida una condicional al formato condicional de cada casilla de clase que aplica un color rojo a dicha casilla cuando 
el valor sea 1 (sea el día de dicha clase)
