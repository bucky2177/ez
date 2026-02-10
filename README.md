
# ez

<!-- badges: start -->

[![CRAN
status](https://www.r-pkg.org/badges/version/ez)](https://CRAN.R-project.org/package=ez)
[![R-CMD-check](https://github.com/bucky2177/ez/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/bucky2177/ez/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

# ez

The aim of the `ez` package for R is to provide a simplified/unified
interface to common analysis techniques, including analysis of variance
and mixed effects modeling.

This repository is a continuation of the original `ez` package developed
by Mike Lawrence (<https://github.com/mike-lawrence/ez>). The goal is to
ensure ongoing compatibility with current versions and packages of R,
and to keep `ez` available on CRAN.

The original author is fully credited for the development of `ez`.
Maintenance of the package has been taken over to address CRAN checks
and dependency updates. Should the original author wish to resume active
development in the future, maintainership will be transferred back.

## Installation

You can install the latest version of `ez` from GitHub with:

``` r
install.packages("devtools")
#> Installiere Paket nach 'C:/Users/cognium-admin/AppData/Local/Temp/RtmpIvMSdP/temp_libpath204047ff6f2f'
#> (da 'lib' nicht spezifiziert)
#> Paket 'devtools' erfolgreich ausgepackt und MD5 Summen abgeglichen
#> 
#> Die heruntergeladenen Binärpakete sind in 
#>  C:\Users\cognium-admin\AppData\Local\Temp\RtmpiQtAB4\downloaded_packages
devtools::install_github("bucky2177/ez")
#> Using GitHub PAT from the git credential store.
#> Downloading GitHub repo bucky2177/ez@HEAD
#> 
#> ── R CMD build ─────────────────────────────────────────────────────────────────
#>       ✔  checking for file 'C:\Users\cognium-admin\AppData\Local\Temp\RtmpiQtAB4\remotes262061e75f47\bucky2177-ez-1359b2e/DESCRIPTION'
#>       ─  preparing 'ez': (412ms)
#>    checking DESCRIPTION meta-information ...     checking DESCRIPTION meta-information ...   ✔  checking DESCRIPTION meta-information
#>       ─  checking for LF line-endings in source and make files and shell scripts
#>   ─  checking for empty or unneeded directories
#> ─  looking to see if a 'data/datalist' file should be added
#>       ─  building 'ez_4.5-0.tar.gz'
#>      
#> 
#> Installiere Paket nach 'C:/Users/cognium-admin/AppData/Local/Temp/RtmpIvMSdP/temp_libpath204047ff6f2f'
#> (da 'lib' nicht spezifiziert)
```

The CRAN version can be installed with:

``` r
install.packages("dRiftDM")
#> Installiere Paket nach 'C:/Users/cognium-admin/AppData/Local/Temp/RtmpIvMSdP/temp_libpath204047ff6f2f'
#> (da 'lib' nicht spezifiziert)
#> Paket 'dRiftDM' erfolgreich ausgepackt und MD5 Summen abgeglichen
#> 
#> Die heruntergeladenen Binärpakete sind in 
#>  C:\Users\cognium-admin\AppData\Local\Temp\RtmpiQtAB4\downloaded_packages
```
