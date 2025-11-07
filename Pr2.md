# Practica 2 - GIT

1. Cread un repositorio (directorio) llamado practica2git e inicializa el sistema de control de versiones
2. Cread un fichero llamado contenido.txt con el siguiente texto:
```
- Introducción a linea de comandos
    - Windows
    - Linux
```
![creamos ficheros](img/1.png)


3. Comprobad el estado del repositorio 

![creamos ficheros](img/2.png)


4. Añadid el fichero a la zona de preparado

Usamos "git add archivo1.txt"


5. Comprobad de nuevo el estado del repositorio

Usamos "git status"

![creamos ficheros](img/3.png)
6. Haced el primer commit con su comentario correspondiente
7. Añadid la línea al fichero:
```
- Mac
``` 

8. Compruebad de nuevo el estado del repositorio
9. Añadid el fichero a preparado
10. Haced otro commit del fichero
11. Cambiad el mensaje del último commit por “Añadido la línea de MAC.”
```
Para cambiar el mensaje del commit se usa:

$git commit --amend -m "Mensaje"
```
