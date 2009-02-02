
====================
Fudge For JavaScript
====================

Although `Ersatz <http://github.com/centro/ersatz/tree/master>`_ is a port of `Mocha <http://mocha.rubyforge.org/>`_ to JavaScript and that's pretty much what :ref:`Fudge <fudge-examples>` is, I couldn't get Ersatz to work with one of my libraries because it uses Prototype.  So I started porting Fudge to JavaScript.  As of this writing it has only been partially implemented.

Install
=======

Download the :ref:`Fudge source distribution <fudge-source>` and copy ``javascript/fudge/`` to your webroot.  To use it in your tests all you need is a script tag like this:

.. code-block:: html
    
    <script src="fudge/fudge.js" type="text/javascript"></script>

If you want to run Fudge's own tests, then cd into the ``javascript/`` directory, start a simple webserver::

    $ python fudge/testserver.py

and open http://localhost:8000/tests/test_fudge.html  Take note that while Fudge's *tests* require jQuery, Fudge itself does not require jQuery.

Usage
=====

Refer to the :ref:`fudge-examples` in Python to get an idea for how to use the JavaScript version.  As mentioned before, the JavaScript port is not yet fully implemented.