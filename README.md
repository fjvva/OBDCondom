# OBDCondom
Inexpensive and easy to hide small PCB to enable/disable CAN/KLINE or any low-speed (non-ethernet) communications from the OBD port to prevent undesired access (theft via OBD). Compatible with both 12V and 24V diagnostic connectors. No markings or names on pcb to make it as generic as possible.

When 3.3V-32V are applied to + and -, communications will be enabled, otherwise, connected wires won't be enabled. Easy to add a switch to it from the OBD2 pins 16 for + and 4/5 for -.

Data lines to be protected must be connected in series. The connector on the left of the + and - is the input, and the one on the opposite side is the output. Connect the wire on the left of the input to the left of the output, and same with the right one.

Only 5 components needed:

  -2x AQY21SOP (AQY212GS). Use PCB dot for pin1 reference.
  
  -1x 0805 ceramic capacitor, 1uF (C0805X105K8RAC7210 for example). Located on top of the + - connector.
  
  -1x 0805 ceramic capacitor, 2.2uF (TMF212B7225KGHT for example). Located next to output connector, opposite side of + - connector.
  
  -1x MIC3490-1.8YM5-TR voltage regulator
