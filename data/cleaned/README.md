**Ce dossier contient les données après nettoyage et préparation.**

_Ces fichiers sont générés à partir des données présentes dans `data/raw/`._

Exemples de transformations :
- nettoyage des noms de colonnes
- gestion des valeurs manquantes
- filtrage des années ou des pays

**Explication des Dataframes**\
**df_original**: df Raw mis en page: mise en minuscule et remplacement des espaces par des _ \
**df_2015:** df contenant uniquement les données de 2015 à 2023\
**df_h1:** On garde uniquement les pays qui ont au moins 7 valeurs renseignées dans la colonne log_gdp_per_capita et on enlève les lignes avec des NaN dans gdp
