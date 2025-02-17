.. _installation:

Installation
============

``gplearn`` requires a recent version of scikit-learn (which requires numpy and
scipy). So first you will need to `follow their installation instructions <http://scikit-learn.org/dev/install.html>`_
to get the dependencies.

Option 1: installation using pip
---------------
Now that you have scikit-learn installed, you can install ``gplearn`` using pip::

    pip install gplearn

Or if you wish to install to the home directory::

    pip install --user gplearn

For the latest development version, first get the source from github::

    git clone https://github.com/trevorstephens/gplearn.git

Then navigate into the local ``gplearn`` directory and simply run::

    python setup.py install

or::

    python setup.py install --user

and you're done!

Option 2: installation using conda
---------------
In case you want to install ``gplearn`` in an anaconda environment, you can run::

    conda install -c conda-forge gplearn

and you're done!
