# Curso python Django

# Sesion 2
# GIT
### Instalar Django
### Configurar un protyecto, modelos, y un admin
* Generar nuestra key
Clonar repositorio

git clone <ruta del repositorio>

configurar  git

git config --global user.name "Luis Saldivar"
git config --global user.mail lesch80@hotmail.com

* crear el archvhio .gitignore
touch .gitignore
* ver estado de cambios
git status
*ver archvos dentro de carpetas
git status -u

*para agregar a git
git add .  #agrega todod desde la raiz
*guardas cambios
git commit -m  "first commit"

* ver istado de cambios de nuestro commit
git log --oneline
git status
git add .
git commit -m “mensaje”
git push origin master
 *extarer codigo
 git pull
 git pull origin master
 *ver mis rutas remotas
 git remote show
 git remote show origin
 *ver ramas del pryecto
 git branch
* agregar ramas
git branch sesiones

*retroceder
git checkout -- archivo moificado

* para deshace camvios depsues de hacer git add
git reset HEAD 

