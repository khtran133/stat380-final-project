# Analyzing the Relationship Between Poverty and Crime

*By Dominic Klonicki and Khoi Tran*

## Overview

Our final project uses data of poverty throughout the United States on a per-county basis, and attempts to establish a relationship between poverty and crime rates. Most importantly, it attempts to establish a relationship between inequality in poverty, as defined by variance in poverty statistics per county (within the same state), and crime rates. 

## Sources

**Economic data, per county/state basis** - *CAINC4__ALL_STATES_1969_2017.csv*

https://drive.google.com/open?id=1kbtFd64UMSoJWdS3v6CK7bzCxKcGn8aa

https://apps.bea.gov/regional/

Notes: Data from Bureau of Economic Analysis, *file exceeds 25MB, too large to upload to github*

**Poverty data, per county basis** - *county_poverty_hist.csv*

https://www.census.gov/programs-surveys/saipe/data/datasets.2016.html

Notes: Data from SAIPE (Small Area Income and Poverty Esimates) Program

**Crime data, per state basis** - *estimated_crimes.csv*

https://crime-data-explorer.fr.cloud.gov/downloads-and-docs

Notes: Data from Uniform Crime Reporting (UCR) Program

**Land data, per county/state basis** - *LND01.xls*

https://www.census.gov/library/publications/2011/compendia/usa-counties-2011.html

Notes: Taken from 2011 Census

## Requirements

### Joins Multiple Data Sources

(A) .Rmd Line number(s) for join operation:

* Lines 110-117

* Lines 154-172

* Lines 311-318

* Line 484

### Data Wrangling (5 of 6 required)

(A) .Rmd Line number(s) for an example of general purpose data wrangling:

* Lines 64-65

* Lines 81-85

* Lines 91-95

* Line 106

* Line 111-113

* Lines 122-128

* Lines 154-155

* Lines 176-179

* Lines 202-207

* Lines 219-236

* Lines 287295

* Lines 312-316

(B) .Rmd Line number(s) for a spread & gather (or equivalent):

* Lines 91-95

* Lines 122-128

* Lines 181-207

(C) .Rmd Line number(s) for use of regular expressions:

* Lines 45-46

* Lines 76-77

* Lines 123-125

* Lines 140-141

* Lines 158-163

* Lines 166-169

* Lines 222-229

(D) .Rmd Line number(s) for use of user-defined functions:

* Lines 499-529 (`https://rdrr.io/cran/openintro/man/abbr2state.html`)

(E) .Rmd Line number(s) for use of loops and/or control flow:

* Lines 165-172

* Lines 183-200

* Lines 219-232

* Lines 253-285

(F) .Rmd Line number(s) for use of vectorized functions:

* Lines 97-98

* Lines 105

* Lines 267-270

* Lines 

* Lines 

### Data Visualization (all 4 required)

(A) .Rmd Line number(s) for visualization with layered data from distinct data structures–e.g., a `geom` that
plots data from a secondary data frame:

* Lines 486-494

* Lines 534-552

* Lines 558-576

(B) .Rmd Line number(s) for visualization displaying many–3 or more–variables (A, B, C, & D must be
four **different** plots):

* Lines 534-552

* Lines 558-576

(C) .Rmd Line number(s) for a third visualization:

* Line 370-375

(D) .Rmd Line number(s) for a fourth visualization:

* Line 391

Other visualizations:

* Line 395

* Lines 414-421

* Lines 425-432

* Lines 442-445

* Lines 460-463

* Lines 471-474

* Lines 580-588

* Lines 599-606

* Lines 617-624

* Lines 634-642

### Data Analysis (3 of 5 required)

(A) .Rmd Line number(s) for statistical modeling/supervised learning:

* Lines 352-395

(B) .Rmd Line number(s) for unsupervised learning:

* Lines 399-474

(C) .Rmd Line number(s) for user-defined simulation(s):

*n/a*

(D) .Rmd Line number(s) for analysis of text data:

*n/a*

(E) .Rmd Line number(s) for R tools for “big data”:

* Line 37

* Line 646
