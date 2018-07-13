# Scipy2018 bqplot
Repo for bqplot talk at Scipy2018

### Dependencies

This package depends on the following packages:

- `ipywidgets` (version >= 7.0.0)
- `bqplot` (version > 0.10.1)
- `scikit-learn`
- `numpy`
- `pandas`
- `mne`
- `pythreejs`
- `ipyleaflet`


### Installation

Using pip:

```
$ pip install bqplot
$ jupyter nbextension enable --py --sys-prefix bqplot
$ pip install pythreejs
$ jupyter nbextension install --py --symlink --sys-prefix pythreejs
$ jupyter nbextension enable --py --sys-prefix pythreejs
$ pip install ipyleaflet
$ jupyter nbextension enable --py --sys-prefix ipyleaflet  
```

Using conda

```
$ conda install -c conda-forge bqplot
$ conda install -c conda-forge pythreejs
conda install -c conda-forge ipyleaflet
```

For a development installation (requires npm (version >= 3.8) and node (version >= 4.0)):

```
$ git clone https://github.com/bloomberg/bqplot.git
$ cd bqplot
$ pip install -e .
$ jupyter nbextension install --py --symlink --sys-prefix bqplot
$ jupyter nbextension enable --py --sys-prefix bqplot
```

Note for developers: the `--symlink` argument on Linux or OS X allows one to
modify the JavaScript code in-place. This feature is not available
with Windows.

### Questions
