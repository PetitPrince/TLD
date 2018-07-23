# Objectif: Trouver quand on mentionne "death/die/died" et "love/like", enregistrer dans un fichier
Hint:
- Pour ouvrir et lire un fichier texte sous forme d'une longue chaine de caractère, la manière la plus courante de l'utiliser est:
```Python
    with open(filename, 'r') as f:
      ma_variable = f.read()
    print(ma_variable)
```
- Il est plus sage et propre de parser la structure des indications de temps & les textes plutôt que de directement chercher les mots d'intérêts.
- Pour séparer une string en liste de string selon un séparateur, vous pouvez utiliser la méthode .split(separateur) disponible pour toute les strings.
- Rechercher dans chaque objet sous-titre le string qui a le/les bon mots
- Enregistrer sous forme de pair [film; temps] dans un fichier

Delivrable:
- un fichier dont chaque ligne comporte la structure
```
[film; temps]
```