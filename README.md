# **Couches_CNN**  
## **Présentation**  
**Couches_CNN** est un projet pédagogique destiné à apprendre, comprendre et implémenter les principales couches d'un réseau de neurones convolutionnel (CNN) en Python.  
L'objectif n'est pas simplement d'utiliser des bibliothèques comme TensorFlow ou PyTorch, mais de comprendre les mécanismes internes qui permettent à un CNN d'analyser et de reconnaître des images.  
Chaque couche est développée progressivement à travers des explications théoriques, des visualisations, des exercices pratiques et des implémentations Python. Le projet permet ainsi de passer d'une compréhension intuitive du deep learning à une compréhension technique approfondie des architectures modernes de vision par ordinateur.  
# **Objectifs pédagogiques**  
À la fin du parcours, l'apprenant sera capable de :  
- Comprendre le fonctionnement d'un réseau de neurones convolutionnel.  
- Manipuler des images sous forme de tenseurs.  
- Implémenter les principales couches d'un CNN.  
- Comprendre la propagation avant (Forward Propagation).  
- Comprendre la rétropropagation (Backpropagation).  
- Comprendre le calcul des gradients.  
- Construire un CNN complet à partir de zéro.  
- Comprendre les bases des architectures modernes de vision par ordinateur.  
# **Structure pédagogique**  
Le projet est organisé en modules indépendants permettant d'apprendre chaque composant séparément avant de les assembler dans un réseau complet.  
## **Module 1 : Représentation des images**  
### **Concepts étudiés**  
- Pixels  
- Images en niveaux de gris  
- Images RGB  
- Matrices  
- Tenseurs  
- Dimensions (Height, Width, Channels)  
### **Exercices**  
- Charger une image.  
- Convertir en matrice.  
- Afficher les canaux RGB.  
- Manipuler les pixels.  
## **Module 2 : Couche de Convolution (Convolution Layer)**  
### **Concepts étudiés**  
- Noyaux (Kernels)  
- Filtres  
- Fenêtre glissante  
- Stride  
- Padding  
### **Compétences acquises**  
- Détection de contours  
- Détection de textures  
- Extraction de caractéristiques  
### **Exercices**  
- Implémenter une convolution 2D.  
- Créer différents filtres.  
- Observer l'effet des kernels.  
### **Implémentation**  
Conv2D  
   
Fonctionnalités :  
- Forward  
- Backward  
- Calcul des gradients  
## **Module 3 : Fonction d'Activation ReLU**  
### **Concepts étudiés**  
- Non-linéarité  
- Saturation  
- Vanishing Gradient  
### **Fonctions abordées**  
- ReLU  
- Leaky ReLU  
- Sigmoid  
- Tanh  
### **Exercices**  
- Visualisation graphique.  
- Comparaison des activations.  
### **Implémentation**  
ReLU  
LeakyReLU  
Sigmoid  
Tanh  
   
## **Module 4 : Couche de Pooling**  
### **Concepts étudiés**  
- Réduction de dimension  
- Conservation des caractéristiques importantes  
### **Types**  
- Max Pooling  
- Average Pooling  
### **Exercices**  
- Implémentation manuelle.  
- Visualisation avant/après pooling.  
### **Implémentation**  
MaxPool2D  
AveragePool2D  
   
## **Module 5 : Batch Normalization**  
### **Concepts étudiés**  
- Normalisation  
- Stabilisation de l'entraînement  
- Internal Covariate Shift  
### **Exercices**  
- Calcul de moyenne et variance.  
- Implémentation complète.  
### **Implémentation**  
BatchNorm  
   
## **Module 6 : Dropout**  
### **Concepts étudiés**  
- Overfitting  
- Régularisation  
### **Exercices**  
- Désactivation aléatoire de neurones.  
- Comparaison avec et sans Dropout.  
### **Implémentation**  
Dropout  
   
## **Module 7 : Flatten Layer**  
### **Concepts étudiés**  
- Passage des cartes de caractéristiques vers les couches denses.  
### **Exercices**  
- Transformation tenseur → vecteur.  
### **Implémentation**  
Flatten  
   
## **Module 8 : Couche Dense (Fully Connected)**  
### **Concepts étudiés**  
- Poids  
- Biais  
- Produits matriciels  
### **Exercices**  
- Construction d'un perceptron multicouche.  
### **Implémentation**  
Linear  
Dense  
   
## **Module 9 : Fonction de Perte (Loss Functions)**  
### **Concepts étudiés**  
- Évaluation des prédictions  
### **Fonctions étudiées**  
- MSE  
- Cross Entropy  
- Binary Cross Entropy  
### **Implémentation**  
MSELoss  
CrossEntropyLoss  
BCELoss  
   
## **Module 10 : Optimisation**  
### **Concepts étudiés**  
- Descente de gradient  
- Mise à jour des poids  
### **Optimiseurs**  
- SGD  
- Momentum  
- RMSProp  
- Adam  
### **Implémentation**  
SGD  
Adam  
RMSProp  
   
## **Module 11 : Backpropagation**  
### **Concepts étudiés**  
- Règle de la chaîne  
- Calcul des gradients  
### **Exercices**  
- Dérivation étape par étape.  
- Visualisation des gradients.  
### **Implémentation**  
- Backpropagation complète sur toutes les couches.  
## **Module 12 : Construction d'un CNN complet**  
### **Architecture exemple**  
Input  
↓  
Conv2D  
↓  
ReLU  
↓  
MaxPool  
↓  
Conv2D  
↓  
ReLU  
↓  
MaxPool  
↓  
Flatten  
↓  
Dense  
↓  
ReLU  
↓  
Dense  
↓  
Softmax  
### **Objectif**  
Créer un réseau complet capable de classifier des images.  
# **Projets pratiques**  
## **Classification de chiffres manuscrits**  
Dataset :  
- MNIST  
Objectif :  
Reconnaître automatiquement les chiffres de 0 à 9.  
## **Classification d'objets**  
Datasets :  
- CIFAR-10  
- CIFAR-100  
Objectif :  
Reconnaître plusieurs catégories d'objets.  
## **Détection de panneaux routiers**  
Dataset :  
- GTSRB  
Objectif :  
Préparer les bases nécessaires à la vision d'une voiture autonome.  
# **Fonctionnalités du projet**  
- Interface pédagogique interactive.  
- Visualisation des tenseurs.  
- Visualisation des kernels.  
- Visualisation des cartes de caractéristiques.  
- Exercices guidés.  
- Défis pratiques.  
- Quiz de validation.  
- Implémentation complète en Python.  
- Comparaison avec TensorFlow et PyTorch.  
- Progression du niveau débutant à avancé.  
# **Technologies utilisées**  
- Python  
- NumPy  
- Matplotlib  
- OpenCV  
- PyQt5  
- TensorFlow (comparaison)  
- PyTorch (comparaison)  
# **Public cible**  
- Étudiants en intelligence artificielle  
- Développeurs Python  
- Débutants en Deep Learning  
- Passionnés de Vision par Ordinateur  
- Futurs ingénieurs en IA  
- Apprenants souhaitant comprendre les CNN en profondeur  
# **Résultat attendu**  
À l'issue du projet, l'apprenant sera capable de construire un réseau de neurones convolutionnel complet, comprendre son fonctionnement interne, implémenter les principales couches sans dépendre d'une bibliothèque de haut niveau et disposer de bases solides pour étudier des architectures avancées telles que ResNet, YOLO, U-Net, EfficientNet ou Vision Transformer.  
   
