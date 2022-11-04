# Info Éco-Énergie

## Idée initiale
Le citoyen est souvent plein de bonne volonté pour économiser l’énergie. Cependant ce n’est pas toujours évident car la notion de consommation d’énergie n’est pas quelque chose de palpable.
Aussi notre idée initiale était d’apporter de la visibilité sur l'état de la consommation d'électricité aux citoyens afin qu’il puisse mieux se situer grâce à une application intuitive et interactive.

## Ce que notre solution réalise
Notre solution permet de visualiser les données sur la consommation d’électricité au Québec. Les chiffres doivent raconter  une histoire. La mise en valeur des données crée une sorte de défi pour inciter à mieux consommer l'énergie pour dépenser moins. Ces données définissent le classement des communes, des villes et des régions dans le palmarès des localités les plus responsables en termes de consommation d'énergie. 
Notre solution affiche:
 - La demande en temp réel d'électricité
 - La production d’électricité provenant des différents sources
 - Les marchés que Québec fournit
 - L’historique de consommation depuis 2016 croisé avec les données de la population des municipalités au Québec
 - Permet à l’utilisateur d’interroger les données à en langage naturelle
 - La prédiction de la consommation pour les 12 prochains mois

## Comment nous l'avons implémenté
 - PowerBI
 - Fonctionnalités PowerBI:
   - Données en temps réel (Real-time streaming)
   - Historique des consommations
   - Question et réponses (Natural language Q&A)
   - Modèle prédictif (Analytics forecasting)
   - "Power Automate"

## Les difficultés rencontrées
 - Le temps
 - Trouver un angle d’approche
 - Trouver les bons jeux de données
 - Comprendre les données et biens filtrer pour avoir les bons chiffres (ex: les codes géographique)
 - Valider les données avec un expert d’Hydro Québec
 - Limitations des licences d’essais
 - Les données de 2016 sur la consommation d’électricité nous semblent partielles

## Ce que nous avons appris
 - Nous avons dû nous informer sur les unités et leur multiple pour exprimer la production ou la conso d'énergie 
 - Québec produit quasiment 100% d’énergie verte. 
 - Livrer un solution dans un court laps de temps

## Améliorations futures pour “Info Éco-Énergie”
 - Valider l'interprétation des données
 - Système d’alerte basé sur les données météo pour inciter à consommer moin d’énergie 
 - Modele previsionnel : ajouter d'autres facteurs pour changer la prévision selon les choix de l'utilisateur. Par exemple: si je consomme moins, quel sera l'impact dans le futur.
 - Une granularité plus fine des données de consommation pour comparer sa consommation à la moyenne de son quartier
 - Rendre compatible avec le français la fonctionnalité permettant d’interroger les données en langage naturel
 - Une carte interactive (type google map) orientée Énergie
 - Améliorer l’affichage pour la consultation via un mobile
 - Vignette présentant des activités du quotidien (1 heure de tv, four, clim… ) et indiquer ce que ça consomme en kWatt-heure pour aider le citoyen à construire un référentiel
 - À partir d’un questionnaire sur son mode de vie, le citoyen dessine son profil de consommation.

## Jeux de données utilisés
 - Population des organisations municipales:  
https://www.donneesquebec.ca/recherche/dataset/repertoire-des-municipalites-du-quebec/resource/c27b1830-2b46-4e80-819b-6238ff7c3b03
 - Historique des données de consommation d’électricité au Québec par secteur d’activité:  
https://www.donneesquebec.ca/recherche/dataset/historique-consommation-electricite-secteur-activite
 - Demande d'électricité au Québec:  
https://www.donneesquebec.ca/recherche/dataset/demande-electricite-quebec
 - HackQC22 - livraison spéciale:  
https://www.donneesquebec.ca/recherche/dataset/hackqc22-livraison-speciale
