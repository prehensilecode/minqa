# minqa
Derivative-free optimization by quadratic approximation based on an interface to Fortran implementations by M. J. D. Powell.

- Author: Douglas Bates, Katharine M. Mullen, John C. Nash, Ravi Varadhan
- Maintainer: Katharine M. Mullen <katharine.mullen@stat.ucla.edu>

Forked from source bundle hosted at: https://CRAN.R-project.org/package=minqa

Project website: https://optimizer.r-forge.r-project.org/

## Why this fork?
The original version hosted at CRAN would [fail to build using MRO 4.0.2
on RHEL8](https://stackoverflow.com/questions/67286689/installing-a-fortran-based-r-package-in-mro-shows-the-copyright-message-in-link).
The fix is simple: remove a line from `src/Makevars`.

## Installation
To install, download the source `.tar.gz` file, and then:
```
    R CMD INSTALL minqa-x.y.z.tar.gz
```
