# Workshop: Improve your plots with `ggplot2`

This repository contains the materials of an introductory workshop on `ggplot2`. Estimated time: 1h 30min.

Clone this repository using git:

```
git clone https://github.com/mireia-bioinfo/workshop_ggplot2.git
``` 

or download as ZIP file using the link above (`Clone or download`).

## Contents

- `presentation_ggplot2.html`. Compiled presentation created using [xaringan](https://github.com/yihui/xaringan) slides.
- `notebook_ggplot2.Rmd`. Ready-to-run examples and exercises that will be discussed at the workshop.
- `data/tvseries_must_watch.rda`. Dataset used for the examples and exercises, extracted from the [`tvseries`](https://github.com/mireia-bioinfo/tvseries) package.

## Requirements

For running the `notebook_ggplot2.Rmd` file you will need the following packages:

```
install.packages(c("ggplot2", "scales", "palettetown", "ggsci"))
```  

If you want to compile the `presentation_ggplot2.Rmd` slides, you will need the following packages:

```
install.packages(c("ggplot2", "xaringan", "dplyr", "kableExtra",
				   "cowplot", "gganimate", "gapminder", "ggiraph",
				   "devtools", "RColorBrewer", "scales", "ggsci",
				   "palettetown", "htmlwidgets", "tvthemes"))
devtools::install_github("mireia-bioinfo/tvseries")
devtools::install_github("ropenscilabs/icon")
```
