# COMANDOS
para activar el ambiente virtaul

cd (nombre de la carpeta) ejemplo cd Documents

mkdir djangogirls (es para crear una carpeta)

cd djangirls 

python -m venv myvenv (para crear el ambiente virtaul)

dir (es para ver las carepts que hay en mi ordenador)

python manage.py runserver (para correr el servidor)

direccion IP del servidor (http://127.0.0.1:8000/)

 ctrl c para apagar el servidor 


 para ver los avances de admin
 http://127.0.0.1:8000/admin/

 git status es para saber si los archivos estan trakeados o no
 git add . es para añadir todos los archivos que no estan traqueados para que sean traqueados

 quede en desplegar enviar tu codigo a git hub

 GIT

 Por ejemplo, para clonar un repositorio en la línea de comandos introducirías el siguiente comando. Entonces se te pediría que introdujeras tu nombre de usuario y contraseña. Cuando te pidan tu contraseña, introduce tu token de acceso personal en lugar de una contraseña.

git clone https://github.com/USERNAME/REPO.git
Username: RebecaBG772
Password: YOUR-PERSONAL-ACCESS-TOKEN

git status (Muestra el estado del proyecto: qué archivos fueron modificados, agregados o pendientes de guardar en Git. Se usa MUCHAS veces)
git add . (Agrega todos los archivos modificados al área de preparación (“staging”) para incluirlos en el próximo commit. Se usa cada vez que quieras guardar nuevos cambios.)
git commit -m "Primer commit" (Guarda oficialmente una versión de tus cambios con un mensaje descriptivo.Se usa cada vez que completes cambios importantes o quieras guardar progreso.)
git remote add origin https://github.com/TU-USUARIO/TU-REPOSITORIO.git (Conecta tu proyecto local con el repositorio de GitHub. Normalmente se usa UNA SOLA VEZ por proyecto.
Si lo vuelves a ejecutar puede aparecer:
remote origin already exists.)
git push -u origin main (Envía tu proyecto y commits desde tu computador hacia GitHub.
🔁 Se usa muchas veces, cada vez que quieras subir cambios nuevos a GitHub.

⚠️ En tu caso probablemente debes usar:

git push -u origin master

porque en tu captura la rama se llama master, no main.)

usar siempre despues de barir la craptea de django girls
myvenv\Scripts\activate