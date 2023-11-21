# Illustrative simulations for family perspective paper

This code reproduces the figures.

To setup use renv which should take < 5 minutes on a standard computer

```r
install.packages("renv")
renv::restore()
```

To run simply compile in RStudio or use

```r
rmarkdown::render("docs/main_figs.rmd")
rmarkdown::render("docs/ascertainment_relatedness.rmd")
```

The simulations are relatively lightweight and so should compile in < 5 minutes
