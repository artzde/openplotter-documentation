# Switches

---

This chapter is under construction

---

For normal switches (opened by default), you have to select "Pull down" in "Switches" tab an connect switch between selected GPIO pin and +3.3v pin (DANGER, NEVER TO +5v). 

For special switches (closed by default), you have to select "Pull up" in "Switches" tab an connect switch between selected GPIO pin and GND pin.

It is not a problem if you make a mistake connecting to GND or +3.3v but be careful and avoid +5v pin. 

Pins numbers are according to this diagram: http://raspi.tv/wp-content/uploads/2014/07/Raspberry-Pi-GPIO-pinouts.png, for example: pin GPIO22 is pin position number 15.