# Common switches
---

This chapter is under construction

---
## Wiring

Pins names are according to the diagram below.

![](RP2_Pinout.png)

For normal switches (open by default), you have to select "Pull down" in "Switches" tab an connect switch between selected GPIO pin and +3.3v pin (DANGER, NEVER TO +5v). 

For special switches (closed by default), you have to select "Pull up" in "Switches" tab an connect switch between selected GPIO pin and GND pin.

It is not a problem if you make a mistake connecting to GND or +3.3v but be careful and avoid the +5v pin.

![](common_sw.png)

## Settings