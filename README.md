![splverse](https://docs.sykdomspulsen.no/packages/hex_dependencies.png)

## drat repository

This [drat](http://dirk.eddelbuettel.com/code/drat.html) package repository provides [splverse](https://docs.sykdomspulsen.org/packages.html) packages.

### Usage

#### Usage via drat

```{.r}
# first add the repo
drat:::addRepo("sykdomspulsen-org")

# either install just one or more given packages
install.packages("spldata")     

# or update already installed packages
update.packages()
```

#### Usage without drat

```{r}
# pass the repo info directly to install.packages()
install.packages("sykdomspulsen", repos="https://docs.sykdomspulsen.org/drat")
```

#### Usage without drat on the shell

```{sh}
Rscript -e 'install.packages("Rcpp", repos="https://docs.sykdomspulsen.org/drat")'
```

### License

Packages in this repository are available under their respective license, which is generally MIT.
