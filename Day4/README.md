# Day 4 - CMOS Inverter Layout using Magic (Sky130)

## Objective
To design, view, and analyze a CMOS inverter layout using Magic tool and extract its SPICE netlist for verification.

---

## Tools Used
- Magic VLSI Layout Tool
- Sky130 PDK
- ngspice

---

## Procedure

### 1. Opening Layout in Magic
The inverter layout was opened using:
---

### 2. Layout Observation
The CMOS inverter consists of:
- PMOS (pull-up network)
- NMOS (pull-down network)
- Input (A)
- Output (Y)
- Power (VPWR)
- Ground (VGND)

---

### 3. Device Identification
Using Magic commands:
- `what` → identified selected device layers
- Verified PMOS and NMOS regions

---

### 4. Extraction Process
Commands used:
This generated:
- sky130_inv.ext
- sky130_inv.spice

---

### 5. Observations from SPICE Netlist
- CMOS inverter uses sky130_fd_pr__pfet_01v8 (PMOS)
- CMOS inverter uses sky130_fd_pr__nfet_01v8 (NMOS)
- Proper connectivity between VDD, GND, input and output verified

---

## Result
Successfully extracted and verified CMOS inverter layout and SPICE netlist using Magic.

---

## Conclusion
This experiment demonstrates the layout-level implementation of a CMOS inverter and its verification through SPICE extraction.
