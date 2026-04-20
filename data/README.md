# Penguins of Kyoto Multilayer Network

## About

This data set is based on the 2020 version of the flowchart of penguin relationships maintained by Kyoto Aquarium (found [here](https://www.kyoto-aquarium.com/sokanzu2020/)). The data set contains 59 named penguins and several types of relationships between them (couples, exes, "it's complicated", friends, enemies, and family).

## Authors and Citation info

This data set was encoded by [Heather Z. Brooks](https://www.hmc.edu/mathematics/people/faculty/heather-zinn-brooks/) (twitter [@HZinnBrooks](https://twitter.com/hzinnbrooks)) and Michelle Feng (twitter [@michellehfeng](https://twitter.com/michellehfeng)). Translations of metadata are by M. Feng, to be taken with a large grain of salt. If you spot any inaccuracies in the translation, please feel free to update and submit a PR!

Huge thanks to [Prof. Hiroki Sayama](https://www.binghamton.edu/ssie/people/profile.html?id=sayama) (twitter [@HirokiSayama](https://twitter.com/HirokiSayama)) for his help with tricky penguin descriptions for Osshii, Hachi, and Chie!

Please cite this data set using the following
```latex
@misc{Penguins_of_Kyoto_dataset,
author = {Heather Z. Brooks and Michelle Feng},
title = {Penguins of Kyoto Multilayer Network},
year = {2020},
url = {https://bitbucket.org/mhfeng/penguins_of_kyoto/src}
}
```

## In this data set

This data set contains named penguins only (no staff members, and no unnamed ex-spouses). We have included each of the following files:

* .csv file of penguin descriptions
    * Penguins of Kyoto - Metadata.csv
* .csv files containing all adjacency matrices
    * Penguins of Kyoto - Couples.csv
    * Penguins of Kyoto - Exes.csv
    * Penguins of Kyoto - Complicated.csv
    * Penguins of Kyoto - Friends.csv
    * Penguins of Kyoto - Enemies.csv
    * Penguins of Kyoto - Family.csv
* .csv files containing edge metadata
    * Penguins of Kyoto - Couples Metadata.csv
    * Penguins of Kyoto - Exes Metadata.csv
    * Penguins of Kyoto - Complicated Metadata.csv
    * Penguins of Kyoto - Friends Metadata.csv
    * Penguins of Kyoto - Enemies Metadata.csv
* .gexf files containing node and edge metadata for each relationship
    * Penguin_Couples.gexf
    * Penguin_Exes.gexf
    * Penguin_Complicated.gexf
    * Penguin_Friends.gexf
    * Penguin_Enemies.gexf
    * Penguin_Family.gexf
* .mat file containing adjacency matrices and metadata tables
    * PenguinsofKyoto.mat
* Python code for generating .gexf files from the .csv's
    * gen_nx.py

