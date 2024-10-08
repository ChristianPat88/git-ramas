# GIT RAMAS (Branches)

## Crear un repositorio

```sh
git init
```

## Ver el status de los archivos

```sh
git status
```

## Git Alias

```sh
git config --global alias.st "status --short"
git config --global alias.a "add"
git config --global alias.c "commit -m"
git config --global alias.l "log --oneline"
```

## Ver las diferencias entre el WD y el LR

```sh
git diff
```

## Ver el contenido de cada commit

```sh
git show <numero-hash>
```

## Crear una rama

```sh
git branch <nombre-rama> # Crea una rama y nos deja en la rama original
git branch feature/ramas # ejemplo
git switch -c <nombre-rama> # Crea una rama y nos mueve a la rama que se creo
```

## Me muevo entre ramas

```sh
git switch <nombre-rama>
git switch feature/ramas # ejemplo