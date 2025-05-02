# MLRecap


Bienvenue dans le projet **MLRecap**, développé dans le cadre du brief **« Prédire la popularité d’un film »**. Ce projet est une solution complète intégrant extraction de données, modélisation machine learning, déploiement d’API et création d’une interface web.

---

## ➤ Menu

* [➤ Structure du projet](#-structure-du-projet)
* [➤ Brief client](#-brief-client)
* [➤ Prérequis](#-prérequis)
* [➤ Critères d’évaluation](#-critères-dévaluation)
* [➤ Licence](#-licence)
* [➤ Auteurs](#-auteurs)

---

## ➤ Structure du projet

| Dépôt GitHub                                                           | Description                                              |
| ---------------------------------------------------------------------- | -------------------------------------------------------- |
| [MLrecap\_scraping](https://github.com/haceneZERROUK/MLrecap_scraping) | Extraction des données pour le dataset du model et automatisé pour les prédictions hebdomadaires. (Scrapy).        |
| [MLrecap\_Model](https://github.com/haceneZERROUK/MLrecap_Model)       | Préparation, entraînement et export du modèle ML.        |
| [MLrecap\_api](https://github.com/haceneZERROUK/MLrecap_api)           | API FastAPI exposant le modèle.                          |
| [MLrecap\_django](https://github.com/haceneZERROUK/MLrecap_django)     | Interface utilisateur web (tableau de bord sous Django). |


### Schéma d’architecture globale

![](placeholder_pour_schema_architecture.png)

Ce schéma montre les interactions entre les composants et les flux de données, orchestrés via une architecture micro-services sur Docker et Azure.

<img width="686" alt="Capture d’écran 2025-05-02 à 18 43 46" src="https://github.com/user-attachments/assets/314c2722-380f-4cac-9b42-f5bd672dfae1" />

___

## ➤ Brief client

Le projet répond à la demande du client New is Always Better, un cinéma souhaitant :

Automatiser la prédiction du succès des nouveaux films chaque semaine.

Sélectionner les deux meilleurs films à projeter dans ses deux salles, selon leur potentiel d’audience.

Obtenir des prévisions précises avant la sortie nationale, en exploitant des données externes (Allociné, IMDb, réseaux sociaux).

Centraliser les résultats dans un tableau de bord simple, visuel et sans nécessité de compétences techniques.

Maximiser le chiffre d’affaires en tenant compte des capacités des salles et des coûts hebdomadaires.

Ce projet est structuré autour de quatre sprints agiles, avec un engagement constant envers le client, des livrables progressifs (modèle ML, API, tableau de bord) et une méthodologie rigoureuse pour garantir qualité et fiabilité.

---

## ➤ Prérequis

* Python 3.10+
* Docker et Docker Compose
* MySQL (pour la base de données transactionnelle)
* MLflow et Azure ML (pour le suivi des expériences)
* Jira (gestion agile)

---

## ➤ Critères d’évaluation

Le projet sera évalué selon :

* La qualité du modèle de prédiction
* La robustesse des services (API, interface web)
* Le respect des exigences fonctionnelles et techniques
* L’intégration des micro-services et de l’automatisation
* L’estimation et la gestion des coûts cloud (Azure)
* La bonne application de la méthode agile


---

## ➤ Licence

Projet sous licence MIT. Voir le fichier `LICENSE`.

---

## ➤ Auteurs

* **Hacene Zerrouk**: [GitHub](https://github.com/haceneZERROUK)
* **Malek Boumedine**: [GitHub](https://github.com/Malek-Boumedine)
* **Khadija Abdelmalek**: [GitHub](https://github.com/khadmalek)
* **Khadija Aassi**: [GitHub](https://github.com/Khadaassi)

Pour toute question, merci d’ouvrir une issue sur le dépôt principal.
