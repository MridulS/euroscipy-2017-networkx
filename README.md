# EuroSciPy 2017 NetworkX [Not maintained]
# Check https://github.com/MridulS/pydata-networkx for the latest version.

### Set Up

For this tutorial, you will need Python3 and the following packages:

- `networkx==2.0b2`
- `pandas`
- `matplotlib`
- `numpy`
- `scipy`
- `ndlib`
- `jupyter`

Python2 may/may not work, no promises :)

### Clone/Download the repo

- `$ cd /path/to/your/directory`
- Clone the repository from GitHub
	 `$ git clone https://github.com/mriduls/euroscipy-2017-networkx`
- `$ cd euroscipy-2017-networkx`

**OR**

- Download the required notebooks from `https://github.com/MridulS/euroscipy-2017-networkx/archive/master.zip`
- unzip the files and change the directory to 
		`$ cd euroscipy-2017-networkx-master` 

### Install packages 
#### Using pip and virtualenv


- Create a virtual environment for this tutorial, so that the installed packages do not mess with your regular Python environment.
    - `$ (sudo) pip install virtualenv`
    - `$ virtualenv -p python3 networkx`
    - `$ source networkx/bin/activate`
- `$ pip install matplotlib networkx==2.0b2 pandas numpy jupyter ndlib`


#### Using Anaconda
If you have the Anaconda distribution of **Python 3** installed, then run the commands below.

- `$ conda env create -f environment.yml`
- `$ source activate networkx`

### Check your environment:

- `$ python checkenv.py`

### Run the Jupyter Notebook

    $ jupyter notebook

Your browser will open to an index page where you can click on a notebook to run it.

### Credits

This tutorial is inspired by the previous offerings of this tutorial at EuroSciPy 2016, SciPy 2015 and Eric Ma's tutorial Network Analysis made Simple https://github.com/ericmjl/Network-Analysis-Made-Simple
