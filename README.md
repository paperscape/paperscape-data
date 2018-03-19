Paperscape data
===============

Publicly available graph data for Paperscape (http://paperscape.org) in CSV format. Includes authors, title and references.

If you use this data, please give us credit by citing the following BibTeX entry:

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

These numbers correspond to the data set of 1991 to the end of 2017 (v2017.12 - released March 18th 2018).
There were 1,219,522 entries with a total of 38,464,630 references, of which we were able to match 14,726,797 with an arXiv id (38%).
Note that not every reference has a corresponding arXiv id, nor have we successfully identified every reference that does.
Our algorithms are currently most successful for high energy physics categories, which can be seen in the following table summarising the extraction success per category:

| Category | Papers | ArXiv refs | Total refs | Avg. arXiv | Avg. total |  Ratio |
|:--------:| ------:| ----------:| ----------:| ----------:| ----------:| ------:|
|  hep-lat |  13784 |     299121 |     364349 |      21.70 |      26.43 | 82.10% |
|   hep-ph |  96173 |    3332496 |    4114100 |      34.65 |      42.78 | 81.00% |
|   hep-th |  76801 |    2270045 |    2820872 |      29.56 |      36.73 | 80.47% |
|   hep-ex |  16553 |     339068 |     496602 |      20.48 |      30.00 | 68.28% |
|    gr-qc |  38488 |     867542 |    1338659 |      22.54 |      34.78 | 64.81% |
|  nucl-th |  24253 |     567751 |     901158 |      23.41 |      37.16 | 63.00% |
|  nucl-ex |   8060 |     149562 |     264224 |      18.56 |      32.78 | 56.60% |
| quant-ph |  58103 |     681014 |    1779232 |      11.72 |      30.62 | 38.28% |
| astro-ph | 192382 |    3469708 |    9109172 |      18.04 |      47.35 | 38.09% |
| cond-mat | 196357 |    1726730 |    6218230 |        8.8 |      31.67 | 27.77% |
|    q-alg |   1177 |       5033 |      18699 |        4.3 |      15.89 | 26.92% |
|  math-ph |  21735 |     152243 |     584801 |        7.0 |      26.91 | 26.03% |
| solv-int |    844 |       3756 |      16294 |        4.5 |      19.31 | 23.05% |
|  atom-ph |     68 |        221 |       1484 |        3.2 |      21.82 | 14.89% |
|  physics |  77710 |     276153 |    1943616 |        3.6 |      25.01 | 14.21% |
|     nlin |  13044 |      51562 |     373383 |        4.0 |      28.62 | 13.81% |
| acc-phys |     47 |         68 |        516 |        1.4 |      10.98 | 13.18% |
| chao-dyn |   1770 |       4282 |      39003 |        2.4 |      22.04 | 10.98% |
|     math | 242462 |     413518 |    5081904 |        1.7 |      20.96 |  8.14% |
| adap-org |    306 |        367 |       4703 |        1.2 |      15.37 |  7.80% |
| funct-an |    320 |        325 |       4528 |        1.0 |      14.15 |  7.18% |
| alg-geom |   1209 |        899 |      12633 |       0.74 |      10.45 |  7.12% |
|    dg-ga |    562 |        510 |       7791 |       0.91 |      13.86 |  6.55% |
| supr-con |     69 |        202 |       3140 |        2.9 |      45.51 |  6.43% |
| patt-sol |    452 |        632 |       9960 |        1.4 |      22.04 |  6.35% |
| comp-gas |    140 |        129 |       2057 |       0.92 |      14.69 |  6.27% |
|    q-fin |   4897 |       7199 |     122354 |        1.5 |      24.99 |  5.88% |
|  chem-ph |    129 |        204 |       3503 |        1.6 |      27.16 |  5.82% |
|  mtrl-th |    165 |        217 |       4729 |        1.3 |      28.66 |  4.59% |
| plasm-ph |     28 |         13 |        327 |       0.46 |      11.68 |  3.98% |
|       cs | 104475 |      79712 |    2092204 |       0.76 |      20.03 |  3.81% |
|     stat |  13333 |      13314 |     356259 |        1.0 |      26.72 |  3.74% |
|    q-bio |  12708 |      13122 |     364294 |        1.0 |      28.67 |  3.60% |
| bayes-an |     11 |          2 |         91 |       0.18 |       8.27 |  2.20% |
|   cmp-lg |    894 |         75 |       9467 |      0.084 |      10.59 |  0.79% |
|   ao-sci |     13 |          2 |        292 |       0.15 |      22.46 |  0.68% |

License
-------

This Paperscape data is made available under the Open Database License: http://opendatacommons.org/licenses/odbl/1.0/. Any rights in individual contents of the database are licensed under the Database Contents License: http://opendatacommons.org/licenses/dbcl/1.0/ - See more at: http://opendatacommons.org/licenses/odbl/#sthash.INIaa7OJ.dpuf
