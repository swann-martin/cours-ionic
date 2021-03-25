# Ionic Cordova #

Ionic Cordova est une suite / framework qui permet de créer une appli mobile pour Android et Ios et aussi Windows mobiles et Blackberry en utilisant du html, css et JavaScript. Il y a une petite lattance car l'appli n'est pas écrite en langage natif.

Les concurrents directs sont Flutter et React Native.

- React Native est un peu plus compliqué à prendre en main mais c'est plus performant. Beaucoup plus réactif. Donc c'est assez cool pour Android et iOS.
- Flutter a été lancé par Google et utilise le langage Dart qui est un mélange entre Java et C++ et est très efficace. Il faut apprendre ce langage puis il y a un déploiement sur iOS et Android.

Le choix de la technologie pour faire son appli : si le projet a déjà été codée en web, on peut utiliser Ionic Cordova pour faire la traduction. Mais si le projet est tout neuf une entreprise peut choisir d'appeler des dev Dart pour faire l'appli en Flutter parce que c'est vraiment très efficace.

## Installer Ionic Cordova ##
Avoir NodeJS déjà installé sur l'ordinateur puis dans la console écrire :

>npm install -g @ionic/cli


Des composants sont déjà pré-installés. Cela permet de créer assez rapidement une application ionic en utilisant des composants ionic dans notre framework.

On trouve tous les modules qui peuvent nous intéresser sur npmjs.com puis il suffit d'installer en faisant un npm install nomDuModule.
Si on installe des tonnes de dépendances par exemple des icons ça alourdit l'appli.

## Commencer un projet ##

Créer un nouveau dossier ou répertoire de travail pour
> ionic start

il va demander de choisir un framework parmi Angular, React ou Vue
> Angular

Projectname :
> nomQueLOnSouhaite

Starter Template? : permet de choisir le template de départ que l'on veut : exemple tabs, sidemenu.

>sidemenu

 Integrate your new app with Capacitor to target native iOS and Android?
 >Yes

Ensuite pour voir dans le browser notre appli on peut faire :
On se rend dans le dossier créé.
>cd nomQueLOnaChoisi

Ionic va ouvrir l'appli sur le localhost:8100 port 8100.

> ionic serve

On peut ensuite ouvrir notre répertoire de travail dans un éditeur de texte exemple VS Codium ou Atom ou Sublime Text
Le dossier renferme des dossiers et fichiers selon la structure Angular.

On va donc utiliser en majorité les documents du dossier src.
