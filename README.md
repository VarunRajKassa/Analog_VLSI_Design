# Analog VLSI Design using Cadence Virtuoso (GPDK180)

## Introduction

This repository presents a complete set of Analog VLSI design experiments implemented using **Cadence Virtuoso** under **GPDK180 technology**. The work covers the full custom analog IC design flow, beginning from transistor-level schematic design to physical layout implementation, verification, parasitic extraction, and final GDS generation.

Analog circuit design forms the backbone of modern semiconductor systems such as PLLs, ADCs, DACs, Voltage Regulators, Memory Sense Amplifiers, RF Front Ends, and Sensor Interfaces. This repository demonstrates practical hands-on understanding of transistor behavior, analog amplification techniques, biasing circuits, and differential architectures.

The objective of this work is to build strong foundational knowledge in analog CMOS design while understanding real-world physical implementation constraints such as device matching, parasitic effects, and layout optimization.

---

# Technology and Tools Used

## Cadence Virtuoso
Used for:
- Schematic Design
- Symbol Generation
- Layout Design
- DRC Verification
- LVS Verification
- Parasitic Extraction

## GPDK180 Technology
Technology node used:
- 180nm CMOS Process
- Suitable for analog educational and prototype designs

## Spectre Simulator
Used for:
- DC Analysis
- AC Analysis
- Transient Analysis
- Operating Point Analysis

---

# Complete Analog Design Flow

The following industrial-standard analog flow was followed throughout all experiments:

### 1. Device Schematic Design
Transistor-level circuits were designed using PMOS and NMOS devices.

### 2. Symbol Creation
Custom symbols were generated for hierarchical circuit integration.

### 3. Testbench Setup
Input sources, supply voltages, and loads were configured for simulation.

### 4. Pre-Layout Simulation
Functional validation performed before layout implementation.

### 5. Physical Layout Design
Transistor placement and routing completed while following design rules.

### 6. DRC (Design Rule Check)
Verified layout correctness against technology rules.

### 7. LVS (Layout Versus Schematic)
Verified logical equivalence between schematic and layout.

### 8. Parasitic Extraction
Extracted parasitic capacitances and resistances.

### 9. Post-Layout Simulation
Validated performance after considering parasitic effects.

### 10. GDSII Generation
Generated final layout database for fabrication flow.

---

# Experiments Implemented

## 1. NMOS Device Characterization

Performed DC analysis to understand:
- Threshold Voltage (Vth)
- Drain Current (Id)
- Saturation Region
- Linear Region
- Device Behavior with varying VGS and VDS

Key Learning:
Understanding NMOS operating regions and current-voltage relationship.

---

## 2. PMOS Device Characterization

Studied:
- PMOS threshold behavior
- Current conduction
- Source-drain characteristics
- Symmetry comparison with NMOS

Key Learning:
Understanding complementary MOS behavior.

---

## 3. Common Source Amplifier

Designed and analyzed:
- Voltage gain
- Phase inversion
- Biasing conditions
- AC response

Key Learning:
Fundamental analog amplification stage.

---

## 4. Common Gate Amplifier

Implemented:
- Low input impedance configuration
- Current buffering
- Frequency behavior

Key Learning:
Useful for high-frequency applications.

---

## 5. Source Follower Amplifier

Studied:
- Voltage buffering
- High input impedance
- Low output impedance

Key Learning:
Voltage buffering applications.

---

## 6. Cascode Amplifier

Designed:
- Improved gain
- Higher output resistance
- Better bandwidth

Key Learning:
Gain boosting and channel length modulation reduction.

---

## 7. Current Mirror

Implemented:
- Bias current generation
- Current replication
- Device matching concepts

Key Learning:
Biasing network fundamentals.

---

## 8. Differential Amplifier

Designed:
- Differential input amplification
- Common mode rejection
- Tail current source operation

Key Learning:
Core building block of operational amplifiers.

---

## 9. Single Stage Differential Amplifier

Analyzed:
- Gain performance
- Differential output
- Load balancing

Key Learning:
Single stage analog signal processing.

---

## 10. Two Stage Differential Amplifier

Implemented:
- Higher gain architecture
- Cascaded differential stages
- Stability understanding

Key Learning:
Foundation for op-amp architecture.

---

# Key Concepts Covered

- MOSFET Physics
- Device Biasing
- Small Signal Analysis
- Gain Calculation
- Frequency Response
- Differential Signaling
- Current Steering
- Analog Layout Matching
- Common Centroid Techniques
- Parasitic Aware Design
- Post Layout Validation

---

# Layout Design Methodologies

Special focus was given to:

- Proper transistor matching
- Symmetrical layout practices
- Reduced mismatch
- Reduced parasitic coupling
- Minimum routing resistance
- Layout compaction
- Proper well and substrate connections

These are critical in real analog chip design.

---

# Verification Performed

## DRC Verification
Ensured:
- Width rules
- Spacing rules
- Enclosure rules
- Via rules

## LVS Verification
Verified:
- Net connectivity
- Device count
- Device sizing

## Extraction Verification
Validated:
- Parasitic capacitance impact
- Delay variation
- Gain degradation

---

# Skills Demonstrated

## Analog Design Skills
- CMOS Analog Design
- Biasing Techniques
- Amplifier Design
- Differential Pair Design
- Current Mirror Design

## Physical Verification Skills
- Layout Design
- DRC
- LVS
- Extraction

## Simulation Skills
- DC Analysis
- AC Analysis
- Transient Analysis
- Operating Point Analysis

---

# Repository Contents

- `Analog_VLSI_Design_Report.pdf` → Complete analog VLSI experimental documentation

---

# Industrial Relevance

The concepts demonstrated in this repository are directly applicable in:

- Analog IC Design
- Mixed Signal Design
- PLL Design
- ADC/DAC Design
- Power Management ICs
- Sensor Interfaces
- RF Front End Design
- Memory Peripheral Circuits

---

# Conclusion

This repository reflects practical hands-on implementation of full custom analog VLSI design flow, starting from transistor-level design to fabrication-ready layout generation.

It demonstrates strong understanding of analog fundamentals, circuit behavior, layout verification, and post-layout performance analysis, forming a solid foundation for advanced semiconductor design roles.
