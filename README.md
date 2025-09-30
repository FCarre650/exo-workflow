# 📘 Workflow Git — Feature Branching

## 🏢 Entreprise : *IPIPI*  
## 📅 Dernière mise à jour : `30/09/2025`  
## 🧑‍💻 Auteur : *Quelqu'un de l'IPIPI*

---

## 🚀 Objectif

Mettre en place un processus de gestion de branches Git clair, reproductible et adapté au travail en équipe.  
Ce workflow repose sur le modèle **Feature Branching**, facilitant le développement, la revue de code et les tests.

---

## 🗂️ Structure des branches

| Branche         | Rôle |
|----------------|------|
| `main`         | Branche de production (stable, prête à être déployée) |
| `dev`      | Branche d'intégration (version en cours de développement stable) |
| `feature/*`    | Branches pour chaque fonctionnalité spécifique |
| `hotfix/*`     | Branches pour les corrections urgentes en production |
| `release/*`    | Préparation des versions (stabilisation, QA, etc.) |

---

## 🛠️ Cycle de vie d'une fonctionnalité (Feature Branch)

### 1. Se baser sur la branche `develop`

```bash
git checkout develop
git pull
```

## 🛠️ Cycle de vie d'une fonctionnalité (Feature Branch) des commit

## Nomenclature des messages des commit

[numéro de ticket][action] message

**Action**

**[CREATE]** : pour une création.

**[REMOVE]** : pour une suppression.

**[MODIF]** : pour une modification.

## Numéro des tickes en cours 

**[130]** : Developpement de la page d'acceuil du site 

**[131]** : Developpement d'une page "about" sur la description de l'entreprise

**[132]** : Developpement d'une page décrivant les services proposés par l'entreprise

**[133]** : Developpement d'une page de contact. 

