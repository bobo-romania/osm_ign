osm_quality
=======

quelques billes en sql pour faire une analyse quantitative comparée du réseau de voirie entre la base OpenStreetMap et la base IGN. 
Les requêtes sont utilisables avec Postgresql / Postgis


Pourquoi réaliser cette analyse :

le but de cette analyse est de pouvoir saisir les différences quantitatives entre les différentes ressources de l'IGN et 
OpenStreetmap.
Elle prend pour référence les informations de L'IGN car elle s'inscrit dans une étude préalable à la migration 
de référentiel de travail. 


l'analyse comparée est réalisée avec les produits :
IGN_bd_topo
IGN_bd_carto
IGN_bd_r500

Une distinction entre le réseau routier carrossable et non carrossable est réalisé. 

D'autres éléments d'analyse suiverons, par l'hydrographie, la correspondance sémantique, la précision géométrique, etc.

sources de ces travaux 
=======

Postgis In action de Regina O. Obe, Leo S. Hsu
L'analyse réalisée par Fabrice Phung, contributeur sur geOrchestra et membre de l'équipe de Géobretagne
Les travaux de Girres Touya au laboratoire COGIT de l'IGN
Les travaux sur la qualité d'OpenStreetMap réalisé par Ophélie Petit AUBERMartin et BILLONPierrick - 2011
La thèse de Carmen BRANDO ESCOBAR

=======

La licence d'utilisation de ces analyses est sous licence WTFPL.

Les données exploitées ne sont pas toutes sous licenc ouverte. elle dépendent donc des conditions d'utilisation 
établies par L'IGN.

L'exploitation du RGE est réalisée dans le cadre du PNR Millevaches en Limousin sans vocation commerciale
