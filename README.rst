#####
pyJac
#####

.. image:: https://zenodo.org/badge/19829533.svg
   :target: https://zenodo.org/badge/latestdoi/19829533

.. image:: https://badge.fury.io/py/pyJac.svg
    :target: https://badge.fury.io/py/pyJac

This utility creates source code to calculate the Jacobian matrix analytically
for a chemical reaction mechanism.

=============
Documentation
=============

The full documentation for pyJac can be found at http://slackha.github.io/pyJac/.

======
Theory
======

Theory, derivations, validation and performance testing can be found in the paper fully describing version 1.0.2 of pyJac:
https://Niemeyer-Research-Group.github.io/pyJac-paper/

============
Installation
============

Detailed installation instructions can be found in the
`full documentation <http://slackha.github.io/pyJac/>`_.
However, pyJac can be installed as a Python module::

   python setup.py install

or from PyPI using pip::

   pip install pyjac

=====
Usage
=====

pyJac can be run as a python module::

   python -m pyjac [options]

The generated source code is placed within the ``out`` (by default) directory,
which is created if it doesn't exist initially.
See the documentation or use ``python pyjac -h`` for the full list of options.

=======
License
=======

pyJac is released under the MIT license; see the
`LICENSE <https://github.com/slackha/pyJac/blob/master/LICENSE>`_ for
details.

If you use this package as part of a scholarly publication, please see
`CITATION.md <https://github.com/slackha/pyJac/blob/master/CITATION.md>`_
for the appropriate citation(s).

============
Contributing
============

We welcome contributions to pyJac! Please see the guide to making contributions
in the `CONTRIBUTING.md <https://github.com/slackha/pyJac/blob/master/CONTRIBUTING.md>`_
file.

=======
Authors
=======

Created by `Kyle Niemeyer <http://kyleniemeyer.com>`_
(`kyle.niemeyer@gmail.com <mailto:kyle.niemeyer@gmail.com>`_) and
Nicholas Curtis (`nicholas.curtis@uconn.edu <mailto:nicholas.curtis@uconn.edu>`_)
