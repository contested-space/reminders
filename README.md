# Comment `git`ter

# Presomptions

Ce document presume que vous n'entrerez pas de mot de passe et que votre `git` est configuré pour fonctionner par SSH, avec `~/.ssh/config` et une identité rsa.

## Créer un repo

1. Aller sur le site de [github](https://github.com/) et créer un nouveau repo
2. Il est important d'initialiser le repo avec un _README.md_ et d'entrer une description
3. Aller dans la page du repo et cliquer sur `SSH` près de la boite pour que votre lien ce clone soit en format ssh.
4. Copiez le lien ssh.
5. Dans le terminal clonez le repo avec `git clone [votre lien copié]`
6. Votre repo est prête à travailler.

## Travailler dans un repo vierge

1. Copier le `.gitignore` d'un repo d'Alexis
2. Remplissez votre `README.md`
3. Ajoutez les fichiers nécessaires
4. Utilisez `git add -A` pour _tracker_ les fichiers que vous venez d'ajouter (vous devrez répéter cette opération pour chaque fichier ajouté au repo)
5. Commitez avec `git commit -am '[votre message de commit]'`
6. Poussez vers le repo avec `git push`

## Références importantes

[Guide de syntaxe markdown](https://confluence.atlassian.com/display/STASH/Markdown+syntax+guide) par Atlassian

[Guide de git](https://www.atlassian.com/git/tutorials/) par Atlassian
