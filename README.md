
# Introduccion de Git

## Descripcion
El programa imprime el mensaje  "Hola mundo" en la consola. El objetivo de la tarea es introducirnos a Git y Github, trabajando con repositorios locales y remotos con ayuda de Git y github.

# Como ejecutar programa
Para ejectutar el programa se puede usar un editor de texto como Visual Studio Code o desde la consola se debe de ejucar el comando: 

java HolaMundo


# Comandos utilizados
- git config --global user.name "Nombre usuario"
- git config --global user.email "miEmail@mail.com"
- git remote add ALIAS URL-GIT_REPOSITORIO-REMOTO
- touch .gitignore
- git init
- git add -A
- git commit -m "Mensaje del commit"
- git status
- git push

# Notas sobre el archivo .gitignore
El archivo .gitignore se creo para especificar que archivos se deben de ignorar a la hora de subir el repositorio local al repositorio remoto. En este caso ignoramos los archivos .log, en este repositorio ignoro el archivo "debug.log". 

Al ejecutar el programa debemos de recibir por consola "Hola git".
 
Para verficar que no se configuro correctamente el archivo .gitignore solo basta con observar el repositorio remoto y notar que el archivo "debug.log" no se encuentra.

