# Contexte
* Prédire le volume de commentaire qu’un document (ex: une page) devrait recevoir dans les prochaines heures sur un réseau social.
* Commentaires récupérés sur facebook (plusieurs pages),  à l’aide d’un robot, publiés durant les 3 derniers jours.
* Pre-processing déjà effectué.
* Les postes dont les commentaires ou tout autres détails sont manquants ont été omis.
* Temporal split: training_set following of test_set (dont le but est de prédire les commentaires suivants => On cache la target dans le test_set).

# Target
Prédire combien de commentaire un poste recevra dans les H prochaines heures (sur Facebook).
* Une ligne : Correspond à un poste sur une page.
* Une colonne : Représente une feature parmi 53 découpé en 4 catégories de features.

# Api Flask
Lire le ReadMe.txt pour utilisation

# Conclusion
Voir Rapport.pdf
