# Data analysis with Python (yt and nonos)

These tutorials require Python 3.8 or newer.

Both tutorials include environment files. It is strongly advised to create virtual
environments before installing anything specifically for these tutorials. To get
started, navigate to a tutorial's subdirectory and create a virtual environment ...

## with conda
```shell
$ conda create --name=<name> --file=environment.yaml
$ conda activate <name>
```

use a meaningful name each time (for instance `idefix-yt-tutorial`, `nonos-tutorial` ...)

## or with `pip`
```shell
$ python -m venv .venv
$ source .venv/bin/activate
$ python -m pip install --upgrade pip
$ python -m pip install --requirement requirements.txt
```