Configuracion cuenta Github:
git config --global user.name "aca nombre de cuenta github"
git config --global user.email "aca el correo de la cuenta github"
git config --list    // para ver los datos


Crear repositorios:
git clone [url]   //clonar un repositorio ya existente desde la cuenta de github
git init         //crear un nuevo repositorio en el pc y luego vincularlo

Verificar:
git status
git log
git log --oneline
git diff
git branch

Agregar
git add .
git add [archivo]

Luego de Agregar, hacer el Commit:
git commit -m "[mensaje]"

Luego para enviar:
git push

Para traer los datos:
git pull

Para cambiar:
git checkout -b "[branch name]"   //crea rama y cambia automaticamente
git merge "[nombre de la branch]"    //desde la rama actual, hace el merge con el nombre que se le ponga
