# 🔵 Karmine Corp - Legal & Contracts Repository 🛡️

![CI Linter](https://img.shields.io/badge/CI-Passing-success?style=for-the-badge&logo=githubactions)
![Git Flow](https://img.shields.io/badge/Workflow-Git_Flow-blue?style=for-the-badge&logo=git)
![Security](https://img.shields.io/badge/Commits-Signed-green?style=for-the-badge&logo=gnupg)

Bienvenue sur le dépôt officiel du département juridique de la **Karmine Corp**.
Ce projet sécurisé centralise l'ensemble des contrats de nos joueurs, coachs,
sponsors et infrastructures (League of Legends, Valorant, Rocket League,
Smash Bros).

## 📋 À propos du projet

Afin de garantir une traçabilité parfaite et d'éviter toute fuite d'information
avant les annonces officielles, notre équipe utilise **Git** pour versionner les
documents légaux.

## 🏗️ Structure du workflow

Nous utilisons un Git Flow strict pour la gestion de nos documents :

* **`prod`** : La branche de production. Ne contient que les contrats
   officialisés et signés.
* **`develop`** : La branche d'intégration. Contient les brouillons en cours de
   rédaction.
* **`feature/*`** : Pour la rédaction d'un nouveau contrat.
* **`fix/*`** : Pour la correction de clauses juridiques en urgence.
* **`rc/*`** : Release Candidate, pour le verrouillage des contrats avant
   soumission aux ligues (Riot Games, RLCS).
* **`chore/*`**  : Pour la configuration du git.

## 🛠️ Installation et Prérequis

Pour contribuer à ce dépôt, vous devez impérativement configurer la signature de
vos commits.

1. Clonez le dépôt en local.
2. Initialisez les hooks Git pour activer le linter Markdown :
   `chmod +x .git/hooks/pre-commit`
3. Assurez-vous d'avoir Node.js installé pour l'exécution du linter local.
