# TASK DESCOMPOSITION
Técnica con mas **impacto** en la calidad del resultado, y las más utilizada en el trabajo real.

## PROBLEMA
Cuando lepedimos todo de golpe a Claude, pidiendo diferentes objetivos, Claude prioriza unos y descuida otros

## ¿COMO SABES QUE SE DEBE DESCOMPONER UNA TAREA?
1. La petición contiene **<<y tambien>>**, **<<además>>** o **<<de paso>>**.

2. Mezclar de verbos de naturaleza distinta.
3. El resultado depende de una decisión intermedia que todavía nadie ha tomado.
4. Neceistar revisar a mitad de camino antes de continuar.
5. La tarea involucra varios documentos que comparar entre sí.
6. Si ya se intento una vez y la respuesta fue genérica

## PROMPT CHANINIG
Técnica que consiste en descomponer una misma tarea en una secuencia de pasos, donde cada paso procesa la salida de la anterior y colocar una **Comprobación** entre paso y paso(puntos de control).

```
  --------------               -------------               -------------
  |   Paso 1   |----- ✓ ----->|   Paso 2   |----- ✓ ----->|   Paso 3   |
  --------------               -------------               -------------

```

> En la documentación oficial de Anthropic los **puntos de contro** se conocen como **Gates**