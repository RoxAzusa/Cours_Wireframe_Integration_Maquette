# Prérequis

Nodejs doit être installé

# Installer le projet

```bash
npm install
```


# Lancer le serveur de développement

```bash
npm run dev
```

# Les dossiers

## /scss
Il contiendra tout vos fichiers scss

## /public

Il contiendra tous les assets publics.
Exemple : Fonts, Images, etc ...

Par exemple, le dossier public contient une image monimage.png

Vous pouvez accéder à une ressource dans le html ou scss ainsi

```html
<img src="/monimage.png />
```

## src/main.js

Pour ceux qui souhaitent faire du javascript, le point d'entré du javascript est main.js, vous pouvez importer d'autre fichiers javascript depuis ici