# SYNTHETIX_BUZZKILL
Final Submission of team BUZZKILL, the electrical track participants of SYNTHETIX 4.0

#IMPORT BLACKBOX THROUGH THE FOLLOWING STEPS
1) Download the .asy file and .lib file and store them under the
same folder as your project (schematic)
2) Go to file>spice directive. Select spice directive and enter the
following command .include composite_blackbox.lib and click
ok.
3) Go to edit>component and in show, select your folder. Click
on refresh and then a component COMPOSITE_SRC will
appear. Select that and click ok and place it on the schematic.
4) There are 2 pins, OUT pin is your input and GND pin is
grounded.
5) For verifying if you are getting the input signal do the
following:
a) Go to simulate>configure analysis
b) Go to transient and type the following: .tran 0 20m and
select ok
c) Run the simulation and view plot. You should get the
following output
This is your input signal.

REMEMBER: ALL FILES SHOULD BE WITHIN THE SAME FOLDER

#SIMULATE THE CIRCUIT

