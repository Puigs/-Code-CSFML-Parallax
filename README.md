# -Code-CSFML-Parallax

<p>
Bonjour à tous,

Aujourd'hui nous allons mettre en place un parallax pour nos différents projets CSFML.

Que vous faites le projet my_hunter ou le my_screen_saver vous devait quand même obligatoirement faire ce #Code!
Toute personne venant me poser la question devra présenter son rendu à 9h45 que ce soit clair <3

Nous allons donc créer un parallax, qu'es qu'un parallax vous me direz, voici ma réponse ----> https://fr.wikipedia.org/wiki/Défilement_parallaxe

Concrètement voici les étapes à faire.
</p>

### Part One
<p>
1) Prendre chaque image du dossier asset/layers est créer une image contenant deux fois la même image. Ok je savais pas comment vous expliquer du coup j'ai créé un exemple dans le dossier asset et je vais vous expliquer comment faire.
2) Télécharger le logiciel gimp.
3) Créer une image vide de taille (largeur de votre image x 2 / hauteur de votre image).
4) Dans la rubrique calque, utiliser le bouton supprimer calque.
5) Ouvrir votre image en tant que calque x2
6) Les aligner
7) Exporter votre image.
8) Faites ça pour toute les images.
</p>

### Part Two
<p>
1) Ouvrer une fenêtre
2) Charger chacune de vos images
3) Préparer une clock pour chaque image
3) Faire défiler vos images de gauche à droite en utilisant VOS CLOCKS jusqu'à que votre image est atteint la position -1920 et vous remettez la position de votre image à 0.
4) J'ai dit utilise tes clocks.
5) Mettez chaque image à une vitesse différentes, plus le calque est loin plus il ira plus lentement que les autres. 
</p>