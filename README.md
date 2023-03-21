# MisterCocktails
Un site de recettes de cocktails personnalisable

Site réalisé en PHP où l'on peut visualiser différentes recettes de cocktails ainsi que s'autentifier, les utilisateurs peuvent ajouter des recettes.
Il y a aussi un espace administrateur pour visualiser les principales informations du site et pour modifier et/ou supprimer des recettes ou ingrédients.

L'index.php initialise la session ainsi que le rooter. Le rooter récupère l'élément 'page' de la variable $_GET et les données du form si besoin. Ces informations sont envoyées vers un controller, celui-ci va vérifier les données du formulaire,  vérifier que l'utilisateur est bien connecté (simple utilisateur ou admin ?) / déconnecté puis redirige vers la page demandée

Layout.php est le template de base utilisé par les différentes views.
