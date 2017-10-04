### git log
Muestra todo el historial de commits del proyecto.

'git log --pretty=format:"%h - %ui, %ar : %s"'
Muestra el historial con el formato que indicamos.

### Limitar la salida del historial

'git log -n': Cambiamos la n por cualquier número entero, poro ejemplo: 'git log -2' nos mostratá los 2 commits más recientes.

'git log --after="2016-04-07 00:00:00"': Muestra los commits realizados después de la fecha especificada.

'git log --before="2016-04-07 00:00:00"': Muestra los commits realizados antes de la fecha especificada.

Las banderas del comando 'got log' se pueden usar juntas según convenga, por ejemplo: 'git log --oneline --graph --after="2017-09-13" --before="2017-09-15"
'

'git log --oneline'

 Este comando nos muestra el historial en una sola línea por commit.