# 🤝 Guide de Contribution Juridique

Merci de contribuer au succès de la Karmine Corp ! Pour maintenir l'intégrité de nos contrats, veuillez suivre ces règles strictes avant de soumettre une modification.

## ✍️ Règles de création de branche
* Ne travaillez **jamais** directement sur `prod` ou `develop`.
* Pour créer une branche, partez directement de la dernière version de la branche `develop`.
* Nommez vos branches explicitement : `feature/nom-du-joueur-contrat` ou `fix/clause-sponsor`.
* Tous vos commits **doivent être signés**.

## 🔍 Processus de Pull Request
1. Ouvrez une Pull Request pointant vers `develop` (pour un brouillon) ou `prod` (depuis une `rc` pour une officialisation).
2. Utilisez le template de Pull Request fourni dans `.github/PULL_REQUEST_TEMPLATE.md`.
3. **Relecture obligatoire :** Une personne doit valider et approuver la Pull Request avant tout merge.
4. Assurez-vous que la CI (GitHub Actions) passe au vert. Aucun contrat mal formaté ne sera accepté.

## 🚨 En cas de conflit
Privilégiez toujours l'utilisation de `git rebase develop` sur votre branche locale pour résoudre les conflits juridiques avant de demander une relecture.