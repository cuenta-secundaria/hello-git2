Conceptos Básicos de Git

Repositorio: Es el lugar donde se almacena tu proyecto, puede ser local (en tu computadora) o remoto (en un servidor).

Commit: Es una instantánea de tu proyecto en un momento dado. Cada commit tiene un mensaje que describe los cambios realizados.

Branch (Rama): Es una línea de desarrollo independiente. La rama principal se llama "master" o "main".

Merge: Es el proceso de unir los cambios de una rama en otra.

Clone: Es la acción de copiar un repositorio remoto a tu computadora.

Pull: Es la acción de traer los cambios de un repositorio remoto a tu repositorio local.

Push: Es la acción de enviar los cambios de tu repositorio local a un repositorio remoto.

Comandos Básicos de Git


Configurar Git:

git config --global user.name "Tu Nombre"
git config --global user.email "tuemail@example.com"





Inicializar un Repositorio:

git init




Clonar un Repositorio:

git clone url_del_repositorio





Añadir Archivos al Índice:

git add nombre_del_archivo





Hacer un Commit:

git commit -m "Mensaje descriptivo"





Ver el Estado de los Archivos:

git status





Ver el Historial de Commits:

git log





Crear una Nueva Rama:

git branch nombre_de_la_rama





Cambiar a Otra Rama:

git checkout nombre_de_la_rama







Unir una Rama:

git merge nombre_de_la_rama






Enviar Cambios al Repositorio Remoto:

git push origin nombre_de_la_rama







Traer Cambios del Repositorio Remoto:

git pull origin nombre_de_la_rama





Poner palabras fáciles a comandos largos:

git config --global alias.nombrenuevocomando "Insetra aquí el comando al que quieras ponerle el nombre nombrenuevocomando"



Ignorar un archivo:
touch .gitignore (para crear el archivo giotignore)
Luego, dentro de gitignore se escribe: **/.DS_Store (que en este caso es el fichero que se quiere ignorar)



Ver qué ha cambiado desde la última fotografía:
git diff

