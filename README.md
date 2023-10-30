# Plumber
The pipeline builder

## Dependencies
- numpy
- matplotlib
- python-dotenv

## Jupyter Notebook

### Mac Setup
```bash
> pip3 install jupyter
> jupyter notebook
```
if notebook unable to open due to `missing or misshapen translation settings schema`, try this
```bash
> pip3 uninstall jupyterlab
> pip3 install jupyterlab
> jupyter lab build
> jupyter lab # or
> jupyter notebook
```

### Execute Jupyter
```bash
> jupyter notebook --no-browser --NotebookApp.allow_origin='*'
```
