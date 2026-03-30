# Projet-Wakdo-Samba-FOFANAWakdo – Borne de commande & Back-office
Présentation Projet
Le projet a été réalisé dans le cadre de l'obtention de la certification RNCP 37805 – Développeur Web.
Il consistera à concevoir une solution de digitalisation d'un fast-food (Wakdo), inspiré du fonctionnement des bornes de commande modernes.
L’application permettra aux clients de passer commande en toute autonomie sur une borne tactile et récupérer celle ci au comptoir grâce à un numéro unique.
Le projet comprend un back-office aidant l'équipe à gérer les produits, le menu et les commandes.
Architecture du projet
Le projet est réalisé en 3 Blocs principales :
Front borne (Bloc 1) : interface client avec utilisation HTML, CSS, JavaScript
Back-office & API (Bloc 2) : gestion des données avec utilisation Node.js, Express, MySQL
Application React (Bloc 3) : recherche de restaurants sur carte avec utilisation React + Vite
Fonctionnalités principales :
Borne de commande :
Parcours utilisateur simple et intuitif
Navigation par catégories (menus, burgers, boissons, desserts…)
Composition de menus (burger + accompagnement + boisson + sauce)
Personnalisation des produits
Gestion du panier en temps réel
Validation de la commande avec un numéro
Back-office :
Authentification des utilisateurs
Gestion des rôles (administration, préparation, accueil)
Gestion des produits et menus
Suivi des commandes
Mise à jour des statuts (en préparation, prêt, livré)
 API :
Récupération des produits et menus
Envoi des commandes (POST /api/orders)
Communication entre le front et le back
Application React :
Recherche de ville
Affichage sur carte (react-leaflet)
Sélection d’un restaurant
Interaction utilisateur dynamique
Base de données :
Une base de données MySQL a été mise en place pour gérer :
les utilisateurs
les produits
les menus
les commandes
Initialisation via :
schema.sql
seed.sql
Sécurité
Le projet inclut :
authentification des utilisateurs
gestion des rôles et permissions
validation des données côté serveur
protection des routes API
