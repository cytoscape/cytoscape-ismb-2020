# Automation in the Cytoscape Ecosystem Tutorial

This repository contains resources that will be used in the Automation in the Cytoscape Ecosystem Tutorial.

## Table of Contents

* [Download instructions](#download-instructions)
* [Python](#python)
* [R](#r)
* [JavaScript](#javascript)

## Download instructions

There are three options for downloading the contents of this repository.

#### Downloading as a ZIP file
You can download the repository as a ZIP file by navigating to https://github.com/cytoscape/cytoscape-ismb-2020, clicking the green "Code" button in the upper right, and then clicking "Download ZIP". You will then need to unzip the file.

#### Downloading using GitHub Desktop
If you have GitHub Desktop installed, you can download this repository by navigating to https://github.com/cytoscape/cytoscape-ismb-2020, clicking the green "Code" button in the upper right, and then clicking "Open with GitHub Desktop".

#### Cloning the repository
You can also clone the repository using git by running the following on the command line:
```
git clone https://github.com/cytoscape/cytoscape-ismb-2020.git
cd cytoscape-ismb-2020
```

## Python

This directory contains the four jupyter notebooks that may be used in the tutorial.

#### Notebooks

`cytoscape-ecosystem-tutorial-py4cytoscape.ipynb` is the completed tutorial for the new [py4Cytoscape](https://py4cytoscape.readthedocs.io/en/latest/) python package, which allows python to communicate programmatically with the Cytoscape desktop application. 
* `cytoscape-ecosystem-tutorial-py4cytoscape-empty.ipynb` is the "fill-in-the-blank" version of the py4Cytoscape notebook, and should be used by those wishing to code along with the tutorial.

`cytoscape-ecosystem-tutorial-ndex2.ipynb` is the complete tutorial for the [ndex2](https://ndex2.readthedocs.io/en/latest/) python package, which allows python to communicate programmatically with NDEx, the online repository for biological networks. 
* `cytoscape-ecosystem-tutorial-ndex2-empty.ipynb` is the "fill-in-the-blank" version of the ndex2 notebook.

#### Running the notebooks

To run the notebooks, navigate to this directory on the command line, then run the `jupyter notebook` command.
```
cd cytoscape-ismb-2020/Python
jupyter notebook
```

## R

The R Example is [here](https://cytoscape.org/cytoscape-automation/for-scripters/R/notebooks/Cytoscape-ecosystem-tutorial.nb.html)

## JavaScript

The JavaScript example contains a standalone web-page that follows the relevant steps from the tutorial. To run the tutorial, navigate to the JavaScript directory in the downloaded tutorials file and do one of the following:

- Open the index.html file in your web browser.
- Mount the web page using a web-server, such as python's http.server. This will behave more like an actual web page would, and is more useful for web development. With python 3 installed, you can use the following command:`sudo python3 -m http.server 80`. After it runs, go to `localhost` in your web browser to see the web page.

 
