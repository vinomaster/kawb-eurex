# European Exchange Financial Analysis

* Repo Name: kawb-eurex
* Required Technology: IBM Knowledge Anyhow Workbench (KAWB)
* Solution Format: IPython Notebooks (ipynb)

## Overview
Using real data from the [European Exchange](http://www.eurexchange.com/exchange-en/about-us/), these tutorials focus on an analysis of historical VSTOXX® as well as historical EURO STOXX 50® data. They demonstrate how to explore financial content to verify that volatility indexes are negatively correlated with stock indexes. Historical data in CSV format is ingested via local as well as remote storage, pre-processed, transfered to pandas Data Frames and saved in a HDF5 file. Python is then used to statistically and graphically analyze the data.

## Tutorials

### Basic
A sample notebook that recreates the [Analyzing Historical VSTOXX Data](http://www.eurexchange.com/vstoxx/b_Analyzing_Historical_VSTOXX_Data.html-1) tutorial.

### Importable Notebooks
A sample notebook (ipynb) that pulls data from a [SWIFT](http://docs.openstack.org/developer/swift/) [Object Store on SoftLayer](http://www.softlayer.com/lp/object-storage) and then uses that data to perform the data analysis workflow outlined in the Basic Tutorial. This sample demonstrates the power of importable notebooks, a feature of KAWB.
