# ECF 15 mars 2023 : Atelier Shell

# Consigne

Créez un script pour supprimer les lignes vides dans un fichier, ajoutez un fichier readme.md pour décrire votre script et expliquez comment l’utiliser.
Mettez ce script sur votre repository github

## Installation

Nécessite bash.

## Usage

### Étape 1
Dans votre terminal placez-vous dans le dossier contenant le fichier ECF_script.sh (pour pouvoir utiliser son chemin relatif en ne donnant que son nom à l'étape suivante).
### Étape 2
Utilisez la commande sh en lui passant :
- comme premier argument le nom du script
- comme second argument le nom du fichier dont vous souhaitez supprimer les lignes vides.

Dans l'exemple suivant, on modifie le fichier input-lignes-vides.txt enregistré dans le même dossier que ECF_script.sh

Le script nous renvoie un message à la fin de son exécution.
```bash
sh ECF_script.sh input-lignes-vides.txt
Les lignes vides de input-lignes-vides.txt ont été supprimées.
```

## Remarque
On peut utiliser le chemin absolu du fichier à modifier s'il n'est pas dans le même répertoire que le script.
