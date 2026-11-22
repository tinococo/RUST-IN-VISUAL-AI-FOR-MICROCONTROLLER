# RUST-IN-VISUAL-AI-FOR-MICROCONTROLLER

Descripción **EN PROCESO**
En esta investigación queremos optimizar modelos de inteligencia artificial visual usando Rust y ejecutarlos en microcontroladores. Elegimos estos dispositivos porque tienen poca memoria y capacidad de procesamiento, así que los modelos deben ser pequeños y rápidos para poder trabajar en ellos.

Vamos a comparar cómo funciona un modelo antes y después de optimizarlo en Rust. Para eso, mediremos cuánto demora en analizar una imagen, cuánta memoria utiliza y si mantiene buenos resultados. Todavía no hemos elegido ni descargado una base de datos, pero podemos usar imágenes públicas para probar los modelos y comparar los resultados.

También queremos explorar si se pueden usar registros de EEG o mediciones de respuesta ocular. Aún no sabemos si los incluiremos, porque primero debemos encontrar una base de datos adecuada y ver cómo se relacionaría con la parte visual del proyecto. Además, podríamos probar algoritmos inspirados en el funcionamiento del cerebro si podemos ejecutarlos en el microcontrolador y medir su desempeño.
Objetivo
Evaluar si optimizar modelos de inteligencia artificial visual con Rust permite que funcionen más rápido y usen menos memoria en un microcontrolador, manteniendo resultados adecuados.
Qué vamos a medir
- Cuánto demora el modelo en analizar una imagen.
- Cuánta memoria utiliza.
- Cuánto espacio ocupa el modelo.
- Qué tan bien clasifica o detecta lo que aparece en las imágenes.
- Cuánta energía consume, si podemos medirla.
Cosas que todavía debemos elegir
- El microcontrolador que vamos a usar.
- Qué tarea visual haremos, como clasificación o detección de objetos.
- Qué modelo vamos a optimizar.
- Qué base de datos usaremos.
- Qué cambios haremos al código en Rust.
- Si incluiremos EEG, respuestas oculares o algoritmos inspirados en el cerebro.
