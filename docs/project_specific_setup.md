# Project-specific setup

This document contains setup instructions specifically for this project only. This design enables
us to keep other docs easily aligned with future upstream changes to
[coefficient-cookiecutter](https://github.com/CoefficientSystems/coefficient-cookiecutter/).


## Install system-level dependencies with [homebrew](https://brew.sh/)

```sh
# brew install wkhtmltopdf
```


## Jupyter kernel

```sh
python -m ipykernel install --user --name folk-music-recommender --display-name "Python (folk-music-recommender)"
```
