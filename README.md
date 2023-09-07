# Bayesian analysis of Lucia's rock types

In [1995, Lucia](https://doi.org/10.1306/7834D4A4-1721-11D7-8645000102C1865D) published a method for using rock fabric to classify carbonate rocks. These classifications have been used industry-wide to estimate permeability from porosity. Let's analyze this seminal paper under a Bayesian statistical framework.

The fun happens in `lucia.ipynb`.

## Running the examples

If you haven't installed python on your computer, [start with that](https://www.python.org/downloads/). Then, from this directory, create a virtual environment:

Windows:

```console
python -m venv venv
.\venv\Scripts\activate
```

Linux/Mac:

```console
python3 -m venv venv
source venv/bin/activate
```

Install the required modules:

```console
pip install -r requirements.txt
```

An open the jupyter notebook with jupyter (`pip install jupyterlab`)

```console
jupyter-lab
```

or with VS-code

```console
code .
```
