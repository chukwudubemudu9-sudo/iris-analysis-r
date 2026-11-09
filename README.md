# Iris analysis in R — DTS 211

Exploratory analysis of the built-in Iris dataset and a k-nearest-neighbours (k-NN) classifier. The R Markdown source and rendered HTML report are included with the script and saved charts and tables.

## Run the analysis

From this folder:

```bash
Rscript iris_analysis.R
```

To rebuild the HTML report in RStudio, open `iris_analysis.Rmd` and select **Knit**, or run:

```r
install.packages(c("rmarkdown", "knitr"))
rmarkdown::render("iris_analysis.Rmd")
```

## Recorded result

The stratified test split contains 45 flowers. With `k = 5`, the saved test accuracy is 42/45 (93.3%). The exact R environment is recorded in `results/sessionInfo.txt`.

