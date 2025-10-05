# Projet PointNet – Classification de nuages de points 3D  

## Objectif  
Dans ce projet, nous avons exploré l’implémentation et l’évaluation du réseau de neurones **PointNet** pour la classification de nuages de points 3D.  
Introduit par *Qi et al.* en 2017, PointNet est une architecture novatrice qui traite directement les nuages de points sans nécessiter leur conversion en grilles de voxels ou en images, évitant ainsi une augmentation exponentielle des besoins en mémoire.  

L’objectif principal était de concevoir des modèles performants capables de classifier des objets 3D à l’aide des ensembles de données **ModelNet10** et **ModelNet40**.  

## Méthodologie  
- Implémentation d’une version de base de **PointNet**.  
- Intégration d’un module **T-Net** pour améliorer l’alignement des points dans l’espace tridimensionnel.  
- Étude de l’impact de différentes stratégies d’**augmentation des données** sur la précision du modèle.  

##  Résultats  
En combinant l’utilisation complète des matrices **T-Net** et des techniques d’augmentation adaptées, nous avons atteint une **précision de 87 %** sur l’ensemble de test.  
Ces résultats démontrent l’efficacité et la robustesse de cette approche pour des tâches de classification 3D complexes.  

## Outils et bibliothèques  
- Python  
- PyTorch / TensorFlow  
- NumPy  
- ModelNet10 & ModelNet40 datasets  

