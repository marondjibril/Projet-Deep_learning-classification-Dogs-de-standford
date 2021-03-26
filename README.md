# Projet-Deep_learning-classification-Dogs-de-standford
Projet : Image classification à l’aide du Deep Learning  
Projet : Image classification à l’aide du Deep Learning


Mise en situation

Vous êtes bénévole pour l'association de protection des animaux de votre quartier. C'est d'ailleurs ainsi que vous avez trouvé votre compagnon idéal, Snooky. Vous vous demandez donc ce que vous pouvez faire en retour pour aider l'association.
 
Votre première rencontre avec Snooky

Vous apprenez, en discutant avec un bénévole, que leur base de données de pensionnaires commence à s'agrandir et qu'ils n'ont pas toujours le temps de référencer les images des animaux qu'ils ont accumulées depuis plusieurs années. Ils aimeraient donc obtenir un algorithme capable de classer les images en fonction de la race du chien présent sur l'image.
Les données

Les bénévoles de l'association n'ont pas eu le temps de réunir les différentes images des pensionnaires dispersées sur leurs disques durs. Pas de problème, vous entraînerez votre algorithme en utilisant le Stanford Dogs Dataset.

Vos missions

L'association vous demande de réaliser un algorithme de détection de la race du chien sur une photo, afin d'accélérer leur travail d’indexation.
Vous avez peu d’expérience sur le sujet, vous décidez donc de contacter un ami expert en classification d’images.
Il vous conseille dans un premier temps de pré-processer des images avec des techniques spécifiques (e.g. éventuellement modification de la taille des images, cropping, ) et de réaliser de la data augmentation (mirroring, cropping...).
Ensuite, il vous incite à mettre en œuvre deux approches que vous comparerez en termes de temps de traitement et de résultat :
1.	Une première en réalisant votre propre réseau CNN, en vous inspirant de réseaux CNN existants. Prenez soin d'optimiser certains hyperparamètres (des layers du modèle, de la compilation du modèle et de l’exécution du modèle)
2.	Une deuxième en utilisant le transfer learning, c’est-à-dire en utilisant un réseau déjà entraîné, et en le modifiant pour répondre à votre problème.
Concernant le transfer learning, votre ami vous précise que :

•	Une première chose obligatoire est de réentraîner les dernières couches pour prédire les classes qui vous intéressent seulement.
•	Il est également possible d’adapter la structure (supprimer certaines couches, par exemple) ou de réentraîner le modèle avec un très faible learning rate pour ajuster les poids à votre problème (plus long) et optimiser les performances.

Livrables attendus

Un repo Github contenant :
●	Un notebook Python (non cleané, pour comprendre votre démarche).
●	Un programme Python qui prend une image (array) en entrée et retourne la race la plus probable du chien présent sur l'image.
●	Votre support de présentation à destination du bénévole qui gère la base de données, qui devra déployer en production la solution que vous préconisez.

Modalités de présentation du travail

Votre présentation pourra prendre cette forme (à titre indicatif) : 
5 min.	Présentation de la problématique, du cleaning effectué, du feature engineering et de l'exploration
10 min	Présentation des différentes pistes de modélisation effectuées
10 min	Présentation du modèle final sélectionné (pour chaque approche) ainsi que des performances et améliorations effectuées
10 min	Séance de questions-réponses

Ressources complémentaires

●	Guide d’utilisation de Google Colaboratory avec TPU.
●	Ce tutoriel présente les concepts de data augmentation. À vous de voir si cela peut améliorer vos performances sur ce projet !
●	Une présentation du transfer learning, ses avantages, les cas d’application et un exemple de code en Keras. 

Compétences data à valider

•	Mettre en place un modèle de Deep Learning
•	Se familiariser avec les réseaux de neurones profonds
•	Sélectionner un modèle adapté à une problématique métier
•	Adapter les paramètres du modèle afin de l’améliorer
•	Transformer les variables pertinentes d'un modèle
•	Évaluer les performances du modèle 
