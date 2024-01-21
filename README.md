# Clase 01 - Git desarrollo colaborativo

## Markdown md
### Titulos
# h1
### h3
#### h4
##### h5
### separador
---
### Listas ordenadas
* Item 1
* Item 2
* Item 3
* Item 4
### Negrita
esto es un texto en **negrita**
### Cursiva
esto es *curciva*
### Link
### imagen
![Alt text](image-1.png)

### Marckdown
lenguaje de marcas nos permite crear documentaciones ,anotaciones de proyecto

### git
![git](_ref/git.png)
![Alt text](image-2.png)
###Configuracion de Git
>Agregar Usuario
comando de consola shell==> sh
```sh
git  config --global user.name  "Santiago Cofman" # Global (Para todos los repos que se creen en este usuario de windows )
gir config --local user.name "Santiago Cofman" # Local  (Para este unico repo,luego de haber creado un repo en github(git init) )
```
>Agregar correo
```sh
git  config --global user.email  "scofman@andreani.com"
```
```sh
git config --global --get-regexp user

```
###  Quitar una propiedad dentro de la configuracion

```sh
git  config --global --unset user.email
```
#### Abrir el editor para hacer configuraciones manuales
```sh
git  config --global
```
### Iniciamos un repositorio de git
```sh
git  init #va a crear en la carpeta del proyecto una carpeta .git ,en el directorio (carpeta)
```
**Nota**:NO HAY QUE BORRAR LA CARPETA .GIT ,ni hay que odificar los archivos  dentro de ella.solo trabajar git sobre ese directorio.no nosotros
### Limpiar consola
```sh
clear
cls
#ctrl + l
```
### GIT STATUS
verifica el estados de los archivos y en que area(o en que parte de la estructura virtual  estan los archivos)
* Untracked : que los archivos estan en el working directory(wd) y no estan siendo seguidos(controlados) por GIT
* STAGED o Index :Archivos que estan preparados para crear un commit (sacar una foto) el snashots  y preserva los cambios hechos en mi codigo fuente(PRE FOTO).
