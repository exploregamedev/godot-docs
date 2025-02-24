:github_url: hide

.. Generated automatically by doc/tools/make_rst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the SeparationRayShape2D.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_SeparationRayShape2D:

SeparationRayShape2D
====================

**Inherits:** :ref:`Shape2D<class_Shape2D>` **<** :ref:`Resource<class_Resource>` **<** :ref:`RefCounted<class_RefCounted>` **<** :ref:`Object<class_Object>`

Separation ray shape for 2D collisions.

Description
-----------

Separation ray shape for 2D collisions. A ray is not really a collision body; instead, it tries to separate itself from whatever is touching its far endpoint. It's often useful for characters.

Properties
----------

+---------------------------+---------------------------------------------------------------------------+-----------+
| :ref:`float<class_float>` | :ref:`length<class_SeparationRayShape2D_property_length>`                 | ``20.0``  |
+---------------------------+---------------------------------------------------------------------------+-----------+
| :ref:`bool<class_bool>`   | :ref:`slide_on_slope<class_SeparationRayShape2D_property_slide_on_slope>` | ``false`` |
+---------------------------+---------------------------------------------------------------------------+-----------+

Property Descriptions
---------------------

.. _class_SeparationRayShape2D_property_length:

- :ref:`float<class_float>` **length**

+-----------+-------------------+
| *Default* | ``20.0``          |
+-----------+-------------------+
| *Setter*  | set_length(value) |
+-----------+-------------------+
| *Getter*  | get_length()      |
+-----------+-------------------+

The ray's length.

----

.. _class_SeparationRayShape2D_property_slide_on_slope:

- :ref:`bool<class_bool>` **slide_on_slope**

+-----------+---------------------------+
| *Default* | ``false``                 |
+-----------+---------------------------+
| *Setter*  | set_slide_on_slope(value) |
+-----------+---------------------------+
| *Getter*  | get_slide_on_slope()      |
+-----------+---------------------------+

If ``false`` (default), the shape always separates and returns a normal along its own direction.

If ``true``, the shape can return the correct normal and separate in any direction, allowing sliding motion on slopes.

.. |virtual| replace:: :abbr:`virtual (This method should typically be overridden by the user to have any effect.)`
.. |const| replace:: :abbr:`const (This method has no side effects. It doesn't modify any of the instance's member variables.)`
.. |vararg| replace:: :abbr:`vararg (This method accepts any number of arguments after the ones described here.)`
.. |constructor| replace:: :abbr:`constructor (This method is used to construct a type.)`
.. |static| replace:: :abbr:`static (This method doesn't need an instance to be called, so it can be called directly using the class name.)`
.. |operator| replace:: :abbr:`operator (This method describes a valid operator to use with this type as left-hand operand.)`
