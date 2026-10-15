# Bitácora

## Ejercicio 0 — ¿Nube o teléfono?

### Pregunta
Para cada app, ¿dónde correría el modelo y por qué: sugerir respuestas en un chat privado, resumir un PDF de 80 páginas, traducir carteles sin datos y decir si va a llover hoy?

### Respuesta
- **(a) Teléfono:** porque las conversaciones son privadas y las respuestas son cortas.
- **(b) Nube:** porque un PDF de 80 páginas necesita mucho procesamiento y un modelo pequeño puede perder información.
- **(c) Teléfono:** porque no hay internet para usar la nube.
- **(d) Ninguno por sí solo:** necesita datos del clima de una API, porque el modelo no conoce el clima actual.

---

## Ejercicio B3 — ¿Qué tan rápido es tu teléfono?

### Pregunta
Con Recado y Más amable, anota los tokens por segundo, los tokens de la respuesta y cuánto tarda en aparecer la primera palabra. Compara los resultados con la tabla del P0.1 y con alguien que tenga otra computadora. Después, revisa si la respuesta hizo lo que pediste.

### Respuesta
La velocidad depende de la computadora y de la RAM disponible en el emulador. Puede variar entre 1.5 y 12 tokens por segundo. También hay que revisar si la respuesta cumple lo que se pidió, no solo qué tan rápido aparece.

---

## Ejercicio C1 — ¿Por qué no obedeció?

### Pregunta
Prueben las tres tareas con su ejemplo: Recado → Más amable, Aviso → Más corto y Mensaje → 3 respuestas. Anoten qué sobra y qué podrían cambiar en el pedido para evitarlo.

### Respuesta
El modelo suele agregar frases, opciones, comillas y negritas porque intenta responder como en una conversación. No siempre entiende exactamente lo que queremos, así que debemos darle instrucciones más claras y mostrarle un ejemplo de cómo responder.

---

## Ejercicio C3 — El límite de un modelo de 1B

### Pregunta
Escribe «Mañana no hay clase. No pregunten. Lo que falte lo ven en su casa y el lunes hay examen de todo» y pide Más amable. ¿La respuesta dice lo mismo? Después, usa Aviso y Más amable para encontrar una frase que no venga del texto. ¿De dónde salió?

### Respuesta
La respuesta puede cambiar el sentido del texto o agregar información que no estaba en el original. Esto ocurre porque el modelo puede interpretar mal las instrucciones e inventar detalles al intentar generar una respuesta más amable. Por eso, debemos revisar que conserve la información original.