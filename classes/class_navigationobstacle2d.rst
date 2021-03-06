:github_url: hide

.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the NavigationObstacle2D.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_NavigationObstacle2D:

NavigationObstacle2D
====================

**Inherits:** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

2D Obstacle used in navigation for collision avoidance.

Description
-----------

2D Obstacle used in navigation for collision avoidance. The obstacle needs navigation data to work correctly. This can be done by having the obstacle as a child of a :ref:`Navigation2D<class_Navigation2D>` node, or using :ref:`set_navigation<class_NavigationObstacle2D_method_set_navigation>`. :ref:`NavigationObstacle<class_NavigationObstacle>` is physics safe.

Methods
-------

+-------------------------+------------------------------------------------------------------------------------------------------------------------+
| :ref:`Node<class_Node>` | :ref:`get_navigation<class_NavigationObstacle2D_method_get_navigation>` **(** **)** const                              |
+-------------------------+------------------------------------------------------------------------------------------------------------------------+
| void                    | :ref:`set_navigation<class_NavigationObstacle2D_method_set_navigation>` **(** :ref:`Node<class_Node>` navigation **)** |
+-------------------------+------------------------------------------------------------------------------------------------------------------------+

Method Descriptions
-------------------

.. _class_NavigationObstacle2D_method_get_navigation:

- :ref:`Node<class_Node>` **get_navigation** **(** **)** const

Returns the :ref:`Navigation2D<class_Navigation2D>` node that the obstacle is using for its navigation system.

----

.. _class_NavigationObstacle2D_method_set_navigation:

- void **set_navigation** **(** :ref:`Node<class_Node>` navigation **)**

Sets the :ref:`Navigation2D<class_Navigation2D>` node used by the obstacle. Useful when you don't want to make the obstacle a child of a :ref:`Navigation2D<class_Navigation2D>` node.

