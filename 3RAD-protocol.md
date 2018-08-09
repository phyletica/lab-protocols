# 3RAD Protocol
### 1. Restriction Digest and Adapter Ligation
Note: ligation must be performed immediately following restriction digest

#### Restriction Digest
##### Reagents
- 20,000 &cap;/mL New England BioLabs Restriction Enzymes
- 10X New England BioLabs CutSmart Buffer
- 2.5 &micro;M Read 1 and Read 2 3RAD Adapters

##### Final Concentrations
In 15 &micro;L:
- 20-100 ng Sample DNA
- 1X Cutsmart Buffer
- 10 &#8746; of read 1 restriction enzyme
- 10 &#8746; of read 2 restriction enzyme
- 10 &#8746; of adapter dimer restriction enzyme
- 0.33 &micro;M read 1 adapter
- 0.33 &micro;M read 2 adapter

##### Procedure
1. Pipette 5 &micro;L of DNA at a concentrations of 4-20 ng/&micro;L onto 96 well plate.
2. Prepare enzyme digestion master mix.
3. Add 6 &micro;L master mix to each sample.
4. Add 2 &micro;L of 2.5 &micro;M each adapter.
5. Incubate samples at:
    - No heated lid
    - 37 &deg;C for 1 hour

| Enzyme Digestion Master Mix   | 1X            | 116X           |
| ----------------------------- | ------------- | -------------- |
| 10X CutSmart Buffer           | 1.5 &micro;L  | 174 &micro;L   |
| H<sub>2</sub>O                | 3.0 &micro;L  | 348 &micro;L   |
| Enzyme 1 20 &#8746;/&micro;L  | 0.5 &micro;L  | 58 &micro;L    |
| Enzyme 2 20 &#8746;/&micro;L  | 0.5 &micro;L  | 58 &micro;L    |
| Enzyme 3 20 &#8746;/&micro;L  | 0.5 &micro;L  | 58 &micro;L    |
| Total volume                  | 6 &micro;L    | 696 &micro;L   |

#### Ligation
##### Reagents
- 400,000 &#8746;/mL New England BioLabs T4 DNA Ligase
- 10X New England Biolabs Ligase Buffer
- Promega 10 mM rATP

##### Final Concentrations
In 20 &micro;L:
- 100 &#8746; of T4 DNA ligase
- 0.25X ligase buffer
- 0.75 mM rATP

##### Procedure
1. Prepare ligation master mix.
2. Add 5 &micro;L ligation master mix to each sample.
3. Incubate samples at:
    - No heated lid
    - 2 cycles of:
        - 22 &deg;C for 20:00
        - 37 &deg;C for 10:00
    - 80 &deg;C for 20:00

| Ligation Master Mix          | 1X            | 106X           |
| ---------------------------- | ------------- | -------------- |
| H<sub>2</sub>O               | 2.75 &micro;L | 291.5 &micro;L |
| 10X Ligase Buffer            | 0.5 &micro;L  | 53 &micro;L    |
| 10 mM rATP                   | 1.5 &micro;L  | 159 &micro;L   |
| Ligase 400,000 &cup;/mL      | 0.25 &micro;L | 26.5 &micro;L  |
| Total volume                 | 5 &micro;L    | 530 &micro;L   |

### 2. Bead Cleanup
1. Pool 5 &micro;L of each sample
2. Mix pooled sample with 1X Speedbeads and briefly vortex.
3. Allow sample to sit for 1 minute.
4. Place sample on magnet stand until solution is completely clear and magnets have been drawn to the side of the tube.
5. Carefully pipette solution from tube and discard.
6. Wash sample twice with 500 &micro;L of 70% ETOH
    1. Add 500 &micro;L of 70% ETOH to tube and let sit for 1 minute.
    2. Carefully pipette ETOH from tube.
    3. Repeat once.
    4. Use toothpick to remove remaining drops of ETOH and let stand until no ETOH remains.
7. Re-suspend in initial volume of [TLE Buffer Solution](tle.md)
- Note: Maybe suspend this in smaller volume?

