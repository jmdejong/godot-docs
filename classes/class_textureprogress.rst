.. _class_TextureProgress:

TextureProgress
===============

**Inherits:** :ref:`Range<class_range>` **<** :ref:`Control<class_control>` **<** :ref:`CanvasItem<class_canvasitem>` **<** :ref:`Node<class_node>` **<** :ref:`Object<class_object>`

**Category:** Core

Brief Description
-----------------

Textured progress bar implementation.

Member Functions
----------------

+--------------------------------+----------------------------------------------------------------------------------------------------------------------------------+
| void                           | :ref:`set_under_texture<class_TextureProgress_set_under_texture>`  **(** :ref:`Object<class_object>` tex  **)**                  |
+--------------------------------+----------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Object<class_object>`    | :ref:`get_under_texture<class_TextureProgress_get_under_texture>`  **(** **)** const                                             |
+--------------------------------+----------------------------------------------------------------------------------------------------------------------------------+
| void                           | :ref:`set_progress_texture<class_TextureProgress_set_progress_texture>`  **(** :ref:`Object<class_object>` tex  **)**            |
+--------------------------------+----------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Object<class_object>`    | :ref:`get_progress_texture<class_TextureProgress_get_progress_texture>`  **(** **)** const                                       |
+--------------------------------+----------------------------------------------------------------------------------------------------------------------------------+
| void                           | :ref:`set_over_texture<class_TextureProgress_set_over_texture>`  **(** :ref:`Object<class_object>` tex  **)**                    |
+--------------------------------+----------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Object<class_object>`    | :ref:`get_over_texture<class_TextureProgress_get_over_texture>`  **(** **)** const                                               |
+--------------------------------+----------------------------------------------------------------------------------------------------------------------------------+
| void                           | :ref:`set_fill_mode<class_TextureProgress_set_fill_mode>`  **(** :ref:`int<class_int>` mode  **)**                               |
+--------------------------------+----------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`          | :ref:`get_fill_mode<class_TextureProgress_get_fill_mode>`  **(** **)**                                                           |
+--------------------------------+----------------------------------------------------------------------------------------------------------------------------------+
| void                           | :ref:`set_radial_initial_angle<class_TextureProgress_set_radial_initial_angle>`  **(** :ref:`float<class_float>` mode  **)**     |
+--------------------------------+----------------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`      | :ref:`get_radial_initial_angle<class_TextureProgress_get_radial_initial_angle>`  **(** **)**                                     |
+--------------------------------+----------------------------------------------------------------------------------------------------------------------------------+
| void                           | :ref:`set_radial_center_offset<class_TextureProgress_set_radial_center_offset>`  **(** :ref:`Vector2<class_vector2>` mode  **)** |
+--------------------------------+----------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Vector2<class_vector2>`  | :ref:`get_radial_center_offset<class_TextureProgress_get_radial_center_offset>`  **(** **)**                                     |
+--------------------------------+----------------------------------------------------------------------------------------------------------------------------------+
| void                           | :ref:`set_fill_degrees<class_TextureProgress_set_fill_degrees>`  **(** :ref:`float<class_float>` mode  **)**                     |
+--------------------------------+----------------------------------------------------------------------------------------------------------------------------------+
| :ref:`float<class_float>`      | :ref:`get_fill_degrees<class_TextureProgress_get_fill_degrees>`  **(** **)**                                                     |
+--------------------------------+----------------------------------------------------------------------------------------------------------------------------------+

Numeric Constants
-----------------

- **FILL_LEFT_TO_RIGHT** = **0**
- **FILL_RIGHT_TO_LEFT** = **1**
- **FILL_TOP_TO_BOTTOM** = **2**
- **FILL_BOTTOM_TO_TOP** = **3**
- **FILL_CLOCKWISE** = **4**
- **FILL_COUNTER_CLOCKWISE** = **5**

Description
-----------

:ref:`ProgressBar<class_progressbar>` implementation that is easier to theme (by just passing a few textures).

Member Function Description
---------------------------

.. _class_TextureProgress_set_under_texture:

- void  **set_under_texture**  **(** :ref:`Object<class_object>` tex  **)**

.. _class_TextureProgress_get_under_texture:

- :ref:`Object<class_object>`  **get_under_texture**  **(** **)** const

.. _class_TextureProgress_set_progress_texture:

- void  **set_progress_texture**  **(** :ref:`Object<class_object>` tex  **)**

.. _class_TextureProgress_get_progress_texture:

- :ref:`Object<class_object>`  **get_progress_texture**  **(** **)** const

.. _class_TextureProgress_set_over_texture:

- void  **set_over_texture**  **(** :ref:`Object<class_object>` tex  **)**

.. _class_TextureProgress_get_over_texture:

- :ref:`Object<class_object>`  **get_over_texture**  **(** **)** const

.. _class_TextureProgress_set_fill_mode:

- void  **set_fill_mode**  **(** :ref:`int<class_int>` mode  **)**

.. _class_TextureProgress_get_fill_mode:

- :ref:`int<class_int>`  **get_fill_mode**  **(** **)**

.. _class_TextureProgress_set_radial_initial_angle:

- void  **set_radial_initial_angle**  **(** :ref:`float<class_float>` mode  **)**

.. _class_TextureProgress_get_radial_initial_angle:

- :ref:`float<class_float>`  **get_radial_initial_angle**  **(** **)**

.. _class_TextureProgress_set_radial_center_offset:

- void  **set_radial_center_offset**  **(** :ref:`Vector2<class_vector2>` mode  **)**

.. _class_TextureProgress_get_radial_center_offset:

- :ref:`Vector2<class_vector2>`  **get_radial_center_offset**  **(** **)**

.. _class_TextureProgress_set_fill_degrees:

- void  **set_fill_degrees**  **(** :ref:`float<class_float>` mode  **)**

.. _class_TextureProgress_get_fill_degrees:

- :ref:`float<class_float>`  **get_fill_degrees**  **(** **)**

