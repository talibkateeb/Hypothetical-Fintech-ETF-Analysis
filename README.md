# Hypothetical-Fintech-ETF-Analysis

For this project I built a financial database and web application by using SQL, Python, and the Voilà library to analyze the performance of a hypothetical fintech ETF.

---

## Technologies

Python 3.7.10

Jupyter Lab 3.0.11

Jupyter Notebook 6.2.0

Pandas 1.2.3

Numpy 1.20.1

Pyviz - hvPlot 0.7.1

sqlalchemy 1.4.7

Voila 0.2.10

---

## Installation Guide

To install required libraries run the following commands:

    pip install pandas

    pip install voila

    pip install sqlalchemy

Install Jupyter with Anaconda. Then create and activate your conda environment to install Pyviz and set it up to work with Jupyter

    conda create -n dev python=3.7 anaconda

    conda activate dev

    conda install -c plotly plotly=4.13.

    conda install -c pyviz hvplot

    jupyter labextension install jupyterlab-plotly@4.13.0

    jupyter labextension install @jupyter-widgets/jupyterlab-manager plotlywidget@4.13.0

    jupyter labextension install @pyviz/jupyterlab_pyviz

    jupyter lab build


To run Jupyter Notebook run this command in directory with notebook file:

    jupyter notebook etf_analyzer.ipynb

To run the Voila Web Application, run this command with the relative jupyter file path

    voila etf_analyzer.ipynb


---


## Usage

Once you run the Jupyter Notebook, click on the first cell then hit:

    Shift + Enter

keys to run the first cell. Keep hitting those keys to run each cell after that or click the Run button to run the entire program.

---

## Voila Web App Recording

Here is a recording of how the web application will look when you run the voila command:


![Example](https://github.com/talibkateeb/Hypothetical-Fintech-ETF-Analysis/blob/main/ETF-analyzer-web-app-vid.gif)

---
## License

[Click here to view](https://github.com/talibkateeb/Hypothetical-Fintech-ETF-Analysis/blob/main/LICENSE)
