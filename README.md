# Images des contenus multimédias EDN

Ce dépôt garde la trace du travail des agents qui choisissent les images de l'artifact « Contenus multimédias EDN ».
Les images elles-mêmes vivent dans l'artifact. Ici, on ne trouve que les journaux.

## Circuit

1. **Chercheur** : propose des images en priorité sur des sites médicaux de référence (DermNet, EyeWiki, Radiopaedia, PubMed Central…), Wikimedia Commons en dernier recours. Au moins deux tours de recherche.
2. **Deux vérificateurs indépendants** regardent chaque image : l'un juge l'exactitude diagnostique, l'autre la valeur pédagogique. PASS seulement si les deux valident, sinon FAIL et le chercheur cherche une remplaçante.
3. **Juge final** : vérifie que le lot ne dérive pas (doublons, mauvais diagnostic) et répartit 10 images en *cours* (visibles en permanence) et 10 en *entraînement* (visibles seulement dans « Se tester »).

## Journaux

`journaux/item-XXX/contenu-YYY-<nom>.md` : un fichier par contenu, avec les images retenues et tous les échanges tour par tour.

## Règles en vigueur

- Au moins deux tours de recherche.
- À partir du 2ᵉ tour, si un tour rapporte moins de 3 nouvelles images validées, la recherche s'arrête et le juge garde ce qui existe (moins de 20 images si besoin).
- Indulgence pour Radiopaedia : une image d'un cas Radiopaedia est acceptée si les deux vérificateurs sont en désaccord, ou si elle n'a été refusée que pour la discrétion du signe. Une image repêchée de cette façon va uniquement en cours, jamais en entraînement.
