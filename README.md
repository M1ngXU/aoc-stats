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
2024 |  155 | 201 |  246 |  323 |  401 |    557 | 1023 |  1973 |  4844
```
Frequency by Rank
```
Year | 100 | 150 | 200 | 300 | 500 | 700 | 1000 | 1500 | 2000 | 3000 | 5000
===========================================================================
2021 |  0% |  0% |  0% |  0% |  3% |  3% |   7% |   7% |  19% |  42% |  73%
2023 |  4% |  4% | 14% | 18% | 22% | 38% |  50% |  60% |  76% |  90% |  96%
2024 |  0% |  0% |  4% | 12% | 42% | 62% |  72% |  82% |  90% |  96% | 100%
```

# Series Chart

```mermaid
---
config:
 themeVariables:
  xyChart:
   plotColorPalette: "#808080, #808080, #808080, #808080, #808080, #f84, #1d6, #77f"
---
xychart-beta
title "Frequency of Ranking within Top-k"
x-axis [100, 150, 200, 300, 500, 700, 1000, 1500, 2000, 3000, 5000]
y-axis "Frequency (in %)" 0 --> 100
line "0%" [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0]
line "25%" [25, 25, 25, 25, 25, 25, 25, 25, 25, 25, 25]
line "50%" [50, 50, 50, 50, 50, 50, 50, 50, 50, 50, 50]
line "75%" [75, 75, 75, 75, 75, 75, 75, 75, 75, 75, 75]
line "100%" [100, 100, 100, 100, 100, 100, 100, 100, 100, 100, 100]
line "2021" [0, 0, 0, 0, 3, 3, 7, 7, 19, 42, 73]
line "2023" [4, 4, 14, 18, 22, 38, 50, 60, 76, 90, 96]
line "2024" [0, 0, 4, 12, 42, 62, 72, 82, 90, 96, 100]
```

```mermaid
flowchart TD 
style 2021 fill:#f84,stroke:#333,stroke-width:2px,color:#fff
style 2023 fill:#1d6,stroke:#333,stroke-width:2px,color:#fff
style 2024 fill:#77f,stroke:#333,stroke-width:2px,color:#fff
```

# Overall
```mermaid
%%{init: {"themeVariables": {"pie1": "#0b510b", "pie2": "#0081d3", "pie3": "#f03a3a", "pie4": "#999900", "pie5": "#a81d1d", "pie6": "#004e8b", "pie7": "#e2e200", "pie8": "#600000", "pie9": "#45a845", "pie10": "#287d28", "pie11": "#80ff80", "pie12": "#62d362"}}}%%
pie
title Ranking within Top-k Segment
"18 * [301, 500]": 18
"18 * [501, 700]": 18
"16 * [2001, 3000]": 16
"15 * [1501, 2000]": 15
"13 * [3001, 5000]": 13
"12 * [701, 1000]": 12
"10 * [1001, 1500]": 10
"9 * [5001, 29212]": 9
"7 * [151, 200]": 7
"6 * [201, 300]": 6
"2 * [1, 100]": 2
"0 * [101, 150]": 0
```
