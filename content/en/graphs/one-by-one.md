---
title: Visualisation using `ggplot2` package.
date: 2019-10-31T10:20:16+09:00
description: Graph Gallery
type: graphs
mode: one-by-one
description: "graph gallery"
image: images/feature2/gallery.png
output: html_document
---


```{r setup, include=TRUE}
knitr::opts_chunk$set(
	echo = FALSE,
	message = FALSE,
	warning = FALSE
    library(tidyquant)
    library(tidyverse)
    library(ggplot2)
)


dir.image <- "static"


```
As always with anything you start with a blank canvas. In this document we will explore how to use some base function in `R` togheter with 

`r knitr::include_graphics(path = "C:/R/spectrumefficiency/static/images/header/background.jpg")`
