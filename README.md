OnStep EQ5 Telescope Controller
===========================
# Telescope Mount Controller
* This Firmware is based on the [Onstep Telescoper Controller](https://github.com/hjd1964/OnStep)
* It is customized to work with the Skywatcher EQ5 mount

# Hardware Used
* Skywatcher EQ5 mount
* Onstep MaxSTM 3.63 PCB
  * TMC5160 driver for RA and DEC axis 
* Stepper motor model: [17HM19-1684S](https://www.omc-stepperonline.com/nema-17-bipolar-0-9deg-44ncm-62-3oz-in-1-68a-2-8v-42x42x47mm-4-wires-17hm19-1684s)
  * 400 $[step/rev]$
  * 1.68 $[A]$
* RA gear ratio: 
  * 16T pulley on motor, 48T on RA axis
  * RA axis worm gear ratio 1:144
  * Total gear ratio: 1:432
  * RA belt:
* DEC gear ratio: 
  * 16T pulley on motor, 48T on RA axis
  * DEC axis worm gear ratio 1:144
  * Total gear ratio: 1:432
  * DEC belt: