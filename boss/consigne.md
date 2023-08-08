# Pseudo code 

## Coder le petit jeu suivant en utilisant des fonctions :

- Un boss possède 150 points de vie
- Vous avez 100 points de vie

## Le joueur possède deux attaques :    

- La première permet d’infliger 20 points de dégâts au boss    
- La seconde permet  d’infliger 10 points de dégâts au boss mais de réduire de 10 points la prochaine attaque du boss
- Le boss ne possède qu’une seule attaque infligeant entre 15 points de vie de dégâts

## Déroulement du jeu :

- Le joueur sélectionne une attaque et inflige des dégâts au boss
- On affiche le nombre de points de vie restant du boss
- Le boss attaque et inflige ses dégâts
- On affiche le nombre de points de vie restant du joueur
- On continue jusqu’à ce que les points de vie du joueur ou du boss tombent à 0

## Aide : 

Utilise des fonctions pour chaque actions 
- Choisir une attaque
- Infliger des dégats au boss
- Afficher les points de vie du boss
- Attaque du boss
- Aficher les points de vie du joueur

Par exmple pour les attaques : 
```
function choisirAttaque() {
    return prompt(`\n Selectionne une attaque: \n a. Inflige 20 points de dégâts \n b. Inflige 10 points de dégâts et réduit la prochaine attaque du boss de 10 points !``);
}
```