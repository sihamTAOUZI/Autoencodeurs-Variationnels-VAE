# Autoencodeurs-Variationnels-VAE
Ce projet explore l’apprentissage non supervisé au moyen d’autoencodeurs convolutionnels et de Variational Autoencoders (VAE) appliqués au dataset MNIST.
L’objectif est de comprendre comment ces modèles apprennent une représentation latente des chiffres manuscrits et comment ils peuvent être utilisés pour :

*reconstruire des images,

*analyser la structure de l’espace latent,

*générer de nouveaux chiffres.

*contenu du projet:

Autoencodeur convolutionnel (AE)

Reconstruction d’images MNIST

Visualisation de l’espace latent via t-SNE

Génération depuis un latent aléatoire

Variational Autoencoder (VAE)

Architecture convolutionnelle

Fonction de perte (MSE + KL divergence)

Reconstruction améliorée

Génération d’images à partir d’un latent gaussien

Visualisation du latent space (t-SNE + sampling)

📂 Structure
├── AE/                # Autoencodeur classique
├── VAE/               # Variational Autoencoder
├── images/            # Visualisations générées
├── README.md
└── requirements.txt

🛠️ Technologies utilisées

Python

PyTorch

NumPy / Matplotlib

Scikit-learn (t-SNE)

MNIST dataset

📈 Résultats

L’AE reconstruit correctement les chiffres mais son espace latent est discontinu.

Le VAE impose une structure gaussienne plus régulière, permettant une meilleure génération.

Des améliorations restent possibles (β-VAE, latent plus grand, réseau plus profond).

📌 Améliorations possibles

β-VAE pour mieux contrôler la régularisation KL

Augmentation de la dimension latente

Ajout de convolutions résiduelles

Entraînement sur d’autres datasets (FashionMNIST, CIFAR)
