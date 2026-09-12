# Robot Échecs

Une application Android qui pilote un **robot joueur d'échecs en LEGO Mindstorms
NXT**. Elle lit la position sur un vrai échiquier avec la caméra du téléphone,
calcule le coup, et commande le bras du robot en Bluetooth pour qu'il déplace
lui-même les pièces.

---

## ⚠️ À lire avant de télécharger

**L'application seule ne sert à rien.** Elle ne joue pas aux échecs sur ton
écran : c'est une télécommande pour une machine physique. Sans le robot, elle
s'ouvre, affiche ses menus, et s'arrête là.

Pour t'en servir, il te faut :

- le **robot cartésien en LEGO Mindstorms NXT**, monté selon les plans ;
- la brique NXT appairée en Bluetooth avec le téléphone ;
- un échiquier et un support pour poser le téléphone au-dessus ;
- **Android 7 ou plus récent**, avec une caméra.

### Se procurer la mécanique

<!-- ALEX : remplace la ligne ci-dessous par le lien Payhip quand la page est en ligne.
     Exemple : Les plans et la nomenclature sont disponibles [sur Payhip](https://payhip.com/...). -->

Les plans de la mécanique et la nomenclature des pièces seront bientôt en vente.
Lien à venir.

### Voir le robot en action

<!-- ALEX : remplace la ligne ci-dessous par le lien de la vidéo quand elle est publiee.
     Exemple : [Voir la vidéo sur YouTube](https://youtu.be/...) -->

La vidéo de présentation arrive prochainement.

---

## Installer

1. Va dans [Releases](../../releases) et télécharge le fichier `.apk` de la
   dernière version.
2. Ouvre-le sur ton téléphone. Android demandera l'autorisation d'installer une
   application venant d'ailleurs que du Play Store : c'est normal, l'application
   n'y est pas publiée.
3. Au premier lancement, un assistant te guide pour appairer la brique NXT,
   connecter le robot, lancer sa calibration et placer la caméra.

L'application existe en français, anglais, espagnol et chinois. Elle suit la
langue du téléphone, et quatre drapeaux permettent d'en changer à tout moment.

## Mises à jour

Une fois installée, l'application vérifie elle-même s'il existe une version plus
récente et te propose de l'installer. Rien à surveiller ici.

## Signaler un problème

L'écran **À propos** contient deux boutons, un pour donner ton avis et un pour
signaler un bug. Les messages arrivent directement au créateur.

---

## In English

This Android app drives a **chess-playing robot built with LEGO Mindstorms NXT**.
It reads the board through the phone camera, picks a move, and commands the robot
over Bluetooth to move the pieces on a real chessboard.

**The app is useless on its own.** It is a remote control for a physical machine,
not a chess game. You need the LEGO robot, an NXT brick paired over Bluetooth, a
chessboard, a stand to hold the phone above it, and Android 7 or newer.

Grab the `.apk` from [Releases](../../releases) and open it on your phone. The app
is in English, French, Spanish and Chinese, and updates itself.

---

<sub>`latest.json`, à la racine de ce dépôt, est le manifeste lu par l'application :
numéro de version, lien de téléchargement, empreinte SHA-256 et notes. Il est mis à
jour automatiquement à chaque publication.</sub>
