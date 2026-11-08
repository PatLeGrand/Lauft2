# Lauft

Jeu d’infiltration réalisé avec Unreal Engine 5.8, en Blueprints.

## Lancer le projet

Cloner le dépôt avec Git LFS, puis ouvrir `Lauft.uproject` dans Unreal Engine 5.8.
La carte de jeu est `Content/Maps/LVL_Maze_Hard.umap`. Cliquer sur Play, puis Jouer.

```sh
git lfs install
git clone https://github.com/PatLeGrand/Lauft2.git
```

## Mission et commandes

Éviter les quatre gardes, saboter le boîtier de sécurité orange en maintenant **E**
pendant trois secondes, puis rejoindre le repère violet et appuyer de nouveau sur
**E** pour s’échapper. Les quatre cachettes permettent de couper la vue des gardes.
Un contact avec un garde entraîne la défaite. Les écrans de fin permettent de rejouer.

- Déplacement : touches de déplacement configurées dans Unreal / manette.
- Souris : orienter la caméra.
- **Espace** : sauter.
- **E** : interagir.
- **M** : afficher ou masquer la mini-carte.
- **Échap** : ouvrir le menu.
- **Entrée** : jouer depuis le menu.

La fréquence d’images est déverrouillée ; la synchronisation verticale est désactivée
par défaut. Les performances dépendent du matériel et des réglages graphiques.

## Personnages et ressources

- Joueur : **Sci-Fi Soldier 02**, provenant de Fab, avec ses animations et matériaux.
- Gardes : **Swat Guy**, provenant de Mixamo, avec les animations Idle, Walking et Running.
- Les ressources et modèles fournis avec Unreal Engine restent la propriété de leurs auteurs.

Les fichiers volumineux Unreal (`.uasset`, `.umap`) sont suivis avec Git LFS.
