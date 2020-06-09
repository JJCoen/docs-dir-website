---
title: "HTML Document"
author: "Jim Coen"
date: "4/29/2020"
output:
  html_document: 
    keep_md: true
    css: styles.css
    fig_height: 6
    fig_width: 6
    toc: yes
    toc_depth: 3
    toc_float: TRUE
    code_folding: hide
---



# HTML Document YAML options

## R Markdown {#nextsteps .emphasized}

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

## Including Plots

### Plot of cars dataset
When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:


```r
plot(cars)
```

![](01-HTML-document_files/figure-html/cars-1.png)<!-- -->

### Air Quality dataset
You can also embed plots, for example:

![](01-HTML-document_files/figure-html/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.

## Stats methods
* regression
* correlation
* linear models

## Line equation

$$y = m x + c$$

