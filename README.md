This is the home of my personal times, ranks and scores on [Advent of Code](https://adventofcode.com/).

Note that only those dates are included on which I participated in a *"competitive"* manner (i.e., being available at 6am CET and having a decent IDE).

In case you wonder, I used Rust in 2021/2023 (solutions [here](https://github.com/M1ngXU/aoc-rs)). The first half of 2021 also in JavaScript.

# Series Table
Rank by Quantile
```
Year | Best |  5% |  10% |  20% |  30% | Median |  75% |   90% | Worst
======================================================================
2021 |  398 | 909 | 1566 | 2211 | 2262 |   3128 | 5374 | 16846 | 29212
2023 |   44 | 167 |  184 |  370 |  590 |    979 | 1989 |  2989 |  5649
```
Frequency by Rank
```
Year | 100 | 150 | 200 | 300 | 500 | 700 | 1000 | 1500 | 2000 | 3000 | 5000
===========================================================================
2021 |  0% |  0% |  0% |  0% |  3% |  3% |   7% |   7% |  19% |  42% |  73%
2023 |  4% |  4% | 14% | 18% | 22% | 38% |  50% |  60% |  76% |  90% |  96%
```

# Series Chart
![Metrics](/cumulative-rank-frequency.svg)


```mermaid
flowchart TD 
style 2021 fill:#f84,stroke:#333,stroke-width:2px,color:#fff
style 2023 fill:#1d6,stroke:#333,stroke-width:2px,color:#fff
```

# Overall
```mermaid
%%{init: {"themeVariables": {"pie1": "#f03a3a", "pie2": "#999900", "pie3": "#a81d1d", "pie4": "#600000", "pie5": "#0081d3", "pie6": "#004e8b", "pie7": "#45a845", "pie8": "#e2e200", "pie9": "#0b510b", "pie10": "#80ff80", "pie11": "#287d28", "pie12": "#62d362"}}}%%
pie
title Ranking within Top-k Segment
"13 * [2001, 3000]": 13
"11 * [1501, 2000]": 11
"11 * [3001, 5000]": 11
"9 * [5001, 29212]": 9
"8 * [501, 700]": 8
"7 * [701, 1000]": 7
"5 * [151, 200]": 5
"5 * [1001, 1500]": 5
"3 * [301, 500]": 3
"2 * [1, 100]": 2
"2 * [201, 300]": 2
"0 * [101, 150]": 0
```
