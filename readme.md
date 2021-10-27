# Calculator Project Setup
[![Build Status](https://app.travis-ci.com/krojas64/calc2.svg?branch=main)](https://app.travis-ci.com/krojas64/calc2)

Updated to include my own Travis CI badge.

To run tests, Lint, and Coverage report use this command:

pytest  --pylint --cov

.pylintrc is the config for pylint
.coveragerc is the config for coverage
setup.py is a config file for pytest

The current calculator is designed to add, subtract, multiply, and divide.
Testing is done on each function of the calculator, with an additional test for divide by zero.
