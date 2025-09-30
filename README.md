# SurVoley-app
Aplicación móvil a crear para el club deportivo SurVoley 

clonar:
git clone https://github.com/Ulisess3/SurVoley-app.git
cd SurVolley

instalar dependencias frontend:
cd frontend
npm install

iniciar:
npx expo start

instalar dependencias backend:
cd ../backend
npm install

iniciar:
npm run build
npm start
npm run start

modo dev:
npm run start:dev


Comandos Git:
<git init>    --> Inicializa un nuevo repositorio Git en la carpeta actual.
<git add .>   --> Prepara todos los archivos modificados para commit.
----------------------------------------------------------------------------------------------------------------
<git clone <URL>> --> Clona un repositorio remoto a tu máquina local.
<git pull>    --> Trae cambios del repositorio remoto y los fusiona con tu rama local.
<git commit -m "mensaje"> --> Crea un commit con los cambios staged y un mensaje descriptivo.
<git push>    --> Envía tus commits locales al repositorio remoto.
----------------------------------------------------------------------------------------------------------------
<git status>  --> Muestra el estado actual del repo: cambios modificados, añadidos o sin trackear.
<git add <archivo>>   --> Prepara un archivo para commit.
<git log> --> Muestra el historial de commits del repo.
<git diff>    --> Muestra las diferencias entre archivos modificados y la última versión commit.
<git branch>  --> Lista todas las ramas locales.
<git branch <nombre>> --> Crea una nueva rama.
<git checkout <rama>> --> Cambia a la rama indicada.
<git merge <rama>>    --> Fusiona la rama indicada en la rama actual.
<git rm --cached <archivo>>   --> Quita un archivo del control de versiones sin borrarlo localmente.
<git reset --hard>    --> Reinicia la rama actual, descartando todos los cambios no commitados.
<git clean -fd>	--> Elimina archivos y directorios no rastreados (sin backup).
<git remote -v>	--> Muestra los repositorios remotos configurados.
<git fetch>	--> Trae cambios del remoto sin fusionarlos automáticamente.
<git stash>	--> Guarda temporalmente cambios locales para limpiar el working tree.
<git stash pop>	--> Recupera los cambios guardados con stash y los aplica de nuevo.