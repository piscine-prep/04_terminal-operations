# Opérations dans le terminal

## Objectif

Maîtriser les opérations de base sur les fichiers dans le terminal. Cet exercice vous enseignera comment créer, copier, déplacer et supprimer des fichiers - compétences essentielles pour gérer vos projets de code.

## Commandes

- `touch` - Créer des fichiers vides
- `cp` - Copier des fichiers
- `mv` - Déplacer ou renommer des fichiers
- `rm` - Supprimer des fichiers
- `cat` - Afficher le contenu des fichiers
- `echo` - Afficher du texte
- `>` et `>>` - Opérateurs de redirection

## Exercice

### Partie 1: Création et manipulation de fichiers

1. Naviguez vers votre dossier `~/c_piscine/shell/ex01/`
2. Créez trois fichiers vides nommés `file1.txt`, `file2.txt`, et `hidden_file.txt`
3. Rendez le troisième fichier caché
4. Ajoutez le texte "Hello, Terminal!" au premier fichier en utilisant la redirection
5. Ajoutez le texte "C Piscine est stimulant!" au deuxième fichier
6. Copiez le contenu du premier fichier dans le fichier caché
7. Créez un dossier appelé `backup`
8. Copiez tous les fichiers texte (non cachés) dans le dossier backup
9. Renommez `file1.txt` en `original.txt`

### Partie 2: Documentation

Créez un fichier appelé `commands_used.txt` dans `~/c_piscine/shell/ex01/` qui contient toutes les commandes que vous avez exécutées pour compléter la Partie 1, dans l'ordre, avec un bref commentaire expliquant ce que fait chaque commande.

## Résultat Attendu

Après avoir complété cet exercice:

- La structure du dossier devrait être:
  ```
  ~/c_piscine/shell/ex01/
  ├── file1.txt (contenant "Hello, Terminal!")
  ├── .hidden_file.txt (contenant "Hello, Terminal!")
  ├── commands_used.txt (contenant toutes les commandes)
  └── backup/
      ├── original.txt (contenant "Hello, Terminal!")
      └── file2.txt (contenant "C Piscine est stimulant!")
  ```
- Le fichier `commands_used.txt` devrait contenir toutes les commandes avec des explications

## Conseils

- L'opérateur `>` écrase les fichiers, tandis que `>>` ajoute à leur contenu
- Pour rendre un fichier caché dans les systèmes Unix, préfixez son nom avec un point (.)
