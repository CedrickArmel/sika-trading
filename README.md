# Sika Algorithimic Trading

An algorithmic trading bot trading bot leveraging Sentiment Analysis and classical quantititative stocks markets analysis technics.

## Installation for developpement

To install this project you need these dependencies installed:

- Python `^3.12`
- [Poetry](https://python-poetry.org/docs/)

### System dependencies

#### Install TA-Lib

On Mac OS X:

```sh
brew install ta-Lib
```

On Linux, Download [ta-lib-0.4.0-src.tar.gz](https://sourceforge.net/projects/ta-lib/files/ta-lib/0.4.0/ta-lib-0.4.0-src.tar.gz/download) and:

```sh
tar -xzf ta-lib-0.4.0-src.tar.gz
cd ta-lib/
./configure --prefix=/usr
make
sudo make install
```

### Clone the project

```sh
git clone <repository>
```

### Install the dependencies

```sh
poetry shell && poetry instal
```

## Project Organization

```md

├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for
│                         sikatrading and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── poetry.lock   <- resolves and locks all dependencies and their sub-dependencies in the pyproject.toml file.
│
│
└── sikatrading   <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes sikatrading a Python module
```

--------
