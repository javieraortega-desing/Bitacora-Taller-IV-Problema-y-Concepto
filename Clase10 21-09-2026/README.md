# 🌐 CLASE 10 — 21/09/2026

## Replanteamiento de la forma

Para esta clase se nos pidió **replantear completamente la forma desarrollada anteriormente** y comenzar a experimentar con distintas materialidades, llegando a un objeto terminado de al menos **40 × 40 cm**.

Aunque la actividad correspondía a una semana que se suponía sería de receso. Porque claramente una semana de “descanso” era el momento perfecto para replantear un objeto completo :) .

Durante este proceso decidimos dejar atrás la forma inicial y comenzar a **abstraer directamente el hongo**, buscando que el objeto no fuera una representación literal, sino una interpretación de sus estructuras y texturas.

## 🍄 Investigación de hongos

Uno de los referentes principales fue el **Phallus indusiatus**, específicamente por la forma de su estructura y la manera en que su textura genera una apariencia extraña y orgánica.

También investigamos el **Clathrus ruber**, un hongo cuya estructura está formada principalmente por una red roja. Esta característica nos interesó porque podía transformarse visualmente en una estructura más abstracta.

A partir de estas referencias comenzamos a reducir la forma del hongo a elementos más simples, principalmente **cúpulas y estructuras repetitivas**, manteniendo la sensación de crecimiento y organismo.

<div>
  <img src="bitacora img/inspiracion3.jpeg" width="200">
   <img src="bitacora img/inspiracion5.jpeg" width="200">
   <img src="bitacora img/(MHNT)_Clathrus_ruber.jpg" width="200">
</div>

## 🕸️ Referente: Sui Park

Tomé como inspiración el trabajo de **Sui Park**, especialmente sus formas orgánicas construidas mediante la repetición y unión de pequeñas piezas.

Me interesa cómo sus estructuras pueden recordar a **organismos alienígenas, hongos o formas que parecen estar creciendo**, generando una apariencia natural pero al mismo tiempo extraña y artificial.

Esta referencia se relaciona directamente con nuestra propuesta, ya que buscamos que la forma del hongo se perciba como un **organismo vivo, extraño y potencialmente peligroso**.

<div>
  <img src="bitacora img/inspiracion4.jpeg" width="300">
   <img src="bitacora img/inspiracion1.jpeg" width="300">
</div>


## 🧵 Proceso de construcción

La estructura principal se realizó mediante **alambre**, creando una serie de cúpulas inspiradas en la abstracción de la red del *Clathrus ruber*. La repetición de estas piezas permite que el objeto mantenga una apariencia orgánica y de crecimiento.

Para integrar el circuito y evitar que los componentes quedaran completamente expuestos, incorporamos una **tela en la parte inferior de la estructura**. Esta funciona también como un difusor, permitiendo que la luz de los LED se distribuya de manera más suave y genere una apariencia más cercana a una iluminación bioluminiscente.

<div>
  <img src="bitacora img/resultado1.jpeg" width="300">
</div>

## 💡 Proceso del circuito

Otra parte importante del desarrollo fue incorporar la interacción mediante sensores.

Utilizamos **dos sensores ultrasónicos**, los cuales detectan la distancia de una persona respecto al objeto y envían esta información al **ESP32**.

El ESP32 procesa estas señales y controla los LED dependiendo de la cercanía de la persona. De esta manera, la iluminación deja de ser estática y comienza a comportarse como una **respuesta defensiva del organismo**.

El código fue desarrollado en **C++ mediante Arduino IDE** y posteriormente cargado directamente al ESP32.

**Proceso:**

<div>
  <img src="bitacora img/circuito1.jpeg" width="200">
  <img src="bitacora img/circuito2.jpeg" width="200">
  <img src="bitacora img/circuito3.jpeg" width="200">
</div>

**Sensor ultrasónico → ESP32 → procesamiento de distancia → cambio en los LED**

Esto permitió relacionar directamente la presencia de una persona con el comportamiento visual del objeto.

## 🌫️ Intento de incorporar humo

Una de las primeras ideas era que el organismo tuviera una segunda reacción cuando una persona se acercara: activar **dos humidificadores**, generando una pequeña cantidad de niebla como mecanismo de defensa.

Sin embargo, esta parte no pudo ser implementada.

No contábamos con todos los componentes necesarios ni con la experiencia suficiente para integrar correctamente los humidificadores al circuito sin arriesgarnos a generar problemas en la conexión. Por esta razón, decidimos mantener el humidificador como parte de la **abstracción visual del hongo**, incorporándolo constantemente dentro de la estructura en lugar de hacerlo depender del sensor.

<div>
  <img src="bitacora img/humificador.jpeg" width="200">
  <img src="bitacora img/humificador2.jpeg" width="200">
  <img src="bitacora img/humificador3.jpeg" width="200">
</div>

## 🟢 Concepto: defensa visual

El concepto de **defensa** nace a partir de nuestra investigación sobre la bioluminiscencia y de cómo diferentes organismos utilizan características visuales como una forma de **advertencia, protección o defensa**.

Nos interesó especialmente la idea de que algo pueda parecer peligroso sin necesariamente serlo, utilizando su apariencia para provocar una reacción en quien se aproxima.

Por eso, nuestra propuesta busca generar una contradicción entre **fragilidad y amenaza**.

El objeto tiene una apariencia orgánica y aparentemente delicada, pero cuando una persona se acerca, los LED reaccionan de manera negativa, haciendo que el organismo parezca estar **respondiendo y protegiéndose**.

La propuesta se basa finalmente en la idea de que **no todo lo que vemos es realmente lo que parece**: un objeto puede ser indefenso, pero su apariencia puede hacerlo parecer peligroso.

##Imagen para visualizar echa por IA  

<div>
  <img src="bitacora img/bioluminicencia.jpeg" width="300">
</div>
