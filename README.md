This [drat](http://dirk.eddelbuettel.com/code/drat.html) package repository provides [splverse](https://docs.sykdomspulsen.no/packages.html) packages.

![splverse](https://docs.sykdomspulsen.no/packages/hex_dependencies.png)

### Usage

#### Usage via drat

```{.r}
# first add the repo
drat::addRepo("sykdomspulsen-org")

# either install just one or more given packages
install.packages("spldata")     

# or update already installed packages
update.packages()
```

#### Usage without drat

```{r}
# pass the repo info directly to install.packages()
install.packages("sykdomspulsen", repos = c("https://docs.sykdomspulsen.no/drat", "https://cran.rstudio.com"))
```

#### Usage without drat on the shell

```{sh}
Rscript -e 'install.packages("spldata", repos = c("https://docs.sykdomspulsen.no/drat", "https://cran.rstudio.com"))'
```

### License

Packages in this repository are available under their respective license, which is generally MIT.
