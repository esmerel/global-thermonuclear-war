Advanced text styles
*****************************************************

Text substitutions
=====================
> If you want to use some substitutions for all documents, put them into ``rst_prolog`` or put them into a separate file and include it into all documents you want to use them in, using the include directive. (Be sure to give the include file a file name extension differing from that of other source files, to avoid Sphinx finding it as a standalone document.)

See http://docutils.sourceforge.net/docs/ref/rst/restructuredtext.html#substitution-definitions

.. todo:: Set up a separate file as an include

Images
======================

.. image:: images/cats.jpg

Figures
=============

Figures are images with captions

.. figure:: images/cats.jpg
  :scale: 50 %

  Beryl and Kolohe.

.. todo:: Should image paths begin with a slash or without one? We should figure that out.

Topics
======================
.. topic:: Your Topic Title

    Subsequent indented lines comprise
    the body of the topic, and are
    interpreted as body elements.

Tables
======================
.. csv-table:: a title
   :header: "name", "firstname", "age"
   :widths: 20, 20, 10

   "Smith", "John", 40
   "Smith", "John, Junior", 20


.. todo:: Glossaries?

.. todo:: Nested lists that contain ordered and unordered items

Definition lists
======================

item
  definition here

second item
  definition here


OMG SORCERY
===============

-a            command-line option "a"
-b file       options can have arguments
              and long descriptions
--long        options can be long also
--input=file  long options can also have
              arguments
/V            DOS/VMS-style options too


Blockquoting
===============
A paragraph containing only two colons indicates
the following indented or quoted text is a literal
block or quoted text is a literal block.

::

  Whitespace, newlines, blank lines, and  all kinds of
  markup (like *this* or \this) is preserved here.

Per-line quoting can also be used for unindented
blocks:

> Useful for quotes from email and
