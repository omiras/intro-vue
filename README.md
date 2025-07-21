# Ejercicios Vue (Intro)

Abre con Live Server cada uno de los ficheros index.html del ejercicio a ralizar

En alguno de ellos tendrás que [configurar el HTML](https://vuejs.org/guide/quick-start.html#using-the-global-build) para quea gobernado por Vue 

## ¿Algo va mal?


0. Intenta no pedir la solución directa a la IA.
1. Asegurate de que has hecho bien el [setup]((https://vuejs.org/guide/quick-start.html#using-the-global-build)) , engoblado todo el HTML por un contenedor `<div id="app"></div>` 
2. Echa un vistazo a la consola del navegador. Normalmente sucede que nos olvidamos importar algo o hay un error de sintaxis
<img src="https://oscarm.tinytake.com/media/17910d3?filename=1753086794204_TinyTake21-07-2025-10-33-00_638886835924646084.png&sub_type=thumbnail_preview&type=attachment&width=615&height=486" title="Powered by TinyTake Screen Capture"/>


### 1-profile-statics

- Para este ejercicio hemos configurado Vue para ti. Borra el contenedor y la variable de estado que viene por defecto. En los próximos ejercicios tendrás que configurar Vue tu mismo.
- Este ejercicio se puede hacer con _ref_ o _reactive_
- El _quid_ de este ejercicio es que, si cambias las variables de estado, debería recalcularse toda la información que presenta la app.
- Deberás añadir algo de HTML para mostrar el mensaje inferior
- Recuerda que todo lo que pongas entre {{ }} se evalua como una expresión JavaScript. Ejemplo: `{{ 3 + 5 }}`
- **No** deberías usar nuevas variables de estado para calular el número total de años que ha trabajado el programador ni el número total de proyectos que ha creado
- Existe una forma con new Date() para obtener el año actual en el que nos encontramos

### 1.5 counter

Implementa un contador. 

### 2-random-password-generator

- Los carácteres para generar el password seguro son 8 de entre todos estos `0123456789abcdefghijklmnopqrstuvwxtz`. Puede ser una buena idea tener una variable donde almacenar esta información
- Para establecer el valor de un input usamos el atributo _value_

### 3-rock-paper-scissors-game

- Necesitarás una [función auxiliar](https://www.codewars.com/kata/5672a98bdbdd995fad00000f) para determinar el ganador 
- También necesitarás otra función auxiliar para determinar qué escoge al azar la IA en cada jugada
