# pylib &mdash; Documentation

This is the rather simplistic documentation example from the Tools & Skills class of The Python Quants.

<br>

<img src="http://hilpisch.com/images/finaince_visual_low.png" width=300px>

## Package

The package documented contains a total of three simple Python files, two of which are in sub-folders/sub-packages, with a single function each.

## Training

In addition to the package files, the Git repository contains also other files used for the training session.

##  Documentation

### Sphinx

The `Sphinx` package represents a standard in Python documentation. See e.g. http://www.sphinx-doc.org and http://www.sphinx-doc.org/en/stable/tutorial.html.

A valuable add-on is the `nbsphinx` extension which allows you to directly include Jupyter Notebook files into your documentation. See https://nbsphinx.readthedocs.io.

### Environment

On the shell, create an environment with `conda`:

    conda create -n docu-pylib python=3.6 ipython
    conda activate docu-pylib
    pip install sphinx nbsphinx

### Build the Documentation

Clone the Github repository to your local working folder:

    git clone --depth=1 http://github.com/yhilpisch/documentation
    
Navigate to the repository folder and install the package:

    cd documentation
    make html

    
## First Steps
    
Start a Python interactive session session and e.g. execute:

    >>> import pylib
    >>> pylib.one(10)
    10
    >>> pylib.two(20)
    40
    >>> pylib.three(3)
    9

## Copyright

The material is copyright (c) Dr. Yves J. Hilpisch | The Python Quants GmbH. MIT License.
