# PROMPT
Es todo lo que le pasamos a Claude

## ¿QUÉ INCLUYE?
- El rol que le asignas
- El contexto
- Los datos con los que tiene que trabjar
- Las reglas que debe de respetar
- Formato de salida de la respuesta

> La calidad del prompt determina la calidad de **la respuesta**

## ANATOMÍA DEL PROMPR
- Rol - Fija el tono y nivel técnico
- Contexto - Explica el **porque** y para **quién**
- Datos - **Si los datos son largos, van arriba del prompt**
- Tarea - Verbo claro y accionable
- Restricciones - Marcar limites de tono y que evitar
- Formato - Como queremos resibir el resultado


## PRINCIPIOS QUE RECOMIENDA ANTHROPIC
1. Ser claro y directo
    - Ser Explícito
    - Cuando el orden importa, usar pasos números.
    - Un último recursos, pedir que te pregunte.
2. Explicar el porqué
    - Few shot o multishot prompting
3. Ejamplos
    - Entre 3 y 5 ejemplos
    - Relevantes
    - Diversos
    - Estructurados
4. Etiquetas XML
    - Donde **empieza** y donde **termina** cada parte del prompt
5. El orden importa
    - Documentos largos arriba
    - La pregunta abajo del todo
    > Mejora hata el 30% la calidad de la respuesta

    > Recomendiación: Citar las frases relevantes del documento en etiquetas <quotes>, después, haz la tarea.
6. Formato de salida
    - Decir que hacer

## ERRORES COMUNES
- Prompt telegráfico - *Mejora esto*
- Dar por sentado el contexto interno - *nombre de proyectos* o *siglas de la empresa*
- Acumular instrucciones en negativos
- Pedir muchas cosas sin enumerar
- Poner la pregunta arriba y el docuemnto grande abajo
- Pensar que un prompt largo es mejor.