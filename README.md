# ETF_analyzer_app
financial database and web application by using SQL, Python to analyze the performance of a hypothetical fintech ETF.

![An image for the header of the Repository](/Images/etf.png)


## Technologies
This platform uses `python 3.7.13` with the following libraries imported in the first code block includes: `Pandas`, `hvplot`, `numpy`, `Pathlib`.

---
## Installation Guide 

In case Pandas library is not available, run the following code in your terminal:

```python

pip install pandas
```



SQLAlchemy is an open-source SQL library for Python. It’s designed to ease the communication between Python-based programs and databases.

To install `sqlalchemy` , make sure your Conda `dev` environment is active, run the following command:

```python
pip install SQLAlchemy
```

To confirm the  installation, run the following code in your terminal:

```python
conda list sqlalchemy
 ```
 
We also need to install Voilà, Voilàa is a Python library, that can convert a Jupyter notebook into a live webpage.

To install Voilà, open a terminal window, and then complete the following steps:

1. Activate your Conda `dev` environment, by running the following code:

```python
conda activate dev
```

2. To install Voilà,run the following command:

```python
conda install -c conda-forge voila
```

---

## Usage

To run the Notebook from the command line, follow the steps:

1)Open your terminal and activate your conda `dev` environment.

```python
conda activate dev
```

2) Navigate to the folder. 

3) Run the following code"

```python
voila etf_analyzer.ipynb
```

![Sample Report](https://www.youtube.com/watch?v=oWQOiqmh_Hk) 




---
## Contributors

Baha Amour
---

## License

MIT.