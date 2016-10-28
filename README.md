# Application de l'Agence Tous Risques

Cette application utilise [lektor](https://www.getlektor.com).

Pour lancer le serveur de développement :

```
lektor server
```

# Déploiement automatique avec Travis

Le fichier [.travis.yml](.travis.yml) permet à Travis de builder puis déployer le site ([voir la doc](https://www.getlektor.com/docs/deployment/travisci/)).

En se connectant à prose.io pour ce dépôt, on peut modifier un fichier contenu dans [content](content) et lors de la sauvegarde (aka le commit), travis est prévenu, le build déclenché, et le site déployé sur gh-pages du projet github https://github.com/enguerran/Agence-Tous-Risques.
