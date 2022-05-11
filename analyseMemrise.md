# Exo -BDD - Analyse Merise

Le but de cet exercice est de maîtriser l'analyse de la création d'une base de données (BDD).

## Cahier des charges

Vous devez créer un dictionnaire des données et un MCD qui correspond aux besoins indiqués ci-dessous.

## Livrables

La dictionnaire des données et le MCD doivent être livrées sous la forme d'un repository git en ligne sur un site comme github, gitlab ou autre.

Le repository doit contenir les fichiers suivants :

- un fichier tableur (`.xls`, `.ods` ou `.csv`) contenant le dictionnaire de données
- un fichier image (`.jpg`, `.png`) contenant le MCD

Pour créer le dictionnaire, vous pouvez utiliser à votre guise Libre Office Calc, Microsoft Office Excel, Google Sheet (export au format `.csv`).

Pour créer le MCD, vous pouvez utiliser à votre guise un crayon et du papier, un outil de dessin (comme [Excalidraw](https://excalidraw.com/)) ou un outil de modélisation.

## Prérequis

Aucun à part un cerveau.

## Besoins

Un client souhaite créer une application de gestion de tâches.

Le client souhaite les fonctionnalités suivantes :

- créer des comptes utilisateurs avec un email et un mot de passe
- créer des tâches avec un titre, une date limite, un statut (réalisé, non) et un responsable
- créer des catégories
- associer une tâche à une catégorie
- créer des tags
- associer une tâche à des tags
- archiver des tâches (c-à-d faire un soft delete)
