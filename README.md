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


To publish your site enabling GitHub Pages to publish your site

On GitHub, navigate to your GitHub Pages site's repository.

Repository settings buttonUnder your repository name, click

Settings.

#### Publishing site 

- navigate to **Settings** of your GitHub repository,

- in **GitHub Pages** section choose **master branch /docs folder** as your **Source**

- Save

Site should be publishet `<user/organization>.github.io/<repistory name>`