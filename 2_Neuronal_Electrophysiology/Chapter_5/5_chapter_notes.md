## Chapter 5: Action Potential Kinetics

**1. Action potentials**
- **Threshold:** -55 mV membrane potential that initiates action potential  
- **All-or-nothing:** Once threshold reached, action potential amplitude is the same
- **Self-regenerative:** Once initiated, action potential self-propagates along axon length without further stimulation via saltatory conduction
- **Refractory period:** Time after initiation during which new action potential cannot be initiated
    - **Absolute:** Period where new action potential is impossible
    - **Relative:** Period where new action potential possible with stronger stimulus

**2. Voltage clamping**
- Technique that allows experimenter to control membrane potential and measure changes to membrane current
- **Voltage clamp circuit:** 
    - **Internal Electrode**: Measures membrane potential
    - **Feedback circuit:** Compares membrane potential to desired membrane potential and adjusts current injected by voltage clamp amplifier to maintain constant membrane potential
    - **Current Electrode:** Injects current into cell to maintain constant membrane potential. The amount of current injected is equal and opposite to membrane current, so membrane current can be measured
- **Patch Clamp:** Technique that allows experimenter to measure membrane current from a single ion channel
    - **Cell-attached:** Patch pipette attached to cell membrane
    - **Whole-cell:** Patch pipette ruptures cell membrane, allowing access to cell interior

**3. Hodgkin-Huxley model**
- Action potential characterized by inward current (depolarizing) followed by outward current (repolarizing)
- **TEA:** Blocks outward repolarizing current by blocking K+ channels
- **TTX:** Blocks depolarizing current by blocking Na+ channels
- **Conclusion:** Action potential phases involve changes in membrane permeability to Na+ and K+

**4. Na+ and K+ current dynamics**
- Na+ conductance increases rapidly when membrane potential depolarizes past threshold
- Na+ channels are inactivated by depolarization, so Na+ conductance decreases rapidly
- K+ conductance increases more slowly when membrane potential depolarizes
- K+ channels are not inactivated by depolarization, so K+ conductance remains high during later phases of action potential

**5. Phases of Action Potential**
- **Rising phase:** Na+ channels open, Na+ flows into cell, membrane potential depolarizes
- **Falling phase:** Na+ channels close, K+ channels open, K+ flows out of cell, membrane potential repolarizes
- **Undershoot:** K+ channels remain open, K+ continues to flow out of cell, membrane potential hyperpolarizes
- **Refractory period:** Na+ channels inactivated, K+ channels remain open, membrane potential cannot be depolarized

**6. Voltage-gated channel overview**
- Note: There are many different subtypes of voltage-gated channels with different kinetics for each ion. These are just generalizations.
- **Na+ channels:** 
    - 4 domains, each with 6 transmembrane segments
    - S4 segment contains positively charged amino acids (voltage sensor)
    - S5 and S6 segments form pore (loop is selectivity filter)
    - Inactivation gate (generally inactivating)
    - Blocked by TTX
- **Ca2+ channels:** 
    - Same structure as Na+ voltage-gated channels
    - Can be inactivating or non-inactivating
    - Blocked by calcium chelators
- **K+ channels:** 
    - 4 subunits, each with 6 transmembrane segments
    - S4 segment is voltage sensor
    - S5 and S6 segments form pore (loop is selectivity filter)
    - Blocked by TEA
    - **Common Variations:**
        - I_K: *most common*, non-inactivating, depolarization activated (no inactivation gate)
        - I_A: N-terminal modified with inactivation ball
        - I_C: C-terminal modified with Ca2+ binding domain (Ca2+ dependent activation)
        - I_M: C-terminal modified with phosphorylation sites (phosphorylation deactivating)

**7. Modifications to Ion Channels**
- Changes to N-terminal change receptor localization
- Changes to C-terminal change regulation
- Changes to S4 change voltage sensitivity
- Changes to S5 and S6 change ion selectivity

**8. Common voltage-gated currents**
- **Na+ currents**
    - **I_Nat**: Fast activating/inactivating, responsible for rising phase of AP in axon
    - **I_Nap**: Slow activating/non-inactivating, enhances excitability of dendrites and soma, and steady state depolarization
