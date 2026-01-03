Analyse des Déterminants des Prix Immobiliers (2015-2023)
Ce projet présente une analyse économétrique approfondie des facteurs influençant la valeur des biens immobiliers, basée sur un échantillon de 150 transactions réalisées entre 2015 et 2023. L'étude utilise diverses techniques de modélisation, allant de la régression linéaire simple aux méthodes de régularisation et aux variables instrumentales.

📋 Résumé du Projet
L'objectif est de quantifier précisément l'impact de chaque caractéristique (physique, géographique et socio-économique) sur le prix de vente. L'étude démontre que si la surface reste le moteur principal de la valeur, l'environnement socio-économique (notamment le revenu du quartier) joue un rôle crucial une fois les biais statistiques corrigés.

🛠️ Méthodologie et Modèles
Le projet suit une démarche progressive pour assurer la robustesse des résultats :
Régression Linéaire (MCO) : Modèles simple et multiple pour établir les fondamentaux du marché.
Transformations Fonctionnelles : Comparaison entre modèles linéaire, semi-logarithmique et log-log. 
Le modèle semi-logarithmique a été retenu comme optimal ($R^2$ ajusté de 79,2%).
Traitement de l'Endogénéité : Utilisation de la méthode des Variables Instrumentales (2SLS) avec la "Distance à l'université" comme instrument pour corriger le biais lié à la "Qualité des écoles".
Régularisation (Machine Learning) : Application de Ridge et Lasso pour traiter la multicolinéarité et améliorer la performance prédictive.

📈 Résultats Clés

Impact de la surface : Chaque mètre carré supplémentaire augmente le prix de 0,21% (modèle semi-log) ou environ 5 040 € (modèle linéaire).



Variables de confort : La présence d'un ascenseur valorise le bien de 2,65% en moyenne.


Localisation : Chaque kilomètre d'éloignement du centre-ville réduit le prix de 0,30%.


Causalité vs Corrélation : L'analyse IV révèle que le revenu médian du quartier est un prédicteur de valeur plus fiable que la seule réputation des écoles, cette dernière étant souvent un biais de richesse du quartier.



Performance Prédictive : Le modèle Ridge obtient le meilleur score de généralisation avec un RMSE de 0,04388.

📊 Statistiques Descriptives (Échantillon)

Variable,Moyenne,Médiane
Prix (k€),"2 107,9","2 105,05"
Surface (m²),"116,71","117,84"
Année de construction,2001,2002
Distance Centre (km),"16,5","16,87"
Revenu Médian (k€),"63,67","63,45"


Voici une proposition de README.md structurée et professionnelle, prête à être copiée-collée sur votre dépôt GitHub. Elle synthétise l'ensemble de votre étude économétrique réalisée à l'Université Paris 1 Panthéon-Sorbonne.

Analyse des Déterminants des Prix Immobiliers (2015-2023)
Ce projet présente une analyse économétrique approfondie des facteurs influençant la valeur des biens immobiliers, basée sur un échantillon de 150 transactions réalisées entre 2015 et 2023. L'étude utilise diverses techniques de modélisation, allant de la régression linéaire simple aux méthodes de régularisation et aux variables instrumentales.

📋 Résumé du Projet
L'objectif est de quantifier précisément l'impact de chaque caractéristique (physique, géographique et socio-économique) sur le prix de vente. L'étude démontre que si la surface reste le moteur principal de la valeur, l'environnement socio-économique (notamment le revenu du quartier) joue un rôle crucial une fois les biais statistiques corrigés.

🛠️ Méthodologie et Modèles
Le projet suit une démarche progressive pour assurer la robustesse des résultats :


Régression Linéaire (MCO) : Modèles simple et multiple pour établir les fondamentaux du marché.


Transformations Fonctionnelles : Comparaison entre modèles linéaire, semi-logarithmique et log-log. Le modèle semi-logarithmique a été retenu comme optimal (R 
2
  ajusté de 79,2%).


Traitement de l'Endogénéité : Utilisation de la méthode des Variables Instrumentales (2SLS) avec la "Distance à l'université" comme instrument pour corriger le biais lié à la "Qualité des écoles".


Régularisation (Machine Learning) : Application de Ridge et Lasso pour traiter la multicolinéarité et améliorer la performance prédictive.

📈 Résultats Clés

Impact de la surface : Chaque mètre carré supplémentaire augmente le prix de 0,21% (modèle semi-log) ou environ 5 040 € (modèle linéaire).


Variables de confort : La présence d'un ascenseur valorise le bien de 2,65% en moyenne.


Localisation : Chaque kilomètre d'éloignement du centre-ville réduit le prix de 0,30%.


Causalité vs Corrélation : L'analyse IV révèle que le revenu médian du quartier est un prédicteur de valeur plus fiable que la seule réputation des écoles, cette dernière étant souvent un biais de richesse du quartier.


Performance Prédictive : Le modèle Ridge obtient le meilleur score de généralisation avec un RMSE de 0,04388.

📊 Statistiques Descriptives (Échantillon)
Variable	Moyenne	Médiane
Prix (k€)	2 107,9	2 105,05
Surface (m²)	116,71	117,84
Année de construction	2001	2002
Distance Centre (km)	16,5	16,87
Revenu Médian (k€)	63,67	63,45

Source : Tableau 1 du rapport.

🚀 Conclusions Pratiques
Pour une évaluation immobilière précise, il est recommandé de privilégier une approche multidimensionnelle via un modèle semi-logarithmique régularisé par Ridge. Cette méthode offre le meilleur équilibre entre pouvoir explicatif et capacité de prédiction sur de nouvelles données.

Auteurs : Elodie NGIRABANZI & Imane MAHAMANE OUSMANE MAIGA 

Institution : Université Paris 1 Panthéon-Sorbonne
