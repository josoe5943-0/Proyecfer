# CURSO GIT

## CLASE 1
### Repositorio
Un repositorio es todo proyecto que tiene un seguimiento por Git.

## Comando git init

El comando `git init` inicializa un repositorio vacío de Git en el directorio actual.

### COMANDO: git commit
Comando para generar un registro de un cambio.
- `git commit <file>`
- `git commit -m <descripción>`
- `git commit <file> -m <descripción>`

### COMANDO: git log
Comando para ver el historial de cambios.
- Muestra los SHA en una sola línea: `git log --oneline`
- Muestra todas las ramas: `git log --graph`

## CLASE 2

### COMANDO: git branch
Devuelve todas las ramas existentes.

### COMANDO: git branch <nomRama>
Crea la rama a partir de la rama padre (en la que nos encontramos), los cambios que ocurren en una rama no afectan a otras hasta utilizar un merge.

### COMANDO: git checkout <nomRama>
Nos permite navegar entre las ramas.

