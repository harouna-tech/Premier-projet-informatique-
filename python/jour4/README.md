## 🔹 Linux — Jour 4 : setgid et travail en groupe (README.md)

📄 **Linux/jour4/README.md**

```md
# Linux — Jour 4 : setgid et travail en groupe

## Objectif
Mettre en place un dossier partagé où tous les fichiers héritent automatiquement
du même groupe.

## Notions abordées
- Groupes Linux
- Bit spécial setgid (`g+s`)
- Héritage du groupe dans un dossier

## setgid
Le bit setgid appliqué à un dossier permet aux fichiers créés à l’intérieur
d’hériter automatiquement du groupe du dossier.

## Commandes utilisées
```bash
chmod g+s dossier_partage
ls -ld dossier_partage
