# ingenieria_web_containers
 Taller Angular-Node-MongoDB-Docker

IMPORTANCIA DE UTILIZAR CONTENEDORES

las ventajas principales asociadas a los contenedores se pueden resumir en:

Solo se tiene que programar la aplicación una sola vez. Dado que una app en Docker se ejecuta dentro de un contenedor, y el contenedor se puede ejecutar en cualquier sistema operativo que tenga Docker instalado, no se tiene que programar y configurar el software para diferentes tipos de plataformas hardware o sistemas operativos en los que tiene que poder ejecutarse. Solo tienes que programarlo una sola vez para Docker.
Se obtiene una mayor consistencia entre los entornos de prueba y los entornos de producción. Cuando se desarrolla con Docker, se hacen pruebas de la app dentro de un contenedor, y la despliegas dentro de un contenedor. Eso significa que el entorno de pruebas es idéntico al entorno en el que se va a ejecutar el software. En consecuencia, los desarrolladores ganan en tranquilidad y en confianza pues saben que los usuarios finales no se van a topar con problemas que el equipo que probó el software hubiera pasado por alto.
Se obtiene mayor modularidad. El desarrollo con contenedores es ideal para un enfoque basado en microservicios para el diseño de aplicaciones. Bajo este modelo, las aplicaciones complejas se dividen en unidades más discretas y pequeñas. Por ejemplo, y sin llegar a cambiar la arquitectura tradicional de la app, la base de datos quizás se ejecute en un contenedor mientras que el front-end de la misma se ejecuta en otro distinto. Este enfoque hace que la aplicación sea modular, reduciendo la complejidad de tener que mantener y actualizar la aplicación, dado que un error o un cambio relacionado con una parte de la app no requiere que se revise la aplicación completa.

Entre otras ventajas encontramos: Retorno de la inversión y ahorro de costos, Estandarización y productividad, Eficiencia de imágenes de contenedor, Compatibilidad y mantenimiento más fácil, Simplicidad y configuraciones más rápidas, Despliegue y escalabilidad rápidos, Pruebas continuas, Plataformas multi-cloud, Aislamiento y Seguridad.


COMO CONSUMIR LA API

El desarrollo a entregar se encuenta en la carpeta "notes-api"
Se puede descargar desde Github y ejecutarla con Visual Studio ejecutando el código: "npm run dev", ya que tiene incluida la función "nodemon" con el fin de evitar que tocara estar abriendo el servidor para hacer las pruebas correspondientes.  Está en una carpeta aparte debido a que tuve problemas al correr el ejemplo de la guia.

El contenedor de docker se puede descargar desde:
"docker pull joseduvan/api-notas"
Se puede verificar la correcta carga desde la ruta:
"https://hub.docker.com/r/joseduvan/api-notas"
