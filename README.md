#  XAI : Explainable AI & Interprétabilité des Modèles

Ce dépôt regroupe l'ensemble des travaux réalisés dans le cadre du module **Intelligence Artificielle Explicable (XAI)** en Master 1 Informatique à l'Université Sorbonne Paris Nord.

L'objectif est de comprendre et d'implémenter des méthodes permettant d'interpréter les prédictions des modèles de Machine Learning (boîtes blanches vs boîtes noires).

##  Contenu du Dépôt

### 1.  Projet LIME (Local Interpretable Model-agnostic Explanations)
Une implémentation et exploration approfondie de la méthode LIME, qui permet d'expliquer localement n'importe quel classifieur.

* **`lime_implementation.py`** : Script Python contenant l'implémentation de l'algorithme LIME (génération de voisinage, pondération, modèle linéaire local).
* **`experimentation.ipynb`** : Notebook de démonstration et d'analyse des résultats de LIME sur différents jeux de données.

### 2.  Travaux Pratiques (TPs)
Série d'exercices progressifs couvrant les concepts clés de l'interprétabilité :

* **TP1 à TP5 (`Tp1.ipynb` - `Tp5.ipynb`)** :
    * Analyse de modèles intrinsèquement interprétables (Arbres de décision, Régression linéaire).
    * Mesure de l'importance des variables (Feature Importance).
    * Méthodes globales vs locales.
* **TP SHAP (`TpShap.ipynb`)** : Utilisation des valeurs de Shapley (SHAP) pour une interprétation basée sur la théorie des jeux.

##  Technologies Utilisées

* **Langage :** Python 3
* **Bibliothèques XAI :** LIME, SHAP
* **Machine Learning :** Scikit-learn, NumPy, Pandas
* **Visualisation :** Matplotlib, Seaborn
* **Environnement :** Jupyter Notebooks

##  Installation et Utilisation

1.  Cloner le dépôt :
    ```bash
    git clone [https://github.com/votre-username/xai-lime-project.git](https://github.com/votre-username/xai-lime-project.git)
    cd xai-lime-project
    ```

2.  Installer les dépendances :
    ```bash
    pip install numpy pandas scikit-learn matplotlib lime shap
    ```

3.  Lancer les notebooks pour voir les explications visuelles :
    ```bash
    jupyter notebook
    ```

---
*Projet réalisé par Tesnime Ben Salem - Master 1 Informatique.*
