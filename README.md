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

These numbers correspond to the data set of 1991 to the end of 2015 (v2015.12 - released May 15th 2016).
There were 1,106,142 entries with a total of 34,354,129 references, of which we were able to match 13,471,155 with an arXiv id (39%).
Note that not every reference has a corresponding arXiv id, nor have we successfully identified every reference that does.
Our algorithms are currently most successful for high energy physics categories, which can be seen in the following table summarising the extraction success per category:

| Category | Papers | ArXiv refs | Total refs | Avg. arXiv | Avg. total |  Ratio |
|:--------:| ------:| ----------:| ----------:| ----------:| ----------:| ------:| 
|  hep-lat |  13243 |     281915 |     344181 |      21.29 |      25.99 | 81.91% |
|   hep-ph |  91417 |    3099726 |    3836462 |      33.91 |      41.97 | 80.80% |
|   hep-th |  73199 |    2121979 |    2644210 |      28.99 |      36.12 | 80.25% |
|   hep-ex |  15771 |     311562 |     459320 |      19.76 |      29.12 | 67.83% |
|    gr-qc |  35888 |     780648 |    1213556 |      21.75 |      33.82 | 64.33% |
|  nucl-th |  22878 |     528484 |     834066 |      23.10 |      36.46 | 63.36% |
|  nucl-ex |   7612 |     138385 |     243800 |      18.18 |      32.03 | 56.76% |
| astro-ph | 179168 |    3205223 |    8286626 |      17.89 |      46.25 | 38.68% |
| quant-ph |  53366 |     599214 |    1581665 |      11.23 |      29.64 | 37.89% |
| cond-mat | 181732 |    1530928 |    5620147 |      8.42  |      30.93 | 27.24% |
|    q-alg |   1177 |       5033 |      18699 |      4.28  |      15.89 | 26.92% |
|  math-ph |  20249 |     138388 |     536610 |      6.83  |      26.50 | 25.79% |
| solv-int |    844 |       3754 |      16288 |      4.45  |      19.30 | 23.05% |
|  atom-ph |     68 |        221 |       1484 |      3.25  |      21.82 | 14.89% |
|  physics |  68050 |     237050 |    1641857 |      3.48  |      24.13 | 14.44% |
|     nlin |  12233 |      47215 |     343439 |      3.86  |      28.07 | 13.75% |
| acc-phys |     47 |         68 |        516 |      1.45  |      10.98 | 13.18% |
| chao-dyn |   1770 |       4282 |      39003 |      2.42  |      22.04 | 10.98% |
|     math | 213993 |     356700 |    4388131 |      1.67  |      20.51 | 8.13%  |
| adap-org |    306 |        367 |       4703 |      1.20  |      15.37 | 7.80%  |
| funct-an |    320 |        325 |       4528 |      1.02  |      14.15 | 7.18%  |
| alg-geom |   1209 |        899 |      12633 |      0.74  |      10.45 | 7.12%  |
|    dg-ga |    562 |        510 |       7791 |      0.91  |      13.86 | 6.55%  |
| supr-con |     69 |        202 |       3140 |      2.93  |      45.51 | 6.43%  |
| patt-sol |    452 |        632 |       9960 |      1.40  |      22.04 | 6.35%  |
| comp-gas |    140 |        129 |       2057 |      0.92  |      14.69 | 6.27%  |
|    q-fin |   4148 |       6175 |     101448 |      1.49  |      24.46 | 6.09%  |
|  chem-ph |    129 |        204 |       3503 |      1.58  |      27.16 | 5.82%  |
|  mtrl-th |    165 |        217 |       4729 |      1.32  |      28.66 | 4.59%  |
| plasm-ph |     28 |         13 |        327 |      0.46  |      11.68 | 3.98%  |
|    q-bio |  11022 |      11204 |     307720 |      1.02  |      27.92 | 3.64%  |
|     stat |  10257 |       8710 |     262866 |      0.85  |      25.63 | 3.31%  |
|       cs |  83712 |      50714 |    1568814 |      0.61  |      18.74 | 3.23%  |
| bayes-an |     11 |          2 |         91 |      0.18  |      8.27  | 2.20%  |
|   cmp-lg |    894 |         75 |       9467 |      0.08  |      10.59 | 0.79%  |
|   ao-sci |     13 |          2 |        292 |      0.15  |      22.46 | 0.68%  |

License
-------

This Paperscape data is made available under the Open Database License: http://opendatacommons.org/licenses/odbl/1.0/. Any rights in individual contents of the database are licensed under the Database Contents License: http://opendatacommons.org/licenses/dbcl/1.0/ - See more at: http://opendatacommons.org/licenses/odbl/#sthash.INIaa7OJ.dpuf
