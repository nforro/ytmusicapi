Contributing to ytmusicapi
##########################

Issues
-------
Please make sure to include sufficient details for reproducing your issue.
This includes the version of the library used as well as detailed instructions for reproduction.
If needed, please include the YouTube Music API response as well by debugging the API (responses
may differ based on the user account, so this helps with reproducing new issues).


Pull requests
--------------
Please open an issue before submitting, unless it's just a typo or some other small error.

Before making changes to the code, install the development requirements using

.. code-block::

    pip install -e .[dev]

Before committing, run style and linter checks using

.. code-block::

    pre-commit run


Code structure
---------------
The folder ``ytmusicapi`` contains the main library which is distributed to the users.
Each main library function in ``ytmusic.py`` is covered by a test in the ``tests`` folder.
If you want to contribute a new function, please create a corresponding unittest.