# vxdb-notebooks
Jupyter notebooks for exploring [virus.exchange](virus.exchange) data.

------------------------

## Dependencies
Access to the API is handled via the [`vxdb'](https://github.com/backchannelinc/vxdb) Python wrapper. That wrapper is really just a slight fork of [MWDB](https://mwdb.cert.pl/) if you prefer it.

Clone `vxdb`, enter the directory and run this to install it:
```
python3 -m pip install .
```
and if you want the CLI as well, run this after:
```
python3 -m pip install vxdb[cli]
```

------------------------

## Contents

| Notebook | Description |
| --- | --- | 
| [0_Exploring_VXDB.ipynb](./0_Exploring_VXDB.ipynb) | Starter notebook for exploring [virus.exchange](https://virus.exchange), which is [VX Underground](https://www.vx-underground.org/)'s malware repository based on [mwdb.cert.pl](https://mwdb.cert.pl). |