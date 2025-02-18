
<!-- README.md is generated from README.Rmd. Please edit that file -->

# synirgogn

<!-- badges: start -->

<!-- badges: end -->

The goal of synirgogn is to …

## Installation

You can install the development version of synirgogn from
[GitHub](https://github.com/) with:

``` r
# install.packages("pak")
pak::pak("auv2/synirgogn")
```

## Um gögnin

Í þessum pakka eru nokkur sýnidæmi um gagnaskrár á atriðaleveli og sem
heildartölur. Tilgangurinn er að sýna ólíkar gagnatýpur sem hægt er að
nota til þess að þróa önnur tól, t.d. til skölunar eða annarra
reikniverka.

``` r
library(synirgogn)
## Dæmi um notkun
data("tengispurningar_2008_2019")
head(tengispurningar_2008_2019)
#>   id prof stig
#> 1  1 2008    3
#> 2  2 2008    0
#> 3  3 2008    6
#> 4  4 2008    4
#> 5  5 2008    4
#> 6  6 2008    3
```
