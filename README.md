# Mise à jour d'un projet sur les IRVE

Dans le cadre du projet Data For Good saison 11 intitulé "Évolution des infrastructures de recharge pour les véhicules électriques", nous avons commencé par rechercher si d'autres développeurs avaient déjà exploité les données ouvertes du gouvernement sur les bornes de recharge pour véhicules électriques (IRVE) disponibles en France : https://www.data.gouv.fr/fr/datasets/fichier-consolide-des-bornes-de-recharge-pour-vehicules-electriques/.

Un projet développé par Nalron est pertinent et poussé, avec de l'analyse de données, des prédictions avec la librairie Prophet puis des visualisations faites sur Tableau. Cependant, ses derniers commits datent d'août 2020 et certaines data sources nécessitent une mise à jour. 


Projet de nalron: https://github.com/nalron/project_electric_cars_france2040

Projet data for good saison 11 :
- Notion page: https://dataforgood.notion.site/volution-des-infrastructures-de-recharge-pour-les-v-hicules-lectriques-984f4f4256f547a5bf13ea88c033e061
- Repo github: https://github.com/dataforgoodfr/batch11_e_cartomobile


# Setup

Créer un environnement virtuel avec toutes les dépendances pour exécuter les notebooks de ce repo :
```
poetry install
```
Ensuite, vous pouvez sélectionner cet environnement virtuel dans VSCode pour exécuter les notebooks. Si vous préférez exéctuer vos notebooks dans le navigateur:
```
poetry run ipython kernel install --user --name=<YOUR_KERNEL_NAME>
jupyter notebook
```
Ensuite, sélectionnez le kernel créé dans l'interface web.