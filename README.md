
# ipyvega

[![Build Status](https://travis-ci.org//ipyvega.svg?branch=master)](https://travis-ci.org//ipyvega)
[![codecov](https://codecov.io/gh//ipyvega/branch/master/graph/badge.svg)](https://codecov.io/gh//ipyvega)


A Custom Jupyter Widget Library for Vega.js

## Installation

You can install using `pip`:

```bash
pip install ipyvega
```

Or if you use jupyterlab:

```bash
pip install ipyvega
jupyter labextension install @jupyter-widgets/jupyterlab-manager
```

If you are using Jupyter Notebook 5.2 or earlier, you may also need to enable
the nbextension:
```bash
jupyter nbextension enable --py [--sys-prefix|--user|--system] ipyvega
```
