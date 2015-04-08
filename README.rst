Simple Data Object Model (SDOM) for C++
=======================================

Many higher abstraction languages directly provide data structures
that allow mapping { YAML, JSON, XML, ... } into a "simple data object
model".  This library attempts to provide such a class library for
C++.  

Class Hierarchy
---------------

(an initial swag at the class hierarchy)::

   Node
    |-- "ValueNode" -- need a better name??
    |     |-- String
    |     |-- Number / Integer -- research number hierarchy
    |     |-- RealNumber
    |     |-- Boolean ??
    |
    |-- CompositeNode
         |-- Dictionary
         |-- List

.. Local Variables:
.. mode: rst
.. End:
