# Benchmark Instances for the Overflowing Bin Packing Problem

This repository contains benchmark instances for the overflowing bin packing problem (OBPP).
That problem was originally introduced in [[1]](#1) together with a first set of benchmark instances (called `Dragone` below).
In [[2]](#2), the problem is further analyzed, and more benchmark instances are proposed.
Some of them are based on instances for the variable-sized bin packing problem (VSBPP), cf. [[3]](#3).

## Instance Sets
- `Dragone`: with parts `F1`, `F2`, `F3` as introduced in [[1]](#1)
- `Belov`: VSBPP instances from [[4]](#4) modified according to [[2]](#2)
- `Crainic`: VSBPP instances from [[5]](#5) modified according to [[2]](#2)
- `Hemmelmayr`: VSBPP instances from [[6]](#6) modified according to [[2]](#2)
- `MS`: instances generated for [[2]](#2)

## Format
Each file contains one instance of the OBPP.
The first line contains the number of bin types.
The following lines contain the bin lengths together with their availability.
Afterwards, the items are specified in the same way.

## References
<a id="1">[1]</a>
Cerrone, C., Dragone, R., Sciomachen, A.: Overflowing bin packing problem: the preservation of digital documents in archival information packages. Preprint, University of Genoa (2023) <http://dx.doi.org/10.2139/ssrn.46472889>, [cached](https://scholar.googleusercontent.com/scholar?q=cache:_QyMLldSwaIJ:scholar.google.com).

<a id="2">[2]</a>
Martinovic, J., Strasdat, N. (2024). The Overflowing Bin Packing Problem: Theoretical Results and a New Flow Formulation. Draft only.

<a id="3">[3]</a>
Delorme, M., Iori, M.: Enhanced pseudo-polynomial formulations for bin packing and cutting stock problems. INFORMS Journal on Computing 32(1), 101–119 (2020) <https://doi.org/10.1287/ijoc.2018.0880>

<a id="4">[4]</a>
Belov, G., Scheithauer, G.: A cutting plane algorithm for the one-dimensional cutting stock problem with multiple stock lengths. European Journal of Operational Research 141(2), 274–294 (2002) <https://doi.org/10.1016/S0377-2217(02)00125-X>

<a id="5">[5]</a>
Crainic, T., Perboli, G., Rei, W., Tadei, R.: Efficient lower bounds and heuristics for the variable cost and size bin packing problem. Computers & Operations Research 38(11), 1474–1482 (2011) <https://doi.org/10.1016/j.cor.2011.01.001>

<a id="6">[6]</a>
Hemmelmayr, V., Schmid, V., Blum, C.: Variable neighbourhood search for the variable sized bin packing problem. Computers & Operations Research 39(5), 1097–1108 (2012) <https://doi.org/10.1016/j.cor.2011.07.003>