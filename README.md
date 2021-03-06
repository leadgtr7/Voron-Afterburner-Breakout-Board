# Voron-Afterburner-Breakout-Board
This is a breakout board for use with the Voron Afterburner toolhead. 
Typically there would be the following wires for the tool head
2 for Hot End Fan
2 For Part Fan
4 For Stepper
2 For thermistor
2 For Heater
3 For Probe
2 For Endstop
for a total of 17 wires

This Board removes reduntant connection across the tool head and thus reduces the number of wires in the cable chain to 14

I have only used this board with an SKRv1.3

If you use a different board you will need to make sure that your board switches the fans on the ground side (ie common 24v).

This does not replace the need for a BAT-85 (or similar schottky diode) on the probe output. Could probably add to the board but space is already really tight.

You will find a spreadsheet with all the wiring colors and info here as well as a part BOM
https://github.com/leadgtr7/Voron-Afterburner-Breakout-Board/blob/main/Voron%20Toolhead%20Breakout%20Board.xlsx
https://github.com/leadgtr7/Voron-Afterburner-Breakout-Board/blob/main/AB%20BOB%20Wiring%20Diagram.pdf

kicad files are here
https://github.com/leadgtr7/Voron-Afterburner-Breakout-Board/tree/main/kicad%20Project

gerbers zipped and ready for your favorite pcb manufacturer are here (I used JLCPCB with a matte black silkscreen)
https://github.com/leadgtr7/Voron-Afterburner-Breakout-Board/tree/main/gerbers

you will need to reprint 2 peices from the clockwork as they include standoffs for the pcb here
https://github.com/leadgtr7/Voron-Afterburner-Breakout-Board/tree/main/Modified%20Clockwork%20Parts

Optional: I also modified the chain anchor to add a zip tie for strain relief on the wires

In addition you will need 2 M2x6mm screws. I used machine screws and wouldn't recommend using the standard voron M2 plastic screws as they are too long

I have also uploaded some pictures of the board installed on the toolhead here. Make sure to trim the leads on the terminal blocks down as the may short on the motor body!
https://github.com/leadgtr7/Voron-Afterburner-Breakout-Board/tree/main/Reference%20Photos
