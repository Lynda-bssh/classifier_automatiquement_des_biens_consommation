# Classifiez automatiquement des biens de consommation

## Contexte et problématique:
Vous êtes Data Scientist au sein de l’entreprise "Place de marché”, qui souhaite lancer une marketplace e-commerce.
Sur la place de marché, des vendeurs proposent des articles à des acheteurs en postant une photo et une description.

Pour l'instant, l'attribution de la catégorie d'un article est effectuée manuellement par les vendeurs, et est donc peu fiable. De plus, le volume des articles est pour l’instant très petit.

Pour rendre l’expérience utilisateur des vendeurs (faciliter la mise en ligne de nouveaux articles) et des acheteurs (faciliter la recherche de produits) la plus fluide possible, et dans l'optique d'un passage à l'échelle, il devient nécessaire d'automatiser cette tâche.

Linda, Lead Data Scientist, vous demande donc d'étudier la faisabilité d'un moteur de classification des articles en différentes catégories, avec un niveau de précision suffisant.

Voici le mail qu’elle vous a envoyé.

## Mission :

- Réaliser, dans une première itération, une étude de faisabilité d'un moteur de classification d'articles, basé sur une image et une description, pour l'automatisation de l'attribution de la catégorie de l'article.
- analyser les descriptions textuelles et les images des produits, au travers des étapes suivantes : 

Un prétraitement des données texte ou image suivant le cas :
- Une extraction de features ;
- Une réduction en 2 dimensions, afin de projeter les produits sur un graphique 2D, sous la forme de points dont la couleur correspondra à la catégorie réelle ;
- Analyse du graphique afin d’en déduire ou pas, à l’aide des descriptions ou des images, la faisabilité de regrouper automatiquement des produits de même catégorie ;
- Réalisation d’une mesure pour confirmer ton analyse visuelle, en calculant la similarité entre les catégories réelles et les catégories issues d’une segmentation en clusters.
Pour l'extraction des features textes il sera necessaire de mettre en oeuvre:

- deux approches de type “bag-of-words”, comptage simple de mots et Tf-idf ;
- une approche de type word/sentence embedding classique avec Word2Vec (ou Glove ou FastText) ;
- une approche de type word/sentence embedding avec BERT ;
- une approche de type word/sentence embedding avec USE (Universal Sentence Encoder).
Pour l'extraction des features images il sera necessaire de mettre en oeuvre:

- un algorithme de type SIFT / ORB / SURF.
- un algorithme de type CNN Transfer Learning.
- Concernant l’approche de type SIFT.
Mettre en oeuvre de :
- Mettre en œuvre des techniques de réduction de dimension.
- Représenter graphiquement des données à grandes dimensions.(LDA, ACP, TSNE...).
- une classification supervisée à partir des images .
- Définir la stratégie d’élaboration d’un modèle d'apprentissage profond, concevoir ou ré-utiliser des modèles pré-entraînés (transfer learning) et entraîner des modèles afin de réaliser une analyse prédictive.
- Utiliser des techniques d’augmentation des données afin d'améliorer la performance des modèles.
- Définir la stratégie de collecte de données en recensant les API disponibles, et réaliser la collecte des données répondant à des critères définis via une API (interface de programmation) en prenant en compte les normes RGPD, afin de les exploiter pour l’élaboration d’un modèle.
  ## Compétences évaluées:
  - Utiliser des techniques d’augmentation des données.
  - Prétraiter des données texte pour obtenir un jeu de données exploitable.
  - Représenter graphiquement des données à grandes dimensions.
  - Prétraiter des données image pour obtenir un jeu de données exploitable.
  - Mettre en œuvre des techniques de réduction de dimension.
  - Définir la stratégie de collecte de données en recensant les API disponibles.
  - Définir la stratégie d’élaboration d’un modèle d'apprentissage profond.
  - Évaluer la performance des modèles d’apprentissage profond selon différents critères.
  - 
