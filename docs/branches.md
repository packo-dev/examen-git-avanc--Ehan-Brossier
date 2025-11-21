branches

 main : branche de base, contient le code en production
dev : branche d'intégration, où toutes les fonctionnalités sont fusionnées avant d'aller en production
feature: branches pour développer de nouvelles fonctionnalités
 hotfix: branches pour corriger des erreurs urgentes en production
 Méthode 

Pour mettre à jour la branche dev avec la correction de main, j'ai utilisé /git merge main/ Cette méthode est appropriée car elle préserve l'historique complet et montre clairement que la correction a été intégrée depuis main.
