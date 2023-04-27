# ARTSEY-ML
An ARTSEY Paintbrush for ML

This is a PCB for using [ARTSEY](https://artsey.io) with Cherry ML. It's designed for 18mm CHerry ML spacing - Plum keycaps will not fit on this.
It uses a [nice!nano](https://nicekeyboards.com/nice-nano) or Pro Micro, and is compatible with the Paintbrush's firmware on ZMK/QMK for both.

<img src="/Pictures/top.jpeg" width="640">
<img src="/Pictures/window.jpeg" width="640">
<img src="/Pictures/two_controllers.jpeg" width="640">

I provide no guarantees for this project; I've assembled and tested both, and the left-hand board running ZMK travels with me. Assembly is fairly straightforward: solder the SMD switch and reset button first, the the sockets/headers and finally the ML switches and controller, component side up. There is a left board and a right board; however, if you don't plan on making it Bluetooth and can forego the SMD reset and power switch, the boards are fully reversible by flipping the PCB and installing the controller component side down - use the firmware you'd use normally (if it's a left-hand board, use the left-hand firmware and vice versa).

All my hardware designs are licensed under the [Creative Commons
Attribution-NonCommercial-ShareAlike 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
license. 
