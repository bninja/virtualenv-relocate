===================
virtualenv-relocate
===================

Stuff missing from virtualenv relocatable feature:

    https://github.com/pypa/virtualenv/issues/558

Apply it to an **exising** virtualenv like:

..code:: bash

    $ virtualenv --relocatable /my/venv
    $ virtualenv-relocate /my/venv
