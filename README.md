# choxos.r-universe.dev

Registry for my personal [R-universe](https://r-universe.dev): <https://choxos.r-universe.dev>

The [`packages.json`](packages.json) file lists the Git repositories of the R
packages published to this universe. Edit it (add/remove entries) to change what
is built and served.

## Install packages from this universe

```r
# Enable this universe
options(repos = c(
    choxos = "https://choxos.r-universe.dev",
    CRAN = "https://cloud.r-project.org"))

# Install (binaries are built for the popular platforms)
install.packages("mlumr")
```

## Packages

| Package | Source |
|---------|--------|
| [mlumr](https://choxos.r-universe.dev/mlumr) | <https://github.com/choxos/mlumr> |
