.. _installation:

Installation
============

Hypercorn is only compatible with Python 3.7 or higher and can be
installed using pipenv or your favorite python package manager.

.. code-block:: sh

    pipenv install hypercorn

It is sufficient to run this single command in your working directory. Besides
installing dependency, it will also create a Pipfile if one doesn't exist yet
along with a linked virtualenv. Now you'll be able to activate your virtualenv
using:

.. code-block:: sh

    pipenv shell

To learn more about it visit `pipenv docs
<https://docs.pipenv.org/install/#installing-packages-for-your-project>`_

If you do not have Python 3.7 or better an error message ``Python 3.7
is the minimum required version`` will be displayed.
