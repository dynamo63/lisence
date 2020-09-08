# Contribution au projet Lisence

## Installation du Projet

Faites un fork du dépôt

Téléchargez votre fork en clonant le dépôt :

```bash
  git clone https://github.com/<votre-nom-utilisateur>/lisence.git 
```

Accédez au dépôt :

```bash
  cd lisence
```

## Procedure de Travail 

Une fois dans le dépôt en local, basculez à la branch develop :

```bash
  git checkout develop
 ```

Rassurez-vous toujours d’avoir la dernière version de la branche **develop** avant de faire votre proposition :

```bash
  git pull https://github.com/dynamo63/lisence.git develop
```

Créez une branche en fonction de votre proposition. Par exemple pour travailler sur une nouvelle proposition de fonctionnalite on peut avoir :

```bash
  git checkout -b feature_fonctionnalite 
```

Vous pouvez maintenant travailler naturellement.

Une fois que vous avez terminé de travailler et que votre resultat est satisfaisant, faites des dernières vérifications :

- Supprimez les fichiers inutiles et inutilisés
- Formatez bien votre code (indentation, règles syntaxiques)
- Renommez bien vos composants (classes, id, variables, fichiers, etc.)
- Rassurez vous d’avoir respecté l’organisation des dossiers du projet (mettre les fichiers dans les dossiers adéquats)
- Commentez correctement votre code pour qu'il soit compréhensible par l'équipe
- Faites une dernière vérification pour confirmer que tout est ok.


Créez un commit :

```bash
  git add . 
  git commit -m "<description courte de la fonctionnalite>"
```

Puis, envoyez votre travail vers votre dépôt distant :

```bash
  git push origin feature_fonctionnalite 
```

Pour terminer, rendez-vous dans le dépôt en ligne du projet sur la branche [develop](https://github.com/dynamo63/lisence/tree/develop) pour créer un pull request.

Laissez un commentaire décrivant le plus clairement possible ce sur quoi vous avez travaillé.
