### Taller 1
**Universidad ICESI**  
**Curso:** Sistemas Operativos  
**Docente:** Daniel Barragán C.  
**Tema:** Comandos de Linux, Estructura de directorio, Virtualización  
**Correo:** daniel.barragan at correo.icesi.edu.co


### Objetivos
* Conocer y emplear comandos de Linux para la realización de tareas administrativas

### Prerrequisitos
* Virtualbox o WMWare
* Máquina virtual con sistema operativo CentOS7

### Descripción
El primer taller del curso sistemas operativos trata sobre el sistema operativo Linux, la estructura de sus directorios y virtualización 

### Actividades

1. Explique la función de los directorios en la raíz de sistema operativo Linux-CentOS.
Proporcione ejemplos de los archivos que se encuentran en cada directorio (explique al menos un
archivo por directorio).

| Directorio   | Archivo ejemplo | Descripción del contenido del directorio  |
|------|------|------|
| a directory | an example file | an awesome description |
|  bin        | cat              |Concatena archivos y/o los muestra como salida para verlos|
|  boot| chain.b  | Ejecuta sistemas Operativos diferentes a Linux |
| dev |  dsp  |  dsa* | Almacena particiones del sistema| 
| etc |  X11 | Contiene la configuracion para Windows System |
|  home| user1 | informacion y configuracion del User1 |
| lib  | kbd | contiene varios keymaps para uso |
| media| cdroom | accede al subsistema instalado previamente (unidad de cd) |
|opt|<package>|lleva a los paquetes estaticos|
|proc|devices| lista de dispositivos configurados|
|root|home|archivos almacenados en el hom del super usuario(root)|
|sbin|init|resume los archivos del init binarios que pueden ser esenciales para el sistema|
|usr|X11R6|contiene librerias, ejecutables, documentos de X Windows Sistem|
| var   | backups | contienen backups de varios sistemas para su recuperacion |
| srv   | www | almacena archivos y directorios de servidores en el sistema como: www   |
| tmp   | Chrome | almacena los archivos temporales  de corta duracion   |


2. En una tabla como se muestra a continuación escriba 10 comandos de Linux no visto en clase. Puede incluir comandos que funcionan una vez han sido instalados con yum

| Comando   | Usuario | Descripción   |
|------|------|------|
| more | root |Muestra un archivo pantalla por pantalla. |
| tac | root |Concatena e imprime archivos invertidos. |
| od | root |Convierte archivos a forma octal u otras. |
| tr | root |Traduce o borra caracteres. |
| uniq | root |Remueve líneas repetidas. |
| wc | root |Cuenta bytes, palabras y líneas. |
| cut | root |Corta secciones de una linea. |
| dev | root |Remueve líneas repetidas. |
| uniq | root |Supone que es un dispositivo de caracteres o bloques. |
| exec | root |Se permite ejecución.. |


3. ¿Cuál es la utilidad del comando printenv en Linux?, Investigue acerca de la creación de variables de ambiente en Linux y como hacerlas permanentes. Cree una variable de ambiente, hágala permanente y muestre evidencias del funcionamiento.
printenv imprime todo o parte de un enterno determinado, su sintaxis es: printenv [ OPCIÓN ] ... [ VARIABLE ], la cual imprime los valores del entorno especificado VARIABLE. Ejemplo: Printenv INICIO: Muestra la ubicación del directorio inicial del usuario actual.

### Nota

El informe debe ser entregado en formato README.md y debe ser subido a un repositorio de github. El repositorio de github debe ser un fork de https://github.com/ICESI-Training/so-workshop1 y para la entrega deberá hacer un Pull Request (PR) respetando la estructura definida. El código fuente y la url de github deben incluirse en el informe.  

## Referencias

* https://github.com/ICESI/so-commands/tree/master/centos7
* https://cmdchallenge.com  
* https://www.gutenberg.org
