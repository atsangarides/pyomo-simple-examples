# pyomo-simple-examples

A collection of notebooks illustrating how `pyomo` can be used to solve:
1. A linear program
2. A mixed integer linear program
3. A non linear program

## Requirements

### python packages
Create a new environment and install dependencies
```shell
# create new environment using poetry
poetry shell
# install packages
poetry install
```

### solvers

Following steps work for MacOS systems. They are also available via `conda`.
Instructions for running within a docker container will be included soon.

```shell
brew install glpk
brew install ipopt
```