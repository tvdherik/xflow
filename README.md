# xflow
Hypersonic Facility Flow Modelling Code

### Notes
XFLOW utilises the [gdtk](https://gdtk.uqcloud.net/) and its [Eilmer](https://gdtk.uqcloud.net/docs/eilmer/about/) CFD capability to model hypersonic ground test facilitities - predicting of nozzle exit composition and temperatures as well as driven tube shock speeds. The code was built specifically to discern non-equilibrium thermochemical facility exit conditions.

### Setup
1. Clone the repository.

```
git clone git@github.com:tvdherik/xflow
```

2. Navigate to /src/ and run 'make install'

```
make install
```

3. Add the following to your .bash_aliases (or .bashrc) file (enabling python to locate the hfmc package).

```
export XFLOW=$HOME/xflow
export PYTHONPATH=${PYTHONPATH}:${XFLOW}/lib
```


### Usage (python 3.10.0+) (requires matplotlib and numpy)
```
import xflow
```

_or use by command line_
```
todo
```
