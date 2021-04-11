# Publicis
Exercice technique


-  Scenario en Gherkin

US_Rechercher_google : Sur la page d’accueil Google L’utilisateur a la possibilité d’effectuer une recherche par mots clés 

Scénario :

Given un utilisateur entre un mot clé dans la barre de recherche Google
When il clique sur le bouton « Rechercher »
Then la page de résultats de recherche s’affiche

Règles de gestion :

Prérequis :
L’utilisateur doit être sur la page d’accueil Google (www.google.com)
La page doit comporter un champ rechercher et un bouton « rechercher » pour lancer la recherche


-  Implémentation des étapes

Critères d’acceptation :

Cas nominal

L’utilisateur accède à la page d’accueil www.google.com
Il clique dans le champ rechercher
Il tape le ou les mots clés (exemple : publicis sapient)
Il clique sur le bouton rechercher
