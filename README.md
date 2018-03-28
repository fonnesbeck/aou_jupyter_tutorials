# aou_jupyter_tutorials
Jupyter tutorials for All of Us workbench users

## Software Requirements

The first step is to install Python on your computer. I will be teaching this course based on **Python 3.6**. Perhaps the easiest way to get a feature-complete version of Python on your system is to install the [Anaconda](https://www.anaconda.com/download). Anaconda is a completely free Python environment that includes includes almost 200 of the best Python packages for science and data analysis. Its simply a matter of downloading the installer (either graphical or command line), and running it on your system.

Be sure to download the Python 3.6 installer, by following the **Python 3.6 link**


## Getting this repository

    git clone https://github.com/fonnesbeck/aou_jupyter_tutorials.git

If you are not familiar with Git and GitHub, you can simply download the zip file of the repository at the top of the main repository page.

Then, move to the directory created by the clone/zip file:

    cd aou_jupyter_tutorials

and install everything using `conda`:

    conda env create -f environment.yml

This will create an **environment** called `jupyter_tutorial` that includes the packages required for the course.  These include:

- ipython
- ipywidgets
- jupyter
- line_profiler
- matplotlib
- notebook
- numpy
- pandas
- pip
- pyzmq
- scipy
- seaborn  
​    
If you are not using the Anaconda Python distribution, you will need to manually install the packages listed in `environment.yml` using `pip`.

Which you probably don't want to do.

So install Anaconda.

To use the environment, you may type:

    source activate jupyter_tutorial