### 3. One Cycle PCR With iTru5-8N Primer
##### Reagents
- Kapa HiFI PCR Kit
- 5 &micro;M iTru5 Primer

##### Final Concentrations
In 50 &micro;L:
- 5 &micro;L of pooled DNA samples
- 1X KAPA HiFi Fidelity Buffer
- 0.3 &micro;M iTru5 Primer
- 0.3 mM each dNTP
- 1 &#8746; of KAPA HiFi Hotstart DNA Polymerase

##### Procedure
1. Prepare PCR master mix.
2. Add 45 &micro;L master mix to six 0.2 mL PCR tubes
3. Add 5 &micro;L pooled DNA to each of the six PCR tubes
4. Incubate samples at:
    - 95 &deg;C for 2:00
    - 98 &deg;C for 0:20
    - 61 &deg;C for 0:15
    - 72 &deg;C for 5:00

| PCR Master Mix             | 1X            | 6.5X            |
| -------------------------- | ------------- | --------------- |
| H<sub>2</sub>O             | 29.5 &micro;L | 191.75 &micro;L |
| 5X Kapa HiFi Buffer        | 10 &micro;L   | 65 &micro;L     |
| 5 &micro;M iTru5-8N Primer | 3 &micro;L    | 19.5 &micro;L   |
| 10mM dNTP                  | 1.5 &micro;L  | 9.75 &micro;L   |
| KAPA Hifi Polymerase       | 1.0 &micro;L  | 6.5 &micro;L    |
| Total volume               | 45 &micro;L   | 292.5           |

### 4. Bead Cleanup
1. Pool iTru5-8N PCR product
2. Mix pooled sample with 2X Speedbeads and briefly vortex.
3. Allow sample to sit for 1 minute.
4. Place sample on magnet stand until solution is completely clear and magnets have been drawn to the side of the tube.
5. Carefully pipette solution from tube and discard.
6. Wash sample twice with 500 &micro;L of 70% ETOH
    1. Add 500 &micro;L of 70% ETOH to tube and let sit for 1 minute.
    2. Carefully pipette ETOH from tube.
    3. Repeat once.
    4. Use toothpick to remove remaining drops of ETOH and let stand until no ETOH remains.
7. Re-suspend in 35 &micro;L [TLE Buffer Solution](tle.md)

### 5. Two Primer Amplification With P5 & iTru7 Primers
##### Reagents
- Kapa HiFI PCR Kit
- 5 &micro;M iTru7 Primer
- 5 &micro;M P5 Primer

##### Final Concentrations
In 50 &micro;L:
- 5 &micro;L of pooled DNA samples
- 1X KAPA HiFi Fidelity Buffer
- 0.3 &micro;M iTru7 Primer
- 0.3 &micro;M P5 Primer
- 0.3 mM each dNTP
- 1 &#8746; of KAPA HiFi Hotstart DNA Polymerase

##### Procedure
1. Prepare PCR master mix.
2. Add 45 &micro;L master mix to six 0.2 mL PCR tubes
3. Add 5 &micro;L pooled DNA to each of the six PCR tubes
4. Incubate samples at:
    - 95 &deg;C for 2:00
    - 6 cycles of:
        - 98 &deg;C for 0:20
        - 61 &deg;C for 0:15
        - 72 &deg;C for 0:30
    - 72 &deg;C 5:00

| PCR Master Mix             | 1X            | 6.5X            |
| -------------------------- | ------------- | --------------- |
| H<sub>2</sub>O             | 26.5 &micro;L | 172.25 &micro;L |
| 5X Kapa HiFi Buffer        | 10 &micro;L   | 65 &micro;L     |
| 5 &micro;M iTru7 Primer    | 3 &micro;L    | 19.5 &micro;L   |
| 5 &micro;M P5 Primer       | 3 &micro;L    | 19.5 &micro;L   |
| 10mM dNTP                  | 1.5 &micro;L  | 9.75 &micro;L   |
| KAPA Hifi Polymerase       | 1.0 &micro;L  | 6.5 &micro;L    |
| Total volume               | 45 &micro;L   | 292.5           |

