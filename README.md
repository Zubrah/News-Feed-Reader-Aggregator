# python feedparser

Building an RSS feed reader in python



# Installation
feedparser can be installed by running pip:

$ pip install feedparser


# Documentation
The feedparser documentation is available on the web at:

https://pythonhosted.org/feedparser/
It is also included in its source format, ReST, in the docs/ directory. To build the documentation you'll need the Sphinx package, which is available at:

https://www.sphinx-doc.org/
You can then build HTML pages using a command similar to:

$ sphinx-build -b html docs/ fpdocs
This will produce HTML documentation in the fpdocs/ directory.

# Testing
Feedparser has an extensive test suite, powered by tox. To run it, type this:

$ python -m venv venv
$ source venv/bin/activate  # or "venv\bin\activate.bat" on Windows
(venv) $ pip install tox
(venv) $ tox
This will spawn an HTTP server that will listen on port 8097. The tests will fail if that port is in use.
