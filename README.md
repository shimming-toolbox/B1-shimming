# B1-shimming

Jupyter book presenting what transmit radiofrequency shimming is and how it is used in MRI applications.

## Getting started
#### 1) You will need to [install miniconda](https://docs.conda.io/en/latest/miniconda.html) in order to set-up your python environment.

#### 2) Clone this GitHub repository on your computer:
```bash
git clone https://github.com/shimming-toolbox/B1-shimming.git
cd B1-shimming
```

> For Windows user, you might need to [install git](https://git-scm.com/downloads) prior to clone the repository.

> If git clone is not working, you can download the zipped version of the repository and unzip it locally on your computer.

#### 3) Run the following commands in order to create your virtual environment and start the jupyter book:

```bash
conda env create -f environment.yml  # Create the conda virtual environment
conda activate b1  # Activate the conda virtual environment
jb build book/  # Build the Jupyter book
```
You can then follow the provided link (e.g. `/mnt/c/Users/XXX/github/B1-shimming/book/_build/html/index.html`) to open 
the Jupyter book in your browser.

> Make sure that your prompt is currently on the `B1-shimming` folder when you call the `environment.yml` file.

> For Windows user, you might need to type these commands in `Anaconda Prompt` if `cmd` does not recognize `conda`.