## Couleurs:
Fond "noir" (marges body) : #1C1C1C
Jaune : #EA9F06
Textes : #212121
Bouton "VOIR LA VENTE": dégradé de #363636 à #9A9A9A, textes #fff (blanc)
Fond articles (main): #F3F3F3
Fond footer : #373737
Fond réduction -45% : #292929
Points ronds sur "navigation footer" : #D1D1D1

## Transitions sur les liens: 
Durée = 500ms
Les textes de liens passent de #212121 à #EA9F06 
Les icones réseaux sociaux ont une opacité de 0.5 au survol
Bouton "VOIR LA VENTE" passe au jaune (#EA9F06) au survol


## Fontes:
tous les textes en: 'liberation_sansregular', Arial...
sauf prix et rabais en: Arial...


## Pour faire fonctionner les fontes
A mettre dans le CSS:
@font-face {
    font-family: 'liberation_sansbold';
    src: url('../fonts/liberationsans-bold-webfont-webfont.woff2') format('woff2'),
         url('../fonts/liberationsans-bold-webfont-webfont.woff') format('woff');
    font-weight: normal;
    font-style: normal;
}
@font-face {
    font-family: 'liberation_sansregular';
    src: url('../fonts/liberationsans-regular-webfont-webfont.woff2') format('woff2'),
         url('../fonts/liberationsans-regular-webfont-webfont.woff') format('woff');
    font-weight: normal;
    font-style: normal;
}

Puis utiliser l'instruction
font-family: 'liberation_sansregular';
lorsque vous en avez besoin