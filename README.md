#Practicando Git

## Configuracion inicial

```sh
git config --global user.name "Jose Ascona"
git config --global user.email "joseluisascona@gmail.com"
```

## Verificar si quedo todo bien
```sh
git config --get-regexp user
```

## Crear un repositorio (Inicializar un repo)
```sh
git init
```

## Areas del repositorio

3 areas

* Working Directory (WD): Directorio donde se van agregando o quitando los archivos durante el desarrollo.
* Stagging Area (SA): Aread de control de cambios. Area temporal intermedia.
* Local Repo (LR): Una caja donde van todas las fotos que fui sacando. 


## El estado de los archivos
* untracked: archivos que estan en el WD pero git no les esta dando seguimiento
* unmodified: Archivos que git ya esta siguiendo y con respecto al WD no fueron modificados.
* modified: Archivos que se encuentran en el repositorio (Estan siendo seguidos por GIT) pero difieren con lo que se encuentra acutalmente en el WD.
* stagged: Archivos que estan en el area temporal/intermedia

## Saber estado actual de los archivos
```sh
git status
```

## 
```sh
git log
git log --oneline
git diff

```

##
```sh
```

##
```sh
```

# gitignore

