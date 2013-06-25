Installation
============

In order to use laspy you'll need to install it onto your system.
You've got two options:

* Install via PyPI (a.k.a. pip)
* Install using distribute or setuptools

Instructions for each type of installation are below.
If you don't know the difference, follow the PyPI instructions.

Installing With PyPI
--------------------

This is the recommended way to install laspy.

1. If needed, `install pip`_.
2. Issue the command ``sudo pip install laspy``.
   If you are using a `virtual environment`_ (recommended), you don't need the sudo.

To check that laspy is installed correctly, type the following: 

.. code-block:: bash

   python -c "import laspy; print laspy.__version__"

If the laspy version echos to the shell, you're good to go!


Installing With Setuptools/Distribute
-------------------------------------

If you want to install laspy from the source tree, or if you want to use the development version, you can install using distribute.

To get the latest development version of laspy:

.. code-block:: bash

   git clone https://github.com/grantbrown/laspy.git
   
Once you've cloned the git repository, change into the new clone directory and run ``sudo python setup.py install``.
This will install laspy for all users of your computer.


Next Steps
----------

Now that you've got laspy installed, you can start learning about laspy with :doc:`tutorial/part1`, start using laspy's :doc:`apps`, or dive into the :doc:`api`.

.. _install pip: http://www.pip-installer.org/en/latest/installing.html
.. _virtual environment: http://www.virtualenv.org/en/latest/
