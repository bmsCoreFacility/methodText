# Example text for manuscripts <!-- omit in toc -->

This document contains example text for a targeted metabolomics run performed in the BMS. 

## Method text

Mass spectrometry analysis

Optimal mass spectrometer (MS) parameters for methoctramine detection were determined via direct-infusion of a prepared standard. Only a single fragment ion originating from the doubly-charged precursor was observed to be reliably produced by methoctramine in positive mode (Q1 mass = 292.0, Q3 mass = 121.1). MS voltages for detection and chromatography conditions were optimized using this precursor-fragment pair. For sample extraction, the starting sample material was diluted to 100uL with water prior to the addition of 500uL of ice-cold 50/50 methanol/ethanol containing an internal standard (12.5uM isotopically labeled threonine, final concentration, Q1 = 125.1, Q3 = 60.1). Mixtures were incubated at -20C for 1-hour, centrifuged for 5-minutes at 12,000g, and 480uL of supernatant recovered. Supernatant material was concentrated in a SpeedVac centrifuge and reconstituted in 80uL of water prior to MS analysis. Targeted mass spectrometry analysis was carried out on a QTRAP5500 instrument interfaced to an Agilent 1290 Infinity II liquid chromatography (LC) system. For analysis, samples were directly separated by an analytical column (2.1mm x 50mm, Kinetix F5 1.7um, Phenomenex) at a flow rate of 0.4mL/min. For analyte elution he gradient held at an initial starting condition of 2% mobile phase B (99.9% acetonitrile, 0.1% formic acid) for 2-minutes before ramping to 60% B over 0.9 minutes, holding at 60% B for 3.1-minutes, raming to 90% B over 0.5-minutes and holding for 1-minute, ramping to 2% B in 0.25-minutes, with a final equilibration at 2% B for 2.25-minutes (total run time of 10-minutes, mobile phase A = 0.1% formic acid in water). Data acquisition on the QTRAP5500 utilized a targeted selected reaction monitoring (SRM) acquisition scheme. Specifically, the QTRAP was globally set to use a positive ion spray voltage of 5500, collision gas of 5, curtain gas of 25, temperature of 450, gas 1 of 45, and a gas 2 setting of 50. The declustering potential was globally set to 60, entrance potential to 10, and cell exit potential to 10. Collision energy values were set for each SRM transition (methoctramine = 21V, threonine = 21V). All SRM transitions were set to a scan duration setting of 100msec, yielding a total cycle time of 0.21 seconds. The resulting data were analyzed using Skyline software (version 24.1.0.199) with additional downstream processing in R.
