# My Project Template
This is my default setup for a project. I've modified [ProjectTemplate](http://projecttemplate.net/) according to my needs. 

## Using this Project

### Getting Started
1. Download the template.
2. Delete the `.git` directory: (`rm -rf .git`)
3. Rename `my-project-template.Rproj` to something meaningful¨
4. Open the new project in RStudio
5. Choose `Tools -> Project Options -> Environment in order to use the `renv` package to create an isolated package library

### Using the Template

```
> install.packages('ProjectTemplate')
> library(ProjectTemplate)
> load.project()
```



## Directory Structure

├── LICENSE
├── cache              <- Cached data
├── config             <- Configuration settings for ProjectTemplate
│   ├── global.dcf
│    
├── data
│   ├── processed      <- The data sets for modelling and visualizations
│   └── raw            <- The original, read-only data.
│
├── documents          <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── papers         <- Generated graphics and figures for reporting
│   └── presentations
│
├─ fits                <- Fitted models
│
├─ lib                 <- Functions not found in packages
│
├─ munge               <- Scripts to download and/or munge data
│
├── README.md          <- The top-level README describing the package
│
├── src                <- Source code for use in this project.
│   │
│   ├── models         <- Scripts for modelling
│   │                      
│   └── visualization  <- Scripts to create exploratory data analysis
│       
│
└── tests              <- Scripts for testing



## Session Information
```
 Session info ─────────────────────────────────────────────────────────────────────────
 setting  value                       
 version  R version 4.0.5 (2021-03-31)
 os       macOS Catalina 10.15.7      
 system   x86_64, darwin17.0          
 ui       RStudio                     
 language (EN)                        
 collate  en_US.UTF-8                 
 ctype    en_US.UTF-8                 
 tz       Europe/Helsinki             
 date     2021-05-25                  

