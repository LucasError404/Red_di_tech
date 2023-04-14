
# Notice d'utilisation de l'application Redtech

Redtech est une application mobile développée en React Native et disponible sur IOS et Android.
Cette application fonctionne avec l'API de Redit et a pour objectif d'afficher son fil d'actualité, son profil, faire ses recherches, et s'abonner ou se désabonner de subreddits. Elle intègre aussi la fonctionnalité réglage, permettant à chaque utilisateur connecté de modifier quelques paramètres de son compte, sans passer par l'application officielle.



## Installation

Après avoir téléchargé le projet sur votre ordinateur veuillez effectuer la commande ci dessous afin d'installer toutes les dependances du ```package.json``` :

```bash
  npm install red
  cd red
```
Pour démarrer le projet il faudra exécuter la commande suivante : 

```bash
  npm start
```
Étant donné que le projet s'éxecute sur Expo vous devrez installer l'application "Expo" disponible sur IOS et Android.

- Sur **Iphone** ouvrez votre caméra et scannez le QR code qui est affiché dans votre terminal, cela va vous rediriger dans l'application "Expo" et ouvrir le projet.

- Sur **Android** ouvrez l'application "Expo" puis flashez le QR code, cela va vous ouvrir le projet.

Pour mettre à l'arrêt le serveur "Expo" veuillez appuyer sur les touches suivantes ```Ctrl + c```.



## Demo

Une fois l'application démarrée avec "expo" vous arriverez sur la page ci-dessous, vous aurez trois choix qui s'offrerons à vous.    

- "Se connecter avec Reddit", permet de vous connecter à l'application en utilisant votre compte Reddit.

- "Créer un compte Reddit", vous redirigera vers la page officielle de Reddit permettant de créer un compte.

- "A propos de Reddit", vous redirigera vers la page officielle de Reddit concernant le "A propos".
 
![App Screenshot](https://i.ibb.co/nc0x8Gg/Page-Connexion-3.png)   

**PAGE DE CONNECTION**  
Une fois que vous aurez appuyé sur le bouton "Se connecter avec Reddit" vous serez redirigé vers la page ci-dessous, qui vous demandera de vous connecter avec votre compte Reddit et l'autorisation pour l'application Redtech d'accéder à vos informations de compte (l'application n'aura jamais accès à vos informations confidentielles).

![App Screenshot](https://i.ibb.co/Qb61Hqq/Acces-Token.png) 

**PAGE D'ACCUEIL**   
Une fois connecté vous accéderez à la page ci-dessous qui est votre fil d'actualité Reddit, vous y trouverez les dernières publications de vos abonnements avec la possibilité de filtrer les publications par "pertinence", "nouveauté", et "Meilleur".  

En bas vous retrouverez le menu qui permet d'accéder à votre profil ou de revenir au menu de l'application.  
  
Au-dessus à droite de la page "accueil" il y a trois icônes, celui de droite permet de se déconnecter de l'application et donc de revenir à la page de connexion, celui du milieu, permet d'accéder à la page de réglages de votre compte, et celui de gauche vous dirigera vers la page de recherche.

![App Screenshot](https://i.ibb.co/GMWmppd/Accueil-New.png)

**PAGE DE REGLAGES**   
La page de Réglages est composée de plusieurs réglages de comptes, vous pourrez y changer le code de votre pays, entre la Grande-Bretagne, l'Allemagne, ou la France. Mais vous pourrez aussi autoriser ou interdire le contenu réservé aux adultes, masquer les votes négatifs, inclure la restriction pour adultes dans ma recherche, afficher le statut de présence en ligne, ou apparaitre ou non dans les résultats de recherche.    

En bas de la page vous trouverz un bouton "Mettre à jour", qui mettra toutes vos modifications à jour.

![App Screenshot](https://i.ibb.co/HzZgdWj/R-glages-1.png)  
  
**PAGE DE RECHERCHE**   
La page de recherche est composée d'une barre de recherche en haut de la page permettant de rechercher des subreddits.  
Une fois votre recherche effectuée vous verrez une liste de subreddits qui correspondent votre recherche. Sur chaque subreddit, vous trouverez un bouton permettant de vous y abonner ou vous y désabonner.   
Si vous appuyez sur un subreddit, l'application vous affichera alors toutes les publications du subreddit en question avec la possibilité de filtrer l'affichage.

| Recherche de subreddit | publications des subreddit |
| --- | --- |
| ![App Screenshot 1](https://i.ibb.co/d2Cf6px/Recherche-2.png) | ![App Screenshot 2](https://i.ibb.co/smWcXLb/Recherche-Sub-2.png) |
  
**PAGE DE PROFIL**  
La page de profil à droite dans le menu vous affichera votre profil Reddit, vous y trouverez en haut de la page votre bannière, photo de profil, description, nombre d'abonnés, nombre de karma et date de création de compte.    

Sur la partie basse de la page vous y trouverez toutes les publications que vous avez publiées. 

![App Screenshot 1](https://i.ibb.co/KyyJYWv/Profil-2.png)







## Informations complémentaires

***Ce projet à été réalisé par Lucas Brunner et David Bui dans le cadre de la formation MSc by EPITECH.***


## Diagrammes

![App Screenshot](https://i.ibb.co/6gCgDyM/Diagramme-sans-nom-drawio-3.png)


![App Screenshot](https://i.ibb.co/FmdC6b5/Diagramme-sans-nom-drawio-2.png)
