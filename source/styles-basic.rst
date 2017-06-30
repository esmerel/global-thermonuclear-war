Basic text styles
*****************************************************


############################################################
This is a subheading.
############################################################

Links
=========
* single ``*asterisks*`` should get you *italics*
* double ``**asterisks**`` should get you **bolding**
* `python <www.python.org>`_ is a standard link
* but if you encase that same code in two backticks on each side, like this: ```python <www.python.org>`_`` you should get a literal

Lists
=========

* Asterisks for
* unordered lists

# Pound / hash signs for
# ordered lists


Directive boxes
======================

.. seealso:: This is a moderately simple **seealso** note.

.. note::  This is a **note** box.

.. tip::  Don't eat yellow snow.

.. warning:: note the space between the directive and the text

.. todo:: We also need to talk about anchors in the text.

About sections
======================

# If under and overline are used, their length must be identical.
# The length of the underline must be at least as long as the title itself

This is a sub-section
------------------------

This is a sub-sub-section
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

When writing up sections, there are some conventions.

* # with overline, for parts
* * with overline, for chapters
* =, for sections
* -, for subsections
* ^, for subsubsections
* ", for paragraphs

.. todo:: We need to discuss whether titles should have over- and under-lines. There are advantages and disadvantages.


Code-related
======================

.. code-block:: php
    :linenos:

    <?php echo 'hello world!'; ?>
