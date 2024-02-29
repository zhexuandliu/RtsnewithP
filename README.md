
<!-- README.md is generated from README.Rmd. Please edit that file -->

Copied almost everything from https://github.com/jkrijthe/Rtsne. Edited several lines of codes to let `Rtsne` function return an extra $P$ matrix in tSNE algorithm.

To install the latest version from the github repository, use:

``` r
if(!require(devtools)) install.packages("devtools") # If not already installed
devtools::install_github("zhexuandliu/RtsnewithP")
```

# References

\[1\] L.J.P. van der Maaten and G.E. Hinton. “Visualizing
High-Dimensional Data Using t-SNE.” Journal of Machine Learning Research
9(Nov):2579-2605, 2008.

\[2\] L.J.P van der Maaten. “Accelerating t-SNE using tree-based
algorithms.” Journal of Machine Learning Research 15.1:3221-3245, 2014.

\[3\] <https://lvdmaaten.github.io/tsne/>

\[4\] <https://github.com/jkrijthe/Rtsne>
