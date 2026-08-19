# MIT 6.036: Introduction to Machine Learning — Week 4 Homework

[![MIT OCW](https://img.shields.io/badge/Course-MIT%206.036-red.svg)](https://openlearninglibrary.mit.edu/)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![Status](https://img.shields.io/badge/Score-100%25-brightgreen.svg)]()

Ce dépôt contient mes solutions complètes aux exercices pratiques de la **semaine 4** du cours *Introduction to Machine Learning* du MIT (Open Learning Library).

---

## Aperçu des thèmes abordés

Le travail de cette semaine est centré sur la théorie et la mise en œuvre vectorisée des **Machines à Vecteurs de Support (SVM)** ainsi que sur l'optimisation par **Descente de Gradient**[cite: 1].

### 1. Concepts Théoriques & Fondations
* **Calcul des Marges & Hinge Loss** : Marge géométrique, séparabilité linéaire et fonctionnement de la fonction de perte *Hinge*[cite: 1].
* **Support Vector Machines (SVM)** : Formulation de la fonction objectif combinant la perte Hinge et le terme de régularisation L2 $\lambda \lVert\theta\rVert^2$.

### 2. Algorithmes d'Optimisation
* **Gradient Numérique (`num_grad`)** : Implémentation de l'approximation du gradient par différences finies[cite: 1].
* **Gradients Analytiques SVM (`d_hinge_loss`, `d_svm_obj_th`)** : Calcul des dérivées partielles par rapport aux poids $\theta$ et au biais $\theta_0$[cite: 1].
* **Minimisation par Lots (`batch_svm_min`)** : Algorithme complet d'entraînement du classifieur SVM via la descente de gradient par lots[cite: 1].

---

## Tableau Récapitulatif des Exercices

| Section | Sujet | Description de l'Exercice |
| :--- | :--- | :--- |
| **1 – 4** | **Margin & Loss** | Analyse théorique des marges et de la perte Hinge |
| **5** | **Linear SVM** | Formulation mathématique des SVM linéaires |
| **6.1 – 6.3** | **Numerical Gradient** | Calcul et validation du gradient numérique |
| **7.1 – 7.2** | **SVM Loss & Gradient** | Calculs analytiques de la perte et des gradients |
| **7.3 – 7.4** | **Batch SVM Optimization** | Entraînement du modèle SVM par descente de gradient |

---
#### https://openlearninglibrary.mit.edu/courses/course-v1:MITx+6.036+1T2019/courseware/Week4/week4_homework/
