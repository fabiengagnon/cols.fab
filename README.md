# cols.fab

"Mieux vaut un mauvais README que pas de README pentoute"
 Éric Duhaime
	
# Les variables
## $colnb
default: 6;

Le nombre maximal de col (sur une row) qu'un site peut avoir.

## $mw
default: 1280;

La largeur maximal du container du site.

## $container
default: container;

La class du container du site.

## $m
default: 30;

La largeur en pixel des margin entre les col.

## $widths
`default: 
w20 20%, 
w25 25%, 
w30 30%, 
w33 33.33%, 
w40 40%, 
w50 50%, 
w60 60%, 
w66 66.66%, 
w70 70%, 
w75 75%, 
w80 80%, 
w100 100%
;`

Array des différentes widths qu'une col peut avoir (Columns avec des widths différentes)
array(class, width)

## $breakpoints
default:  
`full $mw+1 $m $widths, 
$mw $mw $m $widths,
1024 1024 20 $widths, 
800 800 20 $widths, 
480 480 20 $widths
;`

Les différents breakpoints que le site utilise
array(class, width, margin, widths)