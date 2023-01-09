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
- Connecter le PB au Screen
- Connecter le PB au 1er Button
- Connecter le PB à la 1e industrie
- Connecter le PB au 2e Button
- Connecter le PB à la 2e industrie
- etc.
- Connecter la Detection Zone au PB
### Initialisation
Accéder aux variables LUA sur le PB (clic droit > Advanced > Edit LUA parameters):
- Entrer les noms des éléments des éléments produits par les industries connectées (en suivant l'ordre de connexion). Si le nom est long, le séparer sur les deux lignes disponibles.
- Entrer les maintain des différentes industries connectés (en suivant l'ordre de connexion).
## Utilisation
Entrer dans la zone de détection pour activer le PB.  
Appuyer sur les différents boutons pour activer/désactiver les industries associées.
