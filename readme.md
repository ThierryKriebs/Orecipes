# ORecipes
ORecipes est un projet pédagogique dont le but est de créer une SPA React de visualisation de recettes de cuisine. 
L'application va contacter une API REST afin de récupérer les différentes recettes. 
Ce site permet de se connecter pour afficher ses recettes préférées, ou de cliquer sur l'une d'entre elles pour en consulter ses détails. 
Il permet également de gérer une liste d'ingrédients.

## Page d'accueil:
![Présentation](/public/images/captures/1_Accueil.png)

  

## Technologies utilisées:
Ce site a été développé en typescript et React. La configuration a été faite avec le bundle Vite. 
Il a été conçu pour être déployé sur Surge directement avec une github_action (voir branche git dédiée).

## Installation:
- Créer un fichier .env et y indique l'URL de l'API (voir fichier .env.example)
- Exécuter la commande suivante: `pnpm install`
- Enfin, démarrer le serveur web à l'aide de la commande `pnpm dev`

