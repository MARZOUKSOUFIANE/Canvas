# Canvas

un module de capture qui permet de prendre des photos et les modifier en utilsant Canvas

## le module répond aux exigences suivantes:

1.Une interface pour les actions de la capture

2.Enregistrement de l’image encodée

4.fournir des composants permettant d’ajuster la qualité de l’image en ajoutant des effets à l’image (contraste, luminosité, teinte,       etc…)

5.Outline avec des poignets de recadrage

6.Outline avec des poignets sensibles aux mouvements de la sourie (Evénements)

7.Recadrage (en largeur et en hauteur) selon les événements de la sourie

8.Enregistrement de l’image recadrer


## comment utiliser ce module:

1- le module utilise automatiquement le camera de votre machine pour filmer , et dès que vous cliquer sur le boutons "camera" une image    va être prise et affichée dans la page

2- le bouton "download base64" donne la possibilité de télécharger le contenu de l'image encodé en format base64

3- si une image est prise un bouton "couper" va être affiché et va permettre d'afficher un outline de racadrage avec des poignets          sensibles aux mouvement de la souri.
 
   => pour deplacer tout l'outline il faut cliquer deux fois sur la position que vous voulez.
   => pour ajuster la largeur ou la hauteur de l'outline il faut just cliquer sur les poignets concernés et glisser la souri soit à           droite ,à gauche,en haut  soit en bas. 

4- après terminer de l'outline il suffit juste de cliquer sur le bouton "save" pour sauvegarder et voir en clair l'extait de l'image        pris graçe à l'outline

5- en plus de ça et dans le bas de la page il y'a trois zones de types range qui vous permetront d'ajuster la qualité de l'image en        terme de contraste, luminosité et opacité.


#### vous pouvez télécharger le module avec npm :
##         "npm install glsidmodulecapture "
