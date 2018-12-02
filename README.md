## Set up environment
```bash
python3 -m venv ~/venvs/tweb_venv
. ~/venvs/tweb_venv/bin/activate
pip install lektor
cd webpack && npm install && cd -
```

## Build sources

```bash
lektor build --output-path public
lektor build -f webpack
```

## Development server

```bash
lektor server -f webpack
```
