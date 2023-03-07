# FOAD Mardi 07/07/2023

## Instructions

### Git

- Faire un **fork** de ce dépôt ensuite **cloner** sur votre ordinateur et travailler dessus
- Entraîner vous à faire des **commits atomiques**
- Envoyer (**push**) votre travail sur votre **fork github** crée précédemment
- Cette étape est pas nécéssaire pour ceux qui m'ont déjà envoyé leur compte github : Envoyer moi par **email** votre **compte github** pour que je puisse voir votre travail

### Formulaire d'enregistrement

Vous allez créer un formulaire d'enregistrement pour la table sql `user` dans notre projet `movies`.

Créer ce formulaire et sa validation (récupérer tous les champs du formulaire pour les insérer dans la table sql `user`) dans un dossier `register` à la racine de `movies`.

Ce formulaire devra comprendre les champs :

- `pseudo` qui correspondra à la colonne `login` dans la table sql `user`
- `email`
- `password` ,vous devrez hasher ce mot de passe avec la fonction php [password_hash](https://www.php.net/manual/fr/function.password-hash.php)

Pour la colonne `created_at`  insérer la date et l’heure lors de la validation du formulaire.

Pour finir dans la page de ‘login` ne plus commenter les lignes sur le test sur le mot de passe.

Tester vos formulaires de ‘login’ et de ‘register’.

Pour toute question , merci de créer une issue.

