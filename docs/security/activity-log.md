
# Azure Activity Log

## Objectif

Azure Activity Log permet de suivre les opérations réalisées sur les ressources Azure. Il contribue à assurer la traçabilité et l'audit des activités de l'infrastructure Cloud.

## Travaux réalisés

Dans le cadre du projet AZURE SECURE PME, nous avons consulté le journal d'activité Azure au niveau de l'abonnement et du groupe de ressources `rg-azure-secure-pme`.

Nous avons identifié un événement correspondant à la création du groupe de ressources.

## Analyse de l'événement

| Élément | Résultat |
|---|---|
| Catégorie | Administrative |
| Opération | Création / mise à jour d'un groupe de ressources |
| Statut | Succeeded (Réussite) |
| Sous-statut | Created |
| Ressource concernée | rg-azure-secure-pme |
| Région | France Central |

L'événement confirme que la création du groupe de ressources s'est déroulée avec succès.

## Apports en matière de sécurité

Azure Activity Log permet notamment de :

- Identifier les opérations effectuées sur les ressources.
- Connaître l'initiateur d'une opération.
- Vérifier le statut des opérations.
- Faciliter les investigations en cas d'incident.
- Assurer la traçabilité des actions d'administration.

## État d'avancement

**Réalisé :** consultation du journal d'activité et analyse d'un événement réel de création de groupe de ressources.

**À approfondir :** configuration de la collecte centralisée, des alertes et de la conservation avancée des journaux.

## Conclusion

Cette première manipulation nous a permis de vérifier concrètement la traçabilité des opérations dans Azure. Azure Activity Log constitue un élément important de la stratégie de sécurité et d'administration du projet AZURE SECURE PME.
