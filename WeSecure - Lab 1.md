# WeSecure - Lab 1

Bienvenidos a un nuevo laboratorio práctico de `WeSecure`. En este laboratorio abordaremos una vulnerabilidad de la máquina `VbD` del laboratorio anterior y tenderemos un primer acercamiento a herramientas como `nmap` y `metasploit`, las cuales vienen previamente instaladas en nuestra máquina `red`. 

En el [[WeSecure - Lab 0]] ya hemos configurado un entorno de red aislado con nuestra máquina `VbD`, la cual es `metasploitable2`, esta máquina tiene la característica de tener muchas vulnerabilidades por defecto, las cuales pueden ser explotadas de manera legal. Abordarlas todas en un solo laboratorio es difícil, así que, en este laboratorio abordaremos una de esas vulnerabilidades: `vsftpd 2.3.4`.
## Objetivos

- Conocer y aprender sobre `nmap`.
- Conocer y aprender sobre `metasploit`.
- Aprender sobre qué es un `supply chain attack` o `ataque a la cadena de suministro`.
- Buscar exploits sobre vulnerabilidades conocidas en la red.
## Actividades

- Realizar un escaneo de la máquina `VbD` y encontrar en qué puerto se está corriendo el servicio vulnerable.
- Usar `metasploit` para explotar la vulnerabilidad ya mencionada.
- Realizar una búsqueda en internet de exploits desarrollados para explotar esta vulnerabilidad.
- Programar mi propio exploit en el lenguaje de preferencia para explotar la vulnerabilidad.
## Informe

Para este laboratorio se debe entregar informe técnico y de gerencia, incluyendo el código realizado en la actividad.

## Recursos extra
-  [Warning: Malicious version of FTP Software FileZilla stealing users' Credentials](https://thehackernews.com/2014/01/warning-malicious-version-of-ftp.html)
- [Especial Tecnogeek: El backdoor de xz/libzma y cómo fue descubierto](https://www.tecnogeek.com/2024/04/02/el-backdoor-de-xz-libzma-y-como-fue-descubierto/)

