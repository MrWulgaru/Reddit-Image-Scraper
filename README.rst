====================
Reddit-Image-Scraper
====================

Setup
-----

Python
~~~~~~
`Python 2`_ or `Python 3`_ must be installed on your computer.

Dependencies
~~~~~~~~~~~~
To use this script, you will need the libraries `praw`_ and `beautifulsoup`_.
They can be installed by the ``pip`` command through your command line as follows:

.. code-block:: bash

    $ pip install -r requirements.txt

After that, you're good to go!

Installation
~~~~~~~~~~~~

To install simply clone the github repo and run setup.py

.. code-block:: bash

   # Clone the Repo
   $ git clone https://github.com/Rookev/Reddit-Image-Scraper.git

   # Install
   $ python setup.py install

Usage
------
After installing the package, the console script ``reddit_scrapper``
can now be used.

Example
~~~~~~~

Choose a reddit user and download each of his or her Imgur submissions to your local hard drive

.. code-block:: bash

    reddit_scrapper User123 5


This command scrapes the last 5 posts of ``/u/User123``, detects his Imgur submissions and downloads it to your desktop in a newly created folder called `/User123/`

Documentation
-------------

Documentation available at readthedocs

http://reddit-image-scrapper.readthedocs.org/

.. _`Python 2`: https://www.python.org/download/releases/2.7/
.. _`Python 3`: https://www.python.org/download/releases/3.4.1/
.. _`praw`: https://github.com/praw-dev/praw
.. _`beautifulsoup`: http://www.crummy.com/software/BeautifulSoup/