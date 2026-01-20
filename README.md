# pipx_isolate

a [`pipx`](https://pipx.pypa.io/latest/installation/) script installer supporting [inline script metadata](https://packaging.python.org/en/latest/specifications/inline-script-metadata/) for python scripts

WIP: add docs to here, how to add bin dir to `$PATH`, typical usecases, how to use `uv` how to generate script metadata

## Installation

Requires `python3.10+`

To install with pip, run:

```
pip install git+https://github.com/purarue/pipx_isolate
```

## Usage

```
pipx_isolate --help
```

### Tests

```bash
git clone 'https://github.com/purarue/pipx_isolate'
cd ./pipx_isolate
pip install '.[testing]'
flake8 ./pipx_isolate
mypy ./pipx_isolate
```
