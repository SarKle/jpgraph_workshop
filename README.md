# INSERER UN GRAPHIQUE SUR UN SITE

### OUTIL
#### [JpGraph](https://jpgraph.net/features/gallery.php#pie1)
### PREREQUIS
**Un minimum de PHP**

## EN PRATIQUE

* Download JpGraph
(L'extraire dans le dossier du site)

* Documentation - index.html
(Utile pour la création de classes)


JpGraph est une librairie PHP, orienté objet, utile pour la création de graphiques


1. Créer une page index.php
2. Créer une page graphique.php
3. Choisir le modèle sur jpraph.net
4. Coller le php sur la page "graphique.php"
5. Modifier les data (entrer les bonnes données)
6. Ouvrir via localhost

Si l'image ne s'affiche pas!:
Fichier jpgraph/src/gd_image.inc.php
Commenter la ligne             // JpGraphError::RaiseL(25128);//('The function imageantialias() is not available in your PHP installation. Use the GD version that comes with PHP and not the standalone version.')