### 6. Bead Cleanup
1. Pool P5-iTru7 PCR products into single tube
2. Mix pooled sample with 2X Speedbeads and briefly vortex.
3. Allow sample to sit for 1 minute.
4. Place sample on magnet stand until solution is completely clear and magnets have been drawn to the side of the tube.
5. Carefully pipette solution from tube and discard.
6. Wash sample twice with 500 &micro;L of 70% ETOH
    1. Add 500 &micro;L of 70% ETOH to tube and let sit for 1 minute.
    2. Carefully pipette ETOH from tube.
    3. Repeat once.
    4. Use toothpick to remove remaining drops of ETOH and let stand until no ETOH remains.
7. Re-suspend in 35 &micro;L [TLE Buffer Solution](tle.md)

### 7. Size Selection
##### Procedure
Size select DNA with BluePippin
<!-- 1. Add 10 &micro;L internal size standard to 30 &micro;L of sample -->

### 8. Final Amplification with P5 and P7 Primers
##### Reagents
- Kapa HiFI PCR Kit
- 5 &micro;M P5 Primer
- 5 &micro;M P7 Primer

##### Final Concentrations
In 50 &micro;L:
- 5 &micro;L of pooled DNA samples
- 1X KAPA HiFi Fidelity Buffer
- 0.3 &micro;M P5 Primer
- 0.3 &micro;M P7 Primer
- 0.3 mM each dNTP
- 1 &#8746; of KAPA HiFi Hotstart DNA Polymerase

##### Procedure
1. Prepare PCR master mix.
2. Add 45 &micro;L master mix to six 0.2 mL PCR tubes
3. Add 5 &micro;L pooled DNA to each of the six PCR tubes
4. Incubate samples at:
    - 95 &deg;C for 2:00
    - 12 cycles of:
        - 98 &deg;C for 0:20
        - 61 &deg;C for 0:15
        - 72 &deg;C for 0:45
    - 72 &deg;C 5:00

| PCR Master Mix             | 1X            | 6.5X            |
| -------------------------- | ------------- | --------------- |
| H<sub>2</sub>O             | 26.5 &micro;L | 172.25 &micro;L |
| 5X Kapa HiFi Buffer        | 10 &micro;L   | 65 &micro;L     |
| 5 &micro;M P5 Primer       | 3 &micro;L    | 19.5 &micro;L   |
| 5 &micro;M P7 Primer       | 3 &micro;L    | 19.5 &micro;L   |
| 10mM dNTP                  | 1.5 &micro;L  | 9.75 &micro;L   |
| KAPA Hifi Polymerase       | 1.0 &micro;L  | 6.5 &micro;L    |
| Total volume               | 45 &micro;L   | 292.5           |

### 9. Bead Cleanup
1. Pool P5-P7 PCR products into single tube
2. Mix pooled sample with 1X Speedbeads and briefly vortex.
3. Allow sample to sit for 1 minute.
4. Place sample on magnet stand until solution is completely clear and magnets have been drawn to the side of the tube.
5. Carefully remove pipette solution from tube.
6. Wash sample twice with 500 &micro;L of 70% ETOH
    1. Add 500 &micro;L of 70% ETOH to tube and let sit for 1 minute.
    2. Carefully pipette ETOH from tube.
    3. Repeat once.
    4. Use toothpick to remove remaining drops of ETOH and let stand until no ETOH remains.
7. Re-suspend in 35 &micro;L 10mM [Tris-HCl Buffer Solution](tris-hcl.md)

<!-- ### 10. Sample Submission
Sample Submission to UGA sequencing facility

Provide ≥20 µl of product at a 10 nM concentration in 10 mM Tris, pH 8

[nM DNA] = DNA concentration (ng/&micro;L) * 1e6 (&micro;L/L) / (Sample fragment size in bp * 656.4 (g/mole))

Should be ~4ng/uL -->
