# Scan Statue 3D Three.js

Petit projet pour reproduire une scène réelle en 3D web rapidement.

## Installation & run

Pour l'installation : 
```
git clone https://github.com/QuentinJs1/scan-statue-3D.git
cd scan-statue-3D
npm install
```

Pour le run : 
```
npm run dev
```

## Processus

### 1. La première étape est de capturer notre sujet : ici la statue.

Deux options : 
  * soit on la sculpte "à la main" avec des logiciels comme Zbrush ou Blender (long et il faut être doué)
  * soit on la scan en quelques minutes avec une application (plus simple, rendu moins top)
  
On va utiliser Polycam, qui permet de scanner des objets et de les transformer en objet 3d.

Les 7 premiers scans sont gratuits, n'hésitez pas à essayer sur des objets près de vous !

Attention aux objets réfléchissants, le résultat est souvent pas top.

https://poly.cam

L'idée est de prendre un maximum de photos du sujet sous tout les angles, l'application se chargera de générer le rendu 3D.

J'exporte ensuite en format .gltf et je le récupère sur mon pc.

### 2. Faire un scan de la zone

On va créer une image 360° de l'environnement et rajouter notre statue à l'intérieur. 

J'ai pas de caméra 360, du coup je vais passer par l'application Google Street View et reprendre une trentaine d'images.

https://play.google.com/store/apps/details?id=com.google.android.street&hl=en_US&gl=US

### 3. Faire les retouches

Corriger les différents flous sur l'environnement, et faire des retouches sur le mesh si nécessaire.

### 4. Lier le tout et déployer

## Liens utiles : 

* Thread Twitter