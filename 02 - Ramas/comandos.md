# Comando para listar las ramas de mi repositorio

git branch
git branch -v

# Comando para crear una rama

git branch nombre_rama // El nombre de la rama debe ir junto, sin caracteres especiales, ni tildes ni ñ

# Comando para cambiar ramas

git checkout nombre_rama
git switch nombre_rama
git checkout -b nombre_rama // Crear rama y moverse a la misma rama que creó --> Crea la rama y hace el cambio

# Comando para eliminar una rama

git branch -D nombre_rama

# Comando para cabiar el nombre de una rama

git branch -M nuevo_nombre // primero debo irme a la rama que le voy a cambiar el nombre antes de ejecutar este comando

# Comando para eliminar un archivo de git

git rm --cached  nombre_archivo

# Comando para crear nuestros propios comandos

## Siempre lleva la palabra reservada alias punto el nombre del comando o abreviación
git config --global alias.lg 'log --oneline'

