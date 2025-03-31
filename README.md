### Setup

1) python3 -m venv venv
2) source venv/bin/activate 
3) pip install -r requirements.txt 

#### Using JupyterLab with virtual environments

1) Install ipykernel, which consists of IPython as well

``` pip install ipykernel```

2) Create a kernel that can be used to run notebook commands inside the virtual environment

```python -m ipykernel install --user --name=python-snippets-venv```