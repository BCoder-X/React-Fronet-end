crear projecto react
npm create vite@latest
escoger react javascript + swc
repositorio git hub
iniciar repositorio local:
git init
cambiar el nombre de master a main:
git branch -M main
eliminar credenciales de otros usuarios:
abrir administrador de credenciales abrir credenciales de windows
configurar usuario local:
git config --global user.name "nombre"
git config --global user.email "mail"
agregar archivos del proyecto:
git add .
agregar commit:
git commit "primer commit"
enlazar repositorio:
git remote add origin https://github.com/nombre de usuario/nombre de repositorio.git
# subir :
git push -u origin main
# comprobar estado de proyecto:
git status
(si es archivo aparese rojo es nuevo o modificado!)
# Comandos para actualizar el repositorio con la versión local: git status
git add.
git commit -m "nombre de la versión o descripción del commit"
git push

crear Ramas:
# Opción 1: Con git checkout
git checkout -b nombre-de-la-rama
# Esto crea y cambia automáticamente a la nueva rama

# Opción 2: Con git switch (forma más moderna)
git switch -c nombre-de-la-rama
# Hace exactamente lo mismo que la opción anterior

git push origin nombre-de-la-rama
# "origin" es el nombre por defecto del repositorio remoto
# "nombre-de-la-rama" debe coincidir con la rama que creaste


