# SSOAP

This is just a copy of R-package `SSOAP`. It is [removed from CRAN](https://cran.rstudio.com/web/packages/SSOAP/). The homepage [www.omegahat.org/SSOAP](http://www.omegahat.org/SSOAP/) was not responding. There is also a [omegahat github repository](https://github.com/omegahat/SSOAP) but I cannot install from it. So I decided to put a copy of the package here. The author of the package is Duncan Temple Lang.

Install via:
```r
install.packages("devtools")
devtools::install_github("bdemeshev/SSOAP")
```

Or try
```r
install.packages('SSOAP', repos = 'http://www.omegahat.org/R',   dependencies = TRUE, type = 'source')
```

If the package `XMLSchema` is missing it can be installed via
```r
devtools::install_github("omegahat/XMLSchema")
```

