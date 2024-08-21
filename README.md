## Set up the environment

Requirements:
* Python
* Jupyter Lab
* Pytorch

```sh
python -m venv my_environment
source venv/bin/activate
python -m pip install -r requirements.txt
python -m ipykernel install --user --name=my_environment
jupyter lab
```
When selecting a notebook, click on the "my_environment" square.

## Uninstall the environment

```sh
jupyter kernelspec uninstall my_environment
```

