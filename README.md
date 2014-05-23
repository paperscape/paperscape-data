Paperscape data
===============

Publicly available graph data for Paperscape (http://paperscape.org) in CSV format. Includes authors, title and references.

If you use this data, please give us credit. We are in the process of writing a scientific paper, but in the mean time you could use the following BibTeX entry:

```
@misc{paperscape,
    author = {Damien P. George and Robert Knegjens},
    title = {Paperscape},
    howpublished = {\url{http://paperscape.org}},
    doi = {10.5281/zenodo.10052},
}
```

Extraction success
------------------

These numbers correspond to the data set of 1991 to the end of 2013 (v2013.12 - released May 22nd 2014).
There were 903346 entries with a total of 27,361,907 references, of which we were able to match 11,131,443 with an arXiv id (40.68%).
Note that not every reference has a corresponding arXiv id, nor have we succesfully identified every reference that does.
Our algorithms are currently most successful for high energy physics categories, which can be seen in the following table summarising the extraction success per category:

| Category | Papers | ArXiv refs | Total refs | Avg. arXiv | Avg. total |  Ratio |
|:--------:| ------:| ----------:| ----------:| ----------:| ----------:| ------:| 
|  hep-lat |  12030 |     246914 |     303572 |      20.52 |      25.23 | 81.34% |
|   hep-ph |  81847 |    2653420 |    3309781 |      32.42 |      40.44 | 80.17% |
|   hep-th |  65870 |    1839214 |    2310299 |      27.92 |      35.07 | 79.61% |
|   hep-ex |  14002 |     256484 |     385942 |      18.32 |      27.56 | 66.46% |
|  nucl-th |  20379 |     459222 |     718589 |      22.53 |      35.26 | 63.91% |
|    gr-qc |  30671 |     620316 |     983748 |      20.22 |      32.07 | 63.06% |
|  nucl-ex |   6625 |     115093 |     203433 |      17.37 |      30.71 | 56.58% |
| astro-ph | 153681 |    2654078 |    6803464 |      17.27 |      44.27 | 39.01% |
| quant-ph |  44456 |     459549 |    1249300 |      10.34 |      28.10 | 36.78% |
|    q-alg |   1177 |       5033 |      18699 |       4.28 |      15.89 | 26.92% |
| cond-mat | 154699 |    1192443 |    4592914 |       7.71 |      29.69 | 25.96% |
|  math-ph |  16990 |     109999 |     431454 |       6.47 |      25.39 | 25.49% |
| solv-int |    844 |       3754 |      16288 |       4.45 |      19.30 | 23.05% |
|  atom-ph |     68 |        221 |       1484 |       3.25 |      21.82 | 14.89% |
|  physics |  51412 |     169195 |    1154258 |       3.29 |      22.45 | 14.66% |
|     nlin |  10602 |      39028 |     285058 |       3.68 |      26.89 | 13.69% |
| acc-phys |     47 |         68 |        516 |       1.45 |      10.98 | 13.18% |
| chao-dyn |   1770 |       4282 |      39003 |       2.42 |      22.04 | 10.98% |
|     math | 161842 |     259361 |    3185027 |       1.60 |      19.68 |  8.14% |
| adap-org |    306 |        367 |       4703 |       1.20 |      15.37 |  7.80% |
| funct-an |    320 |        325 |       4528 |       1.02 |      14.15 |  7.18% |
| alg-geom |   1209 |        899 |      12634 |       0.74 |      10.45 |  7.12% |
|    dg-ga |    562 |        510 |       7791 |       0.91 |      13.86 |  6.55% |
|    q-fin |   2815 |       4357 |      66920 |       1.55 |      23.77 |  6.51% |
| supr-con |     69 |        202 |       3140 |       2.93 |      45.51 |  6.43% |
| patt-sol |    452 |        632 |       9960 |       1.40 |      22.04 |  6.35% |
| comp-gas |    140 |        129 |       2057 |       0.92 |      14.69 |  6.27% |
|  chem-ph |    129 |        204 |       3503 |       1.58 |      27.16 |  5.82% |
|  mtrl-th |    165 |        217 |       4729 |       1.32 |      28.66 |  4.59% |
| plasm-ph |     28 |         13 |        327 |       0.46 |      11.68 |  3.98% |
|    q-bio |   8014 |       8123 |     214569 |       1.01 |      26.77 |  3.79% |
|       cs |  53519 |      24195 |     886831 |       0.45 |      16.57 |  2.73% |
|     stat |   5688 |       3517 |     137536 |       0.62 |      24.18 |  2.56% |
| bayes-an |     11 |          2 |         91 |       0.18 |       8.27 |  2.20% |
|   cmp-lg |    894 |         75 |       9467 |       0.08 |      10.59 |  0.79% |
|   ao-sci |     13 |          2 |        292 |       0.15 |      22.46 |  0.68% |

License
-------

This Paperscape data is made available under the Open Database License: http://opendatacommons.org/licenses/odbl/1.0/. Any rights in individual contents of the database are licensed under the Database Contents License: http://opendatacommons.org/licenses/dbcl/1.0/ - See more at: http://opendatacommons.org/licenses/odbl/#sthash.INIaa7OJ.dpuf
