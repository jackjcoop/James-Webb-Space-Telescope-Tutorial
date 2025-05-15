<p align="center">
   <img src="https://www.asc-csa.gc.ca/images/recherche/tiles/16f69078-962d-443c-874c-e4003fe173c8.jpg" alt="James Webb" height=300> 
   <br> Crédit d'image | Image credit: <a href=https://www.asc-csa.gc.ca/images/recherche/tiles/16f69078-962d-443c-874c-e4003fe173c8.jpgk>ASC-CSA</a>
</p>

<p align="center">
 <a href="#stars">
  <img alt="Étoiles sur GitHub | GitHub Repo stars" src="https://img.shields.io/github/stars/asc-csa/James-Webb-Space-Telescope-Tutorial">
 </a>
 <a href="#watchers">
  <img alt="Spectateurs sur Github | GitHub watchers" src="https://img.shields.io/github/watchers/asc-csa/James-Webb-Space-Telescope-Tutorial">
 </a>
 <a href="https://github.com/asc-csa/James-Webb-Space-Telescope-Tutorial/commits/main">
  <img alt="Dernier commit sur GitHub | GitHub last commit" src="https://img.shields.io/github/last-commit/asc-csa/James-Webb-Space-Telescope-Tutorial">
 </a>
 <a href="https://github.com/asc-csa/James-Webb-Space-Telescope-Tutorial/graphs/contributors">
  <img alt="Contributeurs sur GitHub | GitHub contributors" src="https://img.shields.io/github/contributors/asc-csa/James-Webb-Space-Telescope-Tutorial">
 </a>
 <a href="https://twitter.com/intent/follow?screen_name=csa_asc">
  <img alt="Suivre sur Twitter | Twitter Follow" src="https://img.shields.io/twitter/follow/csa_asc?style=social">
 </a>
</p>

<h2 align="center">
  <a href="#titre-du-projet">Français</a> |
  <a href="#project-title">English (follows)</a>
</h2>

<a id="titre-du-projet"></a>
# Extraction et analyse des images du télescope spatial James Webb - Un tutoriel

> **Description brève :**
> Ce tutoriel vise à rendre les données du télescope spatial James Webb (JWST) plus accessibles en montrant comment y accéder, les extraire et les utiliser pour compter des galaxies à partir d’images.
> 
---

## À propos
L’objectif principal de ce tutoriel est de faire connaître les données du télescope spatial James Webb (JWST) et d’améliorer son accessibilité. Ce tutoriel doit permettre aux utilisateurs d’accéder aux données JWST et de les extraire. Pour illustrer les applications potentielles de ces données, ce tutoriel guide les utilisateurs dans le comptage du nombre de galaxies à partir des images JWST. 

Veuillez noter que ce tutoriel est strictement expérimental et que les étapes de traitement sont fournies pour démontrer comment manipuler les données en Python. 

## Démarrage rapide
📥 **Installer les dépendances**
   ```bash
   pip install -r requirements.txt
   ```

## Fonctionnalités
JWST_Jupyter_Tutorial.ipynb guidera l’utilisateur sur les étapes de téléchargement et d’extraction des données JWST.

Ensuite, le didacticiel montrera comment ouvrir les données et les enregistrer en tant qu’image pour d’autres utilisations.

La dernière étape consiste à créer un filtre qui examine tous les points lumineux de l’image.
 - Ce filtre expérimental peut être ajusté par l’utilisateur pour modifier le seuil de luminosité ainsi que le nombre de pixels à proximité requis.
 - Tous les pixels qui ne répondent pas aux critères de filtre seront virés au noir.
 - Le reste sera documenté et encerclé, présentant à l’utilisateur une estimation du nombre de galaxies dans l’image.

## Licence

Ce projet est  sous une licence MIT modifiée – voir le fichier [LICENSE](https://github.com/asc-csa/James-Webb-Space-Telescope-Tutorial/blob/main/LICENSE.txt) pour plus de détails.

---

<h2 align="center">
  <a href="#project-title">English </a> |
  <a href="#titre-du-projet">Français (précède)</a>
</h2>

<!-- ============ English ============ 
An engaging title for the project (required)-->
<a id="project-title"></a>
# Extracting and analysis of the James Webb Space Telescope images - A tutorial 

<!-- A short summary phrase for the project (required)-->
> **Brief description:**
> This tutorial aims to make James Webb Space Telescope (JWST) data more accessible by showing how to access, extract, and use the data to count galaxies from images.

---


# About
The primary aim of this tutorial is to raise awareness about the James Webb Space Telescope (JWST) data and enhance its accessibility. This tutorial shall equip the users to access and extarct JWST data. To illustrate the potential applications of this data, this tutorial guide the users in counting the number of galaxies from the JWST images. 

Please note that this tutorial is purely experimental, and processing steps are supplied to demonstrate how to manipulate the data in Python. 
## Quick Start

 📥 **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
 
## Features 
JWST_Jupyter_Tutorial.ipynb will guide the user on the steps to downloading and extracting the JWST data.

Next, the tutorial will demonstrate how to open the data and save it as an image for further uses.

The last step involves creating a filter that looks at all the brightspots in the image. 
- This experimental filter can be adjusted by the user to change the brightness threshold along with the number of nearby pixels required. 
- Any pixels that do not meet the filter criteria will be turned to black.
- The remaining will be documented and circled, presenting the user with an estimate of the number of galaxies in the image.
  
## License

This project is licensed under a modified MIT license - see the [LICENSE](https://github.com/asc-csa/James-Webb-Space-Telescope-Tutorial/blob/main/LICENSE.txt) file for details.


