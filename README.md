# ai-statistics-challenge
This is a basic practical challenge about **Statistics for Devs** with Python.

Check the **develop** branch to see the `ipynb` file.

## Tasks
* Show the average sales
* Create a vertical bar chart showing the reference month and value
* Create a line chart showing the reference month and value.

## Dictionary to be used
```
dict_sales = {
    'data_ref': ['2023-01-01', '2020-02-01', '2021-03-01', '2022-04-01', '2023-05-01', '2023-06-01', '2020-07-01', '2021-08-01', '2022-09-01', '2023-10-01','2022-11-01', '2023-12-01'],
    'value': [400000, 890000, 760000, 430000, 920000,340000, 800000, 500000, 200000, 900000,570000, 995000]
}
```

## Dependencies
### pipenv
pipenv is a dependency management tool for Python that allows creating and managing isolated virtual environments for projects, ensuring that dependencies are consistent and easy to manage.

To install pipenv, run:
```
$ pip install --user pipenv
```

Then, to install pipenv on your project directory, run:
```
$ pipenv install
```

And finally, to activate your new virtual environment, run:
```
$ pipenv shell
```

Learn more about [pipenv](https://pipenv.pypa.io/en/latest/index.html).

---

To install any of the following dependencies on your project **virtual environment**, run:
```
$ pipenv install <name>
```
and replace `<name>` with the correct dependecy name.

If you're not using pipenv or any kind of virtual environment, do the same thing, but with:
```
$ pip install <name>
```

### ipykernel
ipykernel is a kernel for Jupyter Notebook that allows running Python code in an interactive environment, providing features such as autocomplete, debugging, and result visualization.

Learn more about [ipykernel](https://pypi.org/project/ipykernel/).

### pandas
pandas is an open-source library for data manipulation and analysis in Python, providing data structures and operations to work with structured data, including data import/export, merge, groupby, pivot, reshape, and more.

Learn more about [pandas](https://pandas.pydata.org/).

### matplotlib
matplotlib is an open-source library for creating graphs and visualizations in Python, allowing the creation of a variety of charts, including lines, bars, scatter, histograms, and more.

Learn more about [matplotlib](https://matplotlib.org/).