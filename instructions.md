# Exercice final: Freshly Restaurant

Vous devez intégrer en responsive mobile first, les pages suivantes, par ordre de priorité :
- a minima : la page d'accueil et la page des menus
- en option : la page de contact et la page about

Le contenu sur desktop a une largeur maximum de 1400px.
Points de rupture :
- tablette : 780px
- desktop : 1100px

### Polices

Google Fonts
- Athiti : par défaut (graisse : 500)
- Merienda : pour les titres

### Taille des polices

Par défaut : 18px
Titre des pages : 30px
Sous-rubriques : 25px
Titre des menus : 20px
Prix des menus : 50px
Texte sous menus : 15px
Titres du pied de page : 18px
Texte du pied de page, boutons de tri et bouton de validation du formulaire : 16px

Interlignage général de 1.5

Les pictos sont des Font Awesome.

### Couleurs

Marron : #4c4343
Beige : #ebe3db
Rouge : #950000

- Les ombres sur les images ont les valeurs : 3px 3px 8px rgba(76,67,67,.5)

- Les ombres sur les boutons "see more" ont les valeurs : box-shadow: 2px 2px 2px silver;

****************
 PAGE D'ACCUEIL
****************

Le plugin utilisé pour le slider de la page d'accueil est : slick slider (http://kenwheeler.github.io/slick/) que vous devrez personnaliser pour obtenir le rendu tel que sur la maquette.

Navigation
-----------
La rubrique de la page courante est différenciée par le fond marron.
Au survol des rubriques, celles-ci passent progressivement à la couleur blanche pour le texte et rouge pour le fond.

Images des menus
----------------
Au survol des images des menus, celles-ci s'opacifient progressivement (couleur rgba(76,67,67,.9) ) et affichent le prix du menu (cf. capture d'écran)

Au survol des éléments "See more" le fond passe progressivement à la couleur rouge.

************
 PAGE MENUS
************

Le plugin de fonction de tri utilisé pour la page Menus est : mixitup (https://www.kunkalabs.com/mixitup/)

Au survol des images des plats, faire un léger effet de zoom et afficher le nom du plat (cf. capture d'écran).

ATTENTION : Pour le plugin Mixitup, afin que le plugin fonctionne sans bug avec l'effet de zoom ajouté sur la structure figure / figcaption, il est nécessaire d'utiliser une div qui entoure chaque figure.

**************
 PAGE CONTACT
**************

La carte est affichée avec open street map.

