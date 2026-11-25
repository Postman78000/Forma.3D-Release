# Forma Studio — Versions

Téléchargements et nouveautés de chaque version de Forma Studio, de la plus récente à la plus ancienne.

## ⬇️ Télécharger la dernière version : Forma Studio 1.2.5

- [Forma.Studio_1.2.5_x64-setup.exe](https://github.com/Postman78000/Forma.3D-Release/releases/download/v1.2.5/Forma.Studio_1.2.5_x64-setup.exe)
- [Forma.Studio_x64_fr-FR.msi](https://github.com/Postman78000/Forma.3D-Release/releases/download/v1.2.5/Forma.Studio_x64_fr-FR.msi)
- [Page de la release et notes de version](https://github.com/Postman78000/Forma.3D-Release/releases/latest)

Documentation : [wiki](https://github.com/Postman78000/Forma.3D-Release/wiki)

---

## Forma Studio 1.2.5 — 25 novembre 2026

#### Évolutions

- Quatre modes d'affichage : Ombré, Ombré, arêtes visibles, Filaire, arêtes visibles et Filaire remplacent les anciens modes et leurs cases à cocher ; les contours des surfaces courbes et les limites des congés sont tracés, l'éclairage distingue mieux les faces et la touche W fait défiler les modes. Un ancien projet s'ouvre dans le mode le plus proche.

**Téléchargements :** [Forma.Studio_1.2.5_x64-setup.exe](https://github.com/Postman78000/Forma.3D-Release/releases/download/v1.2.5/Forma.Studio_1.2.5_x64-setup.exe) · [Forma.Studio_x64_fr-FR.msi](https://github.com/Postman78000/Forma.3D-Release/releases/download/v1.2.5/Forma.Studio_x64_fr-FR.msi)

---

## Forma Studio 1.2.4 — 25 novembre 2026

#### Corrections

- Sélection des arcs : un arc se sélectionne désormais en entier, y compris avec Maj + clic pour en ajouter plusieurs ; auparavant, seule la petite portion cliquée de chaque arc apparaissait en bleu.
- Décaler la face sur une surface courbe : le décalage s'applique à toute la surface sélectionnée (toutes ses facettes), et non à la seule facette cliquée.

#### Évolutions

- Export STEP : le menu Fichier exporte aussi le projet (ou la sélection) en STEP, et le clic droit sur un volume propose Export STL, OBJ et STEP ; les maillages et les esquisses n'ont plus ces entrées.
- Barres personnalisables partout : dans les modes Maillage et Esquisse, on peut ajouter une commande depuis son menu, déplacer une icône dans sa barre ou la retirer en la glissant hors de la barre.
- Clic droit sur un maillage : nouvelle entrée Convertir en volume (maillage fermé).
- Sélection de maillages mise en évidence : quand un ou plusieurs maillages sont sélectionnés (arbre ou scène, Ctrl/Maj+clic pour plusieurs), ils restent opaques et bleus tandis que les autres maillages deviennent translucides.
- Import 3D unifié : une seule commande Importer un objet 3D dans le mode Maillage lit STEP, STL, OBJ et 3MF, et la détection des objets du fichier (pièces reliées entre elles) a été corrigée ; le bouton Objet 3D de l'onglet Modèle est retiré.
- Mode Maillage : Déplacer utilise directement le manipulateur des volumes (translation et rotation), et Convertir en volume a son icône dans la barre.
- Import 3D analysé : STEP, OBJ et STL sont importés comme maillages ; un fichier à plusieurs objets donne autant de maillages séparés, nommés « Maillage 1 », « Maillage 2 »…
- Plans de construction déplacés comme les volumes : un plan utilise le même manipulateur que les corps (flèches, carrés et anneaux dans la vue, saisie de la distance selon X, Y ou Z) à la place de l'ancien panneau de translation et de rotation et de sa flèche le long de la normale.
- Texte vectoriel et Marquer sur une face : à la validation, un texte d'esquisse devient des surfaces 2D fermées (chaque lettre, trous compris), sélectionnables comme n'importe quel dessin et modifiables par double-clic. Marquer projette ces lettres (ou tout profil fermé d'une esquisse visible) sur la face plane choisie d'un corps, en relief ou en creux, avec un panneau en périphérie de la vue 3D et un aperçu en direct.
- Esquisse : texte en direct et réglages réorganisés : la commande Texte affiche son panneau (police du système écrite dans sa propre police, hauteur en points, gras, italique, souligné, barré) à droite de la zone de dessin, avec le texte et un curseur clignotant dans le dessin (défaut Arial 12 pt Normal). L'arbre du projet s'ouvre en haut à gauche de la zone de dessin, sous les barres d'outils ; les menus Tracés, Retouches et Contraintes s'affichent en entier ; « Autres paramètres » est remplacé par les Préférences (pas de grille) et les Paramètres du projet (paramètres de l'esquisse).

**Téléchargements :** [Forma.Studio_1.2.4_x64-setup.exe](https://github.com/Postman78000/Forma.3D-Release/releases/download/v1.2.4/Forma.Studio_1.2.4_x64-setup.exe) · [Forma.Studio_x64_fr-FR.msi](https://github.com/Postman78000/Forma.3D-Release/releases/download/v1.2.4/Forma.Studio_x64_fr-FR.msi)

---
