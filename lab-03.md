Lab 03 - Nobel laureates
================
Steph Bossert
06 Feb 21

### Load packages and data

``` r
library(tidyverse) 
```

``` r
nobel <- read_csv("data/nobel.csv")
```

## Exercises

### Exercise 1

``` r
names(nobel)
```

    ##  [1] "id"                    "firstname"             "surname"              
    ##  [4] "year"                  "category"              "affiliation"          
    ##  [7] "city"                  "country"               "born_date"            
    ## [10] "died_date"             "gender"                "born_city"            
    ## [13] "born_country"          "born_country_code"     "died_city"            
    ## [16] "died_country"          "died_country_code"     "overall_motivation"   
    ## [19] "share"                 "motivation"            "born_country_original"
    ## [22] "born_city_original"    "died_country_original" "died_city_original"   
    ## [25] "city_original"         "country_original"

``` r
glimpse(nobel)
```

    ## Rows: 935
    ## Columns: 26
    ## $ id                    <dbl> 1, 2, 3, 4, 5, 6, 6, 8, 9, 10, 11, 12, 13, 14, …
    ## $ firstname             <chr> "Wilhelm Conrad", "Hendrik A.", "Pieter", "Henr…
    ## $ surname               <chr> "Röntgen", "Lorentz", "Zeeman", "Becquerel", "C…
    ## $ year                  <dbl> 1901, 1902, 1902, 1903, 1903, 1903, 1911, 1904,…
    ## $ category              <chr> "Physics", "Physics", "Physics", "Physics", "Ph…
    ## $ affiliation           <chr> "Munich University", "Leiden University", "Amst…
    ## $ city                  <chr> "Munich", "Leiden", "Amsterdam", "Paris", "Pari…
    ## $ country               <chr> "Germany", "Netherlands", "Netherlands", "Franc…
    ## $ born_date             <date> 1845-03-27, 1853-07-18, 1865-05-25, 1852-12-15…
    ## $ died_date             <date> 1923-02-10, 1928-02-04, 1943-10-09, 1908-08-25…
    ## $ gender                <chr> "male", "male", "male", "male", "male", "female…
    ## $ born_city             <chr> "Remscheid", "Arnhem", "Zonnemaire", "Paris", "…
    ## $ born_country          <chr> "Germany", "Netherlands", "Netherlands", "Franc…
    ## $ born_country_code     <chr> "DE", "NL", "NL", "FR", "FR", "PL", "PL", "GB",…
    ## $ died_city             <chr> "Munich", NA, "Amsterdam", NA, "Paris", "Sallan…
    ## $ died_country          <chr> "Germany", "Netherlands", "Netherlands", "Franc…
    ## $ died_country_code     <chr> "DE", "NL", "NL", "FR", "FR", "FR", "FR", "GB",…
    ## $ overall_motivation    <chr> NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA, NA,…
    ## $ share                 <dbl> 1, 2, 2, 2, 4, 4, 1, 1, 1, 1, 1, 1, 2, 2, 1, 1,…
    ## $ motivation            <chr> "\"in recognition of the extraordinary services…
    ## $ born_country_original <chr> "Prussia (now Germany)", "the Netherlands", "th…
    ## $ born_city_original    <chr> "Lennep (now Remscheid)", "Arnhem", "Zonnemaire…
    ## $ died_country_original <chr> "Germany", "the Netherlands", "the Netherlands"…
    ## $ died_city_original    <chr> "Munich", NA, "Amsterdam", NA, "Paris", "Sallan…
    ## $ city_original         <chr> "Munich", "Leiden", "Amsterdam", "Paris", "Pari…
    ## $ country_original      <chr> "Germany", "the Netherlands", "the Netherlands"…

``` r
view(nobel)
```

\#\#Exercise 1 answers: observations: 26 columns x 935 entries = 24310
Variables: 26 variables Each variable represents demogrpahic information
about the nobel laurete

### Exercise 2

Remove this text, and add your answer for Exercise 1 here. Add code
chunks as needed. Don’t forget to label your code chunk. Do not use
spaces in code chunk labels.

### Exercise 3

Remove this text, and add your answer for Exercise 1 here. Add code
chunks as needed. Don’t forget to label your code chunk. Do not use
spaces in code chunk labels.

### Exercise 4

…

### Exercise 5

…

### Exercise 6

…
