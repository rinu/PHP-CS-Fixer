================================
Rule ``no_leading_import_slash``
================================

Remove leading slashes in ``use`` clauses.

Examples
--------

Example #1
~~~~~~~~~~

.. code-block:: diff

   --- Original
   +++ New
    <?php
    namespace Foo;
   -use \Bar;
   +use Bar;

Rule sets
---------

The rule is part of the following rule sets:

@PER
  Using the `@PER <./../../ruleSets/PER.rst>`_ rule set will enable the ``no_leading_import_slash`` rule.

@PER-CS1.0
  Using the `@PER-CS1.0 <./../../ruleSets/PER-CS1.0.rst>`_ rule set will enable the ``no_leading_import_slash`` rule.

@PSR12
  Using the `@PSR12 <./../../ruleSets/PSR12.rst>`_ rule set will enable the ``no_leading_import_slash`` rule.

@PhpCsFixer
  Using the `@PhpCsFixer <./../../ruleSets/PhpCsFixer.rst>`_ rule set will enable the ``no_leading_import_slash`` rule.

@Symfony
  Using the `@Symfony <./../../ruleSets/Symfony.rst>`_ rule set will enable the ``no_leading_import_slash`` rule.
