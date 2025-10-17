⚙️ Voltage-Controlled Oscillator in GPTK90

🧩 Overview

This project focuses on designing and simulating a Voltage-Controlled Oscillator (VCO) using the GPTK90 CMOS process.
A VCO generates an output signal whose frequency varies with the input control voltage, making it a core block in circuits like PLLs, frequency synthesizers, and RF systems.

🎯 Goal

To design a working VCO that:

Shows a stable and tunable frequency response

Maintains linear control voltage-to-frequency behavior

Operates efficiently within GPTK90 technology limits

🛠️ Tools & Technology
Category	Details
Technology	GPTK90 (90 nm CMOS)
Design Tool	Cadence Virtuoso
Simulator	Spectre
Design Type	Analog / Mixed-Signal
🔧 Design Description

The circuit is based on a ring oscillator topology, where the delay of each stage depends on the applied control voltage.
Changing the control voltage alters the delay, which directly changes the oscillation frequency.

🧠 Design Steps

Schematic Design: VCO designed using GPTK90 MOSFETs.

Simulation: Performed transient and parametric analysis in Spectre.

Layout: Created layout with DRC and LVS verification.

Analysis: Checked output frequency variation and waveform stability.

📈 Simulation Results
Control Voltage Range : 0.5 V – 1.2 V
Output Frequency Range: ~100 MHz – 450 MHz
Supply Voltage         : 1.2 V


✅ Stable oscillation
✅ Smooth frequency tuning
✅ Consistent output waveform

💡 Applications

Phase-Locked Loops (PLLs)

Frequency Modulators / Demodulators

RF Communication Systems

On-Chip Clock Generation

👤 Author

Ayan Munshi
VLSI Design Student | Analog & Mixed-Signal Circuit Design
