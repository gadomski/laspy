LAS Read-Writer in Python
=========================

Laspy is a Python library for reading, modifying and creating `.LAS point cloud data files`_.
API Documentation and tutorials are available at http://www.laspy.org/.
Laspy was inspired by `liblas`_.
For reading and writing many different flavors of three-dimensional pointcloud files, check out `PDAL`_.


Installation
------------

The simplest way to install laspy is to use `PyPI`_::

    (sudo) pip install laspy

If you are installing laspy to a system directory, you might need the sudo.   

You may also install laspy the old-fashioned way::

    python setup.py build
    python setup.py install 

Again, you may need to run these commands as root/administrator.


Reporting Issues
----------------

If you have an issue or bug you'd like to report, please use `Github issues`_ to do so.


Contributing
------------

Contributions to laspy are very welcome.
Simply `create a pull request`_ on `grantbrown/laspy`_ to send us your patch!


Contributer List
----------------

https://github.com/grantbrown/laspy/contributors


.. _liblas: http://liblas.org
.. _PDAL: http://pointcloud.org
.. _PyPI: https://pypi.python.org/
.. _.LAS point cloud data files: http://asprs.org/Committee-General/LASer-LAS-File-Format-Exchange-Activities.html
.. _Github issues: https://github.com/grantbrown/laspy/issues
.. _create a pull request: https://help.github.com/articles/creating-a-pull-request
.. _grantbrown/laspy: https://github.com/grantbrown/laspy
