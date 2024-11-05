# Answers of Gregory Blatter District25

## Basics
### Task 1
On y trouve le dossier .git qui contient historique des versions précédentes, les références et branches puis les fichiers de configurations aussi et autres...

On y trouve aussi un dossier img ou est stockée une image web que l'on peut réutiliser pour l'afficher dans le markdown.

Finalement on trouve ce fichier answer.md dans lequel j'écris le texte actuellement.

### Task 2

Comme nous l'avons simplement ajouté localement sur notre répertoire, il apparait comme "Untracked" sur Sublime Merge. C'est à dire qu'il est non suivi car Git l'a détecté mais il n'est pas encore ajouté pour le suivi dans le contrôle de version. Pour ça, il faudrait le Stage pour qu'il passe dans les Staged Files prêt à être commit !

### Task 3

Le fichier README.md est passé de Untracked File à Staged File

### Task 4

Le fichier README.md est de nouveau repassé en Unstaged File car une modification a été faite mais je n'ai pas Stage le fichier depuis.

### Task 5

Main est la branche principale du projet, c'est la où on fusionne les changements une fois qu'ils sont prêts et validés.

HEAD représente notre position actuelle dans le dépôt. Il pointe vers le dernier commit de la branche sur laquelle on travail (sur main dans notre cas).

### Task 6

Lorsque l'on Checkout Commit sur le Initial Commit, le HEAD est revenu sur le commit initial c'est à dire la ou on était avant de commencer ce travail. C'est la raison pour laquelle le fichier answers.md devient vièrge. En faisant Checkout Commit sur le dernier Commit, on revient à la version actuelle et donc notre fichier README.md et answers.md reprend la version actuelle. En résumé, le Checkout Commit nous permet de voyager dans le temps de nos différentes périodes de Commit de notre travail.

## Gitgraph

### Task 7

![Gitgraph](img/gitgraph.svg)