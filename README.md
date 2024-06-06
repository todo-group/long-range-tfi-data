# Data repository for "Stochastic parameter optimization analysis of dynamical quantum critical phenomena in long-range transverse-field Ising chain"

## Description

This repo. contains two different types of data.

- `_log`: logarithmic extrapolation
- `` (empty): power-law extrapolation

Each CSV file contains the following observables:

| tag          | symbol                        | description                                    |
| ------------ | ----------------------------- | ---------------------------------------------- |
| `z`          | $z$                           | dynamical critical exponent                    |
| `beta_o_nu`  | $\beta / \nu$                 | magnetization exponent                         |
| `gam_o_nu`   | $\gamma / \nu$                | susceptibility exponent                        |
| `scaling`    | $2\beta/\nu + \gamma/\nu - z$ | leftover exponent of the hyperscaling relation |
| `correction` | $\theta$                      | correction exponent defined in the paper       |
| `optr`       | $R_{\text{opt}}$              | optimal value of correlation ratio             |
| `gc`         | $\Gamma_{\text{c}}$           | critical field                                 |

Each file is consisting of three columns, which are

1. $\sigma$ (interaction decay exponent)
2. observable
3. standard error

from left to right.

Note that $\sigma = \infty$ is missing for `scaling_processed.csv` as its decay is too fast to get a reliable estimate.
