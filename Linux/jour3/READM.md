# Linux — Jour 3 : Droits effectifs

## Objectif
Comprendre pourquoi un utilisateur peut ou non accéder à un fichier ou un dossier
en fonction des permissions effectives.

## Notions abordées
- Lecture de `ls -l`
- Droits effectifs utilisateur / groupe / autres
- Importance du droit `x` sur les dossiers
- Différence entre lire, entrer et modifier

## Points clés
- Sans `x` sur un dossier : impossible d’y entrer (`cd`)
- Sans `r` sur un dossier : impossible de lister (`ls`)
- Les permissions du **groupe** s’appliquent seulement si l’utilisateur appartient au groupe

## Commandes utilisées
```bash
ls -l
groups
id
