## Chatpter 4: Resting Membrane Potential

**1. Resting membrane potenial:** The voltage difference across the membrane of a neuron at rest. It is typically -65 mV (inside is more negative than outside).

**2. Ion Concentration Gradients**
- Ion pumps establish and maintain ion concentration gradients
- Selectively permeable membrane controls permeability of ions
- Typical values (outside/inside):
    - **K+**: 5/100 mM
    - **Na+**: 150/15 mM
    - **Ca2+**: 2/.0002 mM
    - **Cl-**: 150/13 mM

**3. Nernst Potential:** The membrane potential at which the net flow of an ion is zero. It is calculated using the Nernst equation:

    E_ion = (61.5mV)/z * log([ion]_out/[ion]_in)

    z = valence of ion

- **Typical values:**
    - **EK** = -80 mV
    - **ENa** = +61.5 mV
    - **ECa** = +123 mV
    - **ECl** = -65 mV

**4. Driving Force:** The difference between the membrane potential and the Nernst potential. It determines the direction of ion flow and magnitude of ion flow.

**5. Goldman Equation:** The membrane potential at which the net flow of all ions is zero. It is calculated using the Goldman equation:

    E_m = (61.5mV) * log((P_K[K+]_out + P_Na[Na+]_out + P_Ca[Ca2+]_out + P_Cl[Cl-]_in)/(P_K[K+]_in + P_Na[Na+]_in + P_Ca[Ca2+]_in + P_Cl[Cl-]_out))

- **Typical permeability values:**
    - **P_K:P_Na:P_Cl = 40:1:10**

**6. Effect of changing permeability of an ion on membrane potential:** 
- If you increase permeability of an ion, then the membrane potential will move towards the Nernst potential of that ion. 
- Increasing sodium permeability will depolarize the membrane potential.
- Increasing potassium permeability will hyperpolarize the membrane potential.
- Increasing chloride permeability will fix the membrane potential at the chloride Nernst potential, which is the same as the resting membrane potential. Makes neuron less excitable.

**7. Predicting ion flow for different membrane potentials:**
- Inward currents make Vm more positive
- Outward currents make Vm more negative
- More positive than +61.5 mV: Na+ flows out of cell (outward current), because it wants to bring the Vm lower to reach ENa. K+ and Cl- flow into cell, because they want to lower Vm to reach EK and ECl. 
- Between +61.5 mV and - 65 mV: Na+ will flow in (inward current) because it wants to make Vm more positive. K+ and Cl- will flow in (outward current) because they want to make Vm more negative.
- Between -65 mV and -80 mV: Na+ will flow in, K+ will flow out, and Cl- will flow out (inward current). 
- More negative than -80 mV: Na+ will flow in, K+ will flow in, and Cl- will flow out (inward current).

**8. Circuit Model of a Neuron:**
- **Voltage source:** A device that maintains a constant voltage. The ion concentration gradients are voltage sources.
- **Current source:** A device that maintains a constant current. The ion pumps are current sources.
- **Capacitor:** A device that stores charge. The membrane is a capacitor, and the membrane potential is the voltage across the capacitor.
- **Resistor:** A device that resists the flow of current. The ion channels are resistors, and the ion concentration gradients are the voltage sources.
- **Conductance:** The inverse of resistance; the slope of an IV plot.

**9. RC circuit:**
- Initially, the capacitor is uncharged. 
- After connecting circuit, capacitor current spikes and then decays to zero, while its voltage increases to the battery voltage and plateaus.
- When discharging, the capacitor voltage decays exponentially to zero and current spikes and then decays to zero.
- Dielectric: A material that increases the capacitance of a capacitor. The myelin sheath is a dielectric.
- Plates of capacitor: The two sides of the membrane.

**10. Predicting current tracings**
- Increasing membrane capacitance will increase time of charging.
- Increasing membrane resistance will increase time of discharging.
- Increasing injected current will increase the amplitude of the current spikes, but not the time of charging and discharging.

**12. Cable Properties of Neurites**
- **Axial resistance**: The resistance to current flow along the neurite. 
    - Proportional to the length of the neurite
    - inversely proportional to the cross-sectional area of the neurite.
    - More axial resistance is bad, because it will cause the current to decay more quickly.
- **Membrane resistance**: The resistance to current flow across the membrane.
    - More membrane resistance is beneficial, because spikes will travel further and decay less. It increases the length constant.
- **Membrane capacitance**: The capacitance of the membrane.
    - More membrane capacitance is bad for spikes, because it decreases responsivity of the membrane to current injection.

**13. Length Constant:** The distance at which the voltage decays to 37% of its original value. It is calculated using the length constant equation:

    λ = sqrt(Rm/Ra)

**14. Voltage decay equation**

    V(x) = V(0) * e^(-x/λ)

    V(0) = initial voltage at x = 0
    x = distance from injection site

**15. Axon Properties**
- More axon diameter decreases Ra, which increases λ, which increases the distance that the spike can travel.
which increases the distance that the spike can travel.
- Myelination decreases membrane capacitance, which makes the membrane more responsive to current injection.
- Myelin increases membrane resistance, which increases λ, which increases the distance that the spike can travel.
- APs move faster along internodes, because there is less capacitance and more membrane resistance (longer λ).
- Nodes of ranvier are still necessary to regenerate APs.