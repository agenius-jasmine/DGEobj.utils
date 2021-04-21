## Comments from Maintainer

* This is a new package to be added to CRAN, it contains utilities for running DE analysis 
  in concert with the (newish) DGEobj package
* Code Coverage is 99%

---  

## Test environments

RStudio Server Pro (ubuntu 18.04.2)  

* R 3.6.3
* R 4.0.4

Travis-CI (ubuntu 16.04.6)

* R 3.6.3
* R 4.0.2
* R devel (2021-04-14 r80165)

WinBuilder

* devtools::check_win_devel()  
* devtools::check_win_release()  

RHub

* devtools::check_rhub(interactive = F)

---  

## R CMD check results


```
devtools::check()  

0 errors ✓ | 0 warnings ✓ | 0 notes ✓
```

---  

## Reverse dependencies


**NONE**

```
revdepcheck::cran_revdeps('DGEobj.utils', bioc = T)

character(0)
```