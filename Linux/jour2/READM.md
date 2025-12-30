# Linux — Jour 2 : Permissions (bases)

## Objectif
Comprendre les permissions Linux et savoir lire/interpréter un `ls -l`.

## Notions clés
- Différence **fichier** vs **dossier** pour le droit `x`
- Lecture des permissions : `r` (read), `w` (write), `x` (execute)
- Structure : `u` (user/propriétaire) / `g` (group) / `o` (others)
- Commandes : `ls -l`, `chmod` (symbolique et numérique)

## Rappel : x selon fichier / dossier
- Sur un **fichier** : `x` = exécuter le fichier
- Sur un **dossier** : `x` = traverser / entrer (`cd`) et accéder aux éléments

## Commandes vues
```bash
ls -l
chmod 740 fichier
chmod u+rwx,g+r,o= fichier
