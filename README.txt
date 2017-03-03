Simple PlaceHolder

Ajout des fichiers suivant :
css/style.css
js/analytics.js
index.php

Configuration du git/config

Pour changer l'utilisateur et de crée des alias :

#Création d'alias
[alias]
   st = status
   co = checkout
   ba = branch -v -a
   nlog = log --name-status
   glog = log --graph --abbrev-commit
   sglog = log --graph --abbrev-commit --pretty=oneline
   slog = log --pretty=oneline --abbrev-commit
   dlog = log -p
   relog = log --graph --abbrev-commit --pretty=oneline --no-merges
   ci = commit -v
   br = branch -v
   ru = remote update
   su = submodule update
   si = submodule init
#Mise en couleur des messages
[color]
    ui = auto
[color "branch"]
    current = yellow reverse
    local = yellow
    remote = green
[color "diff"]
    meta = yellow bold
    frag = magenta bold
    old = red bold
    new = green bold
[color "status"]
    added = yellow
    changed = green
    untracked = cyan
[merge]
   summary = true