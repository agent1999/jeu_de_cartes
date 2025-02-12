# Cartes

Un jeu de cartes original en Java suivant les règles du génie logiciel. Les règles sont les suivantes :
- Les joueurs doivent poser une carte de valeur supérieur d'uniquement de 1 par rapport à la dernière carte posé dans l'ordre suivant : 3-4-5-6-7-8-9-10-Valet-Dame-Roi-As.
- De plus, des combinaisons existent pour rendre le jeu stimulant :
    - La carte 2 : Littéralement la carte de valeur 2, permet de rejouer.
    - Les séries : Le joueur qui pose une série de cartes dont les valeurs se suivent impose aux autres joueurs de poser à leurs tours une série qui commence par une valeur supérieur de 1 uniquement par rapport à la première carte de la série du joueur d'avant.
    - Les doubles : poser 2 cartes de la même valeur supérieur de 1.
    - Les doubles série: Même chose qu'une série mais chaque carte de la série est en double.
    - La personne qui suit doit faire une double série qui commence par une valeur supérieur de 1 uniquement par rapport à la première carte de la série du joueur d'avant.
    - Les bombes : Trois ou Quatre cartes de la même valeur, ça brise la chaine et la carte 2, le joueur suivant doit ainsi suivre une nouvelle chaine à partir de la valeur de la bombe. Une bombe peut en suivre une autre.
    - La carte JOKER : Remplace n'importe quelle carte mais doit être accompagné par une autre carte. Autrement dit, elle imite la carte qui l'accompagne.

### Comment installer le jeu

- Ouvrir `Eclipse`.
- Sélectionner le dossier `Cartes` en tant que workspace et cliquer sur `Launch`
    - Si vous n'avez pas eu de fenêtre pour sélectionner le workspace, aller dans `File -> Switch Workspace -> Other`.
- Dans `Package Explorer`, cliquer sur `Create a Java project`.
- Décocher la case `Use default location` et mettre dans `Location` le chemin du workspace `Cartes` et cliquer sur `Finish`.
- Dans `Package Explorer`, dérouler le dossier `Cartes`, puis le dossier `src`, et enfin le dossier `test`.
- Ouvrir le fichier `TestCarteSimulation.java`.
- Appuyer sur le bouton vert avec un triangle blanc pour éxécuter le logiciel.

## Journal des modifications

### Version 1.0

- Sortie initiale.

## Crédits

- Merci à [Goboun](https://github.com/Goboun) et Stefx300 pour avoir travailler avec moi.
