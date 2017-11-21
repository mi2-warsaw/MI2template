# MI2template
pkgdown template for MI2 DataLab projects

## Instructions

###Installation

Make sure you have installed the current versions of the [`pkgdown`](https://github.com/hadley/pkgdown) and `MI2template` packages. 

```
# install.packages("devtools")
devtools::install_github("hadley/pkgdown")
devtools::install_github("mi2-warsaw/MI2template")
```

### Usage

To use MI2template, add `_pkgdown.yml` file to your repository. 
This file should have the following content:

```
template:
  package: MI2template
  default_assets: false
```


Run pkgdown from the package directory:
```
pkgdown::build_site()
```
This will generate a `docs/` directory with a website for your package.


