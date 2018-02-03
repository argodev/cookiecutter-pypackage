======================
Cookiecutter PyPackage
======================

.. image:: https://pyup.io/repos/github/argodev/cookiecutter-pypackage/shield.svg
     :target: https://pyup.io/repos/github/argodev/cookiecutter-pypackage/
     :alt: Updates

Cookiecutter_ template for a Python package.

* GitHub repo: https://github.com/argodev/cookiecutter-pypackage/
* Documentation: https://cookiecutter-pypackage.readthedocs.io/
* Free software: BSD license

Features
--------

* Testing setup with ``unittest`` and ``python setup.py test`` or ``py.test``
* Travis-CI_: Ready for Travis Continuous Integration testing
* Tox_ testing: Setup to easily test for Python 2.7, 3.4, 3.5, 3.6
* Sphinx_ docs: Documentation ready for generation with, for example, ReadTheDocs_
* Bumpversion_: Pre-configured version bumping with a single command
* Auto-release to PyPI_ when you push a new tag to master (optional)
* Command line interface using Click (optional)

.. _Cookiecutter: https://github.com/argodev/cookiecutter

Build Status
-------------

Linux:

.. image:: https://img.shields.io/travis/argodev/cookiecutter-pypackage.svg
    :target: https://travis-ci.org/argodev/cookiecutter-pypackage
    :alt: Linux build status on Travis CI

Windows:

.. image:: https://ci.appveyor.com/api/projects/status/github/argodev/cookiecutter-pypackage?branch=master&svg=true
    :target: https://ci.appveyor.com/project/argodev/cookiecutter-pypackage/branch/master
    :alt: Windows build status on Appveyor

Quickstart
----------

Install the latest Cookiecutter if you haven't installed it yet (this requires
Cookiecutter 1.4.0 or higher)::

    pip install -U cookiecutter

Generate a Python package project::

    cookiecutter https://github.com/argodev/cookiecutter-pypackage.git

Then:

* Create a repo and put it there.
* Add the repo to your Travis-CI_ account.
* Install the dev requirements into a virtualenv. (``pip install -r requirements_dev.txt``)
* Run the script `travis_pypi_setup.py` to encrypt your PyPI password in Travis config
  and activate automated deployment on PyPI when you push a new tag to master branch.
* Add the repo to your ReadTheDocs_ account + turn on the ReadTheDocs service hook.
* Release your package by pushing a new tag to master.
* Add a `requirements.txt` file that specifies the packages you will need for
  your project and their versions. For more info see the `pip docs for requirements files`_.
* Activate your project on `pyup.io`_.

.. _`pip docs for requirements files`: https://pip.pypa.io/en/stable/user_guide/#requirements-files

For more details, see the `cookiecutter-pypackage tutorial`_.

.. _`cookiecutter-pypackage tutorial`: https://cookiecutter-pypackage.readthedocs.io/en/latest/tutorial.html

Not Exactly What You Want?
--------------------------

If you have differences in your preferred setup, I encourage you to fork this
to create your own version. Or create your own; it doesn't strictly have to
be a fork.

It's up to you whether or not to rename your fork/own version. Do whatever you
think sounds good.

I strongly suggest that you visit the page of the parent project (this is a
fork of their work) at https://github.com/audreyr/cookiecutter-pypackage


.. _Travis-CI: http://travis-ci.org/
.. _Tox: http://testrun.org/tox/
.. _Sphinx: http://sphinx-doc.org/
.. _ReadTheDocs: https://readthedocs.io/
.. _`pyup.io`: https://pyup.io/
.. _Bumpversion: https://github.com/peritus/bumpversion
.. _PyPi: https://pypi.python.org/pypi

.. _`Nekroze/cookiecutter-pypackage`: https://github.com/Nekroze/cookiecutter-pypackage
.. _`tony/cookiecutter-pypackage-pythonic`: https://github.com/tony/cookiecutter-pypackage-pythonic
.. _`ardydedase/cookiecutter-pypackage`: https://github.com/ardydedase/cookiecutter-pypackage
.. _github comparison view: https://github.com/tony/cookiecutter-pypackage-pythonic/compare/argodev:master...master
.. _`network`: https://github.com/argodev/cookiecutter-pypackage/network
.. _`family tree`: https://github.com/argodev/cookiecutter-pypackage/network/members
