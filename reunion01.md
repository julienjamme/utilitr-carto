# Synthèse de l'échange tél du 2022-01-16

## Objectifs de la fiche

1. exemples pour réaliser (assez) rapidement des cartes d'étude (pas de diff) ;
2. présenter les fonctionnalités de qques *packages* ;
3. introduire les notions essentielles (objectifs d'une carte, méthodes de discrétisation, sémio ?)
4. viser un public large

## Ébauche de plan

1. Introduction
2. Cartes choroplèthes + discrétisation + lissage + *facets*
3. Symboles proportionnels
4. Cartes interactives
5. Autres (anamorphoses, cartons (*inset*))
6. Habillage carte (labels, titre, source, échelle, ...) (`ggrepel` ?)

## *Packages*

+ validé
`ggplot2`
`leaflet`
`oceanis`

+ à voir
`mapsf`
`tmap`

## Autres échanges

Dans l'intro, expliquer comment importer des fonds et des données, puis les "assembler"

discrétisation manuelle *via* `classInt` ? voir sens des bornes méthode de jenks

séparer la partie discrétisation dans une fiche à part

camembert sur carte ? [`scatterpie`](https://cran.r-project.org/web/packages/scatterpie/vignettes/scatterpie.html)
