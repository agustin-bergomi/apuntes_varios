# apuntes_varios

Git

Git trabaja con un sistema de Staging.
Mediante ese sitema los archivos pasan a distintos escalones/etapas.

Etapas:<br>
Archivo en directorio local<br>
Archivo staged<br>
Archivo en repositorio git<br>

Comandos

Comandos unix:

Entrar a directorio:<br>
cd "directorio"<br>
Crear directorio<br>
mkdir "directorio"<br>
Listar archivos en directorio:<br>
ls<br>
(variacion con detalle)<br>
ls -l<br>

Comandos git:<br>
Crear repo:<br>
git init nombre_repo<br>
Estatus del repo:<br>
git status<br>
Agregar un archivo a stage<br>
git add nombre_archivo<br>
(provoca que el archivo comienze a tener seguimiento)<br>
Agregar archivos a stage<br>
git add .<br>


Remover archivo del stage:<br>
git rm --cached <archivo>
Agregar archivos a repositorio<br>
git commit -m "comentario"<br>
"pararse" en un branch;<br>
git chekout "branch"<br>

Git es un sistema de control de versiones por lo cual obviamente ofrece branching para bifurcar del archivo master cuando se agregan funcionalidades.
