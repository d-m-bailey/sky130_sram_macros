LVS and CVC for sky130 SRAM macros
==================================

This document details the steps taken to run successful LVS and CVC on the sky130 sram macros.

Setup::
 
 cp $PDK_ROOT/sky130A/libs.tech/magic/sky130A.magicrc .magicrc
 cp $PDK_ROOT/sky130A/libs.tech/netgen/setup.tcl .

``run_ext.sh``

The default extract style is used for efabless/skywater designs and flattening single device cells gives more readable results::

 
