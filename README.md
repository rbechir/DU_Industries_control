# DU_Industries_control
Script permettant de démarrer/arrêter des industries et de suivre leur statut. Permet de gérer un maximum de 4 industries.
## Instructions d'installation
### Matériel requis :
- 1 Programming Board
- 1 à 4 Manual Button XS
- 1 Modern Screen XS
- 1 Detection Zone XS
### Ordre de connexion
Coller le contenu du fichier code.json dans le PB (clic droit > Advanced > Paste Lua configuration from clipboard).  
Il est indispensable de suivre l'ordre de connexion pour que le script fonctionne bien.
- Connecter tous les PBs au Databank
- Connecter le PB master à la Light
- Connecter les PBs aux TUs (noter l'ordre de connexion)
- Connecter la Detection Zone au PB
### Initialisation
Accéder aux variables LUA sur les différents PBs (clic droit > Advanced > Edit LUA parameters):
- S'assurer que seul le PB master a la case "master" cochée
- Entrer les maintain des différents TUs connectés (en suivant l'ordre de connexion noté précédemment)
## Utilisation
Appuyer sur le bouton pour arrêter/relancer tous les TUs d'un coup.  
Attention à bien rester appuyé sur le bouton jusqu'à ce que la lumière change de couleur, ou jusqu'à ce que le widget du PB ait disparu.
