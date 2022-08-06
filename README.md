# Forecasting Net Profit

This project is an analysis of stock prices, Google trends data, and sales data for MercadoLibre to identify trends in the data as well as forecasting future performance using the Prophet library.

---

## Technologies

This project leverages python with the following packages:

* [Pandas](https://github.com/pandas-dev/pandas) - For plotting and dataframes.

* [PyViz](https://github.com/pyviz/pyviz.org) - For plotting with hvplot.

* [Prophet](https://github.com/facebook/prophet) - For forecasting.

---

## Installation Guide

Before first running the application install the following dependencies:

```python
    pip install pandas
    pip install hvplot
    pip install holoviews
    pip install prophet
```

Login to Conda `Dev` environment and install the following dependencies:

```python
    conda install -c pyviz
```

Jupyter may be required to view the .ipynb file.

```python
    pip install jupyter
```

If using this program with Google Colab, uncomment the first block of code to install all required dependencies.

---

## Usage

If using Google Colab, comment the initial install code, any code marked for Colab in the comments, and comment out the non-Colab code. Files must be uploaded to Colab before usage and upload code is provided. It is also necessary to uncomment any holoviews extensions to use hvplot in Colab.

If using with a non-Colab IDE, comment the initial install code and any code marked for Colab in the comments and uncomment any non-Colab code. All holoviews extensions can optionally be commented.

This project is primarily intended to be used as an analysis and forecasting of the data. The code can be reused to help analyze any data as long as proper data import and setup is done. To reuse the code, it is advised to change out csv files with ones containing proper data. Modification of code may be necessary to prepare data for usage by the Prophet library. All analysis sections, which contain no code, will need to be removed or changed to fit new data.

---

## Contributors

Brought to you by Majid Kouki. You can reach me at [majidkpy@gmail.com](mailto:majidkpy@gmail.com).

---

## License

MIT
