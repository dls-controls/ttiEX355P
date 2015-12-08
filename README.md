INTRODUCTION
------------
This is the EPICS support module for the
Thurlby Thandar Instruments (TTi) EX355P Programmable Bench Power Supply

USAGE
-----


One template is provided here:

1) ttiEX355P.template
This instatiates all the records associated with the controller's 
functionality


The user interface is presently available via EDM screens. 
Starting with the root screen: 
ttiEX355P.edl

Serial communications is managed via EPICS streamDevice, usin the protocol file:
ttiEX355P.protocol

MAINTAINERS
-----------

Current maintainers:
* Ian Gillingham (Diamond Light Source) - ian.gillingham@diamond.ac.uk

First created December 2014.


