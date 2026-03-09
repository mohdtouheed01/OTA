# OTA
The first stage of an operational amplifier (Op-Amp) is typically a differential amplifier that receives two input signals, Vin+ and Vin-. Its primary function is to amplify the difference between these two inputs while rejecting any signal that is common to both inputs, known as the common-mode signal. This property improves the Common Mode Rejection Ratio (CMRR) of the amplifier.

This stage usually consists of a differential transistor pair, a current source, and an active load. The differential pair converts the input voltage difference into current, while the active load helps increase the voltage gain of the stage. Additionally, the first stage provides high input impedance, ensuring that the amplifier does not significantly load the input signal source.

Overall, the first stage plays a critical role in determining the input characteristics, gain, and noise performance of the operational amplifier.
In this, I designed an Ist-stage OTA with an ac gain of around 39.9 dB and a phase margin of 90.28 degrees with total power dissipation of 100.116uW with current of 55.62uA.

A typical CMOS OTA consists of the following components:
Differential Input Pair – Converts the input voltage difference into current.
Current Mirrors – Used for active load and signal conversion.
Biasing Network – Establishes the operating point of the transistors.
Output Stage – Delivers the output current signal
