SparkFun GNSS-RTK Dead Reckoning Breakout - ZED-F9K (Qwiic)
========================================

[![SparkFun GNSS-RTK Dead Reckoning Breakout - ZED-F9K (Qwiic)](https://cdn.sparkfun.com/assets/parts/1/8/2/6/6/18719-SparkFun_GNSS-RTK_Dead_Reckoning_Breakout_-_ZED-F9K__Qwiic_-01.jpg)](https://www.sparkfun.com/products/18719)

[*SparkFun GNSS-RTK Dead Reckoning Breakout - ZED-F9K (Qwiic) (GPS-18719)*](https://www.sparkfun.com/products/18719)

The SparkFun ZED-F9K GNSS Breakout is a high precision, sensor fusion geospatial board with equally impressive configuration options and takes advantage of u-blox's Automotive Dead Reckoning (ADR) technology. The ZED-F9K module provides a highly accurate and continuous position by fusing a 3D IMU sensor, wheel ticks, a vehicle dynamics model, correction data, and GNSS measurements. 

The ZED-F9K module is a 184-channel u-blox F9 engine GNSS receiver, meaning it can receive signals from the GPS, GLONASS, Galileo, and BeiDou constellations with ~0.2 meter accuracy! That's right, such accuracy can be achieved with an  RTK navigation solution when used with a correction source. Note that the ZED-F9K can only operate as a rover, so you will need to connect to a base station. The module supports concurrent reception of four GNSS systems. The combination of GNSS and integrated 3D sensor measurements on the ZED-F9K provide accurate, real-time positioning rates of up to 30Hz.

Compared to other GPS modules, this breakout maximizes position accuracy in dense cities or covered areas. Even under poor signal conditions, continuous positioning is provided in urban environments and is also available during complete signal loss (e.g. short tunnels and parking garages). The ZED-F9K is the ultimate solution for autonomous robotic applications that require accurate positioning under challenging conditions.

Additionally, this u-blox receiver supports I<sup>2</sup>C (u-blox calls this Display Data Channel) which makes it perfect for the Qwiic compatibility so we don't have to use up our precious UART ports. Utilizing our handy Qwiic system, no soldering is required to connect it to the rest of your system. However, we still have broken out 0.1"-spaced pins in case you prefer to use a breadboard.


The SparkFun ZED-F9K GPS Breakout is also equipped with an on-board rechargeable battery that provides power to the RTC on the ZED-F9K.  This reduces the time-to-first fix from a cold start (~26s) to a hot start (~2s). The battery will maintain RTC and GNSS orbit data without being connected to power for plenty of time. The breakout board has five communications ports, four of which are all active simultaneously: USB-C (which enumerates as a COM port), UART1 (with 3.3V TTL), UART2 for RTCM reception (with 3.3V TTL), I<sup>2</sup>C (via the one Qwiic connnector or broken out pins), and SPI. One SMA connector is included for a secure connection to an antenna.

U-blox based GPS products are configurable using the popular, but dense, Windows program called u-center. Plenty of different functions can be configured on the ZED-F9K: baud rates, update rates, geofencing, spoofing detection, external interrupts, SBAS/D-GPS, etc. All of this can be done within the [SparkFun Arduino Library](https://github.com/sparkfun/SparkFun_u-blox_GNSS_Arduino_Library)!

Repository Contents
-------------------

* **/Hardware** - Eagle design files (.brd, .sch)
* **/Production** - Production panel files (.brd)

Documentation
--------------
* **[Library](https://github.com/sparkfun/SparkFun_u-blox_GNSS_Arduino_Library)** - Arduino library
* **[Hookup Guide](https://learn.sparkfun.com/tutorials/2005)** - Basic hookup guide

Product Versions
----------------
* [GPS-18719](https://www.sparkfun.com/products/18719) - Initial release

Version History
---------------
* v1.0 - Initial Release 

License Information
-------------------

This product is _**open source**_! 

Please review the LICENSE.md file for license information. 

If you have any questions or concerns on licensing, please contact technical support on our [SparkFun forums](https://forum.sparkfun.com/viewforum.php?f=152).

Distributed as-is; no warranty is given.

- Your friends at SparkFun.

_<COLLABORATION CREDIT>_
