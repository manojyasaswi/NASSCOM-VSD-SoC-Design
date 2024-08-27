# NASSCOM-VSD-SoC-Design
This is a workshop offered by VLSI System Design, focused on RTL to GDSII flow of ICs using open-source tools and PDKs (Skywater 130).

# Day 1 Lab
Synthesis Steps:

```bash
./flow.tcl -interactive
package require openlane 0.9
prep -design picorv32a
run_synthesis
```
### Synthesis Successful using openLANE interactive
<img width="1470" alt="Synthesis run using Open Lane interactive" src="figures/D1-synthesis_successful.png">


### Synthesized RTL
<img width="1470" alt="Synthesized RTL" src="figures/D1-synthesized-rtl.png">

### Synthesis Reports

Flop Ratio = No. of cells / No. of D FFs
=> Flop Ratio = 14876/1613 = 9.2
<img width="1470" alt="Synthesized RTL" src="figures/D1-sysnthesis-reports.png">
