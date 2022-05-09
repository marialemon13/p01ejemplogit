# GIT Básico

## Istalación

Instalación desde el asistente de Git

## Comandos para credenciales en nuestro equipo

```
git config --global user.name "nombreusuario"
git config --global user.emai. "correousuario"
```

## Crear un repositorio Git

```
git init
```

## Comprobar el estado de Git

Ver la situación en la que están los cambios desde el último commit

```
git status
```

## Añadir archivos al staging area

Añade todos los cambios pendientes

```
git add -A
```

## Crear un commit 

Para guardar un conjunto de cambios y crear un punto de control usamos los "commit"

```
git commit -m "mensaje del commit"
```

## Deshacer cambios a partir de los commit

2 opciones

```
git reset --soft <código-comit>
```

Con --soft podemos volver a un commit anterior sin deshacer cambios.