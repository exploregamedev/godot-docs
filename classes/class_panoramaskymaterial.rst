:github_url: hide

.. Generated automatically by doc/tools/make_rst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the PanoramaSkyMaterial.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_PanoramaSkyMaterial:

PanoramaSkyMaterial
===================

**Inherits:** :ref:`Material<class_Material>` **<** :ref:`Resource<class_Resource>` **<** :ref:`RefCounted<class_RefCounted>` **<** :ref:`Object<class_Object>`

A :ref:`Material<class_Material>` used with :ref:`Sky<class_Sky>` to draw a background texture.

Description
-----------

A resource referenced in a :ref:`Sky<class_Sky>` that is used to draw a background. The Panorama sky material functions similar to skyboxes in other engines, except it uses an equirectangular sky map instead of a cube map.

Using an HDR panorama is strongly recommended for accurate, high-quality reflections. Godot supports the Radiance HDR (``.hdr``) and OpenEXR (``.exr``) image formats for this purpose.

You can use `this tool <https://danilw.github.io/GLSL-howto/cubemap_to_panorama_js/cubemap_to_panorama.html>`__ to convert a cube map to an equirectangular sky map.

Properties
----------

+-----------------------------------+--------------------------------------------------------------+
| :ref:`Texture2D<class_Texture2D>` | :ref:`panorama<class_PanoramaSkyMaterial_property_panorama>` |
+-----------------------------------+--------------------------------------------------------------+

Property Descriptions
---------------------

.. _class_PanoramaSkyMaterial_property_panorama:

- :ref:`Texture2D<class_Texture2D>` **panorama**

+----------+---------------------+
| *Setter* | set_panorama(value) |
+----------+---------------------+
| *Getter* | get_panorama()      |
+----------+---------------------+

:ref:`Texture2D<class_Texture2D>` to be applied to the ``PanoramaSkyMaterial``.

.. |virtual| replace:: :abbr:`virtual (This method should typically be overridden by the user to have any effect.)`
.. |const| replace:: :abbr:`const (This method has no side effects. It doesn't modify any of the instance's member variables.)`
.. |vararg| replace:: :abbr:`vararg (This method accepts any number of arguments after the ones described here.)`
.. |constructor| replace:: :abbr:`constructor (This method is used to construct a type.)`
.. |static| replace:: :abbr:`static (This method doesn't need an instance to be called, so it can be called directly using the class name.)`
.. |operator| replace:: :abbr:`operator (This method describes a valid operator to use with this type as left-hand operand.)`
