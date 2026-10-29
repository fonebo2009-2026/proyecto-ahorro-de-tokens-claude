# Guía de ahorro de tokens en Claude

Ordenada de mayor a menor impacto.

## 1. Abre un chat nuevo para cada tema
En cada mensaje, Claude relee **todo** el historial de la conversación. Un chat de 40 mensajes puede costar decenas de miles de tokens por cada respuesta nueva.

- Cuando cambies de tema, abre un chat nuevo.
- Si un chat se hizo largo pero quieres seguir, pide: *"Resume en 10 líneas lo que hemos decidido"*, copia el resumen y pégalo en un chat nuevo.

## 2. Pide solo lo que cambia
- ❌ "Arregla el error y dame el código completo otra vez."
- ✅ "Arregla el error y muéstrame solo la función modificada."

En textos y código largos, esto ahorra la mayor parte de la respuesta.

## 3. No pegues lo mismo una y otra vez
- Los documentos que usas a menudo van al **conocimiento de un Proyecto**.
- Si ya pegaste algo en el chat, refiérete a ello ("el texto de arriba") en vez de pegarlo de nuevo.
- Pega solo la parte relevante: si el error está en una función, no pegues el archivo entero.

## 4. Apaga lo que no necesitas
- **Búsqueda web:** cada búsqueda trae páginas que se suman al contexto. Apágala para preguntas que no necesitan información actual.
- **Pensamiento extendido:** úsalo para problemas difíciles (matemáticas, lógica, código complejo). Para tareas simples, apágalo.

## 5. Elige el modelo según la tarea
- Tareas simples (traducir, resumir, corregir ortografía, reformatear): un modelo ligero como Haiku.
- Tareas complejas (análisis, programación difícil, escritura larga): un modelo más potente.

## 6. Sé claro a la primera
Una pregunta ambigua genera una respuesta larga que no sirve, y luego otra. Di en una línea:
- **qué** quieres,
- **para qué** o para quién,
- **en qué formato o largo**.

Ejemplo: *"Resume este informe en 5 viñetas para mi jefe, máximo 80 palabras."*

## 7. Limita el largo cuando importe
Añadir *"en 3 frases"*, *"máximo 100 palabras"* o *"solo la lista"* recorta la salida sin perder lo esencial.

---

## Lo que NO ahorra tokens
- **Convertir pedidos a JSON/XML.** Los símbolos y nombres de campo también son tokens.
- **Instrucciones de sistema largas.** Se releen en cada mensaje; cuanto más cortas, mejor.
- **Escribir "no razones" o "no pienses".** El razonamiento se controla con su opción en la interfaz.
- **Pasar el pedido primero por otra IA.** Añade un paso, a menudo alarga el texto y puede cambiar lo que pediste.