─ Packages ──────────────────────────────────────────────────────────────────────────
 package         * version    date       lib source                           
 assertthat        0.2.1      2019-03-21 [1] CRAN (R 4.0.2)                   
 backports         1.2.1      2020-12-09 [1] CRAN (R 4.0.2)                   
 broom             0.7.6.9001 2021-05-23 [1] Github (tidymodels/broom@4a4b5aa)
 cachem            1.0.5      2021-05-15 [1] CRAN (R 4.0.2)                   
 callr             3.7.0      2021-04-20 [1] CRAN (R 4.0.2)                   
 cellranger        1.1.0      2016-07-27 [1] CRAN (R 4.0.2)                   
 cli               2.5.0      2021-04-26 [1] CRAN (R 4.0.2)                   
 colorspace        2.0-1      2021-05-04 [1] R-Forge (R 4.0.5)                
 crayon            1.4.1      2021-02-08 [1] CRAN (R 4.0.2)                   
 DBI               1.1.1      2021-01-15 [1] CRAN (R 4.0.2)                   
 dbplyr            2.1.1      2021-04-06 [1] CRAN (R 4.0.2)                   
 desc              1.3.0      2021-03-05 [1] CRAN (R 4.0.2)                   
 devtools          2.4.1      2021-05-05 [1] CRAN (R 4.0.2)                   
 digest            0.6.27     2020-10-24 [1] CRAN (R 4.0.2)                   
 dplyr           * 1.0.6      2021-05-05 [1] CRAN (R 4.0.2)                   
 ellipsis          0.3.2      2021-04-29 [1] CRAN (R 4.0.2)                   
 evaluate          0.14       2019-05-28 [1] CRAN (R 4.0.1)                   
 fansi             0.4.2      2021-01-15 [1] CRAN (R 4.0.2)                   
 fastmap           1.1.0      2021-01-25 [1] CRAN (R 4.0.2)                   
 forcats         * 0.5.1      2021-01-27 [1] CRAN (R 4.0.2)                   
 fs                1.5.0      2020-07-31 [1] CRAN (R 4.0.2)                   
 generics          0.1.0      2020-10-31 [1] CRAN (R 4.0.2)                   
 ggplot2         * 3.3.3      2020-12-30 [1] CRAN (R 4.0.2)                   
 glue              1.4.2      2020-08-27 [1] CRAN (R 4.0.2)                   
 gtable            0.3.0      2019-03-25 [1] CRAN (R 4.0.2)                   
 haven             2.4.1      2021-04-23 [1] CRAN (R 4.0.2)                   
 here              1.0.1      2020-12-13 [1] CRAN (R 4.0.2)                   
 hms               1.0.0      2021-01-13 [1] CRAN (R 4.0.2)                   
 htmltools         0.5.1.1    2021-01-22 [1] CRAN (R 4.0.2)                   
 httr              1.4.2      2020-07-20 [1] CRAN (R 4.0.2)                   
 jsonlite          1.7.2      2020-12-09 [1] CRAN (R 4.0.2)                   
 knitr             1.33       2021-04-24 [1] CRAN (R 4.0.2)                   
 lifecycle         1.0.0      2021-02-15 [1] CRAN (R 4.0.2)                   
 lubridate         1.7.10     2021-02-26 [1] CRAN (R 4.0.2)                   
 magrittr          2.0.1      2020-11-17 [1] CRAN (R 4.0.2)                   
 memoise           2.0.0      2021-01-26 [1] CRAN (R 4.0.2)                   
 modelr            0.1.8      2020-05-19 [1] CRAN (R 4.0.2)                   
 munsell           0.5.0      2018-06-12 [1] CRAN (R 4.0.2)                   
 pillar            1.6.1      2021-05-16 [1] CRAN (R 4.0.5)                   
 pkgbuild          1.2.0      2020-12-15 [1] CRAN (R 4.0.2)                   
 pkgconfig         2.0.3      2019-09-22 [1] CRAN (R 4.0.2)                   
 pkgload           1.2.1      2021-04-06 [1] CRAN (R 4.0.2)                   
 prettyunits       1.1.1      2020-01-24 [1] CRAN (R 4.0.2)                   
 processx          3.5.2      2021-04-30 [1] CRAN (R 4.0.2)                   
 ProjectTemplate * 0.10.1     2021-02-08 [1] CRAN (R 4.0.2)                   
 ps                1.6.0      2021-02-28 [1] CRAN (R 4.0.2)                   
 purrr           * 0.3.4      2020-04-17 [1] CRAN (R 4.0.2)                   
 R6                2.5.0      2020-10-28 [1] CRAN (R 4.0.2)                   
 Rcpp              1.0.6      2021-01-15 [1] CRAN (R 4.0.2)                   
 readr           * 1.4.0      2020-10-05 [1] CRAN (R 4.0.2)                   
 readxl            1.3.1      2019-03-13 [1] CRAN (R 4.0.2)                   
 remotes           2.3.0      2021-04-01 [1] CRAN (R 4.0.2)                   
 reprex            2.0.0      2021-04-02 [1] CRAN (R 4.0.2)                   
 rlang             0.4.11     2021-04-30 [1] CRAN (R 4.0.2)                   
 rmarkdown         2.8        2021-05-07 [1] CRAN (R 4.0.2)                   
 rprojroot         2.0.2      2020-11-15 [1] CRAN (R 4.0.2)                   
 rstudioapi        0.13       2020-11-12 [1] CRAN (R 4.0.2)                   
 rvest             1.0.0      2021-03-09 [1] CRAN (R 4.0.2)                   
 scales            1.1.1      2020-05-11 [1] CRAN (R 4.0.2)                   
 sessioninfo       1.1.1      2018-11-05 [1] CRAN (R 4.0.2)                   
 stringi           1.6.2      2021-05-17 [1] CRAN (R 4.0.2)                   
 stringr         * 1.4.0      2019-02-10 [1] CRAN (R 4.0.2)                   
 testthat          3.0.2      2021-02-14 [1] CRAN (R 4.0.2)                   
 tibble          * 3.1.2      2021-05-16 [1] CRAN (R 4.0.5)                   
 tidyr           * 1.1.3      2021-03-03 [1] CRAN (R 4.0.2)                   
 tidyselect        1.1.1      2021-04-30 [1] CRAN (R 4.0.2)                   
 tidyverse       * 1.3.1      2021-04-15 [1] CRAN (R 4.0.2)                   
 usethis           2.0.1      2021-02-10 [1] CRAN (R 4.0.2)                   
 utf8              1.2.1      2021-03-12 [1] CRAN (R 4.0.2)                   
 vctrs             0.3.8      2021-04-29 [1] CRAN (R 4.0.2)                   
 withr             2.4.2      2021-04-18 [1] CRAN (R 4.0.2)                   
 xfun              0.23       2021-05-15 [1] CRAN (R 4.0.2)                   
 xml2              1.3.2      2020-04-23 [1] CRAN (R 4.0.2)                   
 yaml              2.2.1      2020-02-01 [1] CRAN (R 4.0.2)  

```