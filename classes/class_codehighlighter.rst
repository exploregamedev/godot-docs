:github_url: hide

.. Generated automatically by doc/tools/make_rst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the CodeHighlighter.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_CodeHighlighter:

CodeHighlighter
===============

**Inherits:** :ref:`SyntaxHighlighter<class_SyntaxHighlighter>` **<** :ref:`Resource<class_Resource>` **<** :ref:`RefCounted<class_RefCounted>` **<** :ref:`Object<class_Object>`

A syntax highlighter for code.

Description
-----------

A syntax highlighter for code.

Properties
----------

+-------------------------------------+------------------------------------------------------------------------------------+-----------------------+
| :ref:`Dictionary<class_Dictionary>` | :ref:`color_regions<class_CodeHighlighter_property_color_regions>`                 | ``{}``                |
+-------------------------------------+------------------------------------------------------------------------------------+-----------------------+
| :ref:`Color<class_Color>`           | :ref:`function_color<class_CodeHighlighter_property_function_color>`               | ``Color(0, 0, 0, 1)`` |
+-------------------------------------+------------------------------------------------------------------------------------+-----------------------+
| :ref:`Dictionary<class_Dictionary>` | :ref:`keyword_colors<class_CodeHighlighter_property_keyword_colors>`               | ``{}``                |
+-------------------------------------+------------------------------------------------------------------------------------+-----------------------+
| :ref:`Dictionary<class_Dictionary>` | :ref:`member_keyword_colors<class_CodeHighlighter_property_member_keyword_colors>` | ``{}``                |
+-------------------------------------+------------------------------------------------------------------------------------+-----------------------+
| :ref:`Color<class_Color>`           | :ref:`member_variable_color<class_CodeHighlighter_property_member_variable_color>` | ``Color(0, 0, 0, 1)`` |
+-------------------------------------+------------------------------------------------------------------------------------+-----------------------+
| :ref:`Color<class_Color>`           | :ref:`number_color<class_CodeHighlighter_property_number_color>`                   | ``Color(0, 0, 0, 1)`` |
+-------------------------------------+------------------------------------------------------------------------------------+-----------------------+
| :ref:`Color<class_Color>`           | :ref:`symbol_color<class_CodeHighlighter_property_symbol_color>`                   | ``Color(0, 0, 0, 1)`` |
+-------------------------------------+------------------------------------------------------------------------------------+-----------------------+

Methods
-------

