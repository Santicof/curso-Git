
# Clase 4

# GIT STASH
ES una pila de almacenamiento que nos otorga git ,permite registrar cambios en el working directory temporalmente que aun n va a poder hacer un commit ,con stash puedo cambiar de rama y no hace falta hacer commit de nada

# Crear un stash
git stash 
git stash -m "Mensaje del stash"

# Ver contenido del stash
git  show <nombre-stash>
git show stash{0}

## Aplicar stash a una nueva rama
git stash branch nombrerama

## 
git stash clear




# Recuperar ultimo stash 
git stash pop

# Recuperar un stash

git stash apply
git stash apply 5

## Para borrar el stash en especifico

