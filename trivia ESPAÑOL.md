Aplicación de preguntas
Requerimientos generales:
Debe utilizar una buena estructura para su aplicación. Separe el código en diferentes archivos como mejor le parezca.
La aplicación debe tener cero errores críticos y hasta tres errores pequeños (un error crítico es
definido como uno que impide que un usuario use o complete una función principal en su
app y para el cual no hay solución alternativa).
Comprometerse y enviar su trabajo a GitHub diariamente.
Publicar una aplicación web en un sitio web público.
Requisitos específicos de la aplicación:
El objetivo de la aplicación Trivia es permitir que el usuario se desafíe a sí mismo en un juego de trivia y
mostrar/guardar sus resultados. Su aplicación debe tener un mínimo de tres páginas diferentes, pero puede agregar más páginas/detalles de los que se enumeran aquí si lo desea. Depende de usted cómo enrutar entre las páginas 2 y 3. Esta API tiene documentación limitada, pero muchas opciones. Para encontrar todos los tipos de dificultad y tipos de preguntas, deberá probar la API para cada uno a fin de crear todas las opciones para su propia aplicación.

La primera página (la única página que importa el orden) que ve el usuario debe ser una página de bienvenida y configuración. La configuración consta de una lista de categorías para elegir que puede obtener de la API, una forma de seleccionar la dificultad (fácil, media, difícil) y una forma de seleccionar el tipo de pregunta de trivia (verdadero/falso o opción múltiple) . Una vez que se completa toda la configuración, el toque de un botón debería iniciar la trivia.
La segunda página es el juego de trivia. Cada pregunta aparecerá en la pantalla a la vez. Debería haber un temporizador funcionando y mostrándose. También debe mostrarse el número de pregunta y de cuántas preguntas. Una vez que el usuario haga clic en una respuesta, infórmele si lo hizo bien o no y pase a la siguiente pregunta. Una vez que haya terminado con todas las preguntas, muestre su resultado y la opción de guardar el resultado o no. Esta última vista debería tener una forma de ver la página de estadísticas.
La tercera página debe ser la página de estadísticas. Esta página debe contener una lista de los juegos de trivia que el usuario ha jugado y un poco de información sobre cada trivia (tiempo empleado, puntaje, categoría, dificultad) y una sección de estadísticas generales donde el usuario puede ver cuántas trivia ha hecho, qué es su puntaje general y cualquier otra cosa que creas que sería interesante saber. Esta página debe ser accesible desde la primera página y el usuario debe poder volver a la primera página.
Configuración (no se requiere clave API):
1. Vaya a https://opentdb.com/api_config.php
2. Haga clic en "Documentación API" para abrir puntos finales/documentación
3. Use el "Asistente de API" para ver un ejemplo de cómo debería ser un punto final de API correcto
Puntos finales:
Los puntos finales que se enumeran a continuación son solo ejemplos y se pueden modificar según los necesite.
1. Para obtener todas las categorías: "https://opentdb.com/api_category.php"
Para obtener un conjunto de preguntas que coincidan con el número de preguntas/tipo de categoría/dificultad/tipo (V/F o
Multi): "https://opentdb.com/api.php?amount=10&category=9&difficulty=medium&type=multiple"