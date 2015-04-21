Nose My Code
============

...it knows your code!

|Build Status| |Pypi Status|

Nose my code colours your code in a stack trace

* Do you like running, testing and debugging your code in the command line using nose?  
* Have you ever been the unfortunate reader of a long stack trace?
* Ever wished the trace output could be a bit more helpful? 

Tested on Python 2.7, and 3.4 runnin on Linux & OSX. Probably works on other versions
of python. Probably doesn't work on Windows.

Built at the Building Better Tools with Python day, Google Campus London, 7th Feb 2015.

To see it in action you can run the tests:

    python test.py --with-mycode

To install:

    pip install nose-mycode

To use:

    nosetests --with-mycode


.. |Build Status| image:: https://travis-ci.org/nose-my-code/nose-my-code.svg?branch=master
    :target: https://travis-ci.org/nose-my-code/nose-my-code

.. |Pypi Status| image:: https://pypip.in/v/restnavigator/badge.png
    :target: https://pypi.python.org/pypi/nose-mycode/
