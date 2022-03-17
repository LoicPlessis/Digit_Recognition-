# Digit_Recognition-
Partie 1 : Base de données, Analyse, Prétraitement et Préparation

​

Pour aborder cette problématique de la reconnaissance des Digits, il est primordial d’avoir ou de collecter une DataSet. Pour cela, la fonction « collection » dans Tools/tools.py vous permettra de collecter votre propre DataSet.

​

NB. La description de votre DataSet et le processus de collection doivent être notés dans le compte rendu final).

Par la suite, il faut Appliquer les traitements nécessaires pour préparer la DataSet en utilisant Numpy et Pandas. Les étapes de ce processus de traitement doivent être bien enchainer, claire, commenter et fonctionnelle dans le Notebook.

​

Partie 2 : Pipeline Apprentissage/Classification Supervisée

​

Cette deuxième partie est réservée pour lancer une série d’expérimentation en préparant un Pipeline de plusieurs techniques de classification supervisé, notamment : KNN, SVM, Arbre de décision, Forêt Aléatoire et XGBoost.

​

Pour une étude expérimentale bien complète, il est recommandé de varier les paramètres de chaque technique utilisée, pour cela, il est préférable d’utiliser les outils proposés par Sklearn comme : Pipeline et GridSearchCV.

​

Partie 3 : Mettre en place la solution dans une application Test Temps Réel

​

Utilisez la fonction « joblib » pour enregistrer votre modèle, cela une fois vous avez préparé votre meilleur modèle de classification.

​

Faites intégrer cette solution dans une Application en utilisant la fonction « rec » qui est dans Tools/tools.py.
