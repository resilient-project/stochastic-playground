# Stochastic Playground

This repository serves as a playground for trying out new PyPSA/PyPSA-Eur stochastic functionalities.
https://pypsa--1250.org.readthedocs.build/en/1250/examples/stochastic-optimization/#part-2-stochastic-optimization-with-pypsa-api

## Clone the repository

To start you need to clone the repository. Since the repository relies on git submodules ([pypsa-eur-resilient](https://github.com/resilient-project/stochastic-playground), you need to include the `--recurse-submodules` flag in your `git clone` command:

`git clone --recurse-submodules https://github.com/resilient-project/stochastic-playground`

## Create environment

Create environment
`conda env create -f workflow/pypsa-eur-resilient/envs/environment.yaml`

and activate
`conda activate pypsa-eur-new-opt`