# Mise à jour importante

## Étapes à suivre

D'abord, s'assurer que le serveur node est arrêté.

On peut ensuite *merger* master dans notre branche.

### Dépendances
Mettre à jour les dépendances:
```
yarn
```

### Fichier .env
Changer DBNAME:
```
DBNAME=machina
```

### Créer la DB
```
yarn run dev
```

* créer la db
* mettre à jour le ddoc
* démarrer le serveur node
