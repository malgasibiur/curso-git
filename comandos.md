# Listado de comandos

## Crear un repositorio
    git init
> este comando crear un repositorio en el directorio donde estamos situados

## Saber estado de cambios
    git status
>Este comando te informa que archivos estan sin seguimiento,
>qué archivos estan con segimiento (en el staging area), 
>y si ya todo estan con puntos de restauracion
>En rojo: sin seguimiento
>En verde: en el Staging area

## crear punto de restauracion
    git commit -m 'mensaje'

## agregar a stagin area y crear punto de restauracion en un solo comando
    git commit -a -m 'mensaje'

> otro modo de hacer un add y u commiit juntos es:
    git commit -am 'mesnaje'

## ver listado completo de commit con su autor <email>, descripcion, timestamp
    git log

>se puede ver un log corto, de una sola linea con
git log --oneline

## moverse hacia cualquier commit
    git checkout nHASH

## Otro modo de volver al ultimo commit
    git checkout master

