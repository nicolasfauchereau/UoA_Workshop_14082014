#Using open-source software for Engineering and Science research

**14 August 2014**


> Room 423-340  
> University of Auckland  
> Conference building  
> between 20 and 24 Symonds street (*between the Engineering building and the security building*)  
> Auckland  
> New Zealand  

[https://wiki.auckland.ac.nz/x/FQEuB](https://wiki.auckland.ac.nz/x/FQEuB)

Email: <mailto:Nicolas.Fauchereau@gmail.com>

All the material (notebooks) are indexed at:

[https://github.com/nicolasfauchereau/UoA_Workshop_14082014](https://github.com/nicolasfauchereau/UoA_Workshop_14082014)

If you have git installed, the easier is to clone my repository (from the command line):

    git clone https://github.com/nicolasfauchereau/UoA_Workshop_14082014

If you are not a git user, simply download the tarball from [here](https://github.com/nicolasfauchereau/UoA_Workshop_14082014/archive/master.zip)

---

Follow the links to the for HTML-rendered (**static**) versions of the notebooks:

+ [Introduction](http://nbviewer.ipython.org/github/nicolasfauchereau/UoA_Workshop_14082014/blob/master/Introduction.ipynb)
+ [Python Introduction](http://nbviewer.ipython.org/github/nicolasfauchereau/UoA_Workshop_14082014/blob/master/Python_intro.ipynb)
+ [Numpy](http://nbviewer.ipython.org/github/nicolasfauchereau/UoA_Workshop_14082014/blob/master/Numpy.ipynb)
+ [Scipy](http://nbviewer.ipython.org/github/nicolasfauchereau/UoA_Workshop_14082014/blob/master/Scipy.ipynb)
+ [Matplotlib](http://nbviewer.ipython.org/github/nicolasfauchereau/UoA_Workshop_14082014/blob/master/Matplotlib.ipynb)
+ [Pandas](http://nbviewer.ipython.org/github/nicolasfauchereau/UoA_Workshop_14082014/blob/master/Pandas.ipynb)

---

### Installation instructions

I recommend using the [Anaconda scientific python distribution](https://store.continuum.io/cshop/anaconda/), which is a completely free enterprise-ready Python distribution for large-scale data processing, predictive analytics, and scientific computing. It includes the python interpreter itself, the python standard library as well as a set of packages exposing data structures and methods for data manipulation and scientific computing and visualization. In particular it provides Numpy, Scipy, Pandas, Matplotlib (...). The full list of packages is available at:

[http://docs.continuum.io/anaconda/pkgs.html](http://docs.continuum.io/anaconda/pkgs.html)

The Anaconda python distribution must be downloaded from:

[http://continuum.io/downloads](http://continuum.io/downloads)

Once copied over, make sure the anaconda installer is executable by going in the right directory (with cd) and entering (example for ```version 2.0.1``` of Anaconda on a 64bit Linux machine):

    $ chmod +x Anaconda-2.0.1-Linux-x86_64.sh

then to launch the installer:

    $ ./Anaconda.2.0.1-Linux-x86_64.sh

The installer will ask you a few questions, the most important is related to the installation directory, I recommend installing in the `$HOME` directory (user installation)

Once Anaconda is installed, you need to update conda (the python ‘package manager’ that comes with anaconda and allows the painless installation and update of third party modules) by entering

    $ /opt/anaconda/bin/conda update conda

Then a good thing is to update the anaconda packages already installed

    $ /opt/anaconda/bin/conda update anaconda

You also need to install [pip](https://github.com/pypa/pip) to install packages from the [Python Package Index](http://pypi.python.org/pypi).

    $ /opt/anaconda/bin/conda install pip

### Running the material (IPython notebooks)

Once the [Anaconda scientific python distribution](https://store.continuum.io/cshop/anaconda/) has been installed:

1. navigate (in the terminal) to the directory where you have unpacked or clone my repository (`*.ipynb` files should be present)
2. run:
```
ipython notebook
```
3. Open `test.ipynb` and in the menu bar select `Cell / Run all` to see if everything installed fine

To visualize the notebooks from my github repository please head to the [README](README.md) which contains links to static, HTML rendered versions of the notebooks, that you can follow online (but not run !).
