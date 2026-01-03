# Analyse des Prix Immobiliers : Projet d'Économétrie Appliquée

Ce projet analyse les déterminants des prix immobiliers sur un échantillon de 150 maisons vendues entre 2015 et 2023.

## 📋 Résumé du projet
L'objectif est de quantifier l'impact de diverses caractéristiques (surface, localisation, équipements) sur la valeur marchande en utilisant des méthodes allant de la régression linéaire simple aux techniques de régularisation et de variables instrumentales.

## 🚀 Résultats Principaux
**Surface Habitable** : C'est le moteur prédominant, expliquant plus de 68% de la variance des prix. Chaque mètre carré supplémentaire génère une augmentation de 0,21% du prix dans le modèle optimal.
* **Localisation** : Chaque kilomètre d'éloignement du centre-ville réduit le prix de 6 140 € en moyenne.
* **Équipements** : La présence d'un ascenseur augmente la valeur du bien de 55 510 € par rapport à un bien identique sans cet équipement.
* **Socio-économie** : L'intégration du revenu médian du quartier et de la qualité des écoles a porté la précision du modèle à 84%.


## 🛠️ Méthodologie Économétrique
### 1. Modélisation de référence
* **MCO (Moindres Carrés Ordinaires)** : Utilisation de modèles linéaires simples et multiples.
* **Modèle Semi-Logarithmique** : Identifié comme le plus robuste statistiquement avec un $R^2$ ajusté de 79,2%.

### 2. Traitement de l'Endogénéité
Pour corriger le biais lié à la variable "Qualité des écoles", la méthode des **Variables Instrumentales (2SLS)** a été appliquée en utilisant la "Distance à l'université" comme instrument. 
* **Découverte majeure** : Le modèle MCO surestimait l'impact de l'école. En réalité, la valorisation est davantage portée par le revenu moyen des résidents que par la proximité immédiate d'une école réputée.

### 3. Régularisation (Machine Learning)
Comparaison des méthodes pour optimiser la prédiction sur de nouvelles données:
* **Ridge** : Meilleure performance avec un RMSE de 0,04388.
* **Lasso** : Moins performant (RMSE de 0,04946) en raison d'une suppression trop drastique de variables secondaires utiles.

## 📊 Statistiques Descriptives
| Variable | Moyenne | Médiane | Écart-type |
| :--- | :--- | :--- | :--- |
| **Prix (milliers €)** | 2 107,9 | 2 105,05 | 229,92 |
| **Surface (m²)** | 116,71 | 117,84 | 37,69 |
| **Distance Centre (km)** | 16,5 | 16,87 | 9,02 |

*Données extraites des statistiques descriptives de l'échantillon.*

## 🎓 Auteurs
* **NGIRABANZI Elodie** 
* **MAHAMANE OUSMANE MAIGA Imane**
* **Université Paris 1 Panthéon-Sorbonne**, 31 Décembre 2025
