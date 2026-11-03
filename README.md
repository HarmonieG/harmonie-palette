# Harmonie Palette

Petite app web pour la peinture de figurines : on importe un modèle 3D, on règle les lumières, on peint par zones et on obtient les couleurs réellement visibles, avec des rampes de valeurs et une palette globale.

**En ligne :** https://harmonieg.github.io/harmonie-palette/

## Fonctions

- **Couleurs :** cercle chromatique, harmonies (complémentaire, analogue, triade…), anneau des proportions (70/20/10…), et type de schéma mesuré sur la figurine (dominante, secondaire, accent).
- **Modèle :** import STL, OBJ ou GLB (les STL d'impression 3D sont redressés), figurine de démo.
- **Lumières :** 1 à 3 lumières directionnelles ou ponctuelles (OSL), presets, déplacement à la souris ou au doigt, curseur de réalisme (des aplats au dégradé réaliste), mode noir et blanc avec 3, 5 ou 7 valeurs.
- **Peinture :** pinceau, gomme, remplissage, annulation, captures d'écran.
- **Sonde :** jusqu'à 8 points pour lire la couleur peinte et la couleur éclairée, avec rampe mesurée, rampe suggérée (hue shifting) et conseils.
- **Rampes :** palette globale en 2D, longueur réglable par couleur ou en total, passerelles de mélange, détection des rampes trop proches.

## Utilisation

Un seul fichier, `index.html`, sans build : ouvre-le dans un navigateur ou héberge-le tel quel (GitHub Pages, Netlify…). Une connexion internet est nécessaire : Three.js est chargé depuis jsDelivr et les polices depuis Google Fonts.

Les modèles 3D restent sur ton appareil. Les réglages (couleurs, lumières) sont gardés dans le navigateur.

## Licence

[MIT](LICENSE). Three.js et three-mesh-bvh, chargés à l'exécution, sont eux aussi sous licence MIT.
