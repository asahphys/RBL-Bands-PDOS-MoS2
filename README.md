# MoS₂ Band Structure and PDOS (DFT – Quantum ESPRESSO)

This repository contains **Density Functional Theory (DFT)** results for **monolayer MoS₂**, focusing on **electronic band structure** and **projected density of states (PDOS)** calculations performed using **Quantum ESPRESSO**.

The data and figures were generated as part of an academic computational study and are shared for **documentation, learning, and portfolio purposes**.

---

## 📁 Repository

```text
.
├── bands/
│   ├── MoS2.bands.in          # Input file for band structure calculation
│   ├── MoS2.bands.out         # Output file from Quantum ESPRESSO
│   └── band_structure.png    # Final band structure plot
│
├── data/
│   ├── MoS2_bands.csv         # Extracted band energy data (CSV format)
│   └── MoS2_pdos_total.csv   # Total density of states data (CSV format)
│
├── pdos/
│   ├── .lowdin                # Lowdin charge projection file
│   ├── MoS2_pdos.png          # PDOS plot
│   ├── mos2.pdos_atm#1(Mo)_wfc#2(s)
│   ├── mos2.pdos_atm#1(Mo)_wfc#3(p)
│   ├── mos2.pdos_atm#1(Mo)_wfc#4(d)
│   └── mos2.pdos_atm#2(S)_wfc#1(s)
│
└── README.md
