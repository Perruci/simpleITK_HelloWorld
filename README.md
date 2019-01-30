# Simple ITK Sandbox

Repository to host some experiments with [SimpleITK](https://github.com/InsightSoftwareConsortium/SimpleITK) and Python.

Heavily inspired in [Simple ITK Notebooks](https://github.com/InsightSoftwareConsortium/SimpleITK-Notebooks).

### Pre-requisits

Python 3 and dependencies listed on (environment.yml)[environment.yml] file. 
Easier setup with (Anaconda)[https://www.anaconda.com/distribution/#download-section] distibution. 

### How to Use

Create a virtual environment with the dependencies of the project.

```(bash)
conda env create -f environment.yml
```

Then activate the virtual environment:

```(bash)
conda activate sitkpy
```

Finaly launch the application Jupyter Notebook.

```(bash)
jupyter notebook
```