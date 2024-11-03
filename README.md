# Tarea 1: introducción a Git
## Objetivos de la Tarea:
Aprender los conseptos basicos de Github y realizar nuestro repositorio
## Programa.
El programa que se realizo es de tipo java en el que con una funsion main se imprime el mensaje "Hola Mundo".

## instrucciones para poder ejecutar el programa "HolaMundo.java".
1. **Archivo.**
   En tu editor de texto de preferencia y realiza el codigo "HolaMundo.java".
2. **Guardar.**
   Una vez realizado el codigo guardar con su respectiva extencion de archivo. (En este caso es .java)
3. **Compilado.**
   Para compliara el archivo que se creo, primero nos aseguramos de estar en la carpeta de nuestro archivo, luego utilizar este comando "javac HolaMundo.java".
 4.**Ejecutar.**
   Luego de la compilacion se utiliza el comando java HolaMundo.java, esto ejecutara el programa dandonos el resultado.
 5.**Salida.**
    El resultado aparecera en la terminal dando como resultado "Hola Git."

 ## Comandos utilizados.
  ### Usados para inicializar Git bash.
   + git config --global user.name "Nombre Usuario"
   + git config --global user.email "userEmail@correo.com"
  ### Entrar en la carpeta y ver los archivos que contiene
   + cd "C:\user\nombre\ruta-de-la-carpeta\carpeta"
   + ls -al
  ### Inicializar el repositorio local.
   + git init
   + git remote add origin url-en-gitHub-del-repositorio-remoto
   + git remote -v
   + touch .gitignore
  ### Enviar cambios al repositorio remoto.
   + git add -A
   + git status
   + git commit -m "mensaje del commit"
   + git push -u origin master
   + git status
   + git push

  ## Archivo .gitignore.
  Este archivo nos sirve para dar la instruccion a Git sobre los archivos que debe de ignorar, en este proyecto solo se ignoro "debug.log".
  
  ## Descripcion del programa ejecutado.
  Al ejecutar nuestro programa "HolaMundo.java" se debe de imprimir el mensaje "Hola Git".

  ## Verificar que debug.log no se subio.
  1. Se debe verificar que en el archivo .gitignore este puesta la siguiente linea "*.log".
  2. al monento de enviar cambios al repositorio y despues de ejecutar el comando git add -A, ejecuta el comango git status,
     con este comando se pueden visualizar los archivos que se mandaron a preparar, y no debe aparecer el archivo "debug.log".
  3. Por ultimo revisa en tu repositorio que no se encuentre le archivo .log. 



