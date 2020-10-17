# Ejercicios Tema 1

#### Ejercicio 1: Buscar una aplicación de ejemplo, preferiblemente propia, y deducir qué patrones es el que usa. ¿Qué habría que hacer para evolucionar a un patrón tipo microservicios?


Para este ejercicio voy a utilizar como ejemplo una aplicación que desarrollé junto a otros compañeros en la asignatura Nuevos Paradigmas de Interacción. El objetivo de este aplicación era proporcionar a los usuarios que visitaban la Alhambra una mayor facilidad para comprender cada lugar dentro de la Alhambra, ciertas historias/curiosidades, rutas, localizaciones y algunos test para poner a prueba la adquisición de conocimientos sobre la visita.  

[ConoceLaAlhambra](https://github.com/Aguilera4/ConoceLaAlhambra.git)

Esta aplicación está desarrollada en Java, empleando una arquitectura de modelo-vista-controlador, ya que el usuario interactuava directamente con la interfaz de usuario que esta a su vez transmitía la acción realizada al controlador que es el encargado de realizar el funcionamiento del proceso.

Para evolucionar la arquitectura de esta aplicación a una arquitectura de microservicios, debemos independizar las distintas funcionalidades de nuestra aplicación en distintos módulos.


#### Ejercicio 2: En la aplicación que se ha usado como ejemplo en el ejercicio anterior, ¿podría usar diferentes lenguajes? ¿Qué almacenes de datos serían lo más convenientes?

Sin lugar a duda se podría utilizar diferentes lenguajes de programación para desarollar esta App como por ejemplo la utilización de javaScript + HTML + CSS, probablemente esta opción fuera sido más eficiente que la utilizada en su momento ya que aporta una mayor versatilidad a nuestra APP.

En cierto modo, en esta aplicación no se utilizaba almacenamiento de datos. Se podría haber desarrollado un pequeño foro para cada localización donde el usuario (registrado anteriormente) comentase alguna curiosidad del sitio, en esta caso podríamos haber utilizado alguna base de datos como mySQL, PostgreSQL, MariaDB y muchas otras.