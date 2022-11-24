## How to use

Run `usethis::edit_r_profile()` to edit your `.Rprofile`. Then write in:

```
options(repos=structure(c(
  FHI="https://sykdomspulsen-org.github.io/drat/",
  CRAN="https://cran.rstudio.com"
)))
```

Save the file and restart R.
