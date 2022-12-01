# ssjgl-tutorial
Tutorial for using Bayesian joint spike-and-slab graphical lasso in R

This tutorial summarizes details of the Bayesian Joint spike-and-slab Graphical Lasso (SSJGL) algorithm (Li et. al 2019), then walks through the steps needed to run the `spikeyglass` package using a real-world metabolomics dataset.

To view the tutorial click [here](https://mljaniczek.github.io/ssjgl-tutorial). 

To run this tutorial yourself, I recommend cloning [the repository](https://github.com/mljaniczek/ssjgl-tutorial) (click the green "CODE" button, then download the zip or open with GitHub Desktop), then opening the file `ssjgl-tutorial.Rproj` and running the code within that environment. Alternatively you can download the .csv file and .Rmd file and run them yourself. 

Ensure you have installed all the necessary packages to run this tutorial!

```
#install.packages("JGL")
#install.packages("igraph", "RColorBrewer", "pheatmap")
#install.packages("tidyverse", "here")
#devtools::install_github("mljaniczek/spikeyglass")
```
