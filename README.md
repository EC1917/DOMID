# DOMID (Detecting Outliers in MIxed-type Data)
The `DOMID` (Detecting Outliers in MIxed-type Data) `R` package includes functions that can be used for detecting outliers in data sets consisting of mixed-type data (i.e. both continuous and discrete variables). Some of the capabilities of the package include:

- Generating artificial data sets of mixed-type data, including some marginal outliers in either the discrete or the continuous domain (or both), as well as joint outliers.
- Calculating scores of outlyingness for both the continuous and the discrete features of a data set.
- Detecting the marginal outliers in a mixed data set, when given scores of outlyingness for discrete & continuous features.
- Finding associations among discrete variables and sets of continuous features.
- Detecting joint outliers for a given association among a discrete and a set of continuous variables.

# Installation
The package can be installed using [devtools](https://www.r-project.org/nosvn/pandoc/devtools.html).
```R
# Set build_vignettes = FALSE if you don't want to install the vignette.
devtools::install_github('EC1917/DOMID', build_vignettes = TRUE)
```
