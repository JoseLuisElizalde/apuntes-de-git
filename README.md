### Curso Git 

Sistema de control de versiones para el mantenimiento eficiente y confiable de archivos.

###Zonas de Git
Zona 1: Directorio de trabajo
Zona 2: Área de preparación
Zona 3: Directorio Git
	
###Configurando GFit por primera vez

git config --global user.name "JoseLuis" /*Configura nombre de usuario*/
git config --global user.email joseluis@example.com /*Configura email*/
git config --global core.editor subl /**Configura editor de texto/
git config --list /**/
 
###Curso Git desde cero 


git init -- inicializar repositorio git


crear archivo readme.md /*Archivo tipo "index" que lee Git*/

git status - Estado del repositorio

git add archivo - para pasar al punto de preparación

git commit -m "mensaje"

git log - ver confirmaciones o commits hechos

git diff /* Muestra las diferencias entre lo que esta en el directorio de trabajo vs lo ya confirmado*/

git diff --staged /*Diferencia entre lo que modificamos y lo que esta en preparación*/

git commit -m "mensaje"

git add .    /*Agregar todos los archivos*/

git reset HEAD readme.md  /*regresar a el directorio de trabajo*/

git add -A  /*Agregar todos los archivos en el espacio de trabajo y que se esten siguiendo*/

git commit --amend  /*Cambiar mensaje en commit*/

git log --oneline /*Muestra los commits en una línea*/

git commit -a -m  /*Se salta el área de preparación*/

git mv archivo archivo_renombrado   /*Renombrar archivos*/

