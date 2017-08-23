This project created an engineering design tool for an RF impedance transformer.

The output impedance of a transistor or power amplifier is high compared to a
typical antenna. If a 300-$\Omega$ or less antenna were connected directly to
a power amplifier with an output impedance of 10-k$\Omega$, nearly all of the
power would be self-absorbed by the amplifier because the antenna is practically
a short circuit in comparison. Instead, we seek to transfer maximum power to the
antenna load and reduce the internal power dissipation of the amplifier.

The solution to this problem is placing an impedance transformer between the
unmatched components.

To generalize the method, the amplifier is a modeled a source with output
resistance $R_t$ and the antenna is modeled as a load resistor $RL$.

Discrete Components or Transmission Line:
An impedance transformer can be implemented either with discrete components or
as a transmission line.  The choice is based on the cost and size of the
solution. Usually low frequency circuits use discrete components while the
transmission line is more favorable at higher RF and microwave frequencies.
In this slideshow, we show how to implement the circuit with discrete
components. 
  
Reproducible Report
  
This slideshow is an engineering tool. It is produced by a computer script
program. Nothing is performed manually as all calulations are performed in code
blocks that are mostly hidden. 

An impedance transformer is a tuned circuit that performs its function at the
frequency of the RF power signal being sent to the antenna. There are different
levels of performance:

(a) No bandwidth control: coil, capacitor, and resistor
(b) Controlled bandwidth: coil, two capacitors, and resistor