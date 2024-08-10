# WeSecure - Lab 2

Bienvenidos a un nuevo laboratorio práctico de `WeSecure`. Para este laboratorio nuestra máquina `VbD` será una versión modificada de la máquina [mercury](https://www.vulnhub.com/entry/the-planets-mercury,544/) de `vulnhub`, la cual puede ser descargada [aquí](https://drive.google.com/file/d/1dAHmEwIUczl6WEGOWwzyPTYfEpBr4TUd/view?usp=sharing). 
## Objetivos

- Aprender sobre enumeración web a través del archivo `robots.txt`.
- Aprender cómo explotar una vulnerabilidad `SQL Injection`.
- Aprender sobre `password spraying`
- Aprender sobre escalada de privilegios.
- Identificar hallazgos importantes dentro de un servidor web.
## Actividades

- Realizar un escaneo de la máquina `VbD` y encontrar en qué puerto se está corriendo el servicio web.
- Encontrar la ruta donde se ejecuta la aplicación web.
- Encontrar que parámetros son controlables para poder ejecutar una `inyección SQL`.
- Escribir un `script` en el lenguaje de programación de preferencia para hacer un `password spraying` en el servicio `SSH`.
- Realizar un movimiento lateral dentro del servidor para apropiarse de otra cuenta de usuario.
## Informe

Para este laboratorio se debe entregar informe técnico y de gerencia, incluyendo los errores que se encontraron dentro del servidor, sugerencias para remediar las vulnerabilidades y el `script` creado.

## Recursos extra
- [SQL injection](https://portswigger.net/web-security/sql-injection)
- [robots.txt](https://portswigger.net/kb/issues/00600600_robots-txt-file)
- [HuntingRobots](https://github.com/rebelskvll/HuntingRobots)
- 
