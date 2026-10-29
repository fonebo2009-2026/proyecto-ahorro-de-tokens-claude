# Proyecto Ahorro de Tokens en Claude 💡

Guía práctica y plantillas para gastar menos tokens (y estirar tus límites de uso) en Claude, sin perder calidad en las respuestas.

> **Idea clave:** lo que más tokens consume no es cómo escribes el pedido, sino **cuánto texto relee Claude en cada mensaje**. En cada respuesta, Claude vuelve a leer todo el historial del chat, tus instrucciones y los archivos adjuntos. Reducir eso es lo que de verdad ahorra.

## 📂 Contenido

| Archivo | Para qué sirve |
|---|---|
| `preferencias-claude.md` | Texto corto para pegar en tus preferencias personales de Claude. Respuestas directas, sin relleno. |
| `instrucciones-proyecto.md` | Instrucciones breves para un Proyecto de Claude. |
| `guia-ahorro-tokens.md` | Los hábitos que más ahorran, ordenados por impacto. |
| `plantillas-pedidos.md` | Formas cortas de pedir cosas que evitan respuestas largas e innecesarias. |

## 🚀 Uso rápido

1. Copia el texto de `preferencias-claude.md` en las preferencias personales de tu cuenta de Claude (se aplican a todos tus chats).
2. Si trabajas con un Proyecto, pega `instrucciones-proyecto.md` en sus instrucciones y sube tus archivos de referencia al conocimiento del Proyecto.
3. Lee `guia-ahorro-tokens.md` una vez y aplica los 3 primeros hábitos. Solo con eso notarás la diferencia.

## ❌ Lo que NO funciona (y por qué lo quitamos)

Una versión anterior de este proyecto proponía "compilar" cada pedido en ChatGPT/Gemini a XML + JSON. Lo descartamos porque:

- **Alarga el pedido.** Las llaves, comillas y nombres de campo del JSON también cuentan como tokens. Un pedido de 10 tokens se convertía en 150–300.
- **Instrucciones largas cuestan en cada mensaje.** Se vuelven a leer en cada respuesta del chat.
- **El razonamiento no se apaga con texto.** El pensamiento extendido se controla con su opción en la interfaz, no escribiendo "no razones".
- **Más pasos = más errores.** Pasar por otra IA añade fallos de traducción y te obliga a repetir preguntas.

## 📊 Ahorro esperado (aproximado)

| Hábito | Ahorro típico |
|---|---|
| Chat nuevo por tema en vez de un chat eterno | Muy alto: evita releer decenas de miles de tokens de historial |
| Pedir solo el cambio, no el texto completo | 50–90% de la salida en ediciones |
| Preferencias de respuesta breve | 10–40% de la salida |
| Apagar búsqueda web / pensamiento extendido cuando no hacen falta | Variable, a menudo alto |
| Modelo ligero para tareas simples | Gasta menos de tu límite por mensaje |

*Las cifras son estimaciones orientativas; dependen del tipo de tarea.*
