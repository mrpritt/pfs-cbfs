# A branch-and-bound algorithm with cyclic best-first search for the permutation flow shop scheduling problem

This repository contains supplementary data to the paper

Ritt, [A branch-and-bound algorithm with cyclic best-first search for the permutation flow shop scheduling problem](https://doi.org/10.1109/COASE.2016.7743493), Proc. 12th Ann. IEEE Int. Conf. on Autom. Sci. Eng. (CASE), 872–877, 2016.

## Abstract

 The permutation flow shop scheduling problem is one of the fundamental problems in scheduling with many practical applications. In this paper, we propose a branch-and-bound algorithm for solving it exactly. The algorithm uses an iterated local search to quickly find a good initial solution, followed by a cyclic best-first search with dynamic bi-directional branching to find the optimal solution and prove its optimality. In computational experiments we analyze the effects of the cyclic best-first search and the dynamic branching strategy, and show that our approach is able to combine preferable characteristics of the current best exact algorithms.

## Supplementary data

* Table III: Performance in proving optimality in the instances of Taillard (1993): [LOMPEN](data/t3-lompen.csv), [DFS/alt](data/t3-dfs-alt.csv), [DFS/dyn](data/t3-dfs-dyn.csv), [CBFS](data/t3-cbfs.csv).
* Table IV: Overall performance in the instances of Taillard (1993): [LOMPEN](data/t4-lompen.csv), [DFS/alt](data/t4-dfs-alt.csv), [DFS/dyn](data/t4-dfs-dyn.csv), [CFBS](data/t4-cbfs.csv).
* Table V: Comparison of CBFS to the results as reported in the literature on the instances of Taillard (1993): [LOMPEN](data/Companys,Mateo%20(2007).csv), [DFS/alt](data/Ladhari,Haouari%20(2005)-Table%202.csv), [CBFS](data/t5-cbfs.csv).

## How to cite

```bibtex
@InProceedings{Ritt/2016,
  author =       {Marcus Ritt},
  title =        {A branch-and-bound algorithm with cyclic best-first search for the permutation flowshop scheduling problem},
  booktitle =    {Proc. 12th Ann. IEEE Int. Conf. on Autom. Sci. Eng.}
  year =         {2016},
  address =      {Fort Worth, USA},
  organization = {IEEE},
  pages =        {872--877},
  doi =          {10.1109/COASE.2016.7743493}
}
```
