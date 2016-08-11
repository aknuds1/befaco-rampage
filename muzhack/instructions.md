# Rampage V1.3.1: Assembly Reference
**Please note that this is an unofficial project page, the official one is [here](http://www.befaco.org/en/rampage/).**

**Thanks for choosing our kits!**
This manual has been written taking into account the problems that we usually find in our workshops.
The order is meant to make assembly as easy as possible. Some steps are not obvious so even if
you're an experienced DIYer, please read the steps completely before starting.

If this is your first project, please read this article before you start assembling the kit:
[www.befaco.org/howto/](http://www.befaco.org/howto/)

**May the luck be with you!**

## Main PCB (the small one)
**Open Main Board Bag A**

### Resistors
Solder the resistors.

### Diodes
Solder the diodes respecting the polarity. A black or white line on the diode must be in the
same place as the white line on the diode symbol on the PCB silkscreen.

### Ferrite
Solder each ferrite bead passing trough a recycled resistor leg and proceed as if it were a
resistor. Ferrite beads don't have polarity. The space for ferrites is relatively tight,
so leave them a bit separated from the board to make them fit between the power connector
and the diodes.

**Open Integrated Circuits Bag**

### ICs
Place the IC sockets taking care of the orientation and solder them on IC1, IC2, IC3, IC4, IC5, IC6, IC7 and IC8. The orientation must match the PCB's outline.

**Open Main Board Bag B**

### Capacitors
Solder the capacitors.

### Electrolytic Capacitors
Values written on the side of the capacitors. Mind polarity. This is a polarised component
so make sure the longer leg goes to the positive terminal on board.

### Transistors
Make sure they are positioned correctly with reference to the silkscreen outline on the PCB.

### Male Pin Headers
Place and solder the two male pin Headers on the silkscreen side, ensuring they are 90º to the PCB. The shortest side of the pins is for soldering.

### Power Connector
Solder the power connector ensuring the position is correct: it must be on the silkscreen side
with the pins facing the edge of the PCB. Have you remembered to fit the ferrites?

## Control PCB
**Open Control Board Bag A**

### Resistors
Solder resistors.

### Diodes
Solder diodes observing the correct polarity. The black line on the diode must be in the
same place as white line on the diode PCB silkscreen

### Capacitors
Solder capacitors.

### Transistors
Make sure they are positioned correctly with reference to the silkscreen outline on the PCB.

### Trimmers
Solder the two 10k trimmers on SYMETRY_A and SYMETRY_B with the screw facing out of the PCB.

**Open Control Board Bag B**

### Female Pin Headers
Place the two female pin headers (To_con_A, To_con_B) and solder them ensuring they are 90º
to the PCB. Then with snips, cut the excess from the pins on the other side to allow
correct placement of the faders (next step).

### Faders
Solder the faders on the side indicated by the drawing ensuring that they are 90º to the PCB.

### Spacers
Fit the two spacers with the male end passing through the control board with the M3
nuts on the same side as the faders.

### Front panel components mounting tips
Now we will proceed to mount jacks, potentiometers, switches and LEDs. This part of assembly is
CRITICAL. Please be gentle and read the instructions carefully. These components must NEVER
be soldered until they are placed on the PCB and fully attached to the front panel.

There are two reasons for this:

* The height of the panel components are not all the same. Because of this, if not attached
properly before soldering, they will not stay properly seated against the panel. This
might cause mechanical torsions, reducing their life expectancy and in the worst case
they will break.
* The second reason is that it is very difficult to align the components to the holes if
the panel is not positioned before soldering. In the case of the LEDs, they are almost
impossible to set to the correct height without reference to the front panel.

**Open Mini-jacks bag**

## Minijacks
Place the mini-jacks ensuring they are on the silkscreen side but don't solder them
until the front panel is in place and with all nuts screwed to it. This way it's
easier to solder them in the right position. Keep in mind that the front panel holes
are quite narrow and it is almost impossible to place it with all the components
already soldered. Caution: the switch nuts and the jack nuts look alike but they are
not and will not fit in each other's threads so don't mix them!

## Potentiometer
Cut the locating lug on all three pots with cutting pliers as pictured:

![Potentiometer](http://aknuds1.github.io/befaco-spring-reverb/pictures/potmeter.png "Potentiometer")

Now place potentiometers on the PCB but... **don't solder them**

## Switches
Place the four toggle switches but **don't solder them** until they are screwed to
the front panel. This way it's easier to solder them in the right position.

You will know which ones are the two and three position switches because when switching,
two will have just two positions and the other two will have a third center position.

Remove the nut from the two push buttons but leave the washers on the switch. Fit
the push buttons with the washers on to the panel but **don’t solder them yet**.

## LEDs
Put the LEDs in place checking the polarity, but don't solder them until the front panel is
in place. This is the only way to solder them in the right position.

The long leg is the + and short one is the minus. On the PCB the square pad is the
minus and there is a + symbol to indicate the correct position.

## FRONT PANEL
1. Place the front panel adjusting the parts one by one as necessary until they fit.
At this point a pair of sharp tweezers can be helpful.
2. Screw the components to the panel until they are tightly aligned, in the following
order: Mini-jacks, switches, pots and push buttons.
3. **Then (finally) solder all of them.** ; )
3. **Place the LEDs** in the panel holes making sure they are on the right level and
proceed to solder them.
4. Place the eight ICs on the sockets of the main board, observing polarity. The mark
on the front of the IC must match the mark on the socket and the PCB's silkscreen.
5. **Plug PCB1 onto PCB2** using the pin headers and ensuring the two 3mm holes match the spacers. Screw the two boards onto each other using two screws.
6. **Put the knobs** on the potentiometers and the caps on the switches/faders.
7. **Plug in the power ribbon cable**: The red wire (negative) corresponds to the pin number
one of the connector. The pin number one is indicated with a small triangle and usually
with a line on your power bus.

## ADJUSTMENT PROCEDURE
Sometimes, due to the tolerance of the pot's value, the response of the shape pot may not
be quite symmetrical. In that case adjustment of “SYMETRY_A” and “SYMETRY_B” trimmers is needed.

1. Connect the Rampage's Out A to an oscilloscope. A software oscilloscope on your computer
is enough but in this case the signal needs to be attenuated to avoid clipping. If
attenuation is needed you can use the "Max Out" in place of "Out A" and adjust the amplitude
with the Balance pot.
2. Set range switch A to Mid (bottom position).
3. Set the Cycle Switch A to Cycle (top position).
4. Push "Manual trigger A" button, to put your Rampage in oscillation mode.
5. Set Rise and Fall faders at minimum.
6. Turn the "shape A" pot all the way clockwise. Check if rise and fall times are
equal. If so you are done. If not go to the next step.
7. Move the “SYMMETRY_A” trimmer and try to match (as much as possible) the rise and fall times.
8. Repeat the procedure for “SYMMETRY B” adjustment.

**Enjoy!**
