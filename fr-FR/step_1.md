`position: sticky` est souvent utilisé pour les barres de navigation ou les éléments que tu souhaites garder visibles lorsque l'utilisateur fait défiler la page vers le bas, mais qui reviennent à leur position normale lorsqu'il fait défiler vers le haut.

Quand un élément est défini sur `position: sticky`, il se comporte initialement comme `position: relative`.

Cela signifie que l'élément apparaîtra dans la position normale dans le document.

Lorsque le point de défilement spécifié est atteint, l'élément passe à une position fixe (comme s'il était réglé sur `position: fixed`) et ne défile pas avec le reste du contenu.

Voici un exemple :

## --- code ---

language: css
filename:
line_numbers: true
line_number_start: 1
line_highlights:
-----------------------------------------------------

.sticky-element {
position: sticky;
top: 50px;
}

\--- /code ---

La ligne 2 définit la propriété de position sur `sticky` pour tout élément avec l'attribut `class="sticky-element"`.

La ligne 3 définit la distance à partir du haut de la fenêtre d'affichage où l'élément devient 'sticky' (sa position devient fixe).