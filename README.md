# MLP-training-Pytorch-

Dans ce projet, nous voulons analyser les représentations intermédiaires (=sortie des couches cachées=embeddings) produites par un réseau de neurones.

Ce réseau de neurones est un réseau profond qui, à partir d'un signal de parole, transcrit les mots prononcés et détecte des concepts sémantiques. Ces concepts sont liés à une application informatique de réservation d'hôtel par dialogue téléphonique humain machine. Plus de détails dans l'article scientifique associé à cet énoncé (et dans les explications de l'enseignant).

Nous souhaitons analyser les représentations intermédiaires des 5 couches cachées  du réseau et comparer l'encodage de ces représentations selon les couches.

Pour cela, veuillez procéder aux actions suivantes :

1. Visualiser (et faite une capture d'écran) des embeddings de chacune des couches cachées calculées sur le corpus de développement (= corpus de validation téléchargeable ici). Pour cela, vous convertirez les fichiers au format tsv et les uploaderez dans la page http://projector.tensorflow.org 

2. Pour chacune des couches cachées, vous entraînerez un MLP simple à une couche cachée en utilisant le corpus d'apprentissage et le corpus de développement (pour early stopping) de la couche considérée. Ce MLP devra apprendre à trouver le concept sémantique visé à partir de l'embedding. Vous appliquerez alors ce MLP sur le corpus de test de cette couche et évaluerez ses performances.
