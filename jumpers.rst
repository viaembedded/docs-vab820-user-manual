.. _jumpers:

Jumpers
=======

LVDS Power Select Jumper
The mainboard has a power select connector that determines the input
voltage for the LVDS connector (LVDS1) and LVDS inverter (INVERTER1). The
pins 1, 3, and 5 correspond to INVERTER1. The Pins 2, 4, and 6 correspond to
LVDS1. The jumper is labeled as "J3" .The jumper settings are shown below.

.. _figure-lvds-power:
.. figure:: images/lvds_power.*
   :align: center
   :alt: LVDS power select jumper diagram

   LVDS power select jumper diagram

LVDS power select jumper setting:

=============== ====== ====== ======
Inverter power  Pin 1  Pin 3  Pin 5
=============== ====== ====== ======
+12V (default)  On     On     Off
+5V             Off    On     On
=============== ====== ====== ======

================ ====== ====== ======
LVDS power       Pin 2  Pin 4  Pin 6
================ ====== ====== ======
+3.3V (default)  On     On     Off
+5V              Off    On     On
================ ====== ====== ======

Boot Select Jumper
^^^^^^^^^^^^^^^^^^

The Boots Select jumper labeled as "J11" is to specify the boot device.

.. _figure-boot-select:
.. figure:: images/boot_select.*
   :align: center
   :alt: Boot Select jumper diagram

   Boot Select jumper diagram

Boot Select jumper (J11) settings:

==================== ========= ========
Boot device          Pins 1-2  Pins2-3
==================== ========= ========
★Micro-SD (default)  short     open
SPI                  open      short
==================== ========= ========
