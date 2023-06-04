# RAJA – Extraction de données par web scraping

Ce programme permet de collecter automatiquement les données des sites ci-dessous :

- Sites :
	- www.manutan.fr
	- www.bruneau.fr
	- www.jpg.fr
	- www.raja.fr
	- www.bernard.fr

- Données collectées :
	- Descriptif du produit
	- Référence
	- Prix (en euros)

Les données sont collectées via Google Chrome en utilisant les packages Python (Selenium et Beautiful Soup) de web scraping.
Elles sont extraites au format Excel (.xlsx).

## Installation

Suivre les étapes ci-dessous pour installer le programme sous Windows.

### Installer Python

- Télécharger Python sur le site officiel : https://www.python.org/downloads/
- Installer Python :
	- Décocher 'Use admin privileges when installing py.exe'
	- Cocher 'Add python.exe to PATH'

### Installer les packages Python (uniquement à la première utilisation)

Pour que le programme s’exécute, certains packages Python doivent préalablement être installés.
Pour ce faire, double-cliquer sur le fichier 'install_requirements.bat'.
- Une fenêtre d’invite commande s’ouvre et télécharge automatiquement les packages
- Attendre que l’instruction « Appuyez sur une touche pour continuer » s’affiche, puis appuyer sur n’importe quelle touche pour quitter
Cette étape n’est nécessaire qu’à la première utilisation uniquement.

### Installer Google Chrome

Télécharger et installer Google Chrome :
https://www.google.com/chrome/?brand=YTUH&gclid=CjwKCAjwo7iiBhAEEiwAsIxQEQU8U0-rcfGsmMoe_i2WYBxOonW4akXg8AYq2d5x5Vyq_ftOWL49sBoCDJUQAvD_BwE&gclsrc=aw.ds

## Sélectionner les paramètres

Dans le fichier "params.xlsx" :
- Dans l'onglet "marques", ajouter/supprimer/modifier les marques souhaitées
- Dans l'onglet "dossier_destination", renseigner le dossier de destination de l'extraction excel des données

## Lancer le programme

Pour lancer l’application d’extraction des données, double-cliquer sur le fichier « launch_app.bat ».
- Une fenêtre d’invite de commande s’ouvre et affiche les sites et marques au fur et à mesure de l’extraction des données
- Un pop-up s’affichera lorsque l’extraction sera terminée
- L’extraction complète dure une vingtaine de minutes (variable sur les postes)