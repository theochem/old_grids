# GRID
[![Python Version](https://img.shields.io/badge/python-3.6%2B-blue.svg)](https://docs.python.org/3/whatsnew/3.6.html)
[![Build Status](https://travis-ci.org/theochem/grid.svg?branch=master)](https://travis-ci.org/theochem/grid)
[![codecov](https://codecov.io/gh/theochem/grid/branch/master/graph/badge.svg)](https://codecov.io/gh/theochem/grid)
[![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://github.com/theochem/grid/blob/master/LICENSE)
[![GitHub contributors](https://img.shields.io/github/contributors/theochem/grid.svg)](https://github.com/theochem/grid/graphs/contributors)
[![Code Style](https://img.shields.io/badge/code%20style-black-black.svg)](https://black.readthedocs.io/en/stable/)

## About
GRID is a pythonic numerical integral package. It derived from legacy HORTON 2 numerical integration module.

## License
GRID is distributed under [GPL License version 3](https://github.com/theochem/grid/blob/master/LICENSE) (GPL v3).

## Dependence
* Installation requirements: `numpy`, `scipy`
* Testing requirement: `pytest`
* QA requirement: `tox`

## Installation
* To install GRID to system:
```bash
pip install .
```

## Local build and Testing
To install editable GRID locally:
```bash
pip install -e .
```
To run tests:
```
pytest tests
```

## Quality Assurance
To run QA locally:
```bash
tox
```