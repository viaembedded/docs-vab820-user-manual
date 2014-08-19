.. _overview:

Product Overview
================

Based on the ultra compact Pico-ITX form factor, measuring 10 cm x 7.2 cm,
the VIA VAB-820 is a VIA Pico-ITX board to feature an ARM SoC. With a
1.0GHz Freescale Cortex-A9 ARM SoC, the VIA VAB-820 combines three
independent, integrated GPUs for 3D/2D graphics acceleration and supports
multiple displays.

The ultra compact VIA VAB-820 Pico-ITX is optimized for both performance
and power to meet the high end demands of advanced industrial and invehicle
applications, boasting a ruggedized design with an extended operating
temperature range from -20 to 70°C, while offering extremely low power
consumption.

The VIA VAB-820 provides an impressive selection of rear I/O in a compact
form factor including HDMI® port, two USB 2.0 ports, one composite input
RCA jack and one RJ-45 GLAN port. Customers can take advantage of VIA’s
industry leading hardware and software support to create customized designs
with a quick time to market. The VIA VAB-820 is also available with board
support packages (BSP) for the Linux Kernel 3.0.35 operating system.

On board pin headers provide support for an additional of two COM
connectors with power supply, one dual-channel LVDS connector, one RTC
battery connector, one micro SD card slot, one Mini-PCIe connector, one MIPI
CSI-2 connector and eight GPIO pin headers, etc.

Key Features
------------

* Supports independent, integrated graphics processing (GPU) for 3D/2D
  and graphics acceleration and multiple displays
* Supports HDMI® port, RJ-45 LAN port and composite input RCA jack
* Supports four USB 2.0 ports (two as pin header)
* Supports one dual-channel 18/24-bit LVDS connector
* Supports two COM connectors with power supply
* Supports two Controller Area Network (FlexCAN)
* Small form factor and low power design
* Fanless and ultra low power consumption
* 4GB onboard eMMC Flash memory
* Support Mini-PCIe x1 connector and Micro SD card slot for expandable storage
* Compatible with Linux Kernel 3.0.35

**VAB-820-P SKU (VAB-820+PWB-P255-L)**:

* Integrated Powered Device (PD) controller and switching regulator
  intended for high power IEEE 802.3at and 802.3af applications
* 25W output power from power over Ethernet (PoE) PD board
* Operates from either PoE or external adaptors (12V)

Product Specifications
----------------------

VAB-820 SKU
^^^^^^^^^^^

* Processor

  * Freescale i.MX 6Dual/6Quad ARM Cortex-A9 @ 1.0 GHz

* Flash Storage

  * 4MB SPI Serial Flash
  * 4GB eMMC Flash

* Graphics

  *  Support three independent, integrated graphics processing units: an OpenGL® ES 2.0
     3D graphics accelerator with four shaders (up to 200 MT/s and OpenCL support), 2D
     graphics accelerator, and dedicated OpenVG™ 1.1 accelerator

* System Memory

  * Onboard 1GB DDR3-1066 SDRAM using 128M x16 memory devices (up to 2GB with
    256M x 16 devices)

* Ethernet

  * Micrel KSZ9031RNXIA Gigabit Ethernet Transceiver with RGMII Support

* Audio

  * Freescale SGTL5000 Low Power Stereo Codec

* Video Decoder

  * ADI ADV7180 8-Bit, 4× Oversampling SDTV Video Decoder

* HDMI

  * Integrated HDMI 1.4 Transmitter

* USB

  * SMSC USB2514 USB 2.0 High Speed 4-Port Hub Controllers

* Onboard I/O

  * 2 X COM connectors with power supply (one supports 8-wire, while the other
    supports 2-wire, CAN1 and CAN2)
  * 1 X Dual-channel, 18/24-bit LVDS connector
  * 1 X RTC battery connector
  * 1 X MIPI CSI-2 connector (supports 2 data lanes)
  * 1 x LVDS panel connector
  * 1 x LVDS Inverter connector
  * 1 x LVDS panel power select jumper
  * 1 X SPI connector
  * 1 X S-Video input pin header
  * 2 X PoE pin headers (support optional VAB-820-P SKU)
  * 1 X Front audio pin header for line-in, line-out and MIC-in
  * 1 X Boot select jumper (for SPI or micro SD)
  * 1 X USB and USB OTG pin header
  * 1 X 1 x DIO, I²C, System reset, Power LED, and WLAN LED pin header
  * 1 X 12V DC-in power connector
  * 1 X Mini-PCIe slot (supports multiple connections and buses including JTAG)

* Front Panel I/O

  * 1 X Micro SD card slot

* Back Panel I/O

  * 1 X HDMI port
  * 2 X USB 2.0 ports
  * 1 X RJ-45 LAN port (supports optional IEEE802.3at Type 2)
  * 1 X Composite input RCA jack

* WatchDog Timer

  * The Watchdog Timer supports two comparison points during each counting period.
    Each of the comparison points is configurable to evoke an interrupt to the ARM core,
    and a second point evokes an external event on the WDOG line

* Power

  * 12VDC

* Operating System

  *  Linux Kernel 3.0.35

* Operating Conditions

  * Operating Temperature: -20°C ~ 70°C
  * Operating Humidity: 0% ~ 95% (relative humidity; non-condensing)
  * Storage Temperature: -40°C ~ 70°C

  .. note:: As the operating temperature provided in the specifications is a result of the test performed in VIA’s
	    chamber, a number of variables can influence this result. Please note that the working temperature may
	    vary depending on the actual situation and environment. It is highly suggested to execute a solid
	    testing and take all the variables into consideration when building the system. Please ensure that the
	    system runs well under the operating temperature in terms of application.

* Form Factor

  * 8-layer PCB
  * 10 cm x 7.2 cm

  .. note:: 1. For the software evaluation, please visit VIA Embedded website to download the image:
	       http://www.viaembedded.com/en/downloads/EvaluationKit.jsp
	    2. After the VAB-820 is shut down, it remains in stand by mode so that some components may retain
	       power. If user has concern about power consumption during shut down, it is recommended to directly
	       unplug the AC adapter from the board.

PWB-P255-L
^^^^^^^^^^

* Integrated Powered Device (PD) controller and switching regulator intended for high
  power IEEE 802.3at and 802.3af applications
* 25W output power from power over Ethernet (PoE)
* Operates from either PoE or external adaptors
* 12V output voltage
  * Operating Conditions

    * Operating Temperature: -20°C up to 70°C
    * Operating Humidity: 0% ~ 95% (relative humidity; non-condensing)

  * Form Factor

    * 4-layer PCB
    * 10 cm x 5.2 cm

Layout diagram
--------------

.. _figure-layout-top:
.. figure:: images/layout_top.*
   :align: center
   :alt: Layout diagram of the VAB-820 mainboard, top view

   Layout diagram of the VAB-820 mainboard, top view

.. _figure-layout-bottom:
.. figure:: images/layout_bottom.*
   :align: center
   :alt: Layout diagram of the VAB-820 mainboard, bottom view

   Layout diagram of the VAB-820 mainboard, top view

Layout diagram description table of the VAB-820 mainboard:

==== ==============================================================================
Item Description
==== ==============================================================================
1    +12V DC-In connector (J9)
2    S-VIDEO input pin header (S-VIDEO1)
3    LVDS power select jumper (J3)
4    Freescale i.MX 6Dual/6Quad ARM Cortex-A9 processor
5    eMMC Flash
6    PoE Input pin header (J13)
7    DIO, I²C, System reset, Power LED, and WLAN LED combination pin header (J7)
8    Micro SD card slot
9    Boot flash Select jumper (J11)
10   USB and USBOTG combination pin header (J8)
11   Front Audio pin header (AUDIO1)
12   SPI connector (J10)
13   DDR3 1066 SDRAM memory
14   PoE Output pin header (J14)
15   LVDS panel connector (LVDS1)
16   LVDS Inverter connector (INVERTER)
17   COM2/CAN connector (J5)
18   DDR3 1066 SDRAM memory
19   Mini-PCIe slot (MINIPCIE)
20   COM1 connector (J4)
21   MIPI CSI-2 connector (J18)
22   CMOS Battery connector (J1)
==== ==============================================================================

Product Dimensions
------------------

.. _figure-dimensions-top:
.. figure:: images/dimensions_top.*
   :align: center
   :alt: Mounting holes and dimensions of the VAB-820, top view

   Mounting holes and dimensions of the VAB-820, top view

.. _figure-dimensions-side:
.. figure:: images/dimensions_side.*
   :align: center
   :alt: Mounting holes and dimensions of the VAB-820, side view

   Mounting holes and dimensions of the VAB-820, side view

Height Distribution
-------------------

.. _figure-height-distribution-top:
.. figure:: images/height_distribution_top.*
   :align: center
   :alt: Height distribution of the VAB-820 mainboard, top view

   Height distribution of the VAB-820 mainboard, top view

.. _figure-height-distribution-bottom:
.. figure:: images/height_distribution_bottom.*
   :align: center
   :alt: Height distribution of the VAB-820 mainboard, bottom view

   Height distribution of the VAB-820 mainboard, bottom view

.. _figure-height-distribution-side:
.. figure:: images/height_distribution_side.*
   :align: center
   :alt: Height distribution of the VAB-820 mainboard with the heatsink installed

   Height distribution of the VAB-820 mainboard with the heatsink installed


