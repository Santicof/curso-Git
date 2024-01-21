## CREO RAMA
git branch nombrerama
## Listar rama 
git branch
## COMPARAR ENTRE RAMAS
git diff rmanombre (compara rama actual con la indicada)
## Cambio entre ramas
git switch nombrerama
git switch -
## Borrar ramas
git branch -d nombrerama
## Empiezo en navbar
### Crear rama y moverse a esa rama
git switch -c dev

# GIT MERGE
TENGO QUE ESTAR EN LA RAMA EN LA QUE ME QUIERO TRAER OS CAMBIOS
git merge nombrerama
## Tipos de algoritmos cuando hago merge
* Fast-fordward -la funcion se hace automaticamente
* Recursiva -no hay conflictos entre la rama origin y destino ,fusion se hace utomaticamente ,crea un commit extra
* Conflicto (Manual. hay conflicto y el ususario tiene que solucionarlo)

## SUbir una rama al remoto
git push -u <remoto> <rama-que-quiero-subir>
git push -u origin dev
