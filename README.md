# Microphone interface

A phantom-powered balanced interface for an [electret microphone](https://en.wikipedia.org/wiki/Electret_microphone) capsule with a built-in [JFET](https://en.wikipedia.org/wiki/JFET).

This interface has no gain, except for doubling the amplitude while converting the single-ended signal
from the capsule into a balanced output signal.

The PCB is designed to fit into a metal tube ⌀11.5 or wider.

![Interface PCB CGI](images/Mic%20PCB.png)

Please note that two OPA1641 ICs are used in the design just because I already had them when designing the circuit. Using OPA1642 would be more space-efficient and I recommend you using OPA1642, not OPA1641 in your design.
