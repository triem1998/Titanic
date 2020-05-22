# Titanic
Le projet a été réalisé par PHAN Dinh Triem, VO Thanh Tin, DEVEAUX Jérôme, NIANG Cheikh Ahmadou Bamba
## Le but du projet
Ce projet a le but de construire un modèle de prévision de survie des passagers sur le Titanic et analyser les impacts des variable: l'age, le sexe, la classe, ... sur la survie des personnes qui étaient sur le Titanic.
Les codes sont écrits en Python et en R. Les commentaires sont détaillées dans le fichier Titanic_R.
## Table de matière
Ce projet a 3 grandes parties:
### Partie A : Data preparation & Descriptive statistics
Dans cette partie, nous visualisons les données et faire une étude descritptive pour donner un sens aux données. 

### Partie B: Sans la variables "Age"
Dans cette partie, nous ne considérons pas la variables "Age" car elle manque beaucoup de données.
Nous utilisent les alogorithmes de Machine learning: la régression logistique, la régression logistique avec l'interaction, l'arbre binéaire, la forêt aléatoire et les courbes ROC
### Partie C: Avec la variables "Age"
Nous imputons les données manquant de la variables "Age" par l'algorithme missForest et appliquer tous les algorithme utilisés dans la partie B
