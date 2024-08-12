# Example text for manuscripts <!-- omit in toc -->

This document contains example text for a data-dependent proteomics run performed in the BMS. 

## Method text

MS Data Acquisition

DDA-MS analysis was carried out on a Thermo QExactive instrument interfaced to a Thermo Vanquish liquid chromatography (LC) system. For analysis, samples separated by an analytical column (2.1mm x 150mm, 2.2µm Acclaim C18). The gradient ramped from an initial starting condition of 2% mobile phase B (100% acetonitrile, 0.1% formic acid) to 15% B over 8-minutes, 55% B over 6-minutes, with column rinsing and equilibration using an additional 6-minutes (20-minute total run time, mobile phase A = 0.1% formic acid in water). Data acquisition on the QExactive utilized a standard data-dependent acquisition scheme. Specifically, the QExactive was globally set to use a positive ion spray voltage of 3400V, an ion transfer tube temperature of 320°C, sheath gas of 32, aux gas of 5, and a default charge state of 1. MS1 survey scans covered a mass range of 100-350m/z at a resolution of 17,500 with an automatic gain control (AGC) target of 1e6 and the injection time set to 100ms maximum. Precursors for tandem MS/MS (MS2) analysis were selected using charge state filtering (1z), dynamic exclusion (3-second duration, exclude isotopes ON), peptide match off, and an intensity threshold of 1.9e5 (8e3 minimum AGC target). MS2 scans were carried out in the Orbitrap at a resolution of 17,500 using a higher-energy collision dissociation setting of 18% (CE), an AGC target of 1e6, injection time set to 42ms, and an isolation window setting of 4m/z. The total allowable MS2 cycle a loop count of 4. MS1 data were acquired in profile mode, and MS2 in centroid.
 


