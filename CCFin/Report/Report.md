# Rapport sur l’étude Heart Disease (1988)

## 1. Introduction

L’ensemble de données **Heart Disease** est une base de référence dans la recherche biomédicale et l’apprentissage automatique. Il a été **publié le 30 juin 1988** et vise à prédire la présence de maladies cardiaques à partir de données cliniques.  
Ce jeu de données est souvent associé à la base UCI Machine Learning Repository, où il est référencé sous le nom **"Heart Disease Data Set"**.

---

## 2. Contexte général

### • Qui a créé la base ?
L’ensemble de données a été compilé par plusieurs chercheurs en cardiologie et en informatique médicale, sous la supervision du :
- **Cleveland Clinic Foundation** (États-Unis)
- En collaboration avec des institutions médicales de :
  - **Budapest, Hongrie**
  - **Zurich, Suisse**
  - **VA Medical Center, Long Beach (Californie)**

Les chercheurs principaux incluent :
- **Robert Detrano**, MD, PhD (Cleveland Clinic Foundation)
- Avec la contribution de cliniciens et analystes de données des trois autres centres.

---

## 3. Quoi : Nature des données

L’objectif du projet est de déterminer la présence ou l’absence de maladie cardiaque (diagnostic binaire) à partir de variables cliniques et démographiques.

### Variables principales :
- **Âge**, **sexe**
- **Type de douleur thoracique**
- **Pression artérielle au repos**
- **Cholestérol sérique**
- **Glycémie à jeun**
- **Résultats de l’électrocardiogramme**
- **Fréquence cardiaque maximale atteinte**
- **Angine induite par l’exercice**
- **Dépression du segment ST**
- **Type de pente du segment ST**
- **Nombre de vaisseaux principaux colorés par fluoroscopie**
- **Type de thalassémie**
- **Variable cible** : présence de maladie cardiaque (valeurs de 0 à 4)

---

## 4. Où : Localisation et contribution des bases

| Base de données | Localisation | Nombre d’observations | Particularités |
|------------------|---------------|------------------------|----------------|
| **Cleveland** | États-Unis | 303 | Jeu de données principal, le plus complet |
| **Hungary** | Budapest, Hongrie | 294 | Données partiellement manquantes |
| **Switzerland** | Zurich, Suisse | 123 | Variables ECG très détaillées |
| **VA Long Beach** | Californie, États-Unis | 200 | Données issues de patients vétérans |

Seule la **base Cleveland** est souvent utilisée pour les études de modélisation car elle contient le moins de valeurs manquantes.

---

## 5. Comment : Méthodologie de collecte

1. **Sélection clinique** : Patients présentant des symptômes cardiaques ont été recrutés dans les hôpitaux partenaires.  
2. **Mesures physiologiques** : Données collectées à partir d’examens standards (tests d’effort, ECG, imagerie fluoroscopique, analyses sanguines).  
3. **Codification** : Les variables ont été numérisées selon un schéma commun, puis anonymisées.  
4. **Intégration** : Les quatre bases ont été agrégées dans un format tabulaire commun (14 variables).  
5. **Publication** : Données rendues publiques via le **UCI Machine Learning Repository** en 1988.

---

## 6. Utilisation scientifique

L’ensemble **Heart Disease** est l’un des plus utilisés pour :
- Tester des modèles de **classification médicale** (régression logistique, SVM, réseaux de neurones, arbres de décision, etc.)
- Étudier les **facteurs de risque cardiovasculaires**
- Démontrer les approches de **prétraitement de données manquantes** et **d’équilibrage de classes**

---

## 7. Conclusion

Le jeu de données **Heart Disease (1988)** constitue une ressource essentielle pour la recherche médicale et l’apprentissage automatique.  
Issu de quatre institutions médicales (Cleveland, Hungary, Switzerland, VA Long Beach), il illustre la collaboration internationale pour la compréhension et la prédiction des maladies cardiovasculaires.

---

## 8. Références

- Detrano, R., et al. (1989). *"International application of a new probability algorithm for the diagnosis of coronary artery disease"*. American Journal of Cardiology, 64(5), 304–310.  
- UCI Machine Learning Repository: [Heart Disease Data Set](https://archive.ics.uci.edu/ml/datasets/heart+disease)

