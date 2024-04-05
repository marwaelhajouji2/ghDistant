# Utilisation du Hook pre-commit

Ce hook pre-commit est conçu pour ajouter automatiquement des informations complémentaires à chaque commit effectué dans ce dépôt Git.


## Instructions :

1. Copiez le fichier `pre-commit` dans le répertoire `.git/hooks/` de votre dépôt Git local.

2. Lorsque vous effectuez un commit, le hook pre-commit sera exécuté automatiquement. Il vous demandera si vous souhaitez vérifier le commit en ajoutant des informations supplémentaires. Si vous répondez "y" (oui), les informations de vérification seront ajoutées au fichier `suivi/commitInfo.txt`.

3. Si vous ne souhaitez pas vérifier le commit, répondez "n" (non) ou appuyez simplement sur la touche "Entrée" pour continuer sans ajouter d'informations supplémentaires.

