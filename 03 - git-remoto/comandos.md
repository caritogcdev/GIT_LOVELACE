# Comando para conectar mi git local con git en la nube

git remote add nombre_conexion url_conexion //Por convensión al nombre_conexion se le llama origin

# Comando para clonar o traer un repositorio de git remoto

git clone url_conexion

# Comando para listar las conexiones remotas

git remote -v

# Comando para eliminar una conexión remota

git remote remove nombre_conexion

# Comando para enviar información al git remoto

git push // solamente hace push en la rama que estoy
git push nombre_conexion nombre_rama // Especificar nombre rama
git push -u nombre_conexion nombre_rama // Si no existe que lo cree
git push --all // sube todas las ramas

# Comando para obtener cambios o la información que hay en el git remoto

git pull
git pull nombre_conexion nombre_rama

# Titulo 2