# Rapport pour la Création de notre site de Calculateurs Médicaux

## Introduction

Le projet consiste à créer un site web permettant aux utilisateurs de réaliser différents calculs médicaux. Nous allons proposer trois calculateurs : l'IMC (Indice de Masse Corporelle), la dose de médicament et la surface corporelle. Chaque calculateur comportera des champs d'entrée dynamiques et affichera instantanément les résultats. Ce rapport décrira les étapes de réflexion et de développement, tout en expliquant chaque aspect du code et les données utilisées.

## 1. Maquette du Site Web

Voici la maquette avec l'idée générale de la mise en page de la page d'accueil qui contient les calculateurs :

- **Header** : Titre du site et menu de navigation.
- **Section IMC** : Entrées pour la taille et la masse, et affichage du résultat.
- **Section Dose de Médicament** : Entrées pour le poids et la dose recommandée, et affichage du résultat.
- **Section Surface Corporelle** : Entrées pour la taille et le poids, et affichage du résultat.
- **Footer** : Informations de copyright et liens vers les sources.

## 2. Conception de la Structure HTML (`accueil.html`)

Il faut maintenant créer la page principale de notre site. Si on suit les consigne, le code HTML est bien structuré et commenté. La page inclut un en-tête contenant le titre du site et un menu de navigation. Chaque section dédiée à un calculateur comprend des champs d’entrée, des labels correspondants et une zone pour afficher le résultat. Il y a aussi des liens vers un fichier CSS pour le style et un fichier JavaScript pour rendre le site plus dynamique.

## 3. Fichier CSS (`style.css`)

Pour rendre l'interface plus agréable on utilise le CSS. Cela inclut en général une typographie soignée, des marges, et des couleurs de fond harmonieuses. L'en-tête aura un fond coloré avec du texte en blanc pour le rendre visible, et la navigation sera fluide et structurée. Les champs de formulaires seront également stylisés pour permettre une interactivité facile pour l'utilisateur.

## 4. Fichier JavaScript (`script.js`)

Enfin, nous allons créer le fichier JavaScript pour rendre notre site interactif. Ce script comportera plusieurs fonctions :

1. **`calculIMC()`** : Cette fonction calcule l'IMC en utilisant la formule classique (masse / taille²) et catégorise le résultat en fonction des recommandations de santé.
   
2. **`calculDose()`** : Elle multiplie le poids par la dose médicament recommandée pour calculer la dose totale.
   
3. **`calculSurface()`** : Calculera la surface corporelle à l'aide de la formule de Du Bois en s'assurant que toutes les entrées sont valides avant de procéder.

Chaque fonction comprend des vérifications pour garantir que les entrées de l'utilisateur sont valides afin d'afficher des résultats significatifs et d'éviter les erreurs.

## 5. Conclusion

Ce projet a permis de mettre en pratique les connaissances du cours en HTML, CSS et JavaScript tout en créant un site utile. Chaque étape a été pensée pour assurer une bonne structure, un design agréable et des fonctionnalités basiques mais essentielles.

### Sources des Données Utilisées

- L’IMC et ses catégories sont basés sur les recommandations de l'Organisation Mondiale de la Santé (OMS).
- La formule de surface corporelle de Du Bois (trouvée sur internet).

### Et la suite ?

À l'avenir, il serait intéressant d'ajouter des fonctionnalités supplémentaires comme des graphiques, des conseils santé ou des articles sur la nutrition et le bien-être en général.
