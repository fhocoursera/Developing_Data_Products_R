---
title: "DDP_Plotly_Slides"
author: "Frederick Orndorff"
output: ioslides_presentation
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = FALSE)
```

## Plotly Assignment
Date: 12/15/2019

- Create a slideshown in R Markdown
- Ensure you have an interactive plot
- Include the date

## Plotly Assignment
1. load library and plot
```{r, message=FALSE}
library(plotly)
```

## Plot
```{r, message=FALSE}
plot_ly(mtcars, x=~wt, y=~mpg, type="scatter", color=~factor(cyl))
```

