# ** Práctica 1 introducción a git y github**

## Descripción de la práctica:

El objetivo de esta práctica es repasar comandos básicos de git y crear un repositorio remoto en github.

El archivo HolaMundo.py es un ejemplo de archivo que se utilizó para hacer modificaciones y poder ver los cambios en el historial de commits

## Ejecutar el archivo HolaMundo.py

Es necesario contar con un compilador de python o un IDE para poder ejecutar el archivo. 

para ejecutar el archivo en terminal: .

```bash 
python3 HolaMundo.py 
```

## Listado de comandos utilizados

>En la siguiente tabla se muestran los comandos utilizados durante la práctica

|   Comandos	|  Función	|
|---	|---	|
| **git init** | inicializa un repositorio local |
| **git config --global user.name** | configura el nombre dentro de git |
| **git config --global user.email** | configura el correo dentro de git |
| **git add** | prepara nuevos cambios dentro de archivos especificado |
| **git commit -m** | guarda los cambios dentro del historial de versiones|
| **git commit -m** | guarda los cambios dentro del historial de versiones|
| **git remote add** | configura la ruta del repositorio remoto|
| **git push -u origin master** | sube el repositorio local al repositorio remoto|

##Notas sobre el archivo .gitignore

El archivo especificado tiene la utilidad de ignorar ciertos archivos específicos con la finalidad de no ser guardados dentro del repositorio remoto.
En el repositorio local el archivo debug.log que fue ignorado por git debido a la configuración guardada en el archivo ignore.git 

para verificar que el archivo debug.log fue ignorado correctamente es necesario usar git status después de haber agregado el archivo .gitignore al repositorio local, el resultado debería sugerir que el archivo debug.log no está siendo rastreado, una vez se suba el repositorio local al remoto el archivo debug.log no debe aparecer.. 
