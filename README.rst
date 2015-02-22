octomanager
===========

.. image:: https://travis-ci.org/arachnegl/nose-my-code.png?branch=master
  :target: https://travis-ci.org/arachnegl/nose-my-code


A pull request manager for GitHub
produces a colour coded nose stack trace

Do you like running, testing and debugging your code in the command line using nose?  

Have you ever been the unfortunate reader of a long stack trace?

Ever wished the trace output could be a bit more helpful? 

We are attempting to build a plug-in for nosetests that will print a colour coded stack trace that will show whether errors are emanating from your code, or from imported/standard library code.

Python packages used:
nosetests

Tested on Python 2.7, and 3.4 on Linux & OSX. Probably works on other versions
of python. Probably doesn't work on Windows.

Built at the Building Better Tools with Python day, Google Campus London, 7th Feb 2015.


To see it in action you can run the test:

    python test.py --with-mycode
