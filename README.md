README - Projet de Classification K-NN

Ce projet vise à démontrer l'utilisation de l'algorithme de classification des k plus proches voisins (K-NN) pour prédire si un client achète ou non un produit en fonction de son âge et de son salaire estimé. Le projet utilise Python avec les bibliothèques pandas, numpy, matplotlib et scikit-learn.
Fichiers du Projet

    Social_Network_Ads.csv: Le jeu de données utilisé pour l'entraînement du modèle. Il contient des informations sur l'âge, le salaire estimé et si le client a acheté ou non le produit.
    knn_classifier.py: Le script Python principal qui charge les données, entraîne le modèle K-NN, effectue des prédictions et affiche les résultats.

Installation

    Assurez-vous d'avoir Python installé sur votre système. Si ce n'est pas le cas, vous pouvez le télécharger à partir de python.org.
    Clonez ce dépôt GitHub sur votre machine locale en utilisant la commande suivante :

    bash

git clone https://github.com/votre_utilisateur/nom_du_depot.git

Assurez-vous d'avoir les bibliothèques requises installées. Vous pouvez les installer en exécutant la commande suivante :

    pip install numpy pandas matplotlib scikit-learn

Utilisation

    Assurez-vous d'être dans le répertoire du projet.
    Exécutez le script knn_classifier.py en utilisant la commande suivante :

    python knn_classifier.py

    Le script affichera les prédictions du modèle ainsi que des graphiques de la distribution des données d'entraînement et de test.

Résultats

    Le script affiche les prédictions du modèle sur les données de test ainsi que la matrice de confusion et le score de précision.
    Deux graphiques sont générés : l'un pour visualiser la classification sur les données d'entraînement et l'autre sur les données de test.

Contributions

Les contributions sont les bienvenues ! Si vous avez des suggestions d'amélioration, des problèmes à signaler ou si vous souhaitez ajouter de nouvelles fonctionnalités, n'hésitez pas à ouvrir une issue ou à envoyer une demande de fusion (pull request).
