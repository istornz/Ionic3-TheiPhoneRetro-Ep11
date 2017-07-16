<p align="center">
  <img src="http://dimitridessus.fr/img/logo_circle.png" width="140px" alt="TheiPhoneRetro-Subscribe">
</p>

# Ionic 3 - Episode 11

La serie te plait ?

Alors n'hésite pas à t'abonner ! Merci :blush:

<a href="https://www.youtube.com/subscription_center?add_user=theiphoneretro">
  <img src="http://www.pngall.com/wp-content/uploads/2016/03/Subscribe-PNG-12.png" width="100px" alt="TheiPhoneRetro-Subscribe">
</a>

Dans cette épisode je vous présente comment mettre en place les notifications Push totalement gratuitement à l'aide de la plateforme OneSignal.

Dans la première partie de la vidéo, je vous présente l'utilité des notifications Push. En seconde partie, je vous indique la marche à suivre pour mettre en place un tel système au sein de votre application.

Bien entendu, il est parfaitement possible de suivre cet épisode sous Windows, Mac ou Linux =)

## Au programme 

- Qu'est-ce qu'une notification push ?
- Les différents types de notification push.
- Création d'un compte sur OneSignal.
- Installation du plugin cordova OneSignal.
- Création d'un projet Firebase - FCM (Android).
- Génération des certificats APNS (iOS).
- Utilisation du dashboard admin OneSignal (envoi de notification).

## Vidéo

<p align="center">
  <a href="https://www.youtube.com/watch?v=Yn7R_Hl8kwQ"><img src="https://img.youtube.com/vi/Yn7R_Hl8kwQ/0.jpg" alt="Ionic3-TheiPhoneRetro-Episode11"></a>
</p>

## Instructions

Pour utiliser ce projet il vous suffit de suivre les étapes ci dessous :

- Installer tout les modules requis.
```{r, engine='sh', count_lines}
npm install 
```

- Ajouter les plateformes de votre choix.
```{r, engine='sh', count_lines}
cordova platform add android
cordova platform add ios
```

- Compilez et lancez le projet.
```{r, engine='sh', count_lines}
ionic run <PLATFORM>
```

- Profitez :tada:
