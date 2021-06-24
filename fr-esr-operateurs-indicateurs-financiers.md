fr-esr-operateurs-indicateurs-financiers.
================

Jeu de données :
<https://data.enseignementsup-recherche.gouv.fr/explore/dataset/fr-esr-operateurs-indicateurs-financiers>

## soucis généraux

-   Variable `Column.1` au milieu du jeu de données
-   Variables financières coupées en deux groupes, avec les variables
    administratives au milieu

## Etablissements manquants

<table>
<thead>
<tr>
<th style="text-align:right;">
Column.1
</th>
<th style="text-align:left;">
uai…identifiant
</th>
<th style="text-align:left;">
etablissement
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:right;">
1349
</td>
<td style="text-align:left;">
075CAMPU
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:right;">
1350
</td>
<td style="text-align:left;">
075CAMPU
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:right;">
1353
</td>
<td style="text-align:left;">
075CAMPU
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:right;">
1585
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:right;">
1584
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:right;">
1348
</td>
<td style="text-align:left;">
075CAMPU
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:right;">
1351
</td>
<td style="text-align:left;">
075CAMPU
</td>
<td style="text-align:left;">
</td>
</tr>
<tr>
<td style="text-align:right;">
1352
</td>
<td style="text-align:left;">
075CAMPU
</td>
<td style="text-align:left;">
</td>
</tr>
</tbody>
</table>

## Incohérences SCSP = Produit encaissable - Ressources propres

Détection des valeurs négatives pour
`SCSP = Produit encaissable - Ressources propres`

<table>
<thead>
<tr>
<th style="text-align:left;">
etablissement
</th>
<th style="text-align:right;">
exercice
</th>
<th style="text-align:right;">
Produits.de.fonctionnement.encaissables
</th>
<th style="text-align:right;">
Ressources.propres
</th>
<th style="text-align:right;">
SCSP
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;">
Université de Lyon
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
43074576
</td>
<td style="text-align:right;">
74311309
</td>
<td style="text-align:right;">
-31236733.00
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Lyon
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
46157079
</td>
<td style="text-align:right;">
71475001
</td>
<td style="text-align:right;">
-25317922.00
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Lyon
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
52211120
</td>
<td style="text-align:right;">
76331379
</td>
<td style="text-align:right;">
-24120259.00
</td>
</tr>
<tr>
<td style="text-align:left;">
Etablissement public Campus Condorcet
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
16073294
</td>
<td style="text-align:right;">
33122790
</td>
<td style="text-align:right;">
-17049496.00
</td>
</tr>
<tr>
<td style="text-align:left;">
Etablissement public Campus Condorcet
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
7532703
</td>
<td style="text-align:right;">
23529188
</td>
<td style="text-align:right;">
-15996485.00
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Bourgogne - Franche-Comté
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
5842788
</td>
<td style="text-align:right;">
19042935
</td>
<td style="text-align:right;">
-13200147.00
</td>
</tr>
<tr>
<td style="text-align:left;">
Languedoc-Roussillon Universités
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
5774107
</td>
<td style="text-align:right;">
18056847
</td>
<td style="text-align:right;">
-12282740.00
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris-Saclay
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
39130116
</td>
<td style="text-align:right;">
50613488
</td>
<td style="text-align:right;">
-11483372.00
</td>
</tr>
<tr>
<td style="text-align:left;">
Languedoc-Roussillon Universités
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
4885386
</td>
<td style="text-align:right;">
15978851
</td>
<td style="text-align:right;">
-11093465.00
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Bourgogne - Franche-Comté
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
12965680
</td>
<td style="text-align:right;">
22831988
</td>
<td style="text-align:right;">
-9866308.00
</td>
</tr>
<tr>
<td style="text-align:left;">
Etablissement public Campus Condorcet
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
17957546
</td>
<td style="text-align:right;">
27048835
</td>
<td style="text-align:right;">
-9091289.00
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Lyon
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
49327898
</td>
<td style="text-align:right;">
58071045
</td>
<td style="text-align:right;">
-8743147.00
</td>
</tr>
<tr>
<td style="text-align:left;">
Université fédérale de Toulouse Midi-Pyrénées
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
42041336
</td>
<td style="text-align:right;">
45520860
</td>
<td style="text-align:right;">
-3479524.00
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Grenoble Alpes
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
40978043
</td>
<td style="text-align:right;">
44081901
</td>
<td style="text-align:right;">
-3103858.00
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Bourgogne - Franche-Comté
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
28774132
</td>
<td style="text-align:right;">
31320101
</td>
<td style="text-align:right;">
-2545969.00
</td>
</tr>
<tr>
<td style="text-align:left;">
Normandie Université
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
18747132
</td>
<td style="text-align:right;">
20906367
</td>
<td style="text-align:right;">
-2159235.00
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Grenoble Alpes
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
35719534
</td>
<td style="text-align:right;">
37314730
</td>
<td style="text-align:right;">
-1595196.00
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Bretagne Loire
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
16033977
</td>
<td style="text-align:right;">
17551168
</td>
<td style="text-align:right;">
-1517191.00
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure des arts et industries textiles
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
3444983
</td>
<td style="text-align:right;">
4161352
</td>
<td style="text-align:right;">
-716369.00
</td>
</tr>
<tr>
<td style="text-align:left;">
Université du Littoral Côte d’Opale
</td>
<td style="text-align:right;">
2012
</td>
<td style="text-align:right;">
85319955
</td>
<td style="text-align:right;">
85849806
</td>
<td style="text-align:right;">
-529851.00
</td>
</tr>
<tr>
<td style="text-align:left;">
Université fédérale de Toulouse Midi-Pyrénées
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
16903350
</td>
<td style="text-align:right;">
17428195
</td>
<td style="text-align:right;">
-524845.00
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris-Saclay
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
53143409
</td>
<td style="text-align:right;">
53548882
</td>
<td style="text-align:right;">
-405473.00
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris-Est
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
20832094
</td>
<td style="text-align:right;">
21089673
</td>
<td style="text-align:right;">
-257579.00
</td>
</tr>
<tr>
<td style="text-align:left;">
Observatoire de Paris
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
12124488
</td>
<td style="text-align:right;">
12125124
</td>
<td style="text-align:right;">
-636.32
</td>
</tr>
</tbody>
</table>

## Incohérences Ressources propres / Produit encaissable

Détection des incohérences (à 1% près) pour
`calculé =  Ressources propres / Produit encaissable`

