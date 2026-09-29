# Clase 12 — Vibecoding

**Fecha:** 29-09-2026

## Antes de la clase

Se nos encargó desarrollar ejercicios prácticos con ESP32 para comprender la programación de entradas y salidas. El trabajo consistía en tres ejercicios progresivos: hacer parpadear un LED, controlarlo mediante un pulsador y, finalmente, encenderlo y apagarlo desde una página web utilizando la red WiFi de la placa.

Para el tercer ejercicio se permitía utilizar IA, siempre que pudiéramos comprender y explicar el código generado.

## Durante la clase

### Desarrollo de los ejercicios

* **Ejercicio 1 — Blink:** programamos un LED para que se encendiera y apagara cada segundo, utilizando `OUTPUT`, `digitalWrite()` y `delay()`.
* **Ejercicio 2 — Pulsador:** incorporamos un botón para controlar el LED mientras permanecía presionado, trabajando con `INPUT_PULLUP` y `digitalRead()`.
* **Ejercicio 3 — Control por WiFi:** intentamos generar con IA un código que permitiera controlar el LED desde una página web. Sin embargo, decidimos escribirlo manualmente, ya que nos resultaba más difícil identificar y corregir los errores del código generado.

### Criterios de interacción

Durante la clase, abordamos los elementos fundamentales para definir el comportamiento de un objeto interactivo:

* **Reposo:** qué hace el objeto cuando nadie interactúa con él; por ejemplo, respirar lentamente mediante la luz.
* **Input / Trigger:** qué estímulo o acción activa la interacción.
* **Output:** cómo responde el objeto ante ese estímulo.
* **Transición:** con qué ritmo e intensidad cambia entre estados.
* **Retorno:** cómo vuelve progresivamente al estado de reposo.

También revisamos el uso del *dimmer* para aumentar gradualmente el brillo y evitar encendidos bruscos. En las tiras LED, el valor máximo de brillo es 255.

## Después de la clase

A partir de los ejercicios y las correcciones, queda como aprendizaje la importancia de comprender el código antes de incorporarlo al proyecto. Para futuras interacciones, es útil solicitar a la IA que comente cada línea o que identifique únicamente aquellas partes que podemos modificar, facilitando la comprensión y los ajustes del programa.

El principal aprendizaje es que el código debe responder a una intención de diseño: definir qué comunica la luz, cómo reacciona ante las personas y cómo evoluciona la interacción, en lugar de limitarse a ejecutar acciones técnicas.


