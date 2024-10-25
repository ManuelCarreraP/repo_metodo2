# Método 2: Clonado y añadir repositorio

# Clonar el repositorio original
git clone -o repo_pruebas https://github.com/danielcastelao/pruebasReadme.git repo_metodo2

# Configurar el nuevo repositorio como remoto
cd repo_metodo2
git remote add origin https://github.com/ManuelCarreraP/repo_metodo2.git

# Comprobar que se realizo correctamente
git remote -v

# Modificar el readme y hacer un commit & push
