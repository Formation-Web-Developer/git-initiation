# Cours d'initiation de Git

**Installation de git**: https://git-scm.com/

Commande pour bien commencer:

```git
git config --global user.email 'your-email@your-domain.ext
git config --global user.name 'your-name'
```

## Initialiser un dépot git:

D'abord se situer dans le dossier de l'application/site

```git
git init
```

## Voir l'actualité de son espace de travail

```git
git status
```

## Ajouter un fichier à le staging area.

```git
git add your-file.ext
```

## Ajouter tous les fichiers (nouveau ou modifié) en une seule fois.

```git
git add --all

or
git add *

or
git add .
```

## Valider l'ajout d'un fichier à son dépot

```git
git commit -m 'your message'
```

# Ignorer des fichiers/dossiers

Créer un fichier `.gitignore` et à l'intérieur placer le nom des fichiers et dossiers à ne pas prendre en compte par git.

# Voir l'historique des commits

```git
git log

ou
git reflog
```

# Voir les modifications d'un/des fichier(s)

```git
git diff
```

# Les branches

voir les branches

```git
git branch
```

créer une nouvelle branche

```git
git branch <branch-name>
```

Se diriger sur une branche

```git
git checkout <branch-name>
```

Fusionner une branche

```git
git merge <branch-name>
```

Supprimer une branche

```git
git branch -d dev
```