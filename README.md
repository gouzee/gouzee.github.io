# QCM Révisions

Petit projet web de révision sous forme de QCM, avec cours intégrés, historique des sessions et mini-jeu de détente.

## Description

Ce site permet de réviser deux cours :

- Développement Web
- Culture de la Création

L’utilisateur peut lire le cours complet, lancer un QCM, répondre aux questions, consulter son score final et revoir ses erreurs.  
Le site propose aussi un historique détaillé des sessions passées ainsi qu’un mini-jeu indépendant pour faire une pause.

## Fonctionnalités

### Révision et QCM

- Choix entre deux QCM :
  - Développement Web
  - Culture de la Création
- Accès au cours complet avant ou après le QCM
- Possibilité d’imprimer ou sauvegarder le cours en PDF
- Questions mélangées à chaque tentative
- Réponses mélangées à chaque tentative
- Affichage du score en direct pendant le QCM
- Affichage du score final à la fin du QCM
- Affichage du temps passé sur chaque QCM
- Affichage des erreurs à la fin du QCM
- Affichage de la réponse donnée en cas d’erreur
- Affichage de la bonne réponse attendue
- Message de confirmation avant de quitter un QCM en cours

### Historique des sessions

- Sauvegarde automatique des tentatives
- Historique séparé pour chaque cours
- Affichage du score, de la date, de l’heure et du temps passé
- Possibilité de cliquer sur une session passée pour consulter le récapitulatif détaillé
- Affichage des questions ratées dans l’historique
- Affichage de la réponse donnée et de la bonne réponse dans l’historique
- Suppression possible de tout l’historique
- Suppression possible uniquement de l’historique d’un cours

### Navigation

- Navigation interne entre le menu, les cours, les QCM, les résultats et le mini-jeu
- Compatibilité avec les boutons retour / avant du navigateur
- Pas de retour possible dans les questions du QCM avec les boutons du navigateur, pour éviter la triche
- Bouton flottant de retour en haut de page avec flèche centrée
- Bouton de retour en haut compatible avec la lecture du cours

### Mini-jeu

- Page indépendante avec un mini-jeu de type dinosaure Chrome
- Dinosaure en style pixel art
- Obstacles sous forme de buissons
- Oiseaux pouvant aussi faire perdre
- Score qui augmente quand les obstacles sont dépassés
- Meilleur score sauvegardé
- Contrôle au clavier avec Espace ou flèche haut
- Contrôle possible sur mobile avec un clic ou un tap

### Personnalisation

- Favicon personnalisé ajouté à partir d’une image
- Interface responsive pour une utilisation sur ordinateur et mobile

## Langages utilisés

- HTML
- CSS
- JavaScript

## Stockage des données

Le projet utilise le `localStorage` du navigateur pour sauvegarder :

- l’historique des tentatives
- les scores des sessions
- les erreurs et réponses données
- le temps passé sur chaque QCM
- le meilleur score du mini-jeu

Les données sont donc conservées dans le navigateur utilisé, mais ne sont pas envoyées sur un serveur.

## Comment utiliser le projet

1. Télécharger ou cloner le projet.
2. Ouvrir le fichier `index.html` dans un navigateur.
3. Choisir un cours pour réviser ou lancer directement un QCM.
4. À la fin du QCM, consulter le score, les erreurs et le temps passé.
5. Revenir plus tard dans l’historique pour revoir les anciennes sessions.

## Auteur

Projet réalisé dans le cadre d’un travail de révision.
