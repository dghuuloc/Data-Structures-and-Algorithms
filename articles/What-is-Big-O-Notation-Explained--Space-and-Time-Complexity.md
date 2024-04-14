# <p align="center">Understanding Big O Notation Explained: Space and Time Complexity</p>
---

## What is Big O Notation?

__Big O__ is a notation that allows us to evaluate this, specifically it allows us to evaluate growth rates by analyzing how __time complexity__ (Time of execution) and __space complexity__ (memory usage) scale for a given algorithm when larger input sizes are processed by it. Big O is driven by the upper bound or higher complexity found in an algorithm so the worst case complexity will be the Big O representation of your code..

## Big-O Complexity Cheat Sheet

<p align="center"><img src="https://github.com/dghuuloc/Data-Structures-and-Algorithms/blob/main/images/bigocheatsheet.png"/></p>

## Big-O Complexities

The chart below depicts the Big-O complexities mentioned above and the number of elements in the input against the number of operations. The color coding provides a rough judgement on their performance.

<p align="center"><img src="https://github.com/dghuuloc/Data-Structures-and-Algorithms/blob/main/images/complexity.png"/></p>

A number of very common order of magnitude functions will come up over and over as you study algorithms. The table below shows just how big of a difference the number of computations between these-alogorithms are for 10, 100, and 1000 input elements:

| TERM         | BIG O NOTATION | COMPUTATIONS FOR 10 ELEMENTS | COMPUTATIONS FOR 100 ELEMENTS | COMPUTATIONS FOR 1000 ELEMENTS |
|--------------|:--------------:|-----------------------------:|------------------------------:|-------------------------------:|
| Constant     |  O(1)          |                            1 |                             1 |                              1 |
| Logarithmic  |  O(log n)      |                            3 |                             7 |                             10 |
| Linear       |  O(n)          |                           10 |                           100 |                           1000 |
| Linearithmic |  O(n log n)    |                           33 |                           664 |                           9966 |
| Quadratic    |  O(n^2)        |                          100 |                         10000 |                        1000000 |
| Exponential  |  O(2^n)        |                         1024 |                   1.26765E+30 |                    1.0715E+301 |
| Factorial    |  O(n!)         |                      3628800 |                   9.3326E+157 |                4.0238726E+2567 |


## References 

- [Understanding Big-O notation](https://www.coengoedegebure.com/understanding-big-o-notation/)
- [Big O Cheatsheet](https://www.hackerearth.com/practice/notes/big-o-cheatsheet-series-data-structures-and-algorithms-with-thier-complexities-1/)
- [Big O complexity Chart](https://www.amitshahi.dev/blog/2019-06-23-big-o-notation/)
- [Know thy Complexities](https://www.bigocheatsheet.com/)
- [Understanding Big O Notation via JavaScript](https://www.digitalocean.com/community/tutorials/js-big-o-notation)
- [What is Big O Notation Explained: Space and Time Complexity](https://www.freecodecamp.org/news/big-o-notation-why-it-matters-and-why-it-doesnt-1674cfa8a23c/)
1
