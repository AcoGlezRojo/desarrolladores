## Comandos básicos linux
* muestra el historial de comandos utilizados

`$ history`
	
* Ejecuta un comando mostrado por el historia

`$ !<id_history>`
	
* Crear un fichero

`$ touch <fichero>`

## Comandos básicos vim

* editar un fichero

`$ vim <fichero>`

pulsamos enter, escribimos lo que queremos y pulsamos esc.

* guardar: `:w`

* salir: `:q`
	
## Comandos básicos git

* Inicializar un proyecto

`$ git init`
	
* Ver los cambios

`$ git status`

* Añadir ficheros para commitear

`$ git add <fichero>`

> puedes agregar todos los ficheros con . o * 

* Añadir un commit

`$ git commit -m "<texto>"`

* Ver el log (historial) de commits

`$ git log`

* Configurar cuenta github (login)

`$ git config --global user.name "John Doe"`
`$ git config --global user.email johndoe@example.com`

* Eliminar un fichero del commit

`$ git rm --cached <fichero>`

> también puedes usar -f para eliminar el fichero

* Ir a un commit anterior

`$ git checkout id_commit`

> este id puedes obtenerlo con desde el log

* Restaurar fichero al estado del commit

`$ git checkout -- <fichero>`



...