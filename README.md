# JupyterNotebookDocs
Documenting all required prerequisites for Computational Physics

 **Python version 3.9.5**

 Download [Python 3.9.5](https://www.python.org/downloads/release/python-395/)

## Method For Installing on X86_64 Intel based MAC
 Install [Anaconda](https://www.anaconda.com/products/individual) 

### Open Terminal and follow

 Install **Homebrew**
>`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`


Install **pip**

>`brew install pip`

Install dependencies libraries

>`pip install numpy, scipy, matplotlib, pandas`

### Launch Anaconda and run Jupyter Notebook

## Method For Installing on arm64 M1 based MAC

### Open Terminal and follow

Install **Homebrew**
>`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

Install **pip**

>`brew install pip`

Install dependencies libraries

>`pip3 install cython pybind11`

>`pip3 install --no-binary :all: --no-use-pep517 numpy`

>`brew install openblas gfortran`

>`export OPENBLAS=/opt/homebrew/opt/openblas/lib/`

>`pip3 install --no-binary :all: --no-use-pep517 scipy`

>`pip3 install jupyter`

>`jupyter notebook`