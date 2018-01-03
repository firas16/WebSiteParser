# WebSiteParser
The goal of this repo is to parse this web site
http://www.encheres-publiques.com/index.php

The script should produce two csv files:
- File that contains past appartment sales in Ile de France (if possibe 2016 and 2017).
  For each sale, the date, departement, starting price, sale price, address, surface, occupied or not.
  http://www.encheres-publiques.com/recherche/resultat-ventes.php?type_bien=1&id_region=12&code_dpt=
- File that contains coming sales with the same attributes except the sale price since it's not sold yet.
  http://www.encheres-publiques.com/recherche/resultats_recherche.php?type_bien=1&id_region=12&code_dpt=
