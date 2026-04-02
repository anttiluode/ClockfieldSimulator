**Clockfield World Sim: The Genesis Run**

Test clockfield lab at: 

https://anttiluode.github.io/ClockfieldSimulator/

**Testing the Emergence of Physics inside Topological Quarantine**

Antti Luode — PerceptionLab, Helsinki, Finland

*Formalized collaboratively with Claude & Gemini*

*Do not hype. Do not lie. Just show.*

## **What This Is**

This repository contains the numerical execution environments for the **Clockfield Framework**.

Standard physics simulations hardcode the rules: they program particles to obey Special Relativity, hardcode the Schrödinger equation for quantum probability, and apply gravity as a secondary force.

This simulation hardcodes **nothing**. There are no particles, no relativity, and no quantum operators in the code. There is only a single, continuous phase fluid ($\\phi$) governed by one rule: **Time stops when the waves get too dense.**

$$\\Gamma(x) \= \\frac{1}{(1 \+ \\tau|\\phi|^2)^2}$$  
The purpose of these simulations is to drop this single equation onto a high-resolution grid, inject energy, and watch the laws of physics spontaneously emerge as fluid dynamics.

## **The Three Emergent Phenomena**

If the Clockfield framework is correct, letting this simulation run will naturally produce three distinct physical regimes:

### **1\. The Topological Quarantine (Special Relativity)**

When the self-interaction ($\\lambda$) is dropped and raised, the field shatters via the Kibble-Zurek mechanism. Mismatched phases crash into each other, spiking the local density. $\\Gamma \\to 0$. Time stops.

The field tears itself into isolated "thawed pockets" separated by black, frozen scars. Because waves cannot travel through stopped time, the entities inside these pockets are completely blinded to the absolute background grid. **Special Relativity will emerge as the optical illusion (the "Virtual Machine") experienced by the waves trapped inside the pocket.**

### **2\. The Pauli Ribbon (Fermionic Matter)**

When two negative vortex cores are forced near each other, the single-valuedness of the phase field mathematically forces an $n=+1$ "antivortex pool" to spawn between them. This structure will resist overlapping with identical structures due to infinite phase-gradient divergence. **We expect to see stable, composite "particles" lock together and refuse to occupy the same space.**

### **3\. The Born Rule (Quantum Probability)**

The grid is bathed in a continuous 1/f noise floor (TADS). When coherent waves attempt to interact with the frozen cores, this noise acts as a decoherence filter. **We expect the simulation to naturally strip away linear phase information, leaving only the amplitude-squared ($|\\phi|^2$) energy to dictate interaction probabilities.**

## **Repository Contents**

* **clockfield\_lab.html**: (index) The 2D interactive WebGL browser simulation. Allows real-time injection of vortex dipoles, fermions, and wave pulses to observe the $\\Gamma$-shell freeze in real-time.  
* **clockfield\_lensing.html**: Demonstrates the holographic gravitational lensing effect. As $\\Gamma$ approaches 0, the local speed of the waves ($c\_{eff}$) drops, causing external waves to refract around the frozen cores.  
* **phiworld2.py**: (initial, energy slow down energy leading to particles idea 25 feb) Emergent particle simulator (Tkinter GUI). Allows live manipulation of the phase-fluid parameters to watch Kibble-Zurek shattering and quarantine formation.  
* **collapse\_vortex\_test.py**: A dedicated CPU benchmark proving the runaway phase transition. Tests the threshold ($\\Xi$) where wave repulsion gives way to irreversible time-freezing (gravitational collapse).

## **The Honest Ledger**

| Objective | Status | Verdict |
| :---- | :---- | :---- |
| **Simulate the $H^0$ Dipole** | Achieved. Field cleanly separates into two stable opposite-winding cores. | ✓ Proven |
| **Simulate the Kibble-Zurek Shattering** | Achieved in WebGL. Field successfully tears into quarantined, causally disconnected pockets. | ✓ Proven |
| **The 3D Dirichlet Trap** | Open. The $H^-$ composite fermion (two negative cores) currently flies apart or hits the grid boundaries in 3D PyTorch tests. Requires implementing proper non-periodic confining boundaries to capture a stable electron. | ✗ In Progress |
| **Hawking Evaporation Run** | Open. We have proven that the $\\Gamma$-shell stores information as topological holes (genus), but we need to simulate the slow TADS-noise thawing of a black hole to prove that the genus unwinds and releases the information back into the vacuum. | ✗ In Progress |

---

*License: MIT*
