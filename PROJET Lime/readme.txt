======================================================
PROJET : Explicabilité de Modèles (LIME)
======================================================

## 1. Membres du Groupe et Contributions

 -HACHEMI Melissa 
 -BEN SALEM Tesnime

*Les contributions ont été partagées équitablement sur tous les aspects du projet :

 						-la conception et l'implémentation de la classe SimpleLIME.
 						-la conduite des expériences et l'analyse des résultats dans le notebook Jupyter.
 						-la rédaction du rapport final.
---

## 3. Instructions d'Exécution

Pour exécuter les expériences et reproduire les résultats du projet, veuillez suivre ces étapes :

### 3.1. Pré-requis

Assurez-vous que l'environnement d'exécution dispose de Python (version recommandée : **Python 3.9+**).

### 3.2. Installation des Dépendances

Les bibliothèques requises sont listées ci-dessous :

* numpy (>= 1.22.0)
* pandas (>= 1.4.0)
* scikit-learn (>= 1.0.0)
* matplotlib (>= 3.5.0)
* jupyter (pour exécuter le notebook)

Vous pouvez installer toutes les dépendances via la commande suivante :

pip install numpy pandas scikit-learn matplotlib jupyter


### 3.3. Exécution du code 

Assurez-vous que les fichiers lime_implementation.py et experimentation.ipynb se trouvent dans le même répertoire.
1-Naviguez jusqu'au répertoire du projet dans le terminal ou invite de commande :

					cd HACHEMI_BENSALEM_LIME

2-Lancez le Notebook Jupyter. pour importer correctement la classe SimpleLIME :

					jupyter notebook experimentation.ipynb

3-Ouvrez le fichier experimentation.ipynb dans le navigateur et exécutez toutes les cellules séquentiellement pour :

								dérouler les expériences.
							        entraîner le modèle .
								générer les explications LIME.
