============
Playground
============

.. literalinclude:: ../test.py
   :language: python
   :lines: 1,3
   :linenos:

.. literalinclude:: conf.py
   :language: python
   :lines: 1,3,5-10
   :linenos:

Hier steht nicht viel [#]_.  Schauen sie einfach mal ans Ende der Seite.
Hier steht nicht viel [#]_.  Schauen sie einfach mal ans Ende der Seite.

Dieser Satz dient zur Demonstration_ von `Hyperlinks in reST`_.

.. code-block:: python
   :caption: this.py
   :name: this-py

   print 'Explicit is better than implicit.'


Fröhlich schreiben

.. code-block:: bash
   :linenos:

   $ echo "hello world" && exit 0
   $ echo "hello world" && exit 0


.. code-block:: python
   :emphasize-lines: 3,5

   def some_function():
       interesting = False
       print 'This line is highlighted.'
       print 'This one is not...'
       print '...but this one is.'


.. [#] Fußnoten können automatisch durchnummeriert werden. Mehr dazu in der reST Kurzreferenz
.. [#] Fußnoten können automatisch durchnummeriert werden. Mehr dazu in der reST Kurzreferenz


.. _Demonstration: http://de.wikipedia.org/wiki/Demonstration
.. _Hyperlinks in reST: http://docutils.sourceforge.net/docs/user/rst/quickref.html#hyperlink-targets
