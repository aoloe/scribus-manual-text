# Notes

## Where are the Bold and Italic buttons?

en mise en page il n'y a pas de gras, on parle de épaisseur (ou graisse). et une bonne police a normalement de nombreux poids, pas simple du gras ou pas gras.
à ce que je sache, dans office, quand tu pèse sur gras, office élargit un peu les traits. pour le grand plaisir des imprimeurs.
dans scribus tu dois choisir la bonne variante de la police.

wikipédia a une liste "extrème" d'épaisseurs:

ultra-léger;
mince (100) ;
extra-léger (200) ;
léger (f300) ;
normal, régulier ou courant,(400) ;
medium ou moyen (500) ;
demi-gras ou semi-gras ( 600) ;
gras (700) ;
extra-gras ( 800) ;
noir (900) ;
extra-noir


pour l'italique, c'est semblable (même si il y a moins de variations).

donc, scribus donne accès à des options bien plus variés et c'est plus difficile de les cacher derrière deux boutons. mais ça pourrait arriver un jour...

tosca, 11.11.2016 on linuxgraphics.org: "Scribus est un vrai logiciel de PAO, destiné à produire des documents imprimés de qualité professionnelle. Il ne bidouille pas les polices, et n'utilise que les fontes et styles qui existent réellement, sans tenter de les adapter."

## Bullet and numbered lists

Starting from Scribus 1.5.2 there is a "real" bullet list functionality.

In 1.4, you can manually create bullet lists:

- crée un style appelé "liste",
- défini un retrait à gauche de 5 mm
- défini un retrait à gauche de la première ligne de -5 mm
- ajoute un tabulateur aligné à gauche aux 5 mm
- à chaque fois que tu veux ajouter une ligne dans la liste, il te faudra ajouter un n-dash (un tiret moyennement large);

4 ou 5 mm sont une bonne mesure pour de nombreuses listes... dans certains cas il faudra adapter la mesure...

## Inserting special characters

- dashes
- special spaces
- pick a special character (GarryP, forums, 12.4.2017):
  - double-click the text and place the cursor where you want the square to be inserted;
  - choose menu "Insert -> Glyph";
  - press the "Show/Hide Enhanced Palette" button (looks like a table);
  - in the "Character Class" drop-down (top-right) choose "Geometric Shapes";
  - double-click the square glyph;
  - press the Insert button;
  - close the "Enhanced Character Palette" dialog;
  - close the "Character Palette" dialog.
  For other symbols just choose a different character class and double-click on the symbol you need.