+---------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                      | :ref:`add_color_region<class_CodeHighlighter_method_add_color_region>` **(** :ref:`String<class_String>` start_key, :ref:`String<class_String>` end_key, :ref:`Color<class_Color>` color, :ref:`bool<class_bool>` line_only=false **)** |
+---------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                      | :ref:`add_keyword_color<class_CodeHighlighter_method_add_keyword_color>` **(** :ref:`String<class_String>` keyword, :ref:`Color<class_Color>` color **)**                                                                               |
+---------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                      | :ref:`add_member_keyword_color<class_CodeHighlighter_method_add_member_keyword_color>` **(** :ref:`String<class_String>` member_keyword, :ref:`Color<class_Color>` color **)**                                                          |
+---------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                      | :ref:`clear_color_regions<class_CodeHighlighter_method_clear_color_regions>` **(** **)**                                                                                                                                                |
+---------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                      | :ref:`clear_keyword_colors<class_CodeHighlighter_method_clear_keyword_colors>` **(** **)**                                                                                                                                              |
+---------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                      | :ref:`clear_member_keyword_colors<class_CodeHighlighter_method_clear_member_keyword_colors>` **(** **)**                                                                                                                                |
+---------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Color<class_Color>` | :ref:`get_keyword_color<class_CodeHighlighter_method_get_keyword_color>` **(** :ref:`String<class_String>` keyword **)** |const|                                                                                                        |
+---------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Color<class_Color>` | :ref:`get_member_keyword_color<class_CodeHighlighter_method_get_member_keyword_color>` **(** :ref:`String<class_String>` member_keyword **)** |const|                                                                                   |
+---------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`   | :ref:`has_color_region<class_CodeHighlighter_method_has_color_region>` **(** :ref:`String<class_String>` start_key **)** |const|                                                                                                        |
+---------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`   | :ref:`has_keyword_color<class_CodeHighlighter_method_has_keyword_color>` **(** :ref:`String<class_String>` keyword **)** |const|                                                                                                        |
+---------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`   | :ref:`has_member_keyword_color<class_CodeHighlighter_method_has_member_keyword_color>` **(** :ref:`String<class_String>` member_keyword **)** |const|                                                                                   |
+---------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                      | :ref:`remove_color_region<class_CodeHighlighter_method_remove_color_region>` **(** :ref:`String<class_String>` start_key **)**                                                                                                          |
+---------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                      | :ref:`remove_keyword_color<class_CodeHighlighter_method_remove_keyword_color>` **(** :ref:`String<class_String>` keyword **)**                                                                                                          |
+---------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                      | :ref:`remove_member_keyword_color<class_CodeHighlighter_method_remove_member_keyword_color>` **(** :ref:`String<class_String>` member_keyword **)**                                                                                     |
+---------------------------+-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Property Descriptions
---------------------

.. _class_CodeHighlighter_property_color_regions:

- :ref:`Dictionary<class_Dictionary>` **color_regions**

+-----------+--------------------------+
| *Default* | ``{}``                   |
+-----------+--------------------------+
| *Setter*  | set_color_regions(value) |
+-----------+--------------------------+
| *Getter*  | get_color_regions()      |
+-----------+--------------------------+

Sets the color regions. All existing regions will be removed. The :ref:`Dictionary<class_Dictionary>` key is the region start and end key, separated by a space. The value is the region color.

----

.. _class_CodeHighlighter_property_function_color:

- :ref:`Color<class_Color>` **function_color**

+-----------+---------------------------+
| *Default* | ``Color(0, 0, 0, 1)``     |
+-----------+---------------------------+
| *Setter*  | set_function_color(value) |
+-----------+---------------------------+
| *Getter*  | get_function_color()      |
+-----------+---------------------------+

Sets color for functions. A function is a non-keyword string followed by a '('.

----

.. _class_CodeHighlighter_property_keyword_colors:

- :ref:`Dictionary<class_Dictionary>` **keyword_colors**

+-----------+---------------------------+
| *Default* | ``{}``                    |
+-----------+---------------------------+
| *Setter*  | set_keyword_colors(value) |
+-----------+---------------------------+
| *Getter*  | get_keyword_colors()      |
+-----------+---------------------------+

Sets the keyword colors. All existing keywords will be removed. The :ref:`Dictionary<class_Dictionary>` key is the keyword. The value is the keyword color.

----

.. _class_CodeHighlighter_property_member_keyword_colors:

- :ref:`Dictionary<class_Dictionary>` **member_keyword_colors**

+-----------+----------------------------------+
| *Default* | ``{}``                           |
+-----------+----------------------------------+
| *Setter*  | set_member_keyword_colors(value) |
+-----------+----------------------------------+
| *Getter*  | get_member_keyword_colors()      |
+-----------+----------------------------------+

Sets the member keyword colors. All existing member keyword will be removed. The :ref:`Dictionary<class_Dictionary>` key is the member keyword. The value is the member keyword color.

----

.. _class_CodeHighlighter_property_member_variable_color:

- :ref:`Color<class_Color>` **member_variable_color**

+-----------+----------------------------------+
| *Default* | ``Color(0, 0, 0, 1)``            |
+-----------+----------------------------------+
| *Setter*  | set_member_variable_color(value) |
+-----------+----------------------------------+
| *Getter*  | get_member_variable_color()      |
+-----------+----------------------------------+

Sets color for member variables. A member variable is non-keyword, non-function string proceeded with a '.'.

----

.. _class_CodeHighlighter_property_number_color:

- :ref:`Color<class_Color>` **number_color**

+-----------+-------------------------+
| *Default* | ``Color(0, 0, 0, 1)``   |
+-----------+-------------------------+
| *Setter*  | set_number_color(value) |
+-----------+-------------------------+
| *Getter*  | get_number_color()      |
+-----------+-------------------------+

Sets the color for numbers.

----

.. _class_CodeHighlighter_property_symbol_color:

- :ref:`Color<class_Color>` **symbol_color**

+-----------+-------------------------+
| *Default* | ``Color(0, 0, 0, 1)``   |
+-----------+-------------------------+
| *Setter*  | set_symbol_color(value) |
+-----------+-------------------------+
| *Getter*  | get_symbol_color()      |
+-----------+-------------------------+

Sets the color for symbols.

Method Descriptions
-------------------

.. _class_CodeHighlighter_method_add_color_region:

- void **add_color_region** **(** :ref:`String<class_String>` start_key, :ref:`String<class_String>` end_key, :ref:`Color<class_Color>` color, :ref:`bool<class_bool>` line_only=false **)**

Adds a color region such as comments or strings.

Both the start and end keys must be symbols. Only the start key has to be unique.

Line only denotes if the region should continue until the end of the line or carry over on to the next line. If the end key is blank this is automatically set to ``true``.

----

.. _class_CodeHighlighter_method_add_keyword_color:

- void **add_keyword_color** **(** :ref:`String<class_String>` keyword, :ref:`Color<class_Color>` color **)**

Sets the color for a keyword.

The keyword cannot contain any symbols except '\_'.

----

.. _class_CodeHighlighter_method_add_member_keyword_color:

- void **add_member_keyword_color** **(** :ref:`String<class_String>` member_keyword, :ref:`Color<class_Color>` color **)**

Sets the color for a member keyword.

The member keyword cannot contain any symbols except '\_'.

It will not be highlighted if preceded by a '.'.

----

.. _class_CodeHighlighter_method_clear_color_regions:

- void **clear_color_regions** **(** **)**

Removes all color regions.

----

.. _class_CodeHighlighter_method_clear_keyword_colors:

- void **clear_keyword_colors** **(** **)**

Removes all keywords.

----

.. _class_CodeHighlighter_method_clear_member_keyword_colors:

- void **clear_member_keyword_colors** **(** **)**

Removes all member keywords.

----

.. _class_CodeHighlighter_method_get_keyword_color:

- :ref:`Color<class_Color>` **get_keyword_color** **(** :ref:`String<class_String>` keyword **)** |const|

Returns the color for a keyword.

----

.. _class_CodeHighlighter_method_get_member_keyword_color:

- :ref:`Color<class_Color>` **get_member_keyword_color** **(** :ref:`String<class_String>` member_keyword **)** |const|

Returns the color for a member keyword.

----

.. _class_CodeHighlighter_method_has_color_region:

- :ref:`bool<class_bool>` **has_color_region** **(** :ref:`String<class_String>` start_key **)** |const|

Return ``true`` if the start key exists, else ``false``.

----

.. _class_CodeHighlighter_method_has_keyword_color:

- :ref:`bool<class_bool>` **has_keyword_color** **(** :ref:`String<class_String>` keyword **)** |const|

Return ``true`` if the keyword exists, else ``false``.

----

.. _class_CodeHighlighter_method_has_member_keyword_color:

- :ref:`bool<class_bool>` **has_member_keyword_color** **(** :ref:`String<class_String>` member_keyword **)** |const|

Return ``true`` if the member keyword exists, else ``false``.

----

.. _class_CodeHighlighter_method_remove_color_region:

- void **remove_color_region** **(** :ref:`String<class_String>` start_key **)**

Removes the color region that uses that start key.

----

.. _class_CodeHighlighter_method_remove_keyword_color:

- void **remove_keyword_color** **(** :ref:`String<class_String>` keyword **)**

Removes the keyword.

----

.. _class_CodeHighlighter_method_remove_member_keyword_color:

- void **remove_member_keyword_color** **(** :ref:`String<class_String>` member_keyword **)**

Removes the member keyword.

.. |virtual| replace:: :abbr:`virtual (This method should typically be overridden by the user to have any effect.)`
.. |const| replace:: :abbr:`const (This method has no side effects. It doesn't modify any of the instance's member variables.)`
.. |vararg| replace:: :abbr:`vararg (This method accepts any number of arguments after the ones described here.)`
.. |constructor| replace:: :abbr:`constructor (This method is used to construct a type.)`
.. |static| replace:: :abbr:`static (This method doesn't need an instance to be called, so it can be called directly using the class name.)`
.. |operator| replace:: :abbr:`operator (This method describes a valid operator to use with this type as left-hand operand.)`
