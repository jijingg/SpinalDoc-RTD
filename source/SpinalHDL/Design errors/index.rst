=============
Design errors
=============

.. toctree::
   :glob:

   *


Introduction
============
The SpinalHDL compile will perform many checks on your design to be sure that the generated VHDL/Verilog will be safe for simulation and synthesis. Basicaly, it should not be possible to generate a broken VHDL/Verilog. There is a not exhaustive list of SpinalHDL checks :

* Assignement overlaping
* Clock crossing
* Hiearchy violation
* Combinatorial loops
* Latches
* Undriven signals
* Width mismatch
* Unreachable switch statements

On each SpinalHDL error report, you will find a stack trace which is realy usefull to accuratly find out where the design error is. It could look overkill in a first look, but as soon you start to go futher the traditional way of doing hardware description, it is realy a helpfull tool. 
