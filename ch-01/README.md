R4DS Chapter 1
================
Jared Harris

## Quarto

Here’s a plot:

``` r
library(ggplot2)

ggplot(diamonds, aes(price, carat)) +
  geom_point()
```

![](ch-01_files/figure-gfm/unnamed-chunk-1-1.png)
