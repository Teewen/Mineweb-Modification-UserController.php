# Mineweb - Modification UserController.php
Modification apportées aux fonctions "Users" du fichier UserController.php

Lors de l'inscription ou de la modification du mot de passe, ce dernier doit être composé d'au moins 6 carractères.
Lors de l'inscription un skin et une cape par défaut (choisi par vos soin dans le répertoire app/webroot/textures/defaults/ - cape.png & skin.png) est créé au nom du joueur dans le répertoire textures.
Lors de la modification du pseudo, le skin et la cape par de l'utilisateur est renommé par le nouveau nom du joueur dans le répertoire textures.
Lors de la suppression d'un utilisateur, le skin et la cape de ce dernier sont aussi supprimés.
