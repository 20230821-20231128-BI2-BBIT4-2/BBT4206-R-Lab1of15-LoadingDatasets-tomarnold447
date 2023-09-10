Business Intelligence Project
================
<Tom Arnold Owiti>
\<10/09/2023\>

- [Student Details](#student-details)
- [Setup Chunk](#setup-chunk)
- [Understanding the Dataset (Exploratory Data Analysis
  (EDA))](#understanding-the-dataset-exploratory-data-analysis-eda)
  - [Loading the Dataset](#loading-the-dataset)
    - [Source:](#source)
    - [Reference:](#reference)

# Student Details

|                                              |                  |
|----------------------------------------------|------------------|
| **Student ID Number**                        | 135203           |
| **Student Name**                             | Tom Arnold Owiti |
| **BBIT 4.2 Group**                           | C                |
| **BI Project Group Name/ID (if applicable)** | …                |

# Setup Chunk

**Note:** the following KnitR options have been set as the global
defaults: <BR>
`knitr::opts_chunk$set(echo = TRUE, warning = FALSE, eval = TRUE, collapse = FALSE, tidy = TRUE)`.

More KnitR options are documented here
<https://bookdown.org/yihui/rmarkdown-cookbook/chunk-options.html> and
here <https://yihui.org/knitr/options/>.

# Understanding the Dataset (Exploratory Data Analysis (EDA))

## Loading the Dataset

### Source:

The dataset that was used can be downloaded here: *\<<a
href="https://www.kaggle.com/datasets/shivamb/government-procurement-dataset\"
class="uri">https://www.kaggle.com/datasets/shivamb/government-procurement-dataset\</a>\>*

### Reference:

*\<Kaggle. (n.d.). Government Procurement Dataset. Kaggle\>  
Refer to the APA 7th edition manual for rules on how to cite datasets:
<https://apastyle.apa.org/style-grammar-guidelines/references/examples/data-set-references>*

``` r
library(readr)
government_procurement_via_gebiz <- read_csv("~/archive (2)/government-procurement-via-gebiz.csv")
```

    ## Rows: 32756 Columns: 7
    ## ── Column specification ────────────────────────────────────────────────────────
    ## Delimiter: ","
    ## chr (6): tender_no., tender_description, agency, award_date, tender_detail_s...
    ## dbl (1): awarded_amt
    ## 
    ## ℹ Use `spec()` to retrieve the full column specification for this data.
    ## ℹ Specify the column types or set `show_col_types = FALSE` to quiet this message.

``` r
View(government_procurement_via_gebiz)
# Provide the executable R code inside the various code chunks as guided by the lab work.
```

…to be continued
