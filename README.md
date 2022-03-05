# Exponential Step Signal Generator

This circuit generates a fixed waveform of exponentially rising DC steps, which
could be used for testing logarithmic amplifiers.

![Printed circuit board](/Images/front.jpeg)

Output voltages range from 320 uV to 3.2V in steps with a ratio of 3.16,
equivalent to a 10 dB change. The waveform repeats at a nominal 50 Hz to allow
a flicker-free image on an analogue oscilloscope.

![Waveform rising in exponential steps](/Images/waveform.jpeg)

The PCB is designed to work as a naked board that sits on top of the 9V battery
that powers it. The output pads are designed to accept the majority of 4mm
binding posts and when unpopulated will also work with crocodile clips.

![Electronic components](/Images/back.jpeg)

The circuit has been laid out primarily in surface mount components; as a
concession to the robustness requirements of the designer, through hole
components are used for the trimmer resistors and the power switch. Further the
trimmer resistor positions will accept components with either staggered or
in-line legs, the former being preferred for mechanical stability.

Multiple footprints for the voltage regulator are provided as a convenience
to accomodate the limited availability of less common negative 5V LDO regulators
required by this design; only one of the options should be fitted.

Resistor R33 can be either a surface mount or through hole component as
is convenient, any value in the range 100 - 150 ohms being adequate if the
preferred value is not available. Higher values will decrease the output drive
capability for the highest voltage steps.
