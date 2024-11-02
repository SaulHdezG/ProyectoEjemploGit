# Tarea 1: Introducción a Git

## Descripción
El programa es un código básico en lenguaje **Java** que imprime el mensaje *Hola Git*.

### Objetivo
El objetivo del proyecto es conocer el funcionamiento de los sistemas de control de versiones, crear repositorios locales y remotos, 
utilizar Git como un Sistema de Control de Versiones Distribuido y GitHub como proveedor de alojamiento de repositorios, 
así como familiarizarse con los comandos para la creación y manejo de archivos.

## Instrucciones de uso
1. Verificar que en el ordendar está instalado Java para que el programa compile sin errores.
2. Copiar el código de HolaMundo.java en el compilador de nuestra preferencia.
3. Guardar el archivo con el nombre HolaMundo.java; en caso de utilizar un compilador online este paso no hace falta.
4. Compilar y esperar la impresión en pantalla de *"Hola Git"*.

## Comando utilizados
Los comandos que se utilizaron fueron los siguientes:
```
git config --global user.name 
git config --global user.email
git init
git remote add
touch
git add
git commit -m
git push
git status
cd
ls -al
git remote -v
git branch
```
## Notas sobre el archivo **.gitignore** 
El archivo .gitignore nos ayuda a seleccionar los archivos que no queremos subir al control de versiones remoto; en este caso, se ignora el archivo debug.log. 
Para corroborar que el archivo fue efectivamente ignorado, usamos el comando git status. 
Aquí aparecerán los archivos que están en el área de preparación (staged) y los no rastreados (untracked). 
Si el archivo se ignoró correctamente, no debe aparecer en ninguno de esos estados, como si Git Bash no lo reconociera.

Si aún se quiere verificar que no se subió por error, se puede comprobar si el archivo está en el control de versiones remoto, en este caso, GitHub.
