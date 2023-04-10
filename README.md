# projet-data-science_ABACLIMohamedAmine

Titre du projet : Prédiction de survie sur le Titanic

Description du projet : Dans ce projet, nous allons construire un modèle de machine learning capable de prédire la survie des passagers à bord du Titanic. Nous allons utiliser un ensemble de données qui contient des informations sur les passagers, telles que leur âge, leur sexe, leur classe de billet et le tarif qu'ils ont payé pour leur voyage. Nous allons entraîner plusieurs modèles de classification et choisir le modèle le plus performant pour faire des prédictions sur un ensemble de données de test.

Guide d'utilisation :

Téléchargez le jeu de données à partir de Kaggle.
Ouvrez le notebook Jupyter et importez les bibliothèques nécessaires.
Chargez l'ensemble de données dans un dataframe Pandas.
Effectuez une analyse exploratoire des données et nettoyez les données en remplaçant les valeurs manquantes et en supprimant les colonnes inutiles.
Divisez les données en ensembles de formation et de test.
Initialisez les modèles de classification que vous souhaitez entraîner et utilisez la validation croisée pour évaluer leurs performances.
Sélectionnez le modèle le plus performant et entraînez-le sur l'ensemble de formation.
Utilisez le modèle entraîné pour faire des prédictions sur l'ensemble de données de test.
Créez un fichier de soumission contenant les prédictions et la colonne PassengerId pour soumettre les résultats sur Kaggle.

Exemple d'utilisation :

Chargement des données : Nous avons chargé les données à partir d'un fichier CSV dans un dataframe Pandas en utilisant la fonction read_csv().

Analyse exploratoire des données : Nous avons utilisé différentes visualisations pour mieux comprendre les données, telles que des diagrammes de dispersion pour montrer les relations entre différentes variables et des diagrammes en boîte pour montrer les distributions.

Nettoyage des données : Nous avons remplacé les valeurs manquantes dans les colonnes 'Age' et 'Fare' en utilisant la moyenne des valeurs existantes et supprimé les colonnes inutiles telles que 'Ticket', 'Cabin' et 'Name'. Nous avons également converti les valeurs de la colonne 'Sex' en valeurs numériques et utilisé un encodeur one-hot pour convertir les valeurs de la colonne 'Embarked' en valeurs numériques.

Entraînement de modèles : Nous avons entraîné plusieurs modèles de classification, tels que la régression logistique, l'arbre de décision, la forêt aléatoire et le SVM, en utilisant la validation croisée pour évaluer leurs performances.

Sélection du modèle : Nous avons choisi le modèle GradientBoostingClassifier comme étant le plus performant.

Faire des prédictions : Nous avons utilisé le modèle entraîné pour faire des prédictions sur l'ensemble de données de test et avons créé un fichier de soumission pour soumettre les résultats sur Kaggle.

Conclusion : 

Ce projet a montré comment utiliser les techniques de machine learning pour prédire la survie des passagers à bord du Titanic. En utilisant des visualisations, des techniques de nettoyage de données et la validation croisée, nous avons pu entraîner plusieurs modèles et choisir le modèle le plus performant pour faire des prédictions précises sur l'ensemble de données de test.
