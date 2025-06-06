## Uso de Git

🔧 Configuración inicial

git config --global user.name "Tu Nombre"
git config --global user.email "tuemail@ejemplo.com"
Configura tu nombre y correo (solo se hace una vez por máquina).

📦 Iniciar y clonar repositorios

git init
Crea un nuevo repositorio Git local.

git clone https://github.com/usuario/repositorio.git
Clona un repositorio remoto a tu computadora.

📂 Trabajando con archivos

git status
Muestra el estado de los archivos (cambios hechos, sin agregar, etc.).

git add archivo.txt
git add .
Agrega archivos al staging area (prepara para hacer commit).
git add . agrega todos los cambios.

git commit -m "Mensaje del commit"
Guarda los cambios en el repositorio con un mensaje.

🔄 Actualizar cambios
git pull
Descarga y fusiona los cambios del repositorio remoto.

git push
Envía tus cambios confirmados al repositorio remoto.

🕐 Historial y versiones
git log
Muestra el historial de commits.

git diff
Muestra las diferencias entre archivos modificados y el último commit.

git checkout archivo.txt
Revierte los cambios en un archivo (vuelve a la última versión confirmada).

🌱 Ramas (branches)
git branch
Muestra las ramas existentes.

git branch nombre-rama
Crea una nueva rama.

git checkout nombre-rama
Cambia a otra rama.

git merge nombre-rama
Fusiona nombre-rama con la rama actual.

🗑️ Deshacer cambios
git reset archivo.txt
Quita un archivo del staging area (sin borrar cambios).

git reset --hard HEAD
Elimina todos los cambios no confirmados (¡cuidado con esto!).