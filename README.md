# n8n

n8n-projects

Hello Github !

Hello world

> 💡 Si vous ne voyez pas encore le message « Hello world » sur GitHub, c'est
> probablement que la modification n'a pas encore été enregistrée (commit) ni
> envoyée vers le dépôt distant.

## Comment l'agent met à jour un fichier

1. **Modifier le fichier localement.** L'agent ouvre le fichier présent dans
   l'espace de travail fourni et applique les changements demandés.
2. **Vérifier l'état du dépôt.** Une fois les modifications réalisées, l'agent
   exécute `git status` pour confirmer les fichiers modifiés.
3. **Enregistrer les changements.** Les fichiers pertinents sont ajoutés avec
   `git add`, puis l'agent crée un commit (`git commit -m "..."`).
4. **Préparer le partage.** Lorsque le commit est prêt, l'agent génère un
   message de Pull Request qui résume la modification et les tests exécutés.
5. **Pousser ou récupérer le commit.** Si un accès au dépôt distant était
   disponible, il suffirait d'exécuter `git push` pour rendre le commit visible
   sur GitHub. Dans cet environnement d'exercice, cette étape est remplacée par
   la génération du message de Pull Request afin que vous puissiez appliquer le
   commit vous-même.

## Enregistrer les changements dans Git

1. Vérifiez l'état du dépôt pour voir les fichiers modifiés présents uniquement
   en local (comme l'ajout de « Hello world ») :
   ```bash
   git status
   ```
2. Ajoutez les fichiers que vous souhaitez enregistrer :
   ```bash
   git add README.md
   ```
3. Créez un commit avec un message descriptif :
   ```bash
   git commit -m "Décrire votre modification ici"
   ```
4. Poussez le commit vers le dépôt distant pour qu'il soit visible sur GitHub :
   ```bash
   git push
   ```

Après ces étapes, vos modifications seront sauvegardées et visibles dans l'historique du dépôt Git.
