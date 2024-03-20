# monte-carlo-simulationss
Monte Carlo simulations for use in valuing financial derivatives


![Screen Shot 2024-03-20 at 12 39 53 AM](https://github.com/harmanbrar7/monte-carlo-simulations/assets/89001739/5ed69c81-1fe8-4741-9c7e-a5a9c1cab29c)

![Screen Shot 2024-03-20 at 12 39 40 AM](https://github.com/harmanbrar7/monte-carlo-simulations/assets/89001739/8abc9613-4287-42ff-8991-430d9436180e)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)


## Introduction

A repo dedicated to mathematical models for use in financial markets and analyzing odds in casino games (currently working on this for blackjack). 

## Features

- Risk-neutral Expectation Pricing Formula in Continuous Time
- Control Variates
- Antithetic Variates
- Gamma Variates

## Installation

```bash
# a simple python notebook enviroment is all you need
# some useful libraries
!pip install py_vollib
!pip install --upgrade pandas_datareader
import math
import numpy as np
import pandas as pd
import datetime
import scipy.stats as stats
import matplotlib.pyplot as plt
from py_vollib.black_scholes.implied_volatility import implied_volatility as iv
from py_vollib.black_scholes import black_scholes as bs
from py_vollib.black_scholes.greeks.analytical import vega, delta
from pandas_datareader import data as pdr
```
