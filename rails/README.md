
# ipycytoscape

[![Build Status](https://travis-ci.org/QuantStack/ipycytoscape.svg?branch=master)](https://travis-ci.org/QuantStack/ipycytoscape)
[![codecov](https://codecov.io/gh/QuantStack/ipycytoscape/branch/master/graph/badge.svg)](https://codecov.io/gh/QuantStack/ipycytoscape)


A Cytoscape widget

## Installation

You can install using `pip`:

```bash
pip install ipycytoscape
```

Or if you use jupyterlab:

```bash
pip install ipycytoscape
jupyter labextension install @jupyter-widgets/jupyterlab-manager
```

If you are using Jupyter Notebook 5.2 or earlier, you may also need to enable
the nbextension:
```bash
jupyter nbextension enable --py [--sys-prefix|--user|--system] ipycytoscape
```