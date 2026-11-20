# AZURE SECURE PME

## Présentation du projet

AZURE SECURE PME est un projet de conception et de sécurisation d'une infrastructure Cloud basée sur Microsoft Azure, destiné à une petite ou moyenne entreprise (PME).

L'objectif est de mettre en place une architecture Cloud sécurisée, de contrôler les accès, de surveiller les activités et de maîtriser les coûts.
## Objectifs du projet

- Concevoir une infrastructure Cloud adaptée aux besoins d'une PME.
- Sécuriser les accès et les identités avec Microsoft Entra ID.
- Mettre en place une gestion des autorisations avec Azure RBAC.
- Assurer la traçabilité des activités et des opérations.
- Contrôler la configuration des ressources Azure.
- Surveiller les dépenses et maîtriser les coûts.
- Documenter les choix techniques et les mesures de sécurité.
## Architecture cible

L'architecture envisagée repose sur des services Cloud Microsoft Azure et des outils complémentaires afin de limiter les coûts tout en assurant un niveau de sécurité adapté aux besoins d'une PME.

| Composant | Technologie | Rôle |
|---|---|---|
| Hébergement web | Azure Static Web Apps | Héberger le portail de démonstration |
| Gestion des identités | Microsoft Entra ID | Gérer les identités et les accès |
| Gestion des permissions | Azure RBAC | Contrôler les autorisations |
| Traçabilité | Azure Activity Log | Suivre les opérations |
| Gouvernance | Azure Policy | Contrôler la configuration |
| Gestion des coûts | Azure Cost Management | Surveiller les dépenses |
| Gestion du code | GitHub | Héberger le code source et la documentation |

Cette architecture constitue une cible de conception. Les services seront déployés et vérifiés progressivement.
## Mesures de sécurité

Le projet s'appuie sur plusieurs principes fondamentaux de cybersécurité :

- **Gestion des identités :** centraliser le contrôle des accès avec Microsoft Entra ID.
- **Moindre privilège :** attribuer uniquement les permissions nécessaires à chaque utilisateur.
- **Contrôle des accès :** utiliser Azure RBAC pour gérer les autorisations.
- **Traçabilité :** exploiter Azure Activity Log pour suivre les opérations.
- **Gouvernance :** utiliser Azure Policy pour contrôler la conformité des ressources.
- **Maîtrise des coûts :** configurer des budgets et des alertes avec Azure Cost Management.
## Technologies et outils utilisés

| Technologie | Utilisation |
|---|---|
| Microsoft Azure | Infrastructure Cloud |
| Microsoft Entra ID | Gestion des identités |
| Azure RBAC | Gestion des permissions |
| Azure Policy | Gouvernance et conformité |
| Azure Activity Log | Journalisation des activités |
| Azure Cost Management | Suivi des dépenses |
| GitHub | Gestion du code source et documentation |
| HTML / CSS / JavaScript | Développement du portail web |

Les technologies seront intégrées progressivement au cours de la réalisation du projet.
## Maîtrise des coûts

La maîtrise des dépenses constitue un élément important du projet. L'objectif est de construire une infrastructure Cloud en privilégiant les services adaptés au budget d'une PME.

Les mesures prévues sont :

- Utiliser prioritairement les offres gratuites éligibles.
- Éviter les ressources Azure non indispensables.
- Configurer un budget Azure avec un seuil de surveillance de 1 €.
- Mettre en place des alertes à 50 %, 80 % et 100 % du budget.
- Surveiller régulièrement les dépenses avec Azure Cost Management.

**Important :** les budgets Azure déclenchent des alertes, mais ne bloquent pas automatiquement les dépenses.
## État d'avancement du projet

### Réalisé

- Création du dépôt GitHub public.
- Rédaction de la présentation et des objectifs du projet.
- Définition de l'architecture Cloud cible.
- Identification des services Azure envisagés.
- Création d'un budget Azure de 1 € avec des alertes à 50 %, 80 % et 100 %.

### En cours

- Préparation de l'environnement Azure.
- Étude des services Cloud et de leurs conditions tarifaires.
- Conception détaillée de l'architecture de sécurité.

### À réaliser

- Déploiement du portail web de démonstration.
- Configuration et vérification des contrôles de sécurité.
- Réalisation des tests techniques.
- Documentation des résultats et des captures d'écran.
## Organisation du projet

Le dépôt GitHub sera organisé progressivement de la manière suivante :

```text
azure-secure-pme/
│
├── README.md
├── docs/
│   ├── architecture/
│   ├── securite/
│   └── captures/
│
├── frontend/
│   ├── index.html
│   ├── css/
│   └── js/
│
└── tests/
```
Cette organisation prévisionnelle permettra de séparer le code source, la documentation technique et les résultats des tests.
## Auteur

Projet réalisé dans le cadre d'un parcours de développement de compétences en Cloud Computing et cybersécurité.

**Domaine :** Administration Cloud, sécurité des infrastructures et gouvernance Azure.

**Plateforme :** Microsoft Azure.

**Dépôt GitHub :** https://github.com/RAPHGUIBINGA/azure-secure-pme

---

*AZURE SECURE PME — Concevoir, sécuriser et maîtriser son infrastructure Cloud.*
