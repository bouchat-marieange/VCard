# VCard
6-exercice-vcard-html (Exercice HTML-CSS - La Prairie)

## Ce que j'ai appris

* Image-lien au survol en une seule ligne de CSS plutot qu'en background-image et :hover grâce à cette astuce:


```html
<a href="ma_page.html">
  <img src="IMAGE.png" onmouseover="this.src='IMAGEHOVER.png'" onmouseout="this.src='IMAGE.png'" />
</a>
```


* Les grilles c'est super !!!

J'aime particulièrement cette méthode de grille qui permet d'attribuer une lettre à chaque partie de la grille et de visualiser en un coup d'oeil la structure de la grille dans le css


```css
#inGrid {
  display: grid;
  grid-template-areas: "h h"
                       "n c"
                       "f f";
}
nav {
  grid-area: n; /* placement de <nav> dans l'emplacement "n" */
}
```


![Le résultat](https://www.alsacreations.com/xmedia/doc/original/grid-03.png)