- **Ca2+ currents**
    - **I_L**: Long-lasting, high threshold, slow activating, slow inactivating. Involved in dendritic excitability and synaptic transmission at axon terminal
    - **I_T**: Transient, low threshold, fast activating/inactivating. Causes burst firing and rapid dendritic depolarization
- **K+ currents**
    - **I_K**: Slow activating, non-inactivating. Responsible for falling phase and refractory period of AP in axon
    - **I_C**: Slow activating, non-inactivating, but requires Ca2+. In soma/dendrites; decreases excitability and increases interval between APs
    - **I_A**: Fast activating/inactivating, responsible for delaying onset of action potential initiation in soma/dendrites
    - **I_M**: Very slow activating, non-inactivating; blocked by activation of muscarinic receptors. Found in soma/dendrites; decreases excitability and spike frequency adaptation.
- **I_h**: Activated by hyperpolarization, involves mixed inward cation current (Na+ and K+). Found in soma/dendrites. Contributes to depolarizing pacemker potentials.

**9. Voltage-gated channels effect in neurons**
- Voltage-gated channels are found all over the neuron, but their expression/relative abundance varies by location both inside the neuron and across different types of neurons
- **Dendrites:** Many different types of voltage-gated channels, but lower density than axon. Na+, K+, Ca2+ channels all present.
    - Current types: I_Nap, I_L, I_T, I_C, I_A, I_M, I_h
- **Soma:** Many different types of voltage-gated channels, but lower density than axon. Few Ca2+ channels.
    - Current types: I_Nap, I_C, I_A, I_M, I_h
- **Hillock:** Extremely high density of voltage-gated channels, especially Na+ channels
- **Axon:** High density of voltage-gated channels, especially Na+ channels and K+ channels near nodes of Ranvier
    - Current types: I_Nat, I_K
- **Axon terminal:** High density of voltage-gated channels, especially Ca2+ channels
    - Current types: I_L

**10. Spike Firing Patterns**
- Important Currents for Neuronal Excitability
    - **I_T**: Causes burst firing and rapid dendritic depolarization
    - **I_A**: Decreases excitability and delays onset of AP
    - **I_M**: Decreases excitability and causes spike frequency adaptation
    - **I_h**: Increases excitability and contributes to depolarizing pacemaker potentials
- **Regular Spiking**
- **Fast Spiking**
- **Burst Spiking:** Rapid firing of APs followed by period of lower activity
- **Chattering:** Rhythmic rapid firing of APs followed by period of lower activity
- **Firing patterns can change:** During sleep, thalamic resting Vm hyperpolarizes, allowing I_h current to cause pacemaker potentials. When awake, thalamic resting Vm depolarizes, causing I_h current to be inactivated and preventing pacemaker potentials.
    - Diffuse modulatory systems such as serotonin can also change firing patterns, especially in cortex

**11. Gap Junctions**
- **Synchronized Activity:** Channels that connect cytoplasm of two cells, allowing ions to flow between cells
    - 1 gap junction = 2 connexons
    - 1 connexon = 6 connexins
    - 1 connexin = 4 transmembrane segments
    - Total of 48 transmembrane segments per gap junction
    - Most common between GABAergic interneuron dendrites

**12. Orthodromic, Antidromic, and Back-Propagating Action Potentials**
- **Orthodromic:** Action potential propagates from soma to axon terminal (normal)
- **Antidromic:** Action potential propagates from axon terminal to soma (abnormal)
    - Can be caused by electrical stimulation
- **Back-propagating:** Action potential propagates from axon terminal to soma and dendrites (normal)
    - Indicate to dendrites that action potential was initiated in axon hillock
    - Learning signal
    - Contributes to synaptic plasticity
- **Compound Action Potential:** Sum of all action potentials in axon bundle
    - Can be used to measure conduction velocity of axon bundle
    - C fibers: Slow pain/temp (unmyelinated) _slowest_
    - Aδ fibers: Fast pain/temp (myelinated)
    - Aβ fibers: Touch/pressure (myelinated)
    - Aα fibers: Touch/proprioception (myelinated) _fastest_
    - Nerve conduction studies will stimulate axon bundle and measure compound action potential to determine if there is damage to specific axon types, given that they have different conduction velocities
