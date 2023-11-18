
# Labo 3: Modélisation UML de l'application AppRoximité

## Explication du README

- Ici le fichier README sert à préciser certains choix de modélisation
- Pratique pour justifier les changements dans le cadre d'un travail d'équipe et pour le correcteur final
- Oui, il peux décrire des évidences pour des modélisateurs d'expérience mais comme nous sommes a faire nos 
premières armes avec le modèle UML, tous les membres de l'équipe pourront bénéfier d'explication commune 
et de la logique sous-jacente à certain choix fait par des membres individuellement
- Étant donné que ces informations n'ont pas a ce retrouver directement dans les diagrammes, on peux les mettre ici

## Généralité
- Changer la version du diagramme dans la case en haut à gauche lors de chaque commit de cette manière à saura le nombre d'itération 
faite sur le diagramme. Par exemple, 2 itérations sur le diagramme de classe, le fait passer de 0 à 0.2

## Diagrammes de classe
- Une ligne avec une flèche pleine pointant de GestionnaireDeCommerce vers Utilisateur montre qu'il s'agit d'une sous-classe
- La flêche avec le losange noir du côté Utilisateur et le 1 du côté Preferences indique que sans un utilisateur, il ne peux y avoir de Preference. 
Et qu'il n'y a qu'une seule instance de Preference par instance d'utilisateur
- La flèche en pointillés avec une pointe ouverte indique que GestionnaireDeCommerce dépend de Notification pour certaines de ses opérations.