<table>
<thead>
<tr>
<th style="text-align:left;">
etablissement
</th>
<th style="text-align:right;">
exercice
</th>
<th style="text-align:right;">
Produits.de.fonctionnement.encaissables
</th>
<th style="text-align:right;">
Ressources.propres
</th>
<th style="text-align:right;">
Ressources.propres…Produits.encaissables
</th>
<th style="text-align:right;">
calculé
</th>
<th style="text-align:right;">
écart
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;">
Normandie Université
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
13120652
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
91.958448
</td>
<td style="text-align:right;">
0.000000
</td>
<td style="text-align:right;">
92
</td>
</tr>
<tr>
<td style="text-align:left;">
Communauté d’universités et établissements d’Aquitaine
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
2520991
</td>
<td style="text-align:right;">
1304674
</td>
<td style="text-align:right;">
89.138914
</td>
<td style="text-align:right;">
51.752426
</td>
<td style="text-align:right;">
37
</td>
</tr>
<tr>
<td style="text-align:left;">
Université fédérale de Toulouse Midi-Pyrénées
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
28253028
</td>
<td style="text-align:right;">
10546087
</td>
<td style="text-align:right;">
74.386653
</td>
<td style="text-align:right;">
37.327281
</td>
<td style="text-align:right;">
37
</td>
</tr>
<tr>
<td style="text-align:left;">
INSA Hauts-de-France
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
9934592
</td>
<td style="text-align:right;">
4144212
</td>
<td style="text-align:right;">
71.815652
</td>
<td style="text-align:right;">
41.714969
</td>
<td style="text-align:right;">
30
</td>
</tr>
<tr>
<td style="text-align:left;">
École française d’Extrême-Orient
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
12694837
</td>
<td style="text-align:right;">
892741
</td>
<td style="text-align:right;">
36.349360
</td>
<td style="text-align:right;">
7.032316
</td>
<td style="text-align:right;">
29
</td>
</tr>
<tr>
<td style="text-align:left;">
Université confédérale Léonard de Vinci
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
1112448
</td>
<td style="text-align:right;">
592939
</td>
<td style="text-align:right;">
79.380160
</td>
<td style="text-align:right;">
53.300379
</td>
<td style="text-align:right;">
26
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national d’histoire de l’art
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
8957168
</td>
<td style="text-align:right;">
1705562
</td>
<td style="text-align:right;">
43.427052
</td>
<td style="text-align:right;">
19.041307
</td>
<td style="text-align:right;">
24
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Guyane
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
28096713
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
23.316315
</td>
<td style="text-align:right;">
0.000000
</td>
<td style="text-align:right;">
23
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure des arts et industries textiles
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
3578604
</td>
<td style="text-align:right;">
1629876
</td>
<td style="text-align:right;">
68.551815
</td>
<td style="text-align:right;">
45.545023
</td>
<td style="text-align:right;">
23
</td>
</tr>
<tr>
<td style="text-align:left;">
Université confédérale Léonard de Vinci
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
517274
</td>
<td style="text-align:right;">
75599
</td>
<td style="text-align:right;">
36.941544
</td>
<td style="text-align:right;">
14.614885
</td>
<td style="text-align:right;">
22
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national supérieur de formation et de recherche pour
l’éducation des jeunes handicapés et les enseignements adaptés
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
2186602
</td>
<td style="text-align:right;">
1243604
</td>
<td style="text-align:right;">
78.374711
</td>
<td style="text-align:right;">
56.873816
</td>
<td style="text-align:right;">
22
</td>
</tr>
<tr>
<td style="text-align:left;">
Communauté d’universités et établissements d’Aquitaine
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
1304577
</td>
<td style="text-align:right;">
765782
</td>
<td style="text-align:right;">
79.437550
</td>
<td style="text-align:right;">
58.699640
</td>
<td style="text-align:right;">
21
</td>
</tr>
<tr>
<td style="text-align:left;">
Université fédérale de Toulouse Midi-Pyrénées
</td>
<td style="text-align:right;">
2017
</td>
<td style="text-align:right;">
19116155
</td>
<td style="text-align:right;">
13946028
</td>
<td style="text-align:right;">
93.029226
</td>
<td style="text-align:right;">
72.954151
</td>
<td style="text-align:right;">
20
</td>
</tr>
<tr>
<td style="text-align:left;">
Observatoire de Paris
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
11795744
</td>
<td style="text-align:right;">
3006913
</td>
<td style="text-align:right;">
44.403151
</td>
<td style="text-align:right;">
25.491508
</td>
<td style="text-align:right;">
19
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut polytechnique de Bordeaux
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
15555712
</td>
<td style="text-align:right;">
7404824
</td>
<td style="text-align:right;">
65.543473
</td>
<td style="text-align:right;">
47.601960
</td>
<td style="text-align:right;">
18
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Bourgogne - Franche-Comté
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
16908584
</td>
<td style="text-align:right;">
13659692
</td>
<td style="text-align:right;">
97.578390
</td>
<td style="text-align:right;">
80.785547
</td>
<td style="text-align:right;">
17
</td>
</tr>
<tr>
<td style="text-align:left;">
Hautes Études-Sorbonne-Arts et Métiers
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
1490037
</td>
<td style="text-align:right;">
919970
</td>
<td style="text-align:right;">
77.662568
</td>
<td style="text-align:right;">
61.741420
</td>
<td style="text-align:right;">
16
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale des Chartes
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
4273314
</td>
<td style="text-align:right;">
727855
</td>
<td style="text-align:right;">
33.085891
</td>
<td style="text-align:right;">
17.032565
</td>
<td style="text-align:right;">
16
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris Lumières
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
2392161
</td>
<td style="text-align:right;">
1143358
</td>
<td style="text-align:right;">
58.762725
</td>
<td style="text-align:right;">
47.796031
</td>
<td style="text-align:right;">
11
</td>
</tr>
<tr>
<td style="text-align:left;">
Université confédérale Léonard de Vinci
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
491152
</td>
<td style="text-align:right;">
208499
</td>
<td style="text-align:right;">
53.092933
</td>
<td style="text-align:right;">
42.451013
</td>
<td style="text-align:right;">
11
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Bretagne Loire
</td>
<td style="text-align:right;">
2017
</td>
<td style="text-align:right;">
14304911
</td>
<td style="text-align:right;">
12180197
</td>
<td style="text-align:right;">
95.057264
</td>
<td style="text-align:right;">
85.146961
</td>
<td style="text-align:right;">
10
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale d’ingénieurs de Brest
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
4153336
</td>
<td style="text-align:right;">
1583076
</td>
<td style="text-align:right;">
47.098814
</td>
<td style="text-align:right;">
38.115770
</td>
<td style="text-align:right;">
9
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut d’études politiques de Bordeaux
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
7965926
</td>
<td style="text-align:right;">
5430766
</td>
<td style="text-align:right;">
76.877327
</td>
<td style="text-align:right;">
68.174949
</td>
<td style="text-align:right;">
9
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national supérieur de formation et de recherche pour
l’éducation des jeunes handicapés et les enseignements adaptés
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
2432117
</td>
<td style="text-align:right;">
1553536
</td>
<td style="text-align:right;">
72.098834
</td>
<td style="text-align:right;">
63.875874
</td>
<td style="text-align:right;">
8
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Haute-Alsace
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
105759563
</td>
<td style="text-align:right;">
21931298
</td>
<td style="text-align:right;">
28.527679
</td>
<td style="text-align:right;">
20.736941
</td>
<td style="text-align:right;">
8
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut d’administration des entreprises de Paris
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
10799581
</td>
<td style="text-align:right;">
9158414
</td>
<td style="text-align:right;">
92.515460
</td>
<td style="text-align:right;">
84.803420
</td>
<td style="text-align:right;">
8
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut d’administration des entreprises de Paris
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
10044473
</td>
<td style="text-align:right;">
8241371
</td>
<td style="text-align:right;">
90.271894
</td>
<td style="text-align:right;">
82.048814
</td>
<td style="text-align:right;">
8
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure de chimie de Lille
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
3186410
</td>
<td style="text-align:right;">
2236093
</td>
<td style="text-align:right;">
78.186611
</td>
<td style="text-align:right;">
70.175935
</td>
<td style="text-align:right;">
8
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut de physique du globe
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
10801533
</td>
<td style="text-align:right;">
6137975
</td>
<td style="text-align:right;">
64.453472
</td>
<td style="text-align:right;">
56.825036
</td>
<td style="text-align:right;">
8
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut d’études politiques d’Aix-en-Provence
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
4639794
</td>
<td style="text-align:right;">
2119715
</td>
<td style="text-align:right;">
51.500670
</td>
<td style="text-align:right;">
45.685541
</td>
<td style="text-align:right;">
6
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut d’études politiques de Lille
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
5305110
</td>
<td style="text-align:right;">
3470197
</td>
<td style="text-align:right;">
71.591654
</td>
<td style="text-align:right;">
65.412348
</td>
<td style="text-align:right;">
6
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut supérieur de mécanique de Paris
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
4077202
</td>
<td style="text-align:right;">
1805927
</td>
<td style="text-align:right;">
49.951094
</td>
<td style="text-align:right;">
44.293292
</td>
<td style="text-align:right;">
6
</td>
</tr>
<tr>
<td style="text-align:left;">
École française d’Extrême-Orient
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
9562379
</td>
<td style="text-align:right;">
924842
</td>
<td style="text-align:right;">
15.978011
</td>
<td style="text-align:right;">
9.671673
</td>
<td style="text-align:right;">
6
</td>
</tr>
<tr>
<td style="text-align:left;">
Normandie Université
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
13789355
</td>
<td style="text-align:right;">
12180033
</td>
<td style="text-align:right;">
93.199334
</td>
<td style="text-align:right;">
88.329244
</td>
<td style="text-align:right;">
5
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Bordeaux
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
466101626
</td>
<td style="text-align:right;">
119154097
</td>
<td style="text-align:right;">
30.346675
</td>
<td style="text-align:right;">
25.563974
</td>
<td style="text-align:right;">
5
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national des sciences appliquées de Lyon
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
53383872
</td>
<td style="text-align:right;">
32853913
</td>
<td style="text-align:right;">
66.159845
</td>
<td style="text-align:right;">
61.542769
</td>
<td style="text-align:right;">
5
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure des arts et techniques du théâtre
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
2033811
</td>
<td style="text-align:right;">
574403
</td>
<td style="text-align:right;">
33.001444
</td>
<td style="text-align:right;">
28.242693
</td>
<td style="text-align:right;">
5
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de la Nouvelle-Calédonie
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
27660020
</td>
<td style="text-align:right;">
3025312
</td>
<td style="text-align:right;">
15.656489
</td>
<td style="text-align:right;">
10.937491
</td>
<td style="text-align:right;">
5
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale d’ingénieurs de Saint-Étienne
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
5323640
</td>
<td style="text-align:right;">
3095620
</td>
<td style="text-align:right;">
62.782570
</td>
<td style="text-align:right;">
58.148560
</td>
<td style="text-align:right;">
5
</td>
</tr>
<tr>
<td style="text-align:left;">
RENATER - Réseau national de communications pour la technologie,
l’enseignement et la recherche
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
33766423
</td>
<td style="text-align:right;">
10133092
</td>
<td style="text-align:right;">
33.659372
</td>
<td style="text-align:right;">
30.009373
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national polytechnique de Toulouse
</td>
<td style="text-align:right;">
2017
</td>
<td style="text-align:right;">
93790790
</td>
<td style="text-align:right;">
31658101
</td>
<td style="text-align:right;">
37.542363
</td>
<td style="text-align:right;">
33.753955
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut d’études politiques de Bordeaux
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
7283664
</td>
<td style="text-align:right;">
5439192
</td>
<td style="text-align:right;">
78.484359
</td>
<td style="text-align:right;">
74.676591
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale des Chartes
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
3560595
</td>
<td style="text-align:right;">
568846
</td>
<td style="text-align:right;">
19.723698
</td>
<td style="text-align:right;">
15.976150
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:left;">
RENATER - Réseau national de communications pour la technologie,
l’enseignement et la recherche
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
37497604
</td>
<td style="text-align:right;">
20220552
</td>
<td style="text-align:right;">
57.534569
</td>
<td style="text-align:right;">
53.924917
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Jean Moulin - Lyon 3
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
117146331
</td>
<td style="text-align:right;">
21173673
</td>
<td style="text-align:right;">
21.696392
</td>
<td style="text-align:right;">
18.074551
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Sorbonne Nouvelle - Paris 3
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
108036013
</td>
<td style="text-align:right;">
7114811
</td>
<td style="text-align:right;">
10.679954
</td>
<td style="text-align:right;">
6.585592
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:left;">
CTLES - Centre technique du livre de l’enseignement supérieur
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
1201053
</td>
<td style="text-align:right;">
304377
</td>
<td style="text-align:right;">
29.202791
</td>
<td style="text-align:right;">
25.342512
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:left;">
ENSCI LIMOGES
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
2834260
</td>
<td style="text-align:right;">
1752667
</td>
<td style="text-align:right;">
65.517525
</td>
<td style="text-align:right;">
61.838607
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:left;">
École française de Rome
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
7174366
</td>
<td style="text-align:right;">
614961
</td>
<td style="text-align:right;">
12.398489
</td>
<td style="text-align:right;">
8.571642
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Sorbonne Nouvelle - Paris 3
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
105555079
</td>
<td style="text-align:right;">
8467218
</td>
<td style="text-align:right;">
10.594812
</td>
<td style="text-align:right;">
8.021611
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:left;">
École des hautes études en sciences sociales
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
64280474
</td>
<td style="text-align:right;">
12266280
</td>
<td style="text-align:right;">
22.152754
</td>
<td style="text-align:right;">
19.082435
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Nîmes
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
22242101
</td>
<td style="text-align:right;">
2604409
</td>
<td style="text-align:right;">
15.041003
</td>
<td style="text-align:right;">
11.709366
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Toulouse 1 - Capitole
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
113854643
</td>
<td style="text-align:right;">
24732250
</td>
<td style="text-align:right;">
24.642773
</td>
<td style="text-align:right;">
21.722654
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université des Antilles
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
99756241
</td>
<td style="text-align:right;">
8566925
</td>
<td style="text-align:right;">
11.716580
</td>
<td style="text-align:right;">
8.587859
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:left;">
Centrale Lille Institut
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
36077764
</td>
<td style="text-align:right;">
8601294
</td>
<td style="text-align:right;">
26.867366
</td>
<td style="text-align:right;">
23.840984
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:left;">
École française de Rome
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
7055286
</td>
<td style="text-align:right;">
539608
</td>
<td style="text-align:right;">
10.695144
</td>
<td style="text-align:right;">
7.648280
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Bretagne-Sud
</td>
<td style="text-align:right;">
2017
</td>
<td style="text-align:right;">
80229988
</td>
<td style="text-align:right;">
15370584
</td>
<td style="text-align:right;">
22.040952
</td>
<td style="text-align:right;">
19.158153
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Cergy-Pontoise
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
153726347
</td>
<td style="text-align:right;">
25119605
</td>
<td style="text-align:right;">
19.728021
</td>
<td style="text-align:right;">
16.340468
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:left;">
Sorbonne Université
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
621240360
</td>
<td style="text-align:right;">
109262444
</td>
<td style="text-align:right;">
20.959246
</td>
<td style="text-align:right;">
17.587789
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national polytechnique de Toulouse
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
97374883
</td>
<td style="text-align:right;">
38525194
</td>
<td style="text-align:right;">
41.113392
</td>
<td style="text-align:right;">
39.563790
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:left;">
École des hautes études en santé publique
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
59020581
</td>
<td style="text-align:right;">
47086428
</td>
<td style="text-align:right;">
81.478637
</td>
<td style="text-align:right;">
79.779675
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris-Dauphine
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
109300442
</td>
<td style="text-align:right;">
48320679
</td>
<td style="text-align:right;">
46.268007
</td>
<td style="text-align:right;">
44.209043
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Gustave Eiffel
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
202837075
</td>
<td style="text-align:right;">
30368427
</td>
<td style="text-align:right;">
16.567591
</td>
<td style="text-align:right;">
14.971832
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure de mécanique et d’aérotechnique de Poitiers
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
16346824
</td>
<td style="text-align:right;">
4865546
</td>
<td style="text-align:right;">
31.652375
</td>
<td style="text-align:right;">
29.764473
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:left;">
École normale supérieure de Rennes
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
21590169
</td>
<td style="text-align:right;">
931491
</td>
<td style="text-align:right;">
6.318093
</td>
<td style="text-align:right;">
4.314422
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de recherche Paris sciences et lettres - PSL Research
University
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
14840285
</td>
<td style="text-align:right;">
9886115
</td>
<td style="text-align:right;">
68.506245
</td>
<td style="text-align:right;">
66.616746
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:left;">
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
26789743
</td>
<td style="text-align:right;">
20822434
</td>
<td style="text-align:right;">
79.244549
</td>
<td style="text-align:right;">
77.725397
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de la Polynésie Française
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
31125201
</td>
<td style="text-align:right;">
3595511
</td>
<td style="text-align:right;">
13.184840
</td>
<td style="text-align:right;">
11.551768
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:left;">
CINES - Centre informatique national de l’enseignement supérieur
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
6709238
</td>
<td style="text-align:right;">
1862375
</td>
<td style="text-align:right;">
29.587309
</td>
<td style="text-align:right;">
27.758368
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:left;">
École normale supérieure de Rennes
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
22239408
</td>
<td style="text-align:right;">
1545147
</td>
<td style="text-align:right;">
9.291187
</td>
<td style="text-align:right;">
6.947788
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université polytechnique Hauts de France
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
105727008
</td>
<td style="text-align:right;">
16609873
</td>
<td style="text-align:right;">
17.826441
</td>
<td style="text-align:right;">
15.710151
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:left;">
École centrale de Lyon
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
37484777
</td>
<td style="text-align:right;">
10769399
</td>
<td style="text-align:right;">
30.565733
</td>
<td style="text-align:right;">
28.730060
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure des arts et techniques du théâtre
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
2005609
</td>
<td style="text-align:right;">
584572
</td>
<td style="text-align:right;">
30.685044
</td>
<td style="text-align:right;">
29.146858
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris 1 - Panthéon Sorbonne
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
227338762
</td>
<td style="text-align:right;">
40955318
</td>
<td style="text-align:right;">
19.566588
</td>
<td style="text-align:right;">
18.015106
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:left;">
Conservatoire national des arts et métiers
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
152321439
</td>
<td style="text-align:right;">
37653151
</td>
<td style="text-align:right;">
26.524918
</td>
<td style="text-align:right;">
24.719535
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Rouen
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
201273874
</td>
<td style="text-align:right;">
24743378
</td>
<td style="text-align:right;">
14.496982
</td>
<td style="text-align:right;">
12.293388
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure d’ingénieurs de Caen
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
18885959
</td>
<td style="text-align:right;">
6291850
</td>
<td style="text-align:right;">
35.595508
</td>
<td style="text-align:right;">
33.314962
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Montpellier
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
392089961
</td>
<td style="text-align:right;">
86434056
</td>
<td style="text-align:right;">
24.247383
</td>
<td style="text-align:right;">
22.044445
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université d’Artois
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
98595373
</td>
<td style="text-align:right;">
10910225
</td>
<td style="text-align:right;">
13.076529
</td>
<td style="text-align:right;">
11.065656
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:left;">
SIGMA Clermont
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
16604402
</td>
<td style="text-align:right;">
2633676
</td>
<td style="text-align:right;">
17.645911
</td>
<td style="text-align:right;">
15.861312
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris-Dauphine
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
111650906
</td>
<td style="text-align:right;">
50994606
</td>
<td style="text-align:right;">
47.567535
</td>
<td style="text-align:right;">
45.673258
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris-Dauphine
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
103192193
</td>
<td style="text-align:right;">
42415705
</td>
<td style="text-align:right;">
43.099487
</td>
<td style="text-align:right;">
41.103599
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris 1 - Panthéon Sorbonne
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
222089900
</td>
<td style="text-align:right;">
37180749
</td>
<td style="text-align:right;">
18.371801
</td>
<td style="text-align:right;">
16.741306
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Sorbonne Paris Cité
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
2499081
</td>
<td style="text-align:right;">
823318
</td>
<td style="text-align:right;">
34.470631
</td>
<td style="text-align:right;">
32.944831
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Picardie Jules-Verne
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
194229240
</td>
<td style="text-align:right;">
23608931
</td>
<td style="text-align:right;">
14.524468
</td>
<td style="text-align:right;">
12.155189
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de technologie de Belfort-Montbéliard
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
35911371
</td>
<td style="text-align:right;">
6020981
</td>
<td style="text-align:right;">
18.897894
</td>
<td style="text-align:right;">
16.766224
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut d’études politiques de Toulouse
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
4627516
</td>
<td style="text-align:right;">
2485300
</td>
<td style="text-align:right;">
55.565427
</td>
<td style="text-align:right;">
53.707000
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:left;">
École des hautes études en santé publique
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
60866025
</td>
<td style="text-align:right;">
15469289
</td>
<td style="text-align:right;">
27.238123
</td>
<td style="text-align:right;">
25.415310
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Jean Moulin - Lyon 3
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
119505223
</td>
<td style="text-align:right;">
25308968
</td>
<td style="text-align:right;">
23.024036
</td>
<td style="text-align:right;">
21.178127
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:left;">
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
27590271
</td>
<td style="text-align:right;">
21360506
</td>
<td style="text-align:right;">
79.828556
</td>
<td style="text-align:right;">
77.420428
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut d’études politiques d’Aix-en-Provence
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
4699549
</td>
<td style="text-align:right;">
2495728
</td>
<td style="text-align:right;">
54.261483
</td>
<td style="text-align:right;">
53.105692
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Nantes
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
323674700
</td>
<td style="text-align:right;">
66630205
</td>
<td style="text-align:right;">
21.183556
</td>
<td style="text-align:right;">
20.585546
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut d’études politiques de Lille
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
5222857
</td>
<td style="text-align:right;">
3625034
</td>
<td style="text-align:right;">
70.489906
</td>
<td style="text-align:right;">
69.407108
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national des langues et civilisations orientales
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
11918145
</td>
<td style="text-align:right;">
4046770
</td>
<td style="text-align:right;">
35.304840
</td>
<td style="text-align:right;">
33.954697
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
École des hautes études en sciences sociales
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
60945368
</td>
<td style="text-align:right;">
11558469
</td>
<td style="text-align:right;">
19.615602
</td>
<td style="text-align:right;">
18.965296
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris 13 - Paris Nord
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
180206702
</td>
<td style="text-align:right;">
23907992
</td>
<td style="text-align:right;">
14.189773
</td>
<td style="text-align:right;">
13.266983
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris-Est Créteil Val-de-Marne
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
241428823
</td>
<td style="text-align:right;">
40018761
</td>
<td style="text-align:right;">
17.814601
</td>
<td style="text-align:right;">
16.575801
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut français d’archéologie orientale du Caire
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
6278795
</td>
<td style="text-align:right;">
1094494
</td>
<td style="text-align:right;">
18.004139
</td>
<td style="text-align:right;">
17.431593
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Franche-Comté
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
196598106
</td>
<td style="text-align:right;">
33033364
</td>
<td style="text-align:right;">
17.687846
</td>
<td style="text-align:right;">
16.802483
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Valenciennes et du Hainaut-Cambrésis
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
103474910
</td>
<td style="text-align:right;">
20661829
</td>
<td style="text-align:right;">
20.568439
</td>
<td style="text-align:right;">
19.967960
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure de l’électronique et de ses applications de
Cergy
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
5982080
</td>
<td style="text-align:right;">
3541617
</td>
<td style="text-align:right;">
60.644174
</td>
<td style="text-align:right;">
59.203772
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
École française d’Athènes
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
5815535
</td>
<td style="text-align:right;">
479592
</td>
<td style="text-align:right;">
9.019119
</td>
<td style="text-align:right;">
8.246739
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Bordeaux-Montaigne
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
95511073
</td>
<td style="text-align:right;">
13548922
</td>
<td style="text-align:right;">
15.016063
</td>
<td style="text-align:right;">
14.185708
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
ABES - Agence bibliographique de l’enseignement supérieur
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
53180696
</td>
<td style="text-align:right;">
29489419
</td>
<td style="text-align:right;">
56.100360
</td>
<td style="text-align:right;">
55.451360
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris-Dauphine
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
110549000
</td>
<td style="text-align:right;">
50380556
</td>
<td style="text-align:right;">
46.676637
</td>
<td style="text-align:right;">
45.573054
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Paris sciences et lettres
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
31780269
</td>
<td style="text-align:right;">
25935926
</td>
<td style="text-align:right;">
82.204247
</td>
<td style="text-align:right;">
81.610152
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national universitaire Jean-François Champollion
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
9566484
</td>
<td style="text-align:right;">
3760747
</td>
<td style="text-align:right;">
40.262703
</td>
<td style="text-align:right;">
39.311695
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure de mécanique et des microtechniques
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
4880041
</td>
<td style="text-align:right;">
2513160
</td>
<td style="text-align:right;">
52.654148
</td>
<td style="text-align:right;">
51.498744
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut d’études politiques de Toulouse
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
4368571
</td>
<td style="text-align:right;">
2506998
</td>
<td style="text-align:right;">
58.169159
</td>
<td style="text-align:right;">
57.387141
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Bordeaux-Montaigne
</td>
<td style="text-align:right;">
2017
</td>
<td style="text-align:right;">
87347810
</td>
<td style="text-align:right;">
9640398
</td>
<td style="text-align:right;">
11.731659
</td>
<td style="text-align:right;">
11.036794
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Montpellier 3 - Paul-Valéry
</td>
<td style="text-align:right;">
2017
</td>
<td style="text-align:right;">
105904492
</td>
<td style="text-align:right;">
13832637
</td>
<td style="text-align:right;">
14.183443
</td>
<td style="text-align:right;">
13.061426
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
ABES - Agence bibliographique de l’enseignement supérieur
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
45644590
</td>
<td style="text-align:right;">
42877796
</td>
<td style="text-align:right;">
94.573556
</td>
<td style="text-align:right;">
93.938396
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
CINES - Centre informatique national de l’enseignement supérieur
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
6819064
</td>
<td style="text-align:right;">
1820630
</td>
<td style="text-align:right;">
27.365955
</td>
<td style="text-align:right;">
26.699119
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Grenoble Alpes
</td>
<td style="text-align:right;">
2017
</td>
<td style="text-align:right;">
445831624
</td>
<td style="text-align:right;">
86395506
</td>
<td style="text-align:right;">
20.062825
</td>
<td style="text-align:right;">
19.378506
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Jean Moulin - Lyon 3
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
117758598
</td>
<td style="text-align:right;">
25535698
</td>
<td style="text-align:right;">
22.719407
</td>
<td style="text-align:right;">
21.684784
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Sorbonne Nouvelle - Paris 3
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
109336595
</td>
<td style="text-align:right;">
13246336
</td>
<td style="text-align:right;">
12.617359
</td>
<td style="text-align:right;">
12.115190
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
École pratique des hautes études
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
42031986
</td>
<td style="text-align:right;">
8206500
</td>
<td style="text-align:right;">
20.485675
</td>
<td style="text-align:right;">
19.524417
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Versailles Saint-Quentin-en-Yvelines
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
143801869
</td>
<td style="text-align:right;">
27207829
</td>
<td style="text-align:right;">
19.984910
</td>
<td style="text-align:right;">
18.920358
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université d’Avignon et des Pays de Vaucluse
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
60077947
</td>
<td style="text-align:right;">
8149364
</td>
<td style="text-align:right;">
14.809652
</td>
<td style="text-align:right;">
13.564651
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
École centrale de Marseille
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
17081653
</td>
<td style="text-align:right;">
3966811
</td>
<td style="text-align:right;">
23.757186
</td>
<td style="text-align:right;">
23.222642
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure de chimie de Rennes
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
8989865
</td>
<td style="text-align:right;">
1830903
</td>
<td style="text-align:right;">
21.056345
</td>
<td style="text-align:right;">
20.366301
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Panthéon-Assas
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
88864558
</td>
<td style="text-align:right;">
17626983
</td>
<td style="text-align:right;">
20.677461
</td>
<td style="text-align:right;">
19.835785
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale des Chartes
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
10227092
</td>
<td style="text-align:right;">
635597
</td>
<td style="text-align:right;">
6.851430
</td>
<td style="text-align:right;">
6.214836
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national des langues et civilisations orientales
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
13553658
</td>
<td style="text-align:right;">
5180242
</td>
<td style="text-align:right;">
39.066243
</td>
<td style="text-align:right;">
38.220250
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université du Havre
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
71833027
</td>
<td style="text-align:right;">
7669747
</td>
<td style="text-align:right;">
11.557734
</td>
<td style="text-align:right;">
10.677188
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Limoges
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
154527254
</td>
<td style="text-align:right;">
25214967
</td>
<td style="text-align:right;">
17.686977
</td>
<td style="text-align:right;">
16.317489
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
École française d’Athènes
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
5863347
</td>
<td style="text-align:right;">
472193
</td>
<td style="text-align:right;">
9.412303
</td>
<td style="text-align:right;">
8.053301
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
Casa de Velázquez de Madrid
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
7150290
</td>
<td style="text-align:right;">
570263
</td>
<td style="text-align:right;">
8.898940
</td>
<td style="text-align:right;">
7.975383
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut polytechnique de Bordeaux
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
14857528
</td>
<td style="text-align:right;">
8296809
</td>
<td style="text-align:right;">
55.083867
</td>
<td style="text-align:right;">
55.842459
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université d’Orléans
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
173453755
</td>
<td style="text-align:right;">
33105728
</td>
<td style="text-align:right;">
18.053647
</td>
<td style="text-align:right;">
19.086198
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Panthéon-Assas
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
91749857
</td>
<td style="text-align:right;">
21522195
</td>
<td style="text-align:right;">
22.891738
</td>
<td style="text-align:right;">
23.457470
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris-Est Marne-la-Vallée
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
95199183
</td>
<td style="text-align:right;">
17666944
</td>
<td style="text-align:right;">
17.461899
</td>
<td style="text-align:right;">
18.557873
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Gustave Eiffel
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
253835797
</td>
<td style="text-align:right;">
89679885
</td>
<td style="text-align:right;">
33.880246
</td>
<td style="text-align:right;">
35.329881
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université d’Évry-Val d’Essonne
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
88293430
</td>
<td style="text-align:right;">
16507200
</td>
<td style="text-align:right;">
17.996524
</td>
<td style="text-align:right;">
18.695842
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure de l’électronique et de ses applications de
Cergy
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
5269838
</td>
<td style="text-align:right;">
2915629
</td>
<td style="text-align:right;">
54.762613
</td>
<td style="text-align:right;">
55.326729
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Bretagne-Sud
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
82335108
</td>
<td style="text-align:right;">
17379598
</td>
<td style="text-align:right;">
20.570892
</td>
<td style="text-align:right;">
21.108369
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale d’ingénieurs de Tarbes
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
17972360
</td>
<td style="text-align:right;">
4373382
</td>
<td style="text-align:right;">
23.231980
</td>
<td style="text-align:right;">
24.333933
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Lumière - Lyon 2
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
141647817
</td>
<td style="text-align:right;">
23585495
</td>
<td style="text-align:right;">
16.061601
</td>
<td style="text-align:right;">
16.650800
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure de chimie de Paris
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
13618851
</td>
<td style="text-align:right;">
3970068
</td>
<td style="text-align:right;">
27.665263
</td>
<td style="text-align:right;">
29.151270
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
École des hautes études en sciences sociales
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
61679210
</td>
<td style="text-align:right;">
11478438
</td>
<td style="text-align:right;">
17.929276
</td>
<td style="text-align:right;">
18.609898
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
École des hautes études en sciences sociales
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
62074237
</td>
<td style="text-align:right;">
10892894
</td>
<td style="text-align:right;">
16.108022
</td>
<td style="text-align:right;">
17.548172
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Poitiers
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
222849135
</td>
<td style="text-align:right;">
31395622
</td>
<td style="text-align:right;">
12.679682
</td>
<td style="text-align:right;">
14.088285
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris 13 - Paris Nord
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
175594130
</td>
<td style="text-align:right;">
25934899
</td>
<td style="text-align:right;">
14.189811
</td>
<td style="text-align:right;">
14.769798
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris-Est Créteil Val-de-Marne
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
233904585
</td>
<td style="text-align:right;">
40223565
</td>
<td style="text-align:right;">
15.853373
</td>
<td style="text-align:right;">
17.196570
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Casa de Velázquez de Madrid
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
7000687
</td>
<td style="text-align:right;">
634435
</td>
<td style="text-align:right;">
8.296771
</td>
<td style="text-align:right;">
9.062468
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de la Polynésie Française
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
24372848
</td>
<td style="text-align:right;">
2933678
</td>
<td style="text-align:right;">
11.230756
</td>
<td style="text-align:right;">
12.036666
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Aix-Marseille université
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
604056601
</td>
<td style="text-align:right;">
117366889
</td>
<td style="text-align:right;">
18.866945
</td>
<td style="text-align:right;">
19.429783
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Bordeaux
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
492164534
</td>
<td style="text-align:right;">
160634045
</td>
<td style="text-align:right;">
31.361647
</td>
<td style="text-align:right;">
32.638281
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université d’Angers
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
138978458
</td>
<td style="text-align:right;">
21781494
</td>
<td style="text-align:right;">
14.897800
</td>
<td style="text-align:right;">
15.672569
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université LILLE 1 - SCIENCES TECHNOLOGIES
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
243520038
</td>
<td style="text-align:right;">
53196894
</td>
<td style="text-align:right;">
20.454326
</td>
<td style="text-align:right;">
21.844976
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université d’Artois
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
95961583
</td>
<td style="text-align:right;">
12048067
</td>
<td style="text-align:right;">
11.930871
</td>
<td style="text-align:right;">
12.555094
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Haute-Alsace
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
93031952
</td>
<td style="text-align:right;">
23215004
</td>
<td style="text-align:right;">
24.003051
</td>
<td style="text-align:right;">
24.953797
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris-Est
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
16470044
</td>
<td style="text-align:right;">
15777944
</td>
<td style="text-align:right;">
94.473081
</td>
<td style="text-align:right;">
95.797825
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national universitaire Jean-François Champollion
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
8484134
</td>
<td style="text-align:right;">
3148382
</td>
<td style="text-align:right;">
36.043761
</td>
<td style="text-align:right;">
37.109056
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université d’Évry-Val d’Essonne
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
88435245
</td>
<td style="text-align:right;">
17606211
</td>
<td style="text-align:right;">
19.102699
</td>
<td style="text-align:right;">
19.908591
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Casa de Velázquez de Madrid
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
7087873
</td>
<td style="text-align:right;">
627266
</td>
<td style="text-align:right;">
8.168318
</td>
<td style="text-align:right;">
8.849848
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de La Réunion
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
121247008
</td>
<td style="text-align:right;">
21885998
</td>
<td style="text-align:right;">
16.918973
</td>
<td style="text-align:right;">
18.050753
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Bordeaux-Montaigne
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
95858241
</td>
<td style="text-align:right;">
15167561
</td>
<td style="text-align:right;">
15.299894
</td>
<td style="text-align:right;">
15.822908
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national des sciences appliquées de Rennes
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
41071059
</td>
<td style="text-align:right;">
11177652
</td>
<td style="text-align:right;">
25.801568
</td>
<td style="text-align:right;">
27.215398
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Reims Champagne-Ardenne
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
186364301
</td>
<td style="text-align:right;">
26291660
</td>
<td style="text-align:right;">
13.508787
</td>
<td style="text-align:right;">
14.107670
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure de chimie de Lille
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
2860631
</td>
<td style="text-align:right;">
2145236
</td>
<td style="text-align:right;">
73.886915
</td>
<td style="text-align:right;">
74.991699
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université CLERMONT-FERRAND 1 - AUVERGNE
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
112402303
</td>
<td style="text-align:right;">
19810703
</td>
<td style="text-align:right;">
16.419833
</td>
<td style="text-align:right;">
17.624819
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Perpignan - Via Domitia
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
74629489
</td>
<td style="text-align:right;">
14708748
</td>
<td style="text-align:right;">
18.795785
</td>
<td style="text-align:right;">
19.709029
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Claude Bernard - Lyon 1
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
382490199
</td>
<td style="text-align:right;">
84331245
</td>
<td style="text-align:right;">
21.080093
</td>
<td style="text-align:right;">
22.047949
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national des langues et civilisations orientales
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
12702968
</td>
<td style="text-align:right;">
4849890
</td>
<td style="text-align:right;">
37.259048
</td>
<td style="text-align:right;">
38.179188
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Poitiers
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
237632809
</td>
<td style="text-align:right;">
37592944
</td>
<td style="text-align:right;">
14.616326
</td>
<td style="text-align:right;">
15.819762
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris 13 - Paris Nord
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
176099759
</td>
<td style="text-align:right;">
27308166
</td>
<td style="text-align:right;">
14.957245
</td>
<td style="text-align:right;">
15.507214
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris 8 - Vincennes - Saint-Denis
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
140070291
</td>
<td style="text-align:right;">
17225722
</td>
<td style="text-align:right;">
11.568794
</td>
<td style="text-align:right;">
12.297913
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
École française de Rome
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
7183260
</td>
<td style="text-align:right;">
1046839
</td>
<td style="text-align:right;">
13.684274
</td>
<td style="text-align:right;">
14.573313
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de La Rochelle
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
67800450
</td>
<td style="text-align:right;">
11289190
</td>
<td style="text-align:right;">
15.831013
</td>
<td style="text-align:right;">
16.650612
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Bordeaux-Montaigne
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
89725185
</td>
<td style="text-align:right;">
12387681
</td>
<td style="text-align:right;">
12.409685
</td>
<td style="text-align:right;">
13.806247
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Bordeaux
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
475749958
</td>
<td style="text-align:right;">
138952095
</td>
<td style="text-align:right;">
28.207218
</td>
<td style="text-align:right;">
29.206959
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure de chimie de Rennes
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
9070325
</td>
<td style="text-align:right;">
2002805
</td>
<td style="text-align:right;">
21.281762
</td>
<td style="text-align:right;">
22.080852
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Lorraine
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
525391345
</td>
<td style="text-align:right;">
78977163
</td>
<td style="text-align:right;">
13.549226
</td>
<td style="text-align:right;">
15.032064
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université du Littoral Côte d’Opale
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
86234598
</td>
<td style="text-align:right;">
13586801
</td>
<td style="text-align:right;">
14.356326
</td>
<td style="text-align:right;">
15.755626
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Centrale Lille Institut
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
38032272
</td>
<td style="text-align:right;">
12170789
</td>
<td style="text-align:right;">
30.674647
</td>
<td style="text-align:right;">
32.001215
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université d’Artois
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
97432448
</td>
<td style="text-align:right;">
13689299
</td>
<td style="text-align:right;">
12.816074
</td>
<td style="text-align:right;">
14.050041
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Pau et des Pays de l’Adour
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
115079460
</td>
<td style="text-align:right;">
23891128
</td>
<td style="text-align:right;">
19.967764
</td>
<td style="text-align:right;">
20.760549
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Conservatoire national des arts et métiers
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
156740550
</td>
<td style="text-align:right;">
46812896
</td>
<td style="text-align:right;">
29.068698
</td>
<td style="text-align:right;">
29.866487
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
23657195
</td>
<td style="text-align:right;">
13189047
</td>
<td style="text-align:right;">
54.865477
</td>
<td style="text-align:right;">
55.750680
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Versailles Saint-Quentin-en-Yvelines
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
145472813
</td>
<td style="text-align:right;">
32879568
</td>
<td style="text-align:right;">
21.725967
</td>
<td style="text-align:right;">
22.601864
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national universitaire Jean-François Champollion
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
8871341
</td>
<td style="text-align:right;">
3419337
</td>
<td style="text-align:right;">
37.631380
</td>
<td style="text-align:right;">
38.543632
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Toulon
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
75416553
</td>
<td style="text-align:right;">
8814229
</td>
<td style="text-align:right;">
10.899974
</td>
<td style="text-align:right;">
11.687393
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris Nanterre
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
194345456
</td>
<td style="text-align:right;">
22222547
</td>
<td style="text-align:right;">
10.606863
</td>
<td style="text-align:right;">
11.434560
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris-Est Créteil Val-de-Marne
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
248157587
</td>
<td style="text-align:right;">
44457285
</td>
<td style="text-align:right;">
16.533659
</td>
<td style="text-align:right;">
17.914941
</td>
<td style="text-align:right;">
-1
</td>
</tr>
<tr>
<td style="text-align:left;">
Université François-Rabelais
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
206666971
</td>
<td style="text-align:right;">
44827699
</td>
<td style="text-align:right;">
19.322010
</td>
<td style="text-align:right;">
21.690790
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Reims Champagne-Ardenne
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
203896323
</td>
<td style="text-align:right;">
33784000
</td>
<td style="text-align:right;">
14.561158
</td>
<td style="text-align:right;">
16.569205
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
École centrale de Lille
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
26073038
</td>
<td style="text-align:right;">
8046693
</td>
<td style="text-align:right;">
29.188167
</td>
<td style="text-align:right;">
30.862123
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut d’études politiques de Lille
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
6004617
</td>
<td style="text-align:right;">
4674152
</td>
<td style="text-align:right;">
75.480002
</td>
<td style="text-align:right;">
77.842633
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
École normale supérieure de Lyon
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
134397588
</td>
<td style="text-align:right;">
18649589
</td>
<td style="text-align:right;">
11.699418
</td>
<td style="text-align:right;">
13.876431
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Collège de France
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
42929050
</td>
<td style="text-align:right;">
10855225
</td>
<td style="text-align:right;">
22.995617
</td>
<td style="text-align:right;">
25.286432
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national des langues et civilisations orientales
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
14041489
</td>
<td style="text-align:right;">
5331156
</td>
<td style="text-align:right;">
36.030054
</td>
<td style="text-align:right;">
37.967170
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national d’histoire de l’art
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
11403561
</td>
<td style="text-align:right;">
2673490
</td>
<td style="text-align:right;">
21.242408
</td>
<td style="text-align:right;">
23.444343
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université du Havre
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
71604683
</td>
<td style="text-align:right;">
9964943
</td>
<td style="text-align:right;">
12.327484
</td>
<td style="text-align:right;">
13.916608
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université d’Avignon et des Pays de Vaucluse
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
55727536
</td>
<td style="text-align:right;">
7114769
</td>
<td style="text-align:right;">
10.896448
</td>
<td style="text-align:right;">
12.767062
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de La Réunion
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
114712118
</td>
<td style="text-align:right;">
17460914
</td>
<td style="text-align:right;">
13.459049
</td>
<td style="text-align:right;">
15.221508
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Bourgogne
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
233131320
</td>
<td style="text-align:right;">
41088737
</td>
<td style="text-align:right;">
15.415896
</td>
<td style="text-align:right;">
17.624718
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale d’ingénieurs de Brest
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
3319332
</td>
<td style="text-align:right;">
1150763
</td>
<td style="text-align:right;">
32.232871
</td>
<td style="text-align:right;">
34.668512
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Toulouse 1 - Capitole
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
106671859
</td>
<td style="text-align:right;">
24312310
</td>
<td style="text-align:right;">
20.348356
</td>
<td style="text-align:right;">
22.791681
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université François-Rabelais
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
200078486
</td>
<td style="text-align:right;">
37401272
</td>
<td style="text-align:right;">
16.774877
</td>
<td style="text-align:right;">
18.693300
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université d’Orléans
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
167736674
</td>
<td style="text-align:right;">
28475700
</td>
<td style="text-align:right;">
15.239236
</td>
<td style="text-align:right;">
16.976431
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université d’Angers
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
154066356
</td>
<td style="text-align:right;">
29024494
</td>
<td style="text-align:right;">
17.181215
</td>
<td style="text-align:right;">
18.838957
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Lorraine
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
584997186
</td>
<td style="text-align:right;">
111884080
</td>
<td style="text-align:right;">
17.064556
</td>
<td style="text-align:right;">
19.125576
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Lumière - Lyon 2
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
137510823
</td>
<td style="text-align:right;">
22069885
</td>
<td style="text-align:right;">
13.935260
</td>
<td style="text-align:right;">
16.049562
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure des sciences de l’information et des
bibliothèques
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
2716485
</td>
<td style="text-align:right;">
622476
</td>
<td style="text-align:right;">
21.280073
</td>
<td style="text-align:right;">
22.914759
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris 1 - Panthéon Sorbonne
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
217858103
</td>
<td style="text-align:right;">
42946612
</td>
<td style="text-align:right;">
17.625125
</td>
<td style="text-align:right;">
19.713112
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national d’histoire de l’art
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
11594006
</td>
<td style="text-align:right;">
2775198
</td>
<td style="text-align:right;">
21.933549
</td>
<td style="text-align:right;">
23.936489
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Picardie Jules-Verne
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
185988270
</td>
<td style="text-align:right;">
27380189
</td>
<td style="text-align:right;">
12.868431
</td>
<td style="text-align:right;">
14.721460
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Picardie Jules-Verne
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
193095118
</td>
<td style="text-align:right;">
31085118
</td>
<td style="text-align:right;">
14.400098
</td>
<td style="text-align:right;">
16.098345
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Poitiers
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
232026895
</td>
<td style="text-align:right;">
30720639
</td>
<td style="text-align:right;">
11.474313
</td>
<td style="text-align:right;">
13.240120
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut d’études politiques d’Aix-en-Provence
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
4828595
</td>
<td style="text-align:right;">
2596801
</td>
<td style="text-align:right;">
51.781564
</td>
<td style="text-align:right;">
53.779640
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
École centrale de Marseille
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
19455479
</td>
<td style="text-align:right;">
5192834
</td>
<td style="text-align:right;">
25.153922
</td>
<td style="text-align:right;">
26.690857
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure d’ingénieurs de Caen
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
17293781
</td>
<td style="text-align:right;">
5369607
</td>
<td style="text-align:right;">
28.912214
</td>
<td style="text-align:right;">
31.049352
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national des sciences appliquées Centre Val de Loire
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
19919269
</td>
<td style="text-align:right;">
5016218
</td>
<td style="text-align:right;">
23.362107
</td>
<td style="text-align:right;">
25.182741
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national des sciences appliquées Centre Val de Loire
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
20673687
</td>
<td style="text-align:right;">
5849906
</td>
<td style="text-align:right;">
26.080258
</td>
<td style="text-align:right;">
28.296385
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Bretagne Occidentale
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
184531427
</td>
<td style="text-align:right;">
34820684
</td>
<td style="text-align:right;">
16.447794
</td>
<td style="text-align:right;">
18.869785
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national polytechnique de Toulouse
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
87567283
</td>
<td style="text-align:right;">
33643210
</td>
<td style="text-align:right;">
36.797665
</td>
<td style="text-align:right;">
38.419840
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Montpellier 3 - Paul-Valéry
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
109206605
</td>
<td style="text-align:right;">
18117852
</td>
<td style="text-align:right;">
14.672683
</td>
<td style="text-align:right;">
16.590436
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Montpellier
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
381031984
</td>
<td style="text-align:right;">
92884932
</td>
<td style="text-align:right;">
22.188351
</td>
<td style="text-align:right;">
24.377201
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université polytechnique Hauts de France
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
103020446
</td>
<td style="text-align:right;">
24050575
</td>
<td style="text-align:right;">
21.575288
</td>
<td style="text-align:right;">
23.345439
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Jean Moulin - Lyon 3
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
100865239
</td>
<td style="text-align:right;">
20824140
</td>
<td style="text-align:right;">
19.136665
</td>
<td style="text-align:right;">
20.645507
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Savoie
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
112099274
</td>
<td style="text-align:right;">
23158934
</td>
<td style="text-align:right;">
18.366377
</td>
<td style="text-align:right;">
20.659308
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut de physique du globe
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
15975650
</td>
<td style="text-align:right;">
12384447
</td>
<td style="text-align:right;">
75.955889
</td>
<td style="text-align:right;">
77.520771
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Sorbonne Université
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
717163165
</td>
<td style="text-align:right;">
242971568
</td>
<td style="text-align:right;">
31.814680
</td>
<td style="text-align:right;">
33.879538
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université d’Avignon et des Pays de Vaucluse
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
58588602
</td>
<td style="text-align:right;">
9485959
</td>
<td style="text-align:right;">
14.551032
</td>
<td style="text-align:right;">
16.190793
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université d’Avignon et des Pays de Vaucluse
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
61078886
</td>
<td style="text-align:right;">
10769573
</td>
<td style="text-align:right;">
15.785790
</td>
<td style="text-align:right;">
17.632236
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université d’Évry-Val d’Essonne
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
87353893
</td>
<td style="text-align:right;">
17650638
</td>
<td style="text-align:right;">
18.561405
</td>
<td style="text-align:right;">
20.205897
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Centre Universitaire de Mayotte
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
3971390
</td>
<td style="text-align:right;">
1257187
</td>
<td style="text-align:right;">
29.875862
</td>
<td style="text-align:right;">
31.656095
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de technologie de Troyes
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
37722511
</td>
<td style="text-align:right;">
12477120
</td>
<td style="text-align:right;">
30.951346
</td>
<td style="text-align:right;">
33.076059
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Bourgogne
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
231100335
</td>
<td style="text-align:right;">
39851701
</td>
<td style="text-align:right;">
14.984838
</td>
<td style="text-align:right;">
17.244329
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Franche-Comté
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
199416829
</td>
<td style="text-align:right;">
35821359
</td>
<td style="text-align:right;">
15.793931
</td>
<td style="text-align:right;">
17.963057
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Nîmes
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
22459025
</td>
<td style="text-align:right;">
3031642
</td>
<td style="text-align:right;">
11.532620
</td>
<td style="text-align:right;">
13.498547
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Toulouse - Jean Jaurès
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
178987147
</td>
<td style="text-align:right;">
14632374
</td>
<td style="text-align:right;">
6.187607
</td>
<td style="text-align:right;">
8.175098
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut d’études politiques de Rennes
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
3719147
</td>
<td style="text-align:right;">
2357262
</td>
<td style="text-align:right;">
61.694120
</td>
<td style="text-align:right;">
63.381792
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
École normale supérieure de Rennes
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
21085997
</td>
<td style="text-align:right;">
1976442
</td>
<td style="text-align:right;">
7.073287
</td>
<td style="text-align:right;">
9.373244
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale d’ingénieurs de Saint-Étienne
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
4949182
</td>
<td style="text-align:right;">
3055324
</td>
<td style="text-align:right;">
60.183865
</td>
<td style="text-align:right;">
61.733919
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Lorraine
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
604311575
</td>
<td style="text-align:right;">
122019034
</td>
<td style="text-align:right;">
18.413057
</td>
<td style="text-align:right;">
20.191411
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut d’administration des entreprises de Paris
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
11443050
</td>
<td style="text-align:right;">
10656268
</td>
<td style="text-align:right;">
91.508531
</td>
<td style="text-align:right;">
93.124368
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris-Est
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
17280156
</td>
<td style="text-align:right;">
9479060
</td>
<td style="text-align:right;">
52.759628
</td>
<td style="text-align:right;">
54.855176
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure de mécanique et d’aérotechnique de Poitiers
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
15995205
</td>
<td style="text-align:right;">
4982149
</td>
<td style="text-align:right;">
29.485630
</td>
<td style="text-align:right;">
31.147766
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut d’études politiques d’Aix-en-Provence
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
5046250
</td>
<td style="text-align:right;">
2842513
</td>
<td style="text-align:right;">
54.308348
</td>
<td style="text-align:right;">
56.329215
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Aix-Marseille université
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
679266524
</td>
<td style="text-align:right;">
173680998
</td>
<td style="text-align:right;">
24.016929
</td>
<td style="text-align:right;">
25.568903
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Bretagne Occidentale
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
181955200
</td>
<td style="text-align:right;">
37427431
</td>
<td style="text-align:right;">
18.171675
</td>
<td style="text-align:right;">
20.569586
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université d’Angers
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
153576315
</td>
<td style="text-align:right;">
31793940
</td>
<td style="text-align:right;">
18.571559
</td>
<td style="text-align:right;">
20.702372
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Savoie
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
117091654
</td>
<td style="text-align:right;">
26612300
</td>
<td style="text-align:right;">
20.323574
</td>
<td style="text-align:right;">
22.727751
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
École normale supérieure de Paris
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
111342713
</td>
<td style="text-align:right;">
31021766
</td>
<td style="text-align:right;">
25.686463
</td>
<td style="text-align:right;">
27.861514
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Collège de France
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
42089180
</td>
<td style="text-align:right;">
9791148
</td>
<td style="text-align:right;">
21.194789
</td>
<td style="text-align:right;">
23.262862
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris Nanterre
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
190890025
</td>
<td style="text-align:right;">
24229271
</td>
<td style="text-align:right;">
11.113959
</td>
<td style="text-align:right;">
12.692790
</td>
<td style="text-align:right;">
-2
</td>
</tr>
<tr>
<td style="text-align:left;">
École centrale de Marseille
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
17299950
</td>
<td style="text-align:right;">
3415456
</td>
<td style="text-align:right;">
17.232420
</td>
<td style="text-align:right;">
19.742577
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Bretagne Occidentale
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
181996778
</td>
<td style="text-align:right;">
38170925
</td>
<td style="text-align:right;">
17.525894
</td>
<td style="text-align:right;">
20.973407
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Bretagne Occidentale
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
183900000
</td>
<td style="text-align:right;">
35400000
</td>
<td style="text-align:right;">
16.367591
</td>
<td style="text-align:right;">
19.249592
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut d’études politiques de Grenoble
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
4621145
</td>
<td style="text-align:right;">
3115581
</td>
<td style="text-align:right;">
64.113656
</td>
<td style="text-align:right;">
67.420109
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Grenoble Alpes
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
458438303
</td>
<td style="text-align:right;">
113292358
</td>
<td style="text-align:right;">
21.257831
</td>
<td style="text-align:right;">
24.712673
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université d’Angers
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
158068470
</td>
<td style="text-align:right;">
35453201
</td>
<td style="text-align:right;">
18.972147
</td>
<td style="text-align:right;">
22.429015
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Haute-Alsace
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
92403695
</td>
<td style="text-align:right;">
20636180
</td>
<td style="text-align:right;">
19.777586
</td>
<td style="text-align:right;">
22.332635
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Savoie
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
108369929
</td>
<td style="text-align:right;">
20756871
</td>
<td style="text-align:right;">
16.173316
</td>
<td style="text-align:right;">
19.153718
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
CTLES - Centre technique du livre de l’enseignement supérieur
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
1220774
</td>
<td style="text-align:right;">
410711
</td>
<td style="text-align:right;">
30.346485
</td>
<td style="text-align:right;">
33.643492
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris-Saclay
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
53143409
</td>
<td style="text-align:right;">
53548882
</td>
<td style="text-align:right;">
97.709996
</td>
<td style="text-align:right;">
100.762979
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris-Est Créteil Val-de-Marne
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
250169181
</td>
<td style="text-align:right;">
51879749
</td>
<td style="text-align:right;">
18.157837
</td>
<td style="text-align:right;">
20.737866
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
École française de Rome
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
7136987
</td>
<td style="text-align:right;">
1067823
</td>
<td style="text-align:right;">
11.883096
</td>
<td style="text-align:right;">
14.961818
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université des Antilles
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
94427996
</td>
<td style="text-align:right;">
11120473
</td>
<td style="text-align:right;">
8.322845
</td>
<td style="text-align:right;">
11.776670
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Aix-Marseille université
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
645711456
</td>
<td style="text-align:right;">
152342901
</td>
<td style="text-align:right;">
20.284201
</td>
<td style="text-align:right;">
23.593031
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Caen Normandie
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
225057812
</td>
<td style="text-align:right;">
37731956
</td>
<td style="text-align:right;">
13.995077
</td>
<td style="text-align:right;">
16.765451
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut d’études politiques de Toulouse
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
4373793
</td>
<td style="text-align:right;">
2672772
</td>
<td style="text-align:right;">
57.617084
</td>
<td style="text-align:right;">
61.108780
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national polytechnique de Toulouse
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
90703225
</td>
<td style="text-align:right;">
35305610
</td>
<td style="text-align:right;">
35.792058
</td>
<td style="text-align:right;">
38.924316
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Toulouse 1 - Capitole
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
107123002
</td>
<td style="text-align:right;">
24915334
</td>
<td style="text-align:right;">
20.012629
</td>
<td style="text-align:right;">
23.258622
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
ABES - Agence bibliographique de l’enseignement supérieur
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
51606209
</td>
<td style="text-align:right;">
21649449
</td>
<td style="text-align:right;">
38.939718
</td>
<td style="text-align:right;">
41.951248
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
École normale supérieure de Rennes
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
19839524
</td>
<td style="text-align:right;">
1579758
</td>
<td style="text-align:right;">
5.042934
</td>
<td style="text-align:right;">
7.962681
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Nantes
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
319854045
</td>
<td style="text-align:right;">
81514840
</td>
<td style="text-align:right;">
22.025391
</td>
<td style="text-align:right;">
25.485011
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
ENI METZ
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
4678822
</td>
<td style="text-align:right;">
3453624
</td>
<td style="text-align:right;">
70.838856
</td>
<td style="text-align:right;">
73.813962
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure de chimie de Paris
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
12216856
</td>
<td style="text-align:right;">
3092804
</td>
<td style="text-align:right;">
22.727599
</td>
<td style="text-align:right;">
25.315872
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
École pratique des hautes études
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
39336084
</td>
<td style="text-align:right;">
7451915
</td>
<td style="text-align:right;">
16.139593
</td>
<td style="text-align:right;">
18.944222
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Versailles Saint-Quentin-en-Yvelines
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
144741546
</td>
<td style="text-align:right;">
36793439
</td>
<td style="text-align:right;">
22.076277
</td>
<td style="text-align:right;">
25.420095
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
94181739
</td>
<td style="text-align:right;">
13182683
</td>
<td style="text-align:right;">
11.042005
</td>
<td style="text-align:right;">
13.997069
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure de l’électronique et de ses applications de
Cergy
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
4877465
</td>
<td style="text-align:right;">
2706497
</td>
<td style="text-align:right;">
52.459997
</td>
<td style="text-align:right;">
55.489829
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure de l’électronique et de ses applications de
Cergy
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
5744380
</td>
<td style="text-align:right;">
3584834
</td>
<td style="text-align:right;">
58.957625
</td>
<td style="text-align:right;">
62.405934
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Franche-Comté
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
197272936
</td>
<td style="text-align:right;">
34289976
</td>
<td style="text-align:right;">
13.967394
</td>
<td style="text-align:right;">
17.381997
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Montpellier
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
388969865
</td>
<td style="text-align:right;">
98997392
</td>
<td style="text-align:right;">
22.652969
</td>
<td style="text-align:right;">
25.451173
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut d’études politiques de Grenoble
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
5154362
</td>
<td style="text-align:right;">
3732058
</td>
<td style="text-align:right;">
69.363619
</td>
<td style="text-align:right;">
72.405819
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Jean Monnet
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
129059338
</td>
<td style="text-align:right;">
26239169
</td>
<td style="text-align:right;">
17.399796
</td>
<td style="text-align:right;">
20.331089
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Nantes
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
291544061
</td>
<td style="text-align:right;">
57849006
</td>
<td style="text-align:right;">
16.986370
</td>
<td style="text-align:right;">
19.842286
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Reims Champagne-Ardenne
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
195513254
</td>
<td style="text-align:right;">
31554133
</td>
<td style="text-align:right;">
12.882439
</td>
<td style="text-align:right;">
16.139127
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure des arts et industries textiles
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
4203138
</td>
<td style="text-align:right;">
3216366
</td>
<td style="text-align:right;">
73.094459
</td>
<td style="text-align:right;">
76.522969
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
SIGMA Clermont
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
16719720
</td>
<td style="text-align:right;">
3947323
</td>
<td style="text-align:right;">
20.561397
</td>
<td style="text-align:right;">
23.608787
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Strasbourg
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
425880523
</td>
<td style="text-align:right;">
111728854
</td>
<td style="text-align:right;">
23.367511
</td>
<td style="text-align:right;">
26.234788
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure des sciences de l’information et des
bibliothèques
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
2624942
</td>
<td style="text-align:right;">
588060
</td>
<td style="text-align:right;">
18.920799
</td>
<td style="text-align:right;">
22.402781
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Paris sciences et lettres
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
17858772
</td>
<td style="text-align:right;">
11443699
</td>
<td style="text-align:right;">
61.397043
</td>
<td style="text-align:right;">
64.078868
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Toulon
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
78315643
</td>
<td style="text-align:right;">
11042328
</td>
<td style="text-align:right;">
10.622464
</td>
<td style="text-align:right;">
14.099773
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure d’ingénieurs de Caen
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
15671580
</td>
<td style="text-align:right;">
4701235
</td>
<td style="text-align:right;">
26.758846
</td>
<td style="text-align:right;">
29.998472
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Normandie Université
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
10354882
</td>
<td style="text-align:right;">
9889407
</td>
<td style="text-align:right;">
92.648212
</td>
<td style="text-align:right;">
95.504777
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Bordeaux
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
474069718
</td>
<td style="text-align:right;">
150317556
</td>
<td style="text-align:right;">
28.915133
</td>
<td style="text-align:right;">
31.707901
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut d’études politiques de Rennes
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
3773648
</td>
<td style="text-align:right;">
2692582
</td>
<td style="text-align:right;">
68.369970
</td>
<td style="text-align:right;">
71.352230
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut d’études politiques de Rennes
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
3693203
</td>
<td style="text-align:right;">
2586502
</td>
<td style="text-align:right;">
67.145916
</td>
<td style="text-align:right;">
70.034114
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Clermont Auvergne
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
303740518
</td>
<td style="text-align:right;">
68150867
</td>
<td style="text-align:right;">
19.865698
</td>
<td style="text-align:right;">
22.437200
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Jean Moulin - Lyon 3
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
112263282
</td>
<td style="text-align:right;">
25404489
</td>
<td style="text-align:right;">
19.388786
</td>
<td style="text-align:right;">
22.629384
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris Diderot
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
302314795
</td>
<td style="text-align:right;">
49695640
</td>
<td style="text-align:right;">
13.068405
</td>
<td style="text-align:right;">
16.438375
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Paris
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
612540056
</td>
<td style="text-align:right;">
125765119
</td>
<td style="text-align:right;">
17.881667
</td>
<td style="text-align:right;">
20.531738
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
CentraleSupélec
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
92998371
</td>
<td style="text-align:right;">
46175098
</td>
<td style="text-align:right;">
46.840319
</td>
<td style="text-align:right;">
49.651513
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de La Rochelle
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
74479711
</td>
<td style="text-align:right;">
14805912
</td>
<td style="text-align:right;">
16.419092
</td>
<td style="text-align:right;">
19.879121
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Franche-Comté
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
208722823
</td>
<td style="text-align:right;">
45778996
</td>
<td style="text-align:right;">
18.441844
</td>
<td style="text-align:right;">
21.932913
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université François-Rabelais
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
192710618
</td>
<td style="text-align:right;">
36144593
</td>
<td style="text-align:right;">
15.465868
</td>
<td style="text-align:right;">
18.755891
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Lorraine
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
594198141
</td>
<td style="text-align:right;">
119134744
</td>
<td style="text-align:right;">
16.907655
</td>
<td style="text-align:right;">
20.049666
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut d’études politiques de Lyon
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
4984697
</td>
<td style="text-align:right;">
3413718
</td>
<td style="text-align:right;">
65.521876
</td>
<td style="text-align:right;">
68.483962
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Le Mans Université
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
92926390
</td>
<td style="text-align:right;">
20325380
</td>
<td style="text-align:right;">
18.801443
</td>
<td style="text-align:right;">
21.872560
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
École normale supérieure de Paris
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
119363091
</td>
<td style="text-align:right;">
33643731
</td>
<td style="text-align:right;">
24.839520
</td>
<td style="text-align:right;">
28.186042
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
École pratique des hautes études
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
40269590
</td>
<td style="text-align:right;">
7655796
</td>
<td style="text-align:right;">
16.007014
</td>
<td style="text-align:right;">
19.011358
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Limoges
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
155226444
</td>
<td style="text-align:right;">
34181469
</td>
<td style="text-align:right;">
19.265535
</td>
<td style="text-align:right;">
22.020390
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris Nanterre
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
192403246
</td>
<td style="text-align:right;">
28305174
</td>
<td style="text-align:right;">
11.964863
</td>
<td style="text-align:right;">
14.711381
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national supérieur de formation et de recherche pour
l’éducation des jeunes handicapés et les enseignements adaptés
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
1848971
</td>
<td style="text-align:right;">
1375217
</td>
<td style="text-align:right;">
71.799720
</td>
<td style="text-align:right;">
74.377424
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut supérieur de mécanique de Paris
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
3925609
</td>
<td style="text-align:right;">
2014664
</td>
<td style="text-align:right;">
48.317217
</td>
<td style="text-align:right;">
51.321056
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Casa de Velázquez de Madrid
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
6984791
</td>
<td style="text-align:right;">
739515
</td>
<td style="text-align:right;">
7.133814
</td>
<td style="text-align:right;">
10.587504
</td>
<td style="text-align:right;">
-3
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Toulouse 3 - Paul Sabatier
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
351335357
</td>
<td style="text-align:right;">
66900754
</td>
<td style="text-align:right;">
14.836282
</td>
<td style="text-align:right;">
19.041851
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Montpellier 3 - Paul-Valéry
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
110224555
</td>
<td style="text-align:right;">
21032180
</td>
<td style="text-align:right;">
15.232223
</td>
<td style="text-align:right;">
19.081211
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Rennes 1
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
267024454
</td>
<td style="text-align:right;">
70839548
</td>
<td style="text-align:right;">
22.591846
</td>
<td style="text-align:right;">
26.529236
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Jean Monnet
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
121171085
</td>
<td style="text-align:right;">
26860136
</td>
<td style="text-align:right;">
17.755894
</td>
<td style="text-align:right;">
22.167117
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Bretagne-Sud
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
87040501
</td>
<td style="text-align:right;">
25874330
</td>
<td style="text-align:right;">
26.211919
</td>
<td style="text-align:right;">
29.726771
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure des arts et techniques du théâtre
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
2106149
</td>
<td style="text-align:right;">
735963
</td>
<td style="text-align:right;">
30.918610
</td>
<td style="text-align:right;">
34.943539
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris Diderot
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
299329595
</td>
<td style="text-align:right;">
47622218
</td>
<td style="text-align:right;">
11.908487
</td>
<td style="text-align:right;">
15.909626
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Sorbonne Université
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
634808624
</td>
<td style="text-align:right;">
169658203
</td>
<td style="text-align:right;">
22.808590
</td>
<td style="text-align:right;">
26.725882
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
École française de Rome
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
6962150
</td>
<td style="text-align:right;">
907410
</td>
<td style="text-align:right;">
9.500470
</td>
<td style="text-align:right;">
13.033474
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de la Nouvelle-Calédonie
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
31183523
</td>
<td style="text-align:right;">
5354798
</td>
<td style="text-align:right;">
13.116081
</td>
<td style="text-align:right;">
17.171883
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de la Polynésie Française
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
29251070
</td>
<td style="text-align:right;">
3647388
</td>
<td style="text-align:right;">
8.298284
</td>
<td style="text-align:right;">
12.469246
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Toulouse - Jean Jaurès
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
177668992
</td>
<td style="text-align:right;">
16587112
</td>
<td style="text-align:right;">
5.456353
</td>
<td style="text-align:right;">
9.335963
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
École centrale de Nantes
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
40396187
</td>
<td style="text-align:right;">
19829400
</td>
<td style="text-align:right;">
45.545727
</td>
<td style="text-align:right;">
49.087306
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Reims Champagne-Ardenne
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
199841214
</td>
<td style="text-align:right;">
33905684
</td>
<td style="text-align:right;">
13.302696
</td>
<td style="text-align:right;">
16.966312
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Strasbourg
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
467499672
</td>
<td style="text-align:right;">
143433084
</td>
<td style="text-align:right;">
27.109083
</td>
<td style="text-align:right;">
30.680895
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Claude Bernard - Lyon 1
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
358184109
</td>
<td style="text-align:right;">
80504737
</td>
<td style="text-align:right;">
18.825637
</td>
<td style="text-align:right;">
22.475798
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Claude Bernard - Lyon 1
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
380452718
</td>
<td style="text-align:right;">
89556059
</td>
<td style="text-align:right;">
19.742661
</td>
<td style="text-align:right;">
23.539340
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris Descartes
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
303094298
</td>
<td style="text-align:right;">
76511388
</td>
<td style="text-align:right;">
21.278431
</td>
<td style="text-align:right;">
25.243427
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Conservatoire national des arts et métiers
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
152056980
</td>
<td style="text-align:right;">
48169900
</td>
<td style="text-align:right;">
27.310779
</td>
<td style="text-align:right;">
31.678848
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Rouen
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
216502699
</td>
<td style="text-align:right;">
41591922
</td>
<td style="text-align:right;">
14.987351
</td>
<td style="text-align:right;">
19.210810
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Limoges
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
150856680
</td>
<td style="text-align:right;">
31830786
</td>
<td style="text-align:right;">
17.053696
</td>
<td style="text-align:right;">
21.100018
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Côte d’Azur
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
258401602
</td>
<td style="text-align:right;">
65980858
</td>
<td style="text-align:right;">
21.902157
</td>
<td style="text-align:right;">
25.534229
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Toulouse 3 - Paul Sabatier
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
346349024
</td>
<td style="text-align:right;">
67793677
</td>
<td style="text-align:right;">
15.705298
</td>
<td style="text-align:right;">
19.573803
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure de chimie de Montpellier
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
12503635
</td>
<td style="text-align:right;">
3711053
</td>
<td style="text-align:right;">
25.692729
</td>
<td style="text-align:right;">
29.679793
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure de chimie de Montpellier
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
12204560
</td>
<td style="text-align:right;">
3403377
</td>
<td style="text-align:right;">
24.196325
</td>
<td style="text-align:right;">
27.886110
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national des sciences appliquées de Rennes
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
39662598
</td>
<td style="text-align:right;">
10754806
</td>
<td style="text-align:right;">
23.603111
</td>
<td style="text-align:right;">
27.115738
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Rennes 2
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
112031397
</td>
<td style="text-align:right;">
19927972
</td>
<td style="text-align:right;">
13.478354
</td>
<td style="text-align:right;">
17.787846
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Grenoble INP
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
110755560
</td>
<td style="text-align:right;">
35921494
</td>
<td style="text-align:right;">
28.775912
</td>
<td style="text-align:right;">
32.433129
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université d’Angers
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
148702818
</td>
<td style="text-align:right;">
31428953
</td>
<td style="text-align:right;">
16.714043
</td>
<td style="text-align:right;">
21.135412
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Clermont Auvergne
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
290700428
</td>
<td style="text-align:right;">
59957538
</td>
<td style="text-align:right;">
16.490990
</td>
<td style="text-align:right;">
20.625198
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Strasbourg
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
499708352
</td>
<td style="text-align:right;">
175055456
</td>
<td style="text-align:right;">
30.854058
</td>
<td style="text-align:right;">
35.031525
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national des sciences appliquées de Lyon
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
54337731
</td>
<td style="text-align:right;">
36081716
</td>
<td style="text-align:right;">
62.466471
</td>
<td style="text-align:right;">
66.402692
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Claude Bernard - Lyon 1
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
380736199
</td>
<td style="text-align:right;">
91920499
</td>
<td style="text-align:right;">
20.374580
</td>
<td style="text-align:right;">
24.142831
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Le Mans Université
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
89167073
</td>
<td style="text-align:right;">
17247106
</td>
<td style="text-align:right;">
15.066636
</td>
<td style="text-align:right;">
19.342461
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Versailles Saint-Quentin-en-Yvelines
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
146925970
</td>
<td style="text-align:right;">
36105604
</td>
<td style="text-align:right;">
21.011595
</td>
<td style="text-align:right;">
24.574011
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Toulon
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
85676318
</td>
<td style="text-align:right;">
17288818
</td>
<td style="text-align:right;">
15.796114
</td>
<td style="text-align:right;">
20.179226
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Limoges
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
168648260
</td>
<td style="text-align:right;">
47375593
</td>
<td style="text-align:right;">
24.533661
</td>
<td style="text-align:right;">
28.091362
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de La Rochelle
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
74490331
</td>
<td style="text-align:right;">
16274054
</td>
<td style="text-align:right;">
18.279155
</td>
<td style="text-align:right;">
21.847203
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure de chimie de Rennes
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
8521096
</td>
<td style="text-align:right;">
1880393
</td>
<td style="text-align:right;">
18.219523
</td>
<td style="text-align:right;">
22.067502
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Strasbourg
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
456794814
</td>
<td style="text-align:right;">
137829468
</td>
<td style="text-align:right;">
25.819015
</td>
<td style="text-align:right;">
30.173168
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Toulon
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
83371084
</td>
<td style="text-align:right;">
14805493
</td>
<td style="text-align:right;">
13.687386
</td>
<td style="text-align:right;">
17.758547
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Cergy-Pontoise
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
152161522
</td>
<td style="text-align:right;">
33910615
</td>
<td style="text-align:right;">
18.303011
</td>
<td style="text-align:right;">
22.285933
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Caen Normandie
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
224796758
</td>
<td style="text-align:right;">
42237645
</td>
<td style="text-align:right;">
14.884396
</td>
<td style="text-align:right;">
18.789259
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national polytechnique de Toulouse
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
90721035
</td>
<td style="text-align:right;">
35915359
</td>
<td style="text-align:right;">
36.085176
</td>
<td style="text-align:right;">
39.588789
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut d’études politiques de Bordeaux
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
7750084
</td>
<td style="text-align:right;">
6276778
</td>
<td style="text-align:right;">
76.650782
</td>
<td style="text-align:right;">
80.989806
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national des sciences appliquées de Rennes
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
40737191
</td>
<td style="text-align:right;">
10612084
</td>
<td style="text-align:right;">
22.308600
</td>
<td style="text-align:right;">
26.050112
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Rennes 2
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
111378481
</td>
<td style="text-align:right;">
21010319
</td>
<td style="text-align:right;">
15.261275
</td>
<td style="text-align:right;">
18.863894
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Nantes
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
333646686
</td>
<td style="text-align:right;">
90939836
</td>
<td style="text-align:right;">
23.622901
</td>
<td style="text-align:right;">
27.256328
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut d’études politiques de Lille
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
5745418
</td>
<td style="text-align:right;">
4494962
</td>
<td style="text-align:right;">
73.755173
</td>
<td style="text-align:right;">
78.235596
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Lille
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
571095700
</td>
<td style="text-align:right;">
106795519
</td>
<td style="text-align:right;">
14.886409
</td>
<td style="text-align:right;">
18.700109
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Pau et des Pays de l’Adour
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
113084650
</td>
<td style="text-align:right;">
26599526
</td>
<td style="text-align:right;">
19.405875
</td>
<td style="text-align:right;">
23.521783
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Perpignan - Via Domitia
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
78417863
</td>
<td style="text-align:right;">
18633088
</td>
<td style="text-align:right;">
19.605807
</td>
<td style="text-align:right;">
23.761280
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Le Mans Université
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
86753573
</td>
<td style="text-align:right;">
17570043
</td>
<td style="text-align:right;">
15.910136
</td>
<td style="text-align:right;">
20.252818
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris-Est Marne-la-Vallée
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
101037276
</td>
<td style="text-align:right;">
25274718
</td>
<td style="text-align:right;">
20.802559
</td>
<td style="text-align:right;">
25.015241
</td>
<td style="text-align:right;">
-4
</td>
</tr>
<tr>
<td style="text-align:left;">
École normale supérieure de Lyon
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
127364851
</td>
<td style="text-align:right;">
21934241
</td>
<td style="text-align:right;">
11.898808
</td>
<td style="text-align:right;">
17.221581
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Muséum national d’histoire naturelle
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
94637929
</td>
<td style="text-align:right;">
50989355
</td>
<td style="text-align:right;">
48.646341
</td>
<td style="text-align:right;">
53.878350
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Picardie Jules-Verne
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
189555981
</td>
<td style="text-align:right;">
35075713
</td>
<td style="text-align:right;">
13.894150
</td>
<td style="text-align:right;">
18.504145
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Toulon
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
81720213
</td>
<td style="text-align:right;">
15192467
</td>
<td style="text-align:right;">
13.383762
</td>
<td style="text-align:right;">
18.590831
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
École centrale de Marseille
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
18184670
</td>
<td style="text-align:right;">
4660487
</td>
<td style="text-align:right;">
20.331240
</td>
<td style="text-align:right;">
25.628659
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Bordeaux
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
459955942
</td>
<td style="text-align:right;">
148065495
</td>
<td style="text-align:right;">
26.771588
</td>
<td style="text-align:right;">
32.191234
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national des sciences appliquées de Lyon
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
55126750
</td>
<td style="text-align:right;">
39712835
</td>
<td style="text-align:right;">
66.675079
</td>
<td style="text-align:right;">
72.039137
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Claude Bernard - Lyon 1
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
391847217
</td>
<td style="text-align:right;">
102711047
</td>
<td style="text-align:right;">
21.661220
</td>
<td style="text-align:right;">
26.212014
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national d’histoire de l’art
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
11712145
</td>
<td style="text-align:right;">
2913854
</td>
<td style="text-align:right;">
19.875360
</td>
<td style="text-align:right;">
24.878910
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Nice - Sophia-Antipolis
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
224034128
</td>
<td style="text-align:right;">
45915556
</td>
<td style="text-align:right;">
15.155048
</td>
<td style="text-align:right;">
20.494893
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Caen Normandie
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
220752870
</td>
<td style="text-align:right;">
41402103
</td>
<td style="text-align:right;">
13.880920
</td>
<td style="text-align:right;">
18.754956
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national des sciences appliquées Centre Val de Loire
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
19888158
</td>
<td style="text-align:right;">
5875853
</td>
<td style="text-align:right;">
24.662686
</td>
<td style="text-align:right;">
29.544481
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Rennes 1
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
270586259
</td>
<td style="text-align:right;">
73841499
</td>
<td style="text-align:right;">
21.878465
</td>
<td style="text-align:right;">
27.289449
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Université d’Orléans
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
170748238
</td>
<td style="text-align:right;">
39561176
</td>
<td style="text-align:right;">
17.968807
</td>
<td style="text-align:right;">
23.169303
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut d’études politiques de Lyon
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
4924622
</td>
<td style="text-align:right;">
3159920
</td>
<td style="text-align:right;">
59.439202
</td>
<td style="text-align:right;">
64.165737
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national des sciences appliquées de Lyon
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
134071624
</td>
<td style="text-align:right;">
44919554
</td>
<td style="text-align:right;">
28.820882
</td>
<td style="text-align:right;">
33.504147
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
École normale supérieure de Paris
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
113419996
</td>
<td style="text-align:right;">
32870233
</td>
<td style="text-align:right;">
23.851736
</td>
<td style="text-align:right;">
28.980986
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
École pratique des hautes études
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
37879752
</td>
<td style="text-align:right;">
6592308
</td>
<td style="text-align:right;">
12.554472
</td>
<td style="text-align:right;">
17.403250
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national des sciences appliquées de Rouen
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
34951406
</td>
<td style="text-align:right;">
12268816
</td>
<td style="text-align:right;">
29.603181
</td>
<td style="text-align:right;">
35.102496
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national des sciences appliquées de Rouen
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
35409984
</td>
<td style="text-align:right;">
12363057
</td>
<td style="text-align:right;">
29.417090
</td>
<td style="text-align:right;">
34.914043
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale d’ingénieurs de Brest
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
2158144
</td>
<td style="text-align:right;">
1193672
</td>
<td style="text-align:right;">
49.958853
</td>
<td style="text-align:right;">
55.310111
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national des sciences appliquées de Toulouse
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
56560445
</td>
<td style="text-align:right;">
18666509
</td>
<td style="text-align:right;">
27.950604
</td>
<td style="text-align:right;">
33.002762
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut polytechnique de Bordeaux
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
13719867
</td>
<td style="text-align:right;">
7581108
</td>
<td style="text-align:right;">
49.829973
</td>
<td style="text-align:right;">
55.256425
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Rennes 1
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
260014006
</td>
<td style="text-align:right;">
61462671
</td>
<td style="text-align:right;">
18.958190
</td>
<td style="text-align:right;">
23.638216
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Grenoble INP
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
112726721
</td>
<td style="text-align:right;">
40163554
</td>
<td style="text-align:right;">
30.529119
</td>
<td style="text-align:right;">
35.629134
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Lille
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
536790729
</td>
<td style="text-align:right;">
114448862
</td>
<td style="text-align:right;">
16.397770
</td>
<td style="text-align:right;">
21.320946
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de technologie de Compiègne
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
59507871
</td>
<td style="text-align:right;">
13999168
</td>
<td style="text-align:right;">
19.006551
</td>
<td style="text-align:right;">
23.524901
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Perpignan - Via Domitia
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
70747520
</td>
<td style="text-align:right;">
13777701
</td>
<td style="text-align:right;">
14.147200
</td>
<td style="text-align:right;">
19.474465
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
École centrale de Lyon
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
32765730
</td>
<td style="text-align:right;">
9451944
</td>
<td style="text-align:right;">
23.394046
</td>
<td style="text-align:right;">
28.847044
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure des arts et techniques du théâtre
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
1957402
</td>
<td style="text-align:right;">
731560
</td>
<td style="text-align:right;">
32.003901
</td>
<td style="text-align:right;">
37.374029
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut d’administration des entreprises de Paris
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
11630641
</td>
<td style="text-align:right;">
11320109
</td>
<td style="text-align:right;">
92.191497
</td>
<td style="text-align:right;">
97.330053
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de technologie de Troyes
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
37186006
</td>
<td style="text-align:right;">
13492734
</td>
<td style="text-align:right;">
31.611553
</td>
<td style="text-align:right;">
36.284440
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Caen Normandie
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
230556388
</td>
<td style="text-align:right;">
48169933
</td>
<td style="text-align:right;">
15.903754
</td>
<td style="text-align:right;">
20.892908
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure de chimie de Rennes
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
8729765
</td>
<td style="text-align:right;">
2128566
</td>
<td style="text-align:right;">
19.161329
</td>
<td style="text-align:right;">
24.382856
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Grenoble Alpes
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
500456196
</td>
<td style="text-align:right;">
156052259
</td>
<td style="text-align:right;">
26.082798
</td>
<td style="text-align:right;">
31.182002
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Reims Champagne-Ardenne
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
199435757
</td>
<td style="text-align:right;">
36962485
</td>
<td style="text-align:right;">
13.784744
</td>
<td style="text-align:right;">
18.533530
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Bretagne-Sud
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
85734436
</td>
<td style="text-align:right;">
24324734
</td>
<td style="text-align:right;">
23.479238
</td>
<td style="text-align:right;">
28.372186
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de technologie de Compiègne
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
63066570
</td>
<td style="text-align:right;">
18310276
</td>
<td style="text-align:right;">
24.489261
</td>
<td style="text-align:right;">
29.033252
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Clermont Auvergne
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
285999842
</td>
<td style="text-align:right;">
61650735
</td>
<td style="text-align:right;">
16.216608
</td>
<td style="text-align:right;">
21.556213
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Strasbourg
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
479911121
</td>
<td style="text-align:right;">
157965204
</td>
<td style="text-align:right;">
28.204814
</td>
<td style="text-align:right;">
32.915512
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Le Mans Université
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
88599297
</td>
<td style="text-align:right;">
19696772
</td>
<td style="text-align:right;">
16.733582
</td>
<td style="text-align:right;">
22.231296
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
École française d’Extrême-Orient
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
10201205
</td>
<td style="text-align:right;">
2641190
</td>
<td style="text-align:right;">
21.024163
</td>
<td style="text-align:right;">
25.890961
</td>
<td style="text-align:right;">
-5
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Franche-Comté
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
196827277
</td>
<td style="text-align:right;">
40649000
</td>
<td style="text-align:right;">
14.784224
</td>
<td style="text-align:right;">
20.652117
</td>
<td style="text-align:right;">
-6
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Nîmes
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
20789895
</td>
<td style="text-align:right;">
3301331
</td>
<td style="text-align:right;">
9.906635
</td>
<td style="text-align:right;">
15.879498
</td>
<td style="text-align:right;">
-6
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Pau et des Pays de l’Adour
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
122870077
</td>
<td style="text-align:right;">
35611078
</td>
<td style="text-align:right;">
23.424760
</td>
<td style="text-align:right;">
28.982710
</td>
<td style="text-align:right;">
-6
</td>
</tr>
<tr>
<td style="text-align:left;">
École centrale de Lyon
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
36691520
</td>
<td style="text-align:right;">
13194426
</td>
<td style="text-align:right;">
30.075047
</td>
<td style="text-align:right;">
35.960424
</td>
<td style="text-align:right;">
-6
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national des sciences appliquées de Rouen
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
35565909
</td>
<td style="text-align:right;">
13006898
</td>
<td style="text-align:right;">
30.265893
</td>
<td style="text-align:right;">
36.571251
</td>
<td style="text-align:right;">
-6
</td>
</tr>
<tr>
<td style="text-align:left;">
Observatoire de la côte d’azur
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
3623066
</td>
<td style="text-align:right;">
1858795
</td>
<td style="text-align:right;">
45.601626
</td>
<td style="text-align:right;">
51.304475
</td>
<td style="text-align:right;">
-6
</td>
</tr>
<tr>
<td style="text-align:left;">
École centrale de Marseille
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
19642381
</td>
<td style="text-align:right;">
6063384
</td>
<td style="text-align:right;">
25.081659
</td>
<td style="text-align:right;">
30.868885
</td>
<td style="text-align:right;">
-6
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut d’études politiques de Toulouse
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
4230847
</td>
<td style="text-align:right;">
2573591
</td>
<td style="text-align:right;">
54.824649
</td>
<td style="text-align:right;">
60.829215
</td>
<td style="text-align:right;">
-6
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Toulouse - Jean Jaurès
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
178943540
</td>
<td style="text-align:right;">
23419922
</td>
<td style="text-align:right;">
7.163713
</td>
<td style="text-align:right;">
13.087884
</td>
<td style="text-align:right;">
-6
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Rennes 1
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
255640841
</td>
<td style="text-align:right;">
65137996
</td>
<td style="text-align:right;">
19.067565
</td>
<td style="text-align:right;">
25.480278
</td>
<td style="text-align:right;">
-6
</td>
</tr>
<tr>
<td style="text-align:left;">
Université François-Rabelais
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
197869370
</td>
<td style="text-align:right;">
45895176
</td>
<td style="text-align:right;">
17.116411
</td>
<td style="text-align:right;">
23.194685
</td>
<td style="text-align:right;">
-6
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Jean Monnet
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
132685860
</td>
<td style="text-align:right;">
33038706
</td>
<td style="text-align:right;">
18.946065
</td>
<td style="text-align:right;">
24.899945
</td>
<td style="text-align:right;">
-6
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Perpignan - Via Domitia
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
73584960
</td>
<td style="text-align:right;">
16034467
</td>
<td style="text-align:right;">
15.339595
</td>
<td style="text-align:right;">
21.790413
</td>
<td style="text-align:right;">
-6
</td>
</tr>
<tr>
<td style="text-align:left;">
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
23441672
</td>
<td style="text-align:right;">
19271599
</td>
<td style="text-align:right;">
76.334982
</td>
<td style="text-align:right;">
82.210855
</td>
<td style="text-align:right;">
-6
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national des sciences appliquées de Rouen
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
40067116
</td>
<td style="text-align:right;">
17557766
</td>
<td style="text-align:right;">
37.558179
</td>
<td style="text-align:right;">
43.820888
</td>
<td style="text-align:right;">
-6
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure de mécanique et d’aérotechnique de Poitiers
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
16308805
</td>
<td style="text-align:right;">
6085966
</td>
<td style="text-align:right;">
31.405894
</td>
<td style="text-align:right;">
37.317057
</td>
<td style="text-align:right;">
-6
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Jean Monnet
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
136961562
</td>
<td style="text-align:right;">
36025913
</td>
<td style="text-align:right;">
20.283958
</td>
<td style="text-align:right;">
26.303667
</td>
<td style="text-align:right;">
-6
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale d’ingénieurs de Tarbes
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
17794479
</td>
<td style="text-align:right;">
5152629
</td>
<td style="text-align:right;">
22.593266
</td>
<td style="text-align:right;">
28.956335
</td>
<td style="text-align:right;">
-6
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure d’arts et métiers
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
98650790
</td>
<td style="text-align:right;">
30968681
</td>
<td style="text-align:right;">
25.558894
</td>
<td style="text-align:right;">
31.392228
</td>
<td style="text-align:right;">
-6
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure de chimie de Paris
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
13614068
</td>
<td style="text-align:right;">
3862147
</td>
<td style="text-align:right;">
21.976341
</td>
<td style="text-align:right;">
28.368795
</td>
<td style="text-align:right;">
-6
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut de physique du globe
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
11003549
</td>
<td style="text-align:right;">
7893625
</td>
<td style="text-align:right;">
65.583050
</td>
<td style="text-align:right;">
71.737082
</td>
<td style="text-align:right;">
-6
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Nice - Sophia-Antipolis
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
229201484
</td>
<td style="text-align:right;">
52114763
</td>
<td style="text-align:right;">
16.917394
</td>
<td style="text-align:right;">
22.737533
</td>
<td style="text-align:right;">
-6
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national des sciences appliquées Centre Val de Loire
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
19429344
</td>
<td style="text-align:right;">
5701261
</td>
<td style="text-align:right;">
22.845620
</td>
<td style="text-align:right;">
29.343559
</td>
<td style="text-align:right;">
-6
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Toulouse - Jean Jaurès
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
181429641
</td>
<td style="text-align:right;">
23537689
</td>
<td style="text-align:right;">
6.973649
</td>
<td style="text-align:right;">
12.973453
</td>
<td style="text-align:right;">
-6
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Grenoble Alpes
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
463893194
</td>
<td style="text-align:right;">
131429324
</td>
<td style="text-align:right;">
22.174090
</td>
<td style="text-align:right;">
28.331807
</td>
<td style="text-align:right;">
-6
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Grenoble Alpes
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
475310540
</td>
<td style="text-align:right;">
135014688
</td>
<td style="text-align:right;">
22.276100
</td>
<td style="text-align:right;">
28.405574
</td>
<td style="text-align:right;">
-6
</td>
</tr>
<tr>
<td style="text-align:left;">
Musée du quai Branly
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
51813395
</td>
<td style="text-align:right;">
10560622
</td>
<td style="text-align:right;">
14.033736
</td>
<td style="text-align:right;">
20.382031
</td>
<td style="text-align:right;">
-6
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris-Est
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
20832094
</td>
<td style="text-align:right;">
21089673
</td>
<td style="text-align:right;">
95.627914
</td>
<td style="text-align:right;">
101.236453
</td>
<td style="text-align:right;">
-6
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de technologie de Troyes
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
43454819
</td>
<td style="text-align:right;">
20248998
</td>
<td style="text-align:right;">
40.181415
</td>
<td style="text-align:right;">
46.597819
</td>
<td style="text-align:right;">
-6
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Bourgogne
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
242846625
</td>
<td style="text-align:right;">
58163457
</td>
<td style="text-align:right;">
17.775973
</td>
<td style="text-align:right;">
23.950696
</td>
<td style="text-align:right;">
-6
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Lorraine
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
571357654
</td>
<td style="text-align:right;">
123149815
</td>
<td style="text-align:right;">
15.349747
</td>
<td style="text-align:right;">
21.553893
</td>
<td style="text-align:right;">
-6
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure des arts et industries textiles
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
3687861
</td>
<td style="text-align:right;">
2691140
</td>
<td style="text-align:right;">
67.387166
</td>
<td style="text-align:right;">
72.972924
</td>
<td style="text-align:right;">
-6
</td>
</tr>
<tr>
<td style="text-align:left;">
Université d’Évry-Val d’Essonne
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
91181392
</td>
<td style="text-align:right;">
24016500
</td>
<td style="text-align:right;">
20.525372
</td>
<td style="text-align:right;">
26.339256
</td>
<td style="text-align:right;">
-6
</td>
</tr>
<tr>
<td style="text-align:left;">
Aix-Marseille université
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
646368001
</td>
<td style="text-align:right;">
179809999
</td>
<td style="text-align:right;">
21.177002
</td>
<td style="text-align:right;">
27.818518
</td>
<td style="text-align:right;">
-7
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Toulouse 1 - Capitole
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
101158194
</td>
<td style="text-align:right;">
28087659
</td>
<td style="text-align:right;">
20.667353
</td>
<td style="text-align:right;">
27.766074
</td>
<td style="text-align:right;">
-7
</td>
</tr>
<tr>
<td style="text-align:left;">
École des hautes études en santé publique
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
57559494
</td>
<td style="text-align:right;">
50836203
</td>
<td style="text-align:right;">
81.219213
</td>
<td style="text-align:right;">
88.319406
</td>
<td style="text-align:right;">
-7
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Lille
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
580718036
</td>
<td style="text-align:right;">
132919902
</td>
<td style="text-align:right;">
16.133931
</td>
<td style="text-align:right;">
22.888888
</td>
<td style="text-align:right;">
-7
</td>
</tr>
<tr>
<td style="text-align:left;">
École normale supérieure de Lyon
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
121923636
</td>
<td style="text-align:right;">
15292790
</td>
<td style="text-align:right;">
5.572107
</td>
<td style="text-align:right;">
12.542925
</td>
<td style="text-align:right;">
-7
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Corse Pasquale Paoli
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
53975139
</td>
<td style="text-align:right;">
17890031
</td>
<td style="text-align:right;">
26.424595
</td>
<td style="text-align:right;">
33.144947
</td>
<td style="text-align:right;">
-7
</td>
</tr>
<tr>
<td style="text-align:left;">
Aix-Marseille université
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
634890534
</td>
<td style="text-align:right;">
169100885
</td>
<td style="text-align:right;">
20.090966
</td>
<td style="text-align:right;">
26.634652
</td>
<td style="text-align:right;">
-7
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Valenciennes et du Hainaut-Cambrésis
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
105915790
</td>
<td style="text-align:right;">
26917721
</td>
<td style="text-align:right;">
17.942495
</td>
<td style="text-align:right;">
25.414266
</td>
<td style="text-align:right;">
-7
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Rouen
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
213508468
</td>
<td style="text-align:right;">
45056471
</td>
<td style="text-align:right;">
13.984680
</td>
<td style="text-align:right;">
21.102896
</td>
<td style="text-align:right;">
-7
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Clermont Auvergne
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
277294633
</td>
<td style="text-align:right;">
58758574
</td>
<td style="text-align:right;">
14.068918
</td>
<td style="text-align:right;">
21.189943
</td>
<td style="text-align:right;">
-7
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut d’études politiques de Lyon
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
4380914
</td>
<td style="text-align:right;">
3009143
</td>
<td style="text-align:right;">
61.765695
</td>
<td style="text-align:right;">
68.687562
</td>
<td style="text-align:right;">
-7
</td>
</tr>
<tr>
<td style="text-align:left;">
Musée du quai Branly
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
49529628
</td>
<td style="text-align:right;">
7151731
</td>
<td style="text-align:right;">
7.266336
</td>
<td style="text-align:right;">
14.439299
</td>
<td style="text-align:right;">
-7
</td>
</tr>
<tr>
<td style="text-align:left;">
Université du Havre
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
75399123
</td>
<td style="text-align:right;">
16559801
</td>
<td style="text-align:right;">
15.049866
</td>
<td style="text-align:right;">
21.962856
</td>
<td style="text-align:right;">
-7
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris 8 - Vincennes - Saint-Denis
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
142912906
</td>
<td style="text-align:right;">
27786017
</td>
<td style="text-align:right;">
12.088507
</td>
<td style="text-align:right;">
19.442623
</td>
<td style="text-align:right;">
-7
</td>
</tr>
<tr>
<td style="text-align:left;">
CY Cergy Paris Université
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
167601090
</td>
<td style="text-align:right;">
50107382
</td>
<td style="text-align:right;">
22.816663
</td>
<td style="text-align:right;">
29.896811
</td>
<td style="text-align:right;">
-7
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Nantes
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
309309842
</td>
<td style="text-align:right;">
81208376
</td>
<td style="text-align:right;">
19.295092
</td>
<td style="text-align:right;">
26.254702
</td>
<td style="text-align:right;">
-7
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure d’arts et métiers
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
98495254
</td>
<td style="text-align:right;">
32574560
</td>
<td style="text-align:right;">
26.399355
</td>
<td style="text-align:right;">
33.072213
</td>
<td style="text-align:right;">
-7
</td>
</tr>
<tr>
<td style="text-align:left;">
Hautes Études-Sorbonne-Arts et Métiers
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
1331152
</td>
<td style="text-align:right;">
1074061
</td>
<td style="text-align:right;">
73.321153
</td>
<td style="text-align:right;">
80.686578
</td>
<td style="text-align:right;">
-7
</td>
</tr>
<tr>
<td style="text-align:left;">
CTLES - Centre technique du livre de l’enseignement supérieur
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
1356918
</td>
<td style="text-align:right;">
597117
</td>
<td style="text-align:right;">
37.335049
</td>
<td style="text-align:right;">
44.005386
</td>
<td style="text-align:right;">
-7
</td>
</tr>
<tr>
<td style="text-align:left;">
Université du Littoral Côte d’Opale
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
84673987
</td>
<td style="text-align:right;">
18424736
</td>
<td style="text-align:right;">
15.196853
</td>
<td style="text-align:right;">
21.759618
</td>
<td style="text-align:right;">
-7
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Rouen
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
212917099
</td>
<td style="text-align:right;">
46536399
</td>
<td style="text-align:right;">
15.101292
</td>
<td style="text-align:right;">
21.856581
</td>
<td style="text-align:right;">
-7
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de la Polynésie Française
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
31017669
</td>
<td style="text-align:right;">
5646439
</td>
<td style="text-align:right;">
11.253528
</td>
<td style="text-align:right;">
18.203944
</td>
<td style="text-align:right;">
-7
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de technologie de Compiègne
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
59890498
</td>
<td style="text-align:right;">
16897824
</td>
<td style="text-align:right;">
19.733109
</td>
<td style="text-align:right;">
28.214533
</td>
<td style="text-align:right;">
-8
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Poitiers
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
239984061
</td>
<td style="text-align:right;">
53269775
</td>
<td style="text-align:right;">
13.989407
</td>
<td style="text-align:right;">
22.197214
</td>
<td style="text-align:right;">
-8
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure d’informatique pour l’industrie et
l’entreprise
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
7055743
</td>
<td style="text-align:right;">
1960444
</td>
<td style="text-align:right;">
19.709533
</td>
<td style="text-align:right;">
27.785082
</td>
<td style="text-align:right;">
-8
</td>
</tr>
<tr>
<td style="text-align:left;">
CentraleSupélec
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
91802056
</td>
<td style="text-align:right;">
49731935
</td>
<td style="text-align:right;">
46.168461
</td>
<td style="text-align:right;">
54.173008
</td>
<td style="text-align:right;">
-8
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale d’ingénieurs de Tarbes
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
19473365
</td>
<td style="text-align:right;">
6933917
</td>
<td style="text-align:right;">
27.771163
</td>
<td style="text-align:right;">
35.607185
</td>
<td style="text-align:right;">
-8
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national des sciences appliquées de Strasbourg
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
22692320
</td>
<td style="text-align:right;">
5903093
</td>
<td style="text-align:right;">
18.286270
</td>
<td style="text-align:right;">
26.013616
</td>
<td style="text-align:right;">
-8
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Haute-Alsace
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
107477451
</td>
<td style="text-align:right;">
39792772
</td>
<td style="text-align:right;">
28.967396
</td>
<td style="text-align:right;">
37.024298
</td>
<td style="text-align:right;">
-8
</td>
</tr>
<tr>
<td style="text-align:left;">
Musée du quai Branly
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
54379060
</td>
<td style="text-align:right;">
14112296
</td>
<td style="text-align:right;">
18.089721
</td>
<td style="text-align:right;">
25.951710
</td>
<td style="text-align:right;">
-8
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de technologie de Compiègne
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
61902915
</td>
<td style="text-align:right;">
19230473
</td>
<td style="text-align:right;">
22.633987
</td>
<td style="text-align:right;">
31.065537
</td>
<td style="text-align:right;">
-8
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris Descartes
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
299220576
</td>
<td style="text-align:right;">
84389602
</td>
<td style="text-align:right;">
20.194501
</td>
<td style="text-align:right;">
28.203141
</td>
<td style="text-align:right;">
-8
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure d’arts et métiers
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
105072716
</td>
<td style="text-align:right;">
39931715
</td>
<td style="text-align:right;">
30.463022
</td>
<td style="text-align:right;">
38.003886
</td>
<td style="text-align:right;">
-8
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Toulouse 3 - Paul Sabatier
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
377922991
</td>
<td style="text-align:right;">
109152804
</td>
<td style="text-align:right;">
21.192755
</td>
<td style="text-align:right;">
28.882287
</td>
<td style="text-align:right;">
-8
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Montpellier
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
451401748
</td>
<td style="text-align:right;">
184510079
</td>
<td style="text-align:right;">
33.317053
</td>
<td style="text-align:right;">
40.874915
</td>
<td style="text-align:right;">
-8
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale des Chartes
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
3349345
</td>
<td style="text-align:right;">
783245
</td>
<td style="text-align:right;">
15.169891
</td>
<td style="text-align:right;">
23.385020
</td>
<td style="text-align:right;">
-8
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Toulouse 3 - Paul Sabatier
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
356585435
</td>
<td style="text-align:right;">
94798315
</td>
<td style="text-align:right;">
17.432027
</td>
<td style="text-align:right;">
26.585022
</td>
<td style="text-align:right;">
-9
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris Lumières
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
2811732
</td>
<td style="text-align:right;">
1866729
</td>
<td style="text-align:right;">
57.320541
</td>
<td style="text-align:right;">
66.390716
</td>
<td style="text-align:right;">
-9
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut supérieur de mécanique de Paris
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
3951939
</td>
<td style="text-align:right;">
2220393
</td>
<td style="text-align:right;">
47.083875
</td>
<td style="text-align:right;">
56.184901
</td>
<td style="text-align:right;">
-9
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Jean Monnet
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
131281129
</td>
<td style="text-align:right;">
34249237
</td>
<td style="text-align:right;">
17.149471
</td>
<td style="text-align:right;">
26.088469
</td>
<td style="text-align:right;">
-9
</td>
</tr>
<tr>
<td style="text-align:left;">
École des hautes études en santé publique
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
54030330
</td>
<td style="text-align:right;">
14284136
</td>
<td style="text-align:right;">
17.496521
</td>
<td style="text-align:right;">
26.437255
</td>
<td style="text-align:right;">
-9
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de technologie de Troyes
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
36495520
</td>
<td style="text-align:right;">
14931516
</td>
<td style="text-align:right;">
31.916761
</td>
<td style="text-align:right;">
40.913285
</td>
<td style="text-align:right;">
-9
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Montpellier 3 - Paul-Valéry
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
113680877
</td>
<td style="text-align:right;">
33229806
</td>
<td style="text-align:right;">
20.720268
</td>
<td style="text-align:right;">
29.230779
</td>
<td style="text-align:right;">
-9
</td>
</tr>
<tr>
<td style="text-align:left;">
École normale supérieure de Paris
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
121534606
</td>
<td style="text-align:right;">
43881736
</td>
<td style="text-align:right;">
26.671343
</td>
<td style="text-align:right;">
36.106371
</td>
<td style="text-align:right;">
-9
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale d’ingénieurs de Brest
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
3516445
</td>
<td style="text-align:right;">
1475382
</td>
<td style="text-align:right;">
33.216046
</td>
<td style="text-align:right;">
41.956635
</td>
<td style="text-align:right;">
-9
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Montpellier 3 - Paul-Valéry
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
117176936
</td>
<td style="text-align:right;">
32438212
</td>
<td style="text-align:right;">
18.309757
</td>
<td style="text-align:right;">
27.683103
</td>
<td style="text-align:right;">
-9
</td>
</tr>
<tr>
<td style="text-align:left;">
Collège de France
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
39833494
</td>
<td style="text-align:right;">
10070200
</td>
<td style="text-align:right;">
16.303390
</td>
<td style="text-align:right;">
25.280735
</td>
<td style="text-align:right;">
-9
</td>
</tr>
<tr>
<td style="text-align:left;">
RENATER - Réseau national de communications pour la technologie,
l’enseignement et la recherche
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
30185383
</td>
<td style="text-align:right;">
17376697
</td>
<td style="text-align:right;">
48.542965
</td>
<td style="text-align:right;">
57.566594
</td>
<td style="text-align:right;">
-9
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national universitaire Jean-François Champollion
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
9417925
</td>
<td style="text-align:right;">
4033012
</td>
<td style="text-align:right;">
34.280640
</td>
<td style="text-align:right;">
42.822724
</td>
<td style="text-align:right;">
-9
</td>
</tr>
<tr>
<td style="text-align:left;">
École centrale de Nantes
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
38915808
</td>
<td style="text-align:right;">
20776424
</td>
<td style="text-align:right;">
43.618573
</td>
<td style="text-align:right;">
53.388135
</td>
<td style="text-align:right;">
-10
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Corse Pasquale Paoli
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
57459827
</td>
<td style="text-align:right;">
21534980
</td>
<td style="text-align:right;">
27.813808
</td>
<td style="text-align:right;">
37.478324
</td>
<td style="text-align:right;">
-10
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de La Réunion
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
122266576
</td>
<td style="text-align:right;">
29238587
</td>
<td style="text-align:right;">
14.407743
</td>
<td style="text-align:right;">
23.913802
</td>
<td style="text-align:right;">
-10
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national polytechnique de Toulouse
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
95975446
</td>
<td style="text-align:right;">
46845171
</td>
<td style="text-align:right;">
39.227999
</td>
<td style="text-align:right;">
48.809537
</td>
<td style="text-align:right;">
-10
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure de chimie de Montpellier
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
12260086
</td>
<td style="text-align:right;">
4412838
</td>
<td style="text-align:right;">
26.442196
</td>
<td style="text-align:right;">
35.993532
</td>
<td style="text-align:right;">
-10
</td>
</tr>
<tr>
<td style="text-align:left;">
École centrale de Nantes
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
38177103
</td>
<td style="text-align:right;">
19928862
</td>
<td style="text-align:right;">
42.141322
</td>
<td style="text-align:right;">
52.201085
</td>
<td style="text-align:right;">
-10
</td>
</tr>
<tr>
<td style="text-align:left;">
Université du Littoral Côte d’Opale
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
90719462
</td>
<td style="text-align:right;">
26321239
</td>
<td style="text-align:right;">
19.076868
</td>
<td style="text-align:right;">
29.013883
</td>
<td style="text-align:right;">
-10
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale d’ingénieurs de Tarbes
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
17362586
</td>
<td style="text-align:right;">
5421541
</td>
<td style="text-align:right;">
21.590315
</td>
<td style="text-align:right;">
31.225423
</td>
<td style="text-align:right;">
-10
</td>
</tr>
<tr>
<td style="text-align:left;">
CTLES - Centre technique du livre de l’enseignement supérieur
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
1351380
</td>
<td style="text-align:right;">
639068
</td>
<td style="text-align:right;">
37.004247
</td>
<td style="text-align:right;">
47.290030
</td>
<td style="text-align:right;">
-10
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de La Rochelle
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
87529381
</td>
<td style="text-align:right;">
34774405
</td>
<td style="text-align:right;">
29.369480
</td>
<td style="text-align:right;">
39.728837
</td>
<td style="text-align:right;">
-10
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut polytechnique de Bordeaux
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
18977948
</td>
<td style="text-align:right;">
14075917
</td>
<td style="text-align:right;">
64.572108
</td>
<td style="text-align:right;">
74.169858
</td>
<td style="text-align:right;">
-10
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de technologie de Belfort-Montbéliard
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
36898725
</td>
<td style="text-align:right;">
11381716
</td>
<td style="text-align:right;">
21.339179
</td>
<td style="text-align:right;">
30.845825
</td>
<td style="text-align:right;">
-10
</td>
</tr>
<tr>
<td style="text-align:left;">
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
91450204
</td>
<td style="text-align:right;">
16410644
</td>
<td style="text-align:right;">
8.257762
</td>
<td style="text-align:right;">
17.944896
</td>
<td style="text-align:right;">
-10
</td>
</tr>
<tr>
<td style="text-align:left;">
Muséum national d’histoire naturelle
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
91590826
</td>
<td style="text-align:right;">
51933855
</td>
<td style="text-align:right;">
46.483434
</td>
<td style="text-align:right;">
56.702027
</td>
<td style="text-align:right;">
-10
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut d’études politiques de Bordeaux
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
6654770
</td>
<td style="text-align:right;">
5800602
</td>
<td style="text-align:right;">
76.035746
</td>
<td style="text-align:right;">
87.164575
</td>
<td style="text-align:right;">
-11
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Lille Nord de France
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
37402854
</td>
<td style="text-align:right;">
9811851
</td>
<td style="text-align:right;">
15.471902
</td>
<td style="text-align:right;">
26.232894
</td>
<td style="text-align:right;">
-11
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure de chimie de Paris
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
14109764
</td>
<td style="text-align:right;">
5407756
</td>
<td style="text-align:right;">
27.338203
</td>
<td style="text-align:right;">
38.326339
</td>
<td style="text-align:right;">
-11
</td>
</tr>
<tr>
<td style="text-align:left;">
Sorbonne Université
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
629713751
</td>
<td style="text-align:right;">
203342940
</td>
<td style="text-align:right;">
21.783025
</td>
<td style="text-align:right;">
32.291329
</td>
<td style="text-align:right;">
-11
</td>
</tr>
<tr>
<td style="text-align:left;">
CY Cergy Paris Université
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
190300596
</td>
<td style="text-align:right;">
81057308
</td>
<td style="text-align:right;">
31.465149
</td>
<td style="text-align:right;">
42.594353
</td>
<td style="text-align:right;">
-11
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Corse Pasquale Paoli
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
62166642
</td>
<td style="text-align:right;">
27131863
</td>
<td style="text-align:right;">
33.007839
</td>
<td style="text-align:right;">
43.643765
</td>
<td style="text-align:right;">
-11
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de la Nouvelle-Calédonie
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
33374270
</td>
<td style="text-align:right;">
9349845
</td>
<td style="text-align:right;">
17.377447
</td>
<td style="text-align:right;">
28.015130
</td>
<td style="text-align:right;">
-11
</td>
</tr>
<tr>
<td style="text-align:left;">
Grenoble INP
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
109249402
</td>
<td style="text-align:right;">
43292328
</td>
<td style="text-align:right;">
28.168798
</td>
<td style="text-align:right;">
39.627062
</td>
<td style="text-align:right;">
-11
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de la Polynésie Française
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
30724783
</td>
<td style="text-align:right;">
6387986
</td>
<td style="text-align:right;">
10.087622
</td>
<td style="text-align:right;">
20.790988
</td>
<td style="text-align:right;">
-11
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Toulouse 1 - Capitole
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
104387088
</td>
<td style="text-align:right;">
30790089
</td>
<td style="text-align:right;">
18.915938
</td>
<td style="text-align:right;">
29.496070
</td>
<td style="text-align:right;">
-11
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Pau et des Pays de l’Adour
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
136077111
</td>
<td style="text-align:right;">
57430616
</td>
<td style="text-align:right;">
30.970141
</td>
<td style="text-align:right;">
42.204465
</td>
<td style="text-align:right;">
-11
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Guyane
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
26418331
</td>
<td style="text-align:right;">
6086350
</td>
<td style="text-align:right;">
12.476704
</td>
<td style="text-align:right;">
23.038359
</td>
<td style="text-align:right;">
-11
</td>
</tr>
<tr>
<td style="text-align:left;">
Hautes Études-Sorbonne-Arts et Métiers
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
1485279
</td>
<td style="text-align:right;">
1214566
</td>
<td style="text-align:right;">
70.392364
</td>
<td style="text-align:right;">
81.773593
</td>
<td style="text-align:right;">
-11
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut polytechnique de Bordeaux
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
14069112
</td>
<td style="text-align:right;">
8884876
</td>
<td style="text-align:right;">
52.096692
</td>
<td style="text-align:right;">
63.151647
</td>
<td style="text-align:right;">
-11
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale d’ingénieurs de Saint-Étienne
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
5236667
</td>
<td style="text-align:right;">
3821997
</td>
<td style="text-align:right;">
62.398335
</td>
<td style="text-align:right;">
72.985298
</td>
<td style="text-align:right;">
-11
</td>
</tr>
<tr>
<td style="text-align:left;">
École centrale de Nantes
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
43310108
</td>
<td style="text-align:right;">
25825744
</td>
<td style="text-align:right;">
49.003604
</td>
<td style="text-align:right;">
59.629830
</td>
<td style="text-align:right;">
-11
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de la Nouvelle-Calédonie
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
31281693
</td>
<td style="text-align:right;">
6954410
</td>
<td style="text-align:right;">
11.092619
</td>
<td style="text-align:right;">
22.231565
</td>
<td style="text-align:right;">
-11
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Côte d’Azur
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
251605790
</td>
<td style="text-align:right;">
81198795
</td>
<td style="text-align:right;">
20.584725
</td>
<td style="text-align:right;">
32.272228
</td>
<td style="text-align:right;">
-12
</td>
</tr>
<tr>
<td style="text-align:left;">
Université fédérale de Toulouse Midi-Pyrénées
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
16903350
</td>
<td style="text-align:right;">
17428195
</td>
<td style="text-align:right;">
90.631958
</td>
<td style="text-align:right;">
103.104976
</td>
<td style="text-align:right;">
-12
</td>
</tr>
<tr>
<td style="text-align:left;">
Observatoire de Paris
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
36515357
</td>
<td style="text-align:right;">
9437287
</td>
<td style="text-align:right;">
14.291319
</td>
<td style="text-align:right;">
25.844707
</td>
<td style="text-align:right;">
-12
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris-Saclay
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
459728532
</td>
<td style="text-align:right;">
224704635
</td>
<td style="text-align:right;">
36.452087
</td>
<td style="text-align:right;">
48.877679
</td>
<td style="text-align:right;">
-12
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Grenoble Alpes
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
35719534
</td>
<td style="text-align:right;">
37314730
</td>
<td style="text-align:right;">
92.912018
</td>
<td style="text-align:right;">
104.465892
</td>
<td style="text-align:right;">
-12
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure de chimie de Lille
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
3003638
</td>
<td style="text-align:right;">
1680822
</td>
<td style="text-align:right;">
44.046253
</td>
<td style="text-align:right;">
55.959540
</td>
<td style="text-align:right;">
-12
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut de physique du globe
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
11549561
</td>
<td style="text-align:right;">
8898177
</td>
<td style="text-align:right;">
64.557112
</td>
<td style="text-align:right;">
77.043422
</td>
<td style="text-align:right;">
-12
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Nîmes
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
23246739
</td>
<td style="text-align:right;">
5923629
</td>
<td style="text-align:right;">
13.381799
</td>
<td style="text-align:right;">
25.481548
</td>
<td style="text-align:right;">
-12
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure d’ingénieurs de Caen
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
17784429
</td>
<td style="text-align:right;">
7771809
</td>
<td style="text-align:right;">
31.490598
</td>
<td style="text-align:right;">
43.700076
</td>
<td style="text-align:right;">
-12
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Bretagne Loire
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
16033977
</td>
<td style="text-align:right;">
17551168
</td>
<td style="text-align:right;">
97.390822
</td>
<td style="text-align:right;">
109.462350
</td>
<td style="text-align:right;">
-12
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut français d’archéologie orientale du Caire
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
6455984
</td>
<td style="text-align:right;">
2018640
</td>
<td style="text-align:right;">
19.301287
</td>
<td style="text-align:right;">
31.267736
</td>
<td style="text-align:right;">
-12
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Lumière - Lyon 2
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
146971456
</td>
<td style="text-align:right;">
46685382
</td>
<td style="text-align:right;">
18.569222
</td>
<td style="text-align:right;">
31.764931
</td>
<td style="text-align:right;">
-13
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Valenciennes et du Hainaut-Cambrésis
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
107249291
</td>
<td style="text-align:right;">
34095264
</td>
<td style="text-align:right;">
18.745753
</td>
<td style="text-align:right;">
31.790666
</td>
<td style="text-align:right;">
-13
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Sorbonne Paris Cité
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
4269179
</td>
<td style="text-align:right;">
3160739
</td>
<td style="text-align:right;">
60.540118
</td>
<td style="text-align:right;">
74.036226
</td>
<td style="text-align:right;">
-13
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Corse Pasquale Paoli
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
54822585
</td>
<td style="text-align:right;">
22389137
</td>
<td style="text-align:right;">
27.405118
</td>
<td style="text-align:right;">
40.839258
</td>
<td style="text-align:right;">
-13
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Bourgogne - Franche-Comté
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
28774132
</td>
<td style="text-align:right;">
31320101
</td>
<td style="text-align:right;">
95.619614
</td>
<td style="text-align:right;">
108.848118
</td>
<td style="text-align:right;">
-13
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure de mécanique et d’aérotechnique de Poitiers
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
15209094
</td>
<td style="text-align:right;">
5647593
</td>
<td style="text-align:right;">
23.779260
</td>
<td style="text-align:right;">
37.133001
</td>
<td style="text-align:right;">
-13
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure de mécanique et des microtechniques
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
5622326
</td>
<td style="text-align:right;">
3203123
</td>
<td style="text-align:right;">
43.517985
</td>
<td style="text-align:right;">
56.971492
</td>
<td style="text-align:right;">
-13
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de la Nouvelle-Calédonie
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
30414586
</td>
<td style="text-align:right;">
8117139
</td>
<td style="text-align:right;">
13.142625
</td>
<td style="text-align:right;">
26.688310
</td>
<td style="text-align:right;">
-14
</td>
</tr>
<tr>
<td style="text-align:left;">
Observatoire de la côte d’azur
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
3495150
</td>
<td style="text-align:right;">
2126464
</td>
<td style="text-align:right;">
46.538432
</td>
<td style="text-align:right;">
60.840422
</td>
<td style="text-align:right;">
-14
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Bretagne Loire
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
13489741
</td>
<td style="text-align:right;">
13432555
</td>
<td style="text-align:right;">
85.088787
</td>
<td style="text-align:right;">
99.576078
</td>
<td style="text-align:right;">
-14
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Grenoble Alpes
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
40978043
</td>
<td style="text-align:right;">
44081901
</td>
<td style="text-align:right;">
93.473327
</td>
<td style="text-align:right;">
107.574442
</td>
<td style="text-align:right;">
-14
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure de chimie de Montpellier
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
12296680
</td>
<td style="text-align:right;">
5040007
</td>
<td style="text-align:right;">
27.039738
</td>
<td style="text-align:right;">
40.986730
</td>
<td style="text-align:right;">
-14
</td>
</tr>
<tr>
<td style="text-align:left;">
Muséum national d’histoire naturelle
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
93236386
</td>
<td style="text-align:right;">
65883811
</td>
<td style="text-align:right;">
56.905712
</td>
<td style="text-align:right;">
70.663197
</td>
<td style="text-align:right;">
-14
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris-Saclay
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
361899522
</td>
<td style="text-align:right;">
120704164
</td>
<td style="text-align:right;">
19.535510
</td>
<td style="text-align:right;">
33.352949
</td>
<td style="text-align:right;">
-14
</td>
</tr>
<tr>
<td style="text-align:left;">
École centrale de Lyon
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
36757572
</td>
<td style="text-align:right;">
16090412
</td>
<td style="text-align:right;">
29.206899
</td>
<td style="text-align:right;">
43.774415
</td>
<td style="text-align:right;">
-15
</td>
</tr>
<tr>
<td style="text-align:left;">
École centrale de Lyon
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
54719751
</td>
<td style="text-align:right;">
26229239
</td>
<td style="text-align:right;">
33.235349
</td>
<td style="text-align:right;">
47.933769
</td>
<td style="text-align:right;">
-15
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut supérieur de mécanique de Paris
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
4293613
</td>
<td style="text-align:right;">
2730263
</td>
<td style="text-align:right;">
48.678048
</td>
<td style="text-align:right;">
63.588940
</td>
<td style="text-align:right;">
-15
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale d’ingénieurs de Brest
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
3509934
</td>
<td style="text-align:right;">
1722201
</td>
<td style="text-align:right;">
34.224518
</td>
<td style="text-align:right;">
49.066478
</td>
<td style="text-align:right;">
-15
</td>
</tr>
<tr>
<td style="text-align:left;">
Normandie Université
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
18747132
</td>
<td style="text-align:right;">
20906367
</td>
<td style="text-align:right;">
96.315356
</td>
<td style="text-align:right;">
111.517682
</td>
<td style="text-align:right;">
-15
</td>
</tr>
<tr>
<td style="text-align:left;">
CentraleSupélec
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
90109437
</td>
<td style="text-align:right;">
53417653
</td>
<td style="text-align:right;">
44.529035
</td>
<td style="text-align:right;">
59.280864
</td>
<td style="text-align:right;">
-15
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure d’ingénieurs de Caen
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
16306753
</td>
<td style="text-align:right;">
6720340
</td>
<td style="text-align:right;">
25.538953
</td>
<td style="text-align:right;">
41.212006
</td>
<td style="text-align:right;">
-16
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national des sciences appliquées de Toulouse
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
56443287
</td>
<td style="text-align:right;">
25132536
</td>
<td style="text-align:right;">
28.349899
</td>
<td style="text-align:right;">
44.527060
</td>
<td style="text-align:right;">
-16
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national des sciences appliquées de Toulouse
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
57834170
</td>
<td style="text-align:right;">
26564789
</td>
<td style="text-align:right;">
30.029974
</td>
<td style="text-align:right;">
45.932688
</td>
<td style="text-align:right;">
-16
</td>
</tr>
<tr>
<td style="text-align:left;">
Grenoble INP
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
122314564
</td>
<td style="text-align:right;">
63273208
</td>
<td style="text-align:right;">
35.507024
</td>
<td style="text-align:right;">
51.729905
</td>
<td style="text-align:right;">
-16
</td>
</tr>
<tr>
<td style="text-align:left;">
SIGMA Clermont
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
16974437
</td>
<td style="text-align:right;">
5873271
</td>
<td style="text-align:right;">
18.188780
</td>
<td style="text-align:right;">
34.600682
</td>
<td style="text-align:right;">
-16
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Côte d’Azur
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
23978497
</td>
<td style="text-align:right;">
20944018
</td>
<td style="text-align:right;">
71.410010
</td>
<td style="text-align:right;">
87.344999
</td>
<td style="text-align:right;">
-16
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure d’informatique pour l’industrie et
l’entreprise
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
6848791
</td>
<td style="text-align:right;">
2266845
</td>
<td style="text-align:right;">
16.902648
</td>
<td style="text-align:right;">
33.098470
</td>
<td style="text-align:right;">
-16
</td>
</tr>
<tr>
<td style="text-align:left;">
Université des Antilles
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
94906299
</td>
<td style="text-align:right;">
22642936
</td>
<td style="text-align:right;">
7.316345
</td>
<td style="text-align:right;">
23.858201
</td>
<td style="text-align:right;">
-17
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure de chimie de Paris
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
13642660
</td>
<td style="text-align:right;">
5579855
</td>
<td style="text-align:right;">
23.618488
</td>
<td style="text-align:right;">
40.900052
</td>
<td style="text-align:right;">
-17
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de La Réunion
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
138222644
</td>
<td style="text-align:right;">
56841401
</td>
<td style="text-align:right;">
23.631266
</td>
<td style="text-align:right;">
41.123075
</td>
<td style="text-align:right;">
-17
</td>
</tr>
<tr>
<td style="text-align:left;">
Centre Universitaire de Mayotte
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
3382008
</td>
<td style="text-align:right;">
1100265
</td>
<td style="text-align:right;">
15.872109
</td>
<td style="text-align:right;">
32.532892
</td>
<td style="text-align:right;">
-17
</td>
</tr>
<tr>
<td style="text-align:left;">
Muséum national d’histoire naturelle
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
78578246
</td>
<td style="text-align:right;">
46818132
</td>
<td style="text-align:right;">
41.280236
</td>
<td style="text-align:right;">
59.581544
</td>
<td style="text-align:right;">
-18
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national des sciences appliquées de Strasbourg
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
22438581
</td>
<td style="text-align:right;">
8525707
</td>
<td style="text-align:right;">
19.605981
</td>
<td style="text-align:right;">
37.995749
</td>
<td style="text-align:right;">
-18
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut d’études politiques de Grenoble
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
4365818
</td>
<td style="text-align:right;">
3548952
</td>
<td style="text-align:right;">
61.997614
</td>
<td style="text-align:right;">
81.289509
</td>
<td style="text-align:right;">
-19
</td>
</tr>
<tr>
<td style="text-align:left;">
Muséum national d’histoire naturelle
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
80131724
</td>
<td style="text-align:right;">
42415292
</td>
<td style="text-align:right;">
32.603200
</td>
<td style="text-align:right;">
52.931960
</td>
<td style="text-align:right;">
-20
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut d’études politiques de Grenoble
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
5055863
</td>
<td style="text-align:right;">
4485836
</td>
<td style="text-align:right;">
68.048442
</td>
<td style="text-align:right;">
88.725426
</td>
<td style="text-align:right;">
-21
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national des sciences appliquées de Strasbourg
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
22665034
</td>
<td style="text-align:right;">
8981233
</td>
<td style="text-align:right;">
18.860382
</td>
<td style="text-align:right;">
39.625941
</td>
<td style="text-align:right;">
-21
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris-Sud
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
352071102
</td>
<td style="text-align:right;">
141516872
</td>
<td style="text-align:right;">
19.123313
</td>
<td style="text-align:right;">
40.195538
</td>
<td style="text-align:right;">
-21
</td>
</tr>
<tr>
<td style="text-align:left;">
Université fédérale de Toulouse Midi-Pyrénées
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
21482970
</td>
<td style="text-align:right;">
20178344
</td>
<td style="text-align:right;">
72.256857
</td>
<td style="text-align:right;">
93.927162
</td>
<td style="text-align:right;">
-22
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure d’informatique pour l’industrie et
l’entreprise
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
7075440
</td>
<td style="text-align:right;">
2869574
</td>
<td style="text-align:right;">
18.290834
</td>
<td style="text-align:right;">
40.556828
</td>
<td style="text-align:right;">
-22
</td>
</tr>
<tr>
<td style="text-align:left;">
École française d’Extrême-Orient
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
9797461
</td>
<td style="text-align:right;">
3910542
</td>
<td style="text-align:right;">
17.526132
</td>
<td style="text-align:right;">
39.913831
</td>
<td style="text-align:right;">
-22
</td>
</tr>
<tr>
<td style="text-align:left;">
Université fédérale de Toulouse Midi-Pyrénées
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
42041336
</td>
<td style="text-align:right;">
45520860
</td>
<td style="text-align:right;">
82.896761
</td>
<td style="text-align:right;">
108.276435
</td>
<td style="text-align:right;">
-25
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Lille Nord de France
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
34153142
</td>
<td style="text-align:right;">
12318937
</td>
<td style="text-align:right;">
10.954325
</td>
<td style="text-align:right;">
36.069703
</td>
<td style="text-align:right;">
-25
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris-Sud
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
346527801
</td>
<td style="text-align:right;">
146482581
</td>
<td style="text-align:right;">
17.750061
</td>
<td style="text-align:right;">
42.271524
</td>
<td style="text-align:right;">
-25
</td>
</tr>
<tr>
<td style="text-align:left;">
CentraleSupélec
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
93989479
</td>
<td style="text-align:right;">
68326447
</td>
<td style="text-align:right;">
47.740730
</td>
<td style="text-align:right;">
72.695846
</td>
<td style="text-align:right;">
-25
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale d’ingénieurs de Saint-Étienne
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
4770936
</td>
<td style="text-align:right;">
3075888
</td>
<td style="text-align:right;">
38.376641
</td>
<td style="text-align:right;">
64.471375
</td>
<td style="text-align:right;">
-26
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure d’informatique pour l’industrie et
l’entreprise
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
7075358
</td>
<td style="text-align:right;">
3428990
</td>
<td style="text-align:right;">
19.559463
</td>
<td style="text-align:right;">
48.463837
</td>
<td style="text-align:right;">
-29
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Lyon
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
49327898
</td>
<td style="text-align:right;">
58071045
</td>
<td style="text-align:right;">
87.388632
</td>
<td style="text-align:right;">
117.724548
</td>
<td style="text-align:right;">
-30
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut français d’archéologie orientale du Caire
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
5829542
</td>
<td style="text-align:right;">
2371037
</td>
<td style="text-align:right;">
10.256277
</td>
<td style="text-align:right;">
40.672784
</td>
<td style="text-align:right;">
-30
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure de mécanique et des microtechniques
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
5178722
</td>
<td style="text-align:right;">
3565486
</td>
<td style="text-align:right;">
39.123282
</td>
<td style="text-align:right;">
68.848762
</td>
<td style="text-align:right;">
-30
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national des sciences appliquées de Toulouse
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
62302729
</td>
<td style="text-align:right;">
40487137
</td>
<td style="text-align:right;">
34.348279
</td>
<td style="text-align:right;">
64.984532
</td>
<td style="text-align:right;">
-31
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national des sciences appliquées de Lyon
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
52885685
</td>
<td style="text-align:right;">
50702865
</td>
<td style="text-align:right;">
64.613676
</td>
<td style="text-align:right;">
95.872569
</td>
<td style="text-align:right;">
-31
</td>
</tr>
<tr>
<td style="text-align:left;">
Observatoire de la côte d’azur
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
3993654
</td>
<td style="text-align:right;">
3307576
</td>
<td style="text-align:right;">
50.679553
</td>
<td style="text-align:right;">
82.820795
</td>
<td style="text-align:right;">
-32
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure de mécanique et des microtechniques
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
5123035
</td>
<td style="text-align:right;">
3567604
</td>
<td style="text-align:right;">
37.996324
</td>
<td style="text-align:right;">
69.638486
</td>
<td style="text-align:right;">
-32
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Paris-Saclay
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
39130116
</td>
<td style="text-align:right;">
50613488
</td>
<td style="text-align:right;">
97.806666
</td>
<td style="text-align:right;">
129.346634
</td>
<td style="text-align:right;">
-32
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut national des sciences appliquées de Strasbourg
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
22660869
</td>
<td style="text-align:right;">
12073694
</td>
<td style="text-align:right;">
19.867799
</td>
<td style="text-align:right;">
53.279925
</td>
<td style="text-align:right;">
-33
</td>
</tr>
<tr>
<td style="text-align:left;">
Institut d’études politiques de Lyon
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
5357861
</td>
<td style="text-align:right;">
5249186
</td>
<td style="text-align:right;">
63.606092
</td>
<td style="text-align:right;">
97.971672
</td>
<td style="text-align:right;">
-34
</td>
</tr>
<tr>
<td style="text-align:left;">
Observatoire de la côte d’azur
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
3574797
</td>
<td style="text-align:right;">
2825603
</td>
<td style="text-align:right;">
44.680243
</td>
<td style="text-align:right;">
79.042334
</td>
<td style="text-align:right;">
-34
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Côte d’Azur
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
19462930
</td>
<td style="text-align:right;">
19342608
</td>
<td style="text-align:right;">
61.831102
</td>
<td style="text-align:right;">
99.381789
</td>
<td style="text-align:right;">
-38
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure de mécanique et des microtechniques
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
6201808
</td>
<td style="text-align:right;">
6097247
</td>
<td style="text-align:right;">
49.145765
</td>
<td style="text-align:right;">
98.314024
</td>
<td style="text-align:right;">
-49
</td>
</tr>
<tr>
<td style="text-align:left;">
Observatoire de Paris
</td>
<td style="text-align:right;">
2015
</td>
<td style="text-align:right;">
12124488
</td>
<td style="text-align:right;">
12125124
</td>
<td style="text-align:right;">
50.324706
</td>
<td style="text-align:right;">
100.005248
</td>
<td style="text-align:right;">
-50
</td>
</tr>
<tr>
<td style="text-align:left;">
École nationale supérieure des arts et industries textiles
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
3444983
</td>
<td style="text-align:right;">
4161352
</td>
<td style="text-align:right;">
66.444305
</td>
<td style="text-align:right;">
120.794558
</td>
<td style="text-align:right;">
-54
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Lyon
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
52211120
</td>
<td style="text-align:right;">
76331379
</td>
<td style="text-align:right;">
86.767832
</td>
<td style="text-align:right;">
146.197551
</td>
<td style="text-align:right;">
-59
</td>
</tr>
<tr>
<td style="text-align:left;">
École normale supérieure de Cachan
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
91467016
</td>
<td style="text-align:right;">
71421902
</td>
<td style="text-align:right;">
12.069104
</td>
<td style="text-align:right;">
78.084872
</td>
<td style="text-align:right;">
-66
</td>
</tr>
<tr>
<td style="text-align:left;">
Etablissement public Campus Condorcet
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
17957546
</td>
<td style="text-align:right;">
27048835
</td>
<td style="text-align:right;">
83.041174
</td>
<td style="text-align:right;">
150.626567
</td>
<td style="text-align:right;">
-68
</td>
</tr>
<tr>
<td style="text-align:left;">
École normale supérieure de Cachan
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
85912961
</td>
<td style="text-align:right;">
66872740
</td>
<td style="text-align:right;">
10.295684
</td>
<td style="text-align:right;">
77.837778
</td>
<td style="text-align:right;">
-68
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Lyon
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
46157079
</td>
<td style="text-align:right;">
71475001
</td>
<td style="text-align:right;">
85.355126
</td>
<td style="text-align:right;">
154.851656
</td>
<td style="text-align:right;">
-69
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Bourgogne - Franche-Comté
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
12965680
</td>
<td style="text-align:right;">
22831988
</td>
<td style="text-align:right;">
97.294041
</td>
<td style="text-align:right;">
176.095569
</td>
<td style="text-align:right;">
-79
</td>
</tr>
<tr>
<td style="text-align:left;">
Université de Lyon
</td>
<td style="text-align:right;">
2021
</td>
<td style="text-align:right;">
43074576
</td>
<td style="text-align:right;">
74311309
</td>
<td style="text-align:right;">
82.605271
</td>
<td style="text-align:right;">
172.517796
</td>
<td style="text-align:right;">
-90
</td>
</tr>
<tr>
<td style="text-align:left;">
Etablissement public Campus Condorcet
</td>
<td style="text-align:right;">
2020
</td>
<td style="text-align:right;">
16073294
</td>
<td style="text-align:right;">
33122790
</td>
<td style="text-align:right;">
79.597281
</td>
<td style="text-align:right;">
206.073441
</td>
<td style="text-align:right;">
-126
</td>
</tr>
<tr>
<td style="text-align:left;">
Languedoc-Roussillon Universités
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
5774107
</td>
<td style="text-align:right;">
18056847
</td>
<td style="text-align:right;">
91.238126
</td>
<td style="text-align:right;">
312.721032
</td>
<td style="text-align:right;">
-221
</td>
</tr>
<tr>
<td style="text-align:left;">
Université Bourgogne - Franche-Comté
</td>
<td style="text-align:right;">
2018
</td>
<td style="text-align:right;">
5842788
</td>
<td style="text-align:right;">
19042935
</td>
<td style="text-align:right;">
96.286020
</td>
<td style="text-align:right;">
325.922060
</td>
<td style="text-align:right;">
-230
</td>
</tr>
<tr>
<td style="text-align:left;">
Etablissement public Campus Condorcet
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
7532703
</td>
<td style="text-align:right;">
23529188
</td>
<td style="text-align:right;">
81.148865
</td>
<td style="text-align:right;">
312.360490
</td>
<td style="text-align:right;">
-231
</td>
</tr>
<tr>
<td style="text-align:left;">
Languedoc-Roussillon Universités
</td>
<td style="text-align:right;">
2019
</td>
<td style="text-align:right;">
4885386
</td>
<td style="text-align:right;">
15978851
</td>
<td style="text-align:right;">
90.413101
</td>
<td style="text-align:right;">
327.074483
</td>
<td style="text-align:right;">
-237
</td>
</tr>
</tbody>
</table>
