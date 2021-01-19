# YAYATC- Yet Another YATC
### A new temperature controller, because the YATC links were broken.

YAYATC is a temperature controller designed to heat or cool things to any temperature, within reason. YAYATC can handle either a 10k NTC thermistor or the 1-wire thing from Sparkfun as a temperature sensor. As long as only one is plugged in, YAYATC will automatically detect which to use.
No external power supply is needed- all circuitry is powered directly from the wall.  

The goal here was to minimize design time, and other temperature controllers may have better performance, cheaper BOMs, easier assembly, etc.

Revision 1 has not been tested. If you want to make one anyways, go ahead.

Revision 1 known issues:
~~ - No way to tell if temperature is positive or negative ~~  
~~ - Only 2 digits. No way to display temperatures above 100. ~~
