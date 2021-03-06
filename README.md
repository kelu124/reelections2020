# Réélections pour les municipales 2020

Exploring 2020 election datasets: [the reelected mayors data (excel) is here](https://github.com/kelu124/reelections2020/raw/master/2020_maires_reelus_clean.xls) ( [même excel, sauf les maires élus à l'unanimité](https://github.com/kelu124/reelections2020/raw/master/020_maires_reelus_sauf-unanimite_clean.xls) - voir artefact "Pourcentage de maires réélus" en dessous).

Also with [contact details from the townhall](https://github.com/kelu124/reelections2020/raw/master/2020_maires_reelus_full.xls)

## __Sources (from data.gouv.fr):__

* 2014 Elections 
  * maires-17-06-2014.zip
  * elus_mun2014.zip
* 2020 Elections
  * 2020-03-16-resultats-communes-de-moins-de-1-000.xlsx
  * 2020-03-16-resultats-par-bv.xlsx
  * 2020-03-16-resultats-communes-de-1-000-et-plus.xlsx
* Towns data
  * MDB-INSEE-V2.xls
  * communes_gps.csv

## Code

* [DataCleaning](20200403-Elections2020.ipynb)
* [Processing](20200404-ExploringReelectedMayors.ipynb)
* [SenseMaking](20200404-Exploring.ipynb)

# Quelques visualisation / exemples

## Pourcentage de maires réélus

![](/france.png)

## Artefact sur les votes / voix exprimées

Il y a un pic bleu étrange à 100% sur les petites villes.

![](https://raw.githubusercontent.com/kelu124/reelections2020/master/voixexprimees.png)


## Autres

![](https://raw.githubusercontent.com/kelu124/reelections2020/master/region.png)

![](https://raw.githubusercontent.com/kelu124/reelections2020/master/metier.png)
