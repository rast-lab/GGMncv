# GGMncv 2.1.1

## Bug Fixes

- Updated `src/Makevars.in` to require C++14 (`CXX_STD = CXX14`) to comply with
  the minimum standard now enforced by RcppArmadillo. Fixes compilation errors
  on systems with recent versions of RcppArmadillo that require C++14 or later.
