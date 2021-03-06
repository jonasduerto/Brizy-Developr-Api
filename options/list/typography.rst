Typography
==========

Typography option type.

Config
------

+------------+-------------+-------------+------------------------------------------------------------------------------+
| **Name**   |  **Type**   | **Default** | **Description**                                                              |
+============+=============+=============+==============================================================================+
| fontFamily | ``boolean`` | ``true``    | Enable or disable font family select.                                        |
|            |             |             ||                                                                             |
|            |             |             || Usually this is used for hiding font family select on mobile devices.       |
+------------+-------------+-------------+------------------------------------------------------------------------------+

Value
-----

+---------------+-------------+-------------+---------------------------------------------------------------------------+
| **Name**      |  **Type**   | **Default** | **Description**                                                           |
+===============+=============+=============+===========================================================================+
| fontFamily    | ``string``  | ``"lato"``  | Provide font family name.                                                 |
+---------------+-------------+-------------+---------------------------------------------------------------------------+
| fontSize      | ``number``  | ``17``      | Default font size.                                                        |
+---------------+-------------+-------------+---------------------------------------------------------------------------+
| fontWeight    | ``number``  | ``400``     | Default font weight.                                                      |
|               |             |             ||                                                                          |
|               |             |             || Allowed values:                                                          |
|               |             |             || - ``100``                                                                |
|               |             |             || - ``200``                                                                |
|               |             |             || - ``300``                                                                |
|               |             |             || - ``400``                                                                |
|               |             |             || - ``500``                                                                |
|               |             |             || - ``600``                                                                |
|               |             |             || - ``700``                                                                |
|               |             |             || - ``800``                                                                |
|               |             |             || - ``900``                                                                |
+---------------+-------------+-------------+---------------------------------------------------------------------------+
| lineHeight    | ``number``  | ``1.0``     | Default line height.                                                      |
+---------------+-------------+-------------+---------------------------------------------------------------------------+
| letterSpacing | ``number``  | ``0.0``     | Default letter spacing.                                                   |
+---------------+-------------+-------------+---------------------------------------------------------------------------+


Minimal Usage
-------------

.. code-block:: javascript

    {
      id: "typography",
      type: "typography-dev"
    }

Usage
-----

.. code-block:: javascript

    {
      id: "typography",
      type: "typography-dev"
      config: {
        fontFamily: false,
      },
      value: {
        fontFamily: "lato",
        fontSize: "11",
        fontWeight: "700",
        lineHeight: "1.2",
        letterSpacing: "1.5",
      }
    }
