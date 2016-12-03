# Tools defined

Openplotter has a chance to integrate programs.

This was done to be open for addons done by experts and to keep openplotter simple for newcomer.

In the **openplotter.conf **you can add or delete tools.

Example:

_\[TOOLS\]

_py = \[\['Analog ads1115', 'put analog values to SignalK', 'analog\_ads1115.py', '0'\], \['Analog Firmata', 'put analog values to SignalK', 'oppymata.py', '0'\], \['SignalK Simulator', 'change values with sliders and send values to SignalK', 'SK-simulator.py', '0'\], \['wireless temp', 'measure', 'rtl\_433SK.py', '0'\], \['Auto Setup', 'configure basic system', 'autosetup\_tty.py', '0'\]\]_

![](/assets/toolsDefined.png)

The first name in the menu section is: _Analog ads1115_

The statusbar shows: _put analog values to SignalK_

The program to start is: _analog\_ads1115.py_

The autostart on boot is disabled: _0_

So the first element of the list is _\['Analog ads1115', 'put analog values to SignalK', 'analog\_ads1115.py', '0'\]_



After menu selection this form popup

![](/assets/ToolsDefined.jpg)

**settings** - can be used to open a setup form or open a configuration file

**start** - normal start

**stop** - uses pkill command to stop the app



here some tools:

[Analog ads1115](/Analog ads)

[Analog Firmata](/Analog Firmata)

[SignalK Simulator](/SignalK Simulator)

[wireless temp](/wireless temp)

[Auto Setup](/Auto Setup)

**You can look at the code for these tools and build your own app/addon.**
