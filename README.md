# BD_blog

BASE DE DONNEES D'UN BLOG

Nous nous attelons à créer une base de données d'un blog.
I - CAHIER DES CHARGES
Le but de ce TP est de créer la base de données d'un blog avec les tables essentielles.
Comme dans le fonctionnement d'un blog, le gloggeur fera des posts (billets) et chaque billets possedera ses propre comentaires, les commentaires seront fais par les utilisateurs ou le bloggeur lui même. Il faut aussi noter que les billets sont émis selon une catégorie bien definie.

II - STRUCTURES DES TABLES
De ce qui précède nous pouvons faire ressortir les tables suivantes
*Admin: elle contiendra les données sur l'administrateur du blog
*utilisateurs: stock les informations des utilisateurs et du bloggeur
*catégorie: contient toutes les catégories auxquelles se référeront les billets
*billets: liste des billets du blog
*commentaires:  liste des commentaires du blog pour chaque billet 

Structure de tables proposée:
Admin:
id_admin
nom
password
email

Utilisateurs:
id_user
nom
prenom
password
email

Categories:
id_cat
nom_cat

billets:
id
titre
contenu
date
id_auteur
id_catégorie

Commentaires:
id_com
contenu
date
id_auteur
id_billet
