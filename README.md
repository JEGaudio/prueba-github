## Configuracion cuenta Github:
`git config --global user.name "` _aca nombre de cuenta github_ `"`

`git config --global user.email "` _aca el correo de la cuenta github_ `"`

`git config --list`    // para ver los datos


## Crear repositorios:
`git clone "` _url_ `"`  //clonar un repositorio ya existente desde la cuenta de github  *poner url entre comillas

`git init`         //crear un nuevo repositorio en el pc y luego vincularlo

## Verificar:
`git status`

`git log`

`git log --oneline`

`git diff`

`git branch`


## Agregar
`git add .`

`git add ` _archivo_

Luego de Agregar, hacer el Commit:

`git commit -m "` _mensaje_ `"`

Luego para enviar:
`git push`

## Para traer los datos:
`git pull`

## Para cambiar:
`git checkout -b "` _branch name_ `"` 

//crea rama y cambia automaticamente *hay que hacer un git add, git commit y git push origin "[nombre]"

`git merge "` _nombre de la branch_ `"`    //desde la rama actual, hace el merge con el nombre que se le ponga

`git switch`           //para cambiar de rama
`git restore --source ` _numero hash_ _archivo_

