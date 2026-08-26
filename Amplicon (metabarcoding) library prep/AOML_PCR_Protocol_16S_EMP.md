

# NOAA/AOML PCR Protocol for 16S rRNA Amplicon Sequencing (EMP 515F-806R) 

## PROTOCOL INFORMATION

### Minimum Information about an Omics Protocol (MIOP)

-   MIOP terms are listed in the YAML frontmatter of this page.
-   See <https://github.com/BeBOP-OBON/miop/blob/main/model/schema/terms.yaml> for list and definitions.

### Making eDNA FAIR (FAIRe)

-   FAIRe terms are listed in the YAML frontmatter of this page.
-   See <https://fair-edna.github.io/download.html> for the FAIRe checklist and more information.
-   See <https://fair-edna.github.io/guidelines.html#missing-values> for guidelines on missing values that can be used for missing FAIRe or MIOP terms.

### Authors

| PREPARED BY | AFFILIATION | ORCID | DATE |
|------------------|------------------|------------------|------------------|
| Stephanie Rosales | NOAA/AOML, UM/ CIMAS | <https://orcid.org/0000-0002-2678-9287> | 2026-08-10 |

#### Internal Protocols

| PROTOCOL NAME | LINK | VERSION | RELEASE DATE |
|------------------|------------------|------------------|------------------|
| AOML 'Omics Protocols | <https://github.com/aomlomics/protocols> | not applicable | ongoing |
| NOAA 'Omics Metabarcoding Assays | <https://github.com/NOAA-Omics/noaa-omics-metabarcoding-assays> | not applicable | ongoing |

#### External Protocols

| PROTOCOL NAME | LINK | ISSUER / AUTHOR | ACCESS DATE |
|------------------|------------------|------------------|------------------|
| Earth Microbiome Project 16S Protocol | <http://press.igsb.anl.gov/earthmicrobiome/protocols-and-standards/16s/> | Earth Microbiome Project | 2026-08-11 |
| Invitrogen Qubit 1X dsDNA HS Assay Kits User Guide | <https://assets.thermofisher.com/TFS-Assets/LSG/manuals/MAN0017455_Qubit_1X_dsDNA_HS_Assay_Kit_UG.pdf> | ThermoFisher Scientific | 2026-08-11 |
| Mag-Bind TotalPure NGS | ([OmegaMagManualMF27.0002.M1378 v2.1.pdf](https://drive.google.com/open?id=1KdSkzh9ts_fvbzi_0J8Q0XaqZh71bOqh) | Omega | 2026-08-11 |

### Protocol Revision Record

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
|---------|--------------|--------------------------|
| 1.0.0   | 2026-08-12   | Initial release          |

### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
|----|----|
| NOAA | National Oceanic and Atmospheric Administration |
| AOML | Atlantic Oceanographic and Meteorological Laboratory |
| UM | University of Miami |
| CIMAS | Cooperative Institute for Marine and Atmospheric Studies |
| PCR | Polymerase chain reaction |
| EMP | Earth Microbiome Project |
| eDNA | environmental DNA |
| NTC | No template control |
| EtOH | Ethanol |

### Glossary

| SPECIALISED TERM | DEFINITION |
|------------------------------------|------------------------------------|
| Extraction Blank | A type of negative control to confirm there is no contamination during DNA extractions. Normally an empty filter is extracted and PCR amplified alongside other samples |
| No Template Control | A type of negative control during PCR to confirm there is no contamination during the PCR process. Normally nuclease-free water is run in place of DNA on a PCR |

## BACKGROUND

### Summary

This protocol describes steps for performing PCR for the prokaryotic 16S rRNA V4 hypervariable marker gene region using environmental DNA at NOAA's AOML. This protocol follows the Earth Microbiome Project (EMP) guidelines for 16S rRNA amplicon sequencing using barcoded 515F and 806R primers.
Complete downstream QC, normalization, pooling, and sequencing preparation procedures are integrated.
For more details, refer to:http://press.igsb.anl.gov/earthmicrobiome/protocols-and-standards/16s/

### Method description and rationale

This protocol is used for PCR amplifying the 16S rRNA V4 marker gene region of environmental DNA.
Illumina adapters, pads, linkers, and Golay barcodes are incorporated directly into the primers for single-step barcoded library generation.

### Spatial coverage and environment(s) of relevance

This protocol can be used to amplify the 16S V4 marker gene region of any environmental DNA sample.

## PERSONNEL REQUIRED

One person with molecular biology experience.

### Safety

This protocol involves chemical, thermal, and electrical hazards.
Standard laboratory PPE (gloves, lab coat, safety glasses) should be worn at all times.
Handle ethanol, bleach, and nucleic acid gel stain according to institutional safety procedures and SDS requirements.
Do not use Ethidium bromide.
Use an autoclave glove when handling hot molten agarose, allow agarose to cool to 60°C prior to tray casting to prevent tray warping/cracking, and follow safety protocols for UV light visualization.
Do not handle the electrophoresis chamber while the power supply is energized.

### Training requirements

Basic molecular biology training is sufficient for this protocol including sterile technique, pipetting small volumes, and programming/running PCR thermal cyclers.

### Time needed to execute the procedure

Protocol takes about 4 hours (240 minutes) including thermal cycler run time.

## EQUIPMENT

For 96-well Plate:

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
|---------------|---------------|---------------|---------------|---------------|
| **Durable equipment** |  |  |  |  |
| 100-1000 µL Pipette | Eppendorf Research Plus Adjustable-Volume Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| 10-100 µL Pipette | Eppendorf Research Plus Adjustable-Volume Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| 0.1-2.5 µL Pipette | Eppendorf Research Plus Adjustable-Volume Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| Multichannel Pipette | Eppendorf Research Plus 8-Channel Pipette | Eppendorf | 1 | Used for 96-well plate aliquoting |
| Thermal Cycler | Mastercycler Nexus Thermal Cycler | Eppendorf | 1 | Can be substituted with generic |
| PCR Hood | PCR Laminar Flow Hood | Generic Brand | 1 | Used for PCR prep |
| Microwave | Generic Microwave | Generic Brand | 1 | Used for melting agarose |
| Flask | Erlenmeyer Flask | Generic Brand | 1 | Used for mixing agarose solution |
| Thermometer | Laboratory Thermometer | any brand | 1 | Used for monitoring agarose temperature |
| Stir bars | Magnetic Stir Bar | any brand | 1 | Used for mixing agarose gel solution |
| Stir plate | Magnetic Stir Plate | any brand | 1 | Used for mixing agarose gel solution |
| Graduated Cylinder | 500 mL Graduated Cylinder | Generic Brand | 1 | Used for measuring TBE or TAE buffer |
| Gel Tray & Box | Gel Electrophoresis Box and Casting Tray | Generic Brand | 1 | Can be substituted with generic |
| Gel Combs | Gel Electrophoresis Combs | Generic Brand | 2 | Can be substituted with generic |
| Power Supply | Voltage Source / Power Supply | Generic Brand | 1 | Electrophoresis power supply |
| UV Light Source | UV Transilluminator / Gel Imager | Generic Brand | 1 | Used for gel visualization |
| Autoclave Glove | Heat-resistant Glove | Generic Brand | 1 | Worn when handling hot flask |
| **Consumable equipment** |  |  |  |  |
| 5mL Master Mix Tube | 5 mL Polypropylene Tube | Generic | 1 | Size depends on total master mix volume |
| Platinum™ Hot Start PCR Master Mix (2X) | Platinum Hot Start PCR Master Mix (2X) | ThermoFisher | 2.0 | (mL) Cat. no. 13000014 |
| 515F Forward Primer (10 µM) | 515F Barcoded Forward Primer Plate/Tube | IDT / Synthesized | 100 | (µL) Diluted to 10 µM stock |
| 806R Reverse Primer (10 µM) | 806R Reverse Primer Tube | IDT / Synthesized | 100 | (µL) Diluted to 10 µM stock |
| Long 10 µL Filter Tips | Extended-length 10 µL Pipette Tips | Generic | 2 | Needed to reach deep primer wells |
| Reagent Reservoir | Multichannel Reagent Reservoir | Generic | 2 | Used for multichannel pipetting |
| Gloves | Nitrile Gloves, Exam Grade, Powder-free | ULINE | 1 | (box) Can be substituted with generic |
| Kim Wipes | KimWipe Delicate Task Wipers | KimTech | 1 | (box) Can be substituted with generic |
| 96-well PCR Plate | 96-well Thin-wall PCR Plate | Generic | 2 |  |
| PCR Plate Seal | Silverseal Aluminum / Adhesive Seal | USA Scientific | 2 |  |
| 200 µL Filter Tips | Pipette Tips, 200 µL | Generic | 2 | (boxes) Can be substituted with generic |
| Parafilm | Parafilm M Lab Film | Generic | 1 | (roll) Used for loading dye prep |
| **Chemicals** |  |  |  |  |
| Bleach | DNA Decontaminant / Bleach Solution | any | 1 | Bottle for hood sterilization |
| EtOH | Ethanol | Generic Brand | 1 | (wash bottle) Molecular grade ethanol |
| DI water | Deionized water | Generic | 900 | (mL) |
| PCR-grade water | Molecular Biology Grade Water | ThermoFisher / Fisher | 3.0 | (mL) |
| TAE or TBE Buffer (1X) | 1X TAE or TBE Buffer | Thermo Scientific | 1.0 | (L) Buffer for gel and box |
| Agarose | Agarose LE, Molecular Biology Grade | Thermo Scientific | 4.5 | (g) |
| Nucleic Acid Stain | GelRed or equivalent Nucleic Acid Stain | Biotium / Invitrogen | 30 | (µL) Light sensitive - store in dark |
| Gel Loading Dye | DNA Gel Loading Dye (6X) | Thermo Scientific | 100 | (µL per plate) |
| 100bp DNA Ladder | GeneRuler 100 bp DNA Ladder | Thermo Scientific | 10 | (µL per gel row) |
| **Quantification Reagents** |  |  |  |  |
| Qubit dsDNA HS Assay | Qubit dsDNA HS Quantification Assay Kit | ThermoFisher | 1 | (kit) |
| Qubit Assay Tubes | 0.5 mL thin-walled polypropylene tubes | ThermoFisher | 98 | Required for Qubit fluorometer |

## STANDARD OPERATING PROCEDURE

### Protocol

#### Preparation

1.  Remove PCR reagents from -20°C storage and allow them to thaw on ice or at room temperature.
2.  Remove PCR primers from -80°C storage to thaw at 4°C and keep cool during the entire process to prevent primer degradation.
3.  Wipe down the PCR hood thoroughly with bleach and ethanol.
4.  Place disposables such as tubes, plates, plate sealers, and PCR-grade water into the PCR hood and sterilize under UV light for 20 minutes.
5.  Once fully thawed, vortex the PCR reagents and spin down briefly.
6.  Very gently vortex the primers and spin down the primer plate in a plate centrifuge to avoid cross-contamination between wells.
7.  Keep all reagents cool or on ice throughout the duration of the protocol.

#### PCR Setup and Amplification

1.  Prepare the PCR master mix in a 5 mL tube according to the table below. Make enough master mix for all samples, a no template control (NTC), and 10% extra volume to account for pipetting loss.
2.  **Do not** add template DNA or barcoded forward primers (515F) to the master mix; add them individually to each well.

| Component | Volume per Rxn (50 µL) | Volume per Rxn (25 µL)\* | Order to Add |
|------------------|------------------|------------------|------------------|
| PCR-grade water | 26.0 µL | 13.0 µL | 1 |
| Platinum™ Hot Start PCR Master Mix (2X) | 20.0 µL | 10.0 µL | 2 |
| Reverse primer (806R, 10 µM) | 1.0 µL | 0.5 µL | 3 |
| Barcoded Forward primer (515F, 10 µM) | 1.0 µL | 0.5 µL | 4 (add to well) |
| Template DNA | 2.0 µL | 1.0 µL | 5 (add to well) |
| **Total Reaction Volume** | **50.0 µL** | **25.0 µL** |  |

*\*Note: Reactions can be scaled to 25 µL, but pipetting 0.5 µL of primer may be difficult, especially when using a multichannel pipette.*

| PCR Primer Name | Direction | Sequence (5’ -\> 3’) | Sequence Details / Adapter Construct |
|------------------|------------------|------------------|------------------|
| 515F | Forward | `GTGYCAGCMGCCGCGGTAA` | `AATGATACGGCGACCACCGAGATCT` (Illumina 5' adapter) + `ACACGCT` (Pad) + `XXXXXXXXXXXX` (12 bp Golay barcode) + `TATGGTAATT` (Linker) + `GTGYCAGCMGCCGCGGTAA` (515F) |
| 806R | Reverse | `GGACTACNVGGGTWTCTAAT` | `CAAGCAGAAGACGGCATACGAGAT` (3' Illumina rev comp adapter) + `AGTCAGCCAG` (Pad) + `CC` (Linker) + `GGACTACNVGGGTWTCTAAT` (806R) |

3.  Once the master mix reagents are combined, mix gently and spin down to collect the mixture and remove air bubbles.
4.  For 50 µL total reactions, aliquot 47.0 µL of master mix into each designated tube or well of a 96-well plate.
5.  Add 1.0 µL of unique barcoded 515F forward primer (10 µM) to each individual well using long 10 µL filter tips.
6.  Add 2.0 µL of template DNA (or PCR-grade water for NTC) to respective wells.
7.  Seal the plate securely, mix gently, and spin down in a plate centrifuge. Examine wells to ensure all bubbles are removed.
8.  Load samples into the thermocycler and execute the following program:

| PCR Step             | Temperature | Duration | Repetitions |
|----------------------|-------------|----------|-------------|
| Initial Denaturation | 94°C        | 3 min    | 1x          |
| Denaturation         | 94°C        | 45 s     | 35x         |
| Annealing            | 50°C        | 60 s     | 35x         |
| Extension            | 72°C        | 90 s     | 35x         |
| Final Extension      | 72°C        | 10 min   | 1x          |
| Hold                 | 4°C         | ∞        | Hold        |

#### Quality Control and PCR Clean-Up

### 1.5% Agarose Gel Electrophoresis

**Purpose:** Verify the presence and approximate size of the target amplicon (\~300–350 bp) following PCR amplification.

#### A. Prepare 1.5% Agarose Gel Solution on 23 cm wide x 14 cm long

1.  Measure 4.5 g of agarose powder on a laboratory scale.
2.  Measure 300 mL of 1X TAE or 1X TBE buffer using a graduated cylinder and transfer into a microwavable Erlenmeyer flask.
3.  Add the agarose powder to the buffer in the flask and swirl to mix.
4.  Microwave for 3 minutes in short pulses, swirling the flask between pulses until the agarose is completely dissolved and clear. If solution evaporates, add DI water to restore volume.
5.  Allow the agarose solution to cool to \~60°C by placing the flask on a magnetic stir plate with a stir bar, monitoring with a thermometer.
6.  Add 30 µL of GelRed (or equivalent nucleic acid stain) to the cooled solution and swirl gently.
7.  Insert well combs into the gel tray and pour the agarose solution slowly to avoid creating bubbles.
8.  Allow the gel to solidify at room temperature for 20–30 minutes (or at 4°C for 10–15 minutes).

#### B. Set Up Electrophoresis Chamber and Load Samples

1.  Place the solidified agarose gel into the electrophoresis gel box.
2.  Fill the gel box with 1X TAE (or TBE) buffer until the gel is completely submerged. *Note: Use the exact same buffer in the gel box as used in the gel matrix.*
3.  Prepare loading dye on a piece of Parafilm by dispensing 1 µL of 6X loading dye per sample position.
4.  Combine 4 µL of each PCR product with 1 µL of loading dye on the Parafilm and mix by pipetting.
5.  Load 5 µL of 100 bp DNA ladder into the center column of each row.
6.  Carefully load 5 µL of each prepared sample into alternating wells using a multichannel pipette.

#### C. Run and Visualize Gel

1.  Attach the lid, connect power leads, and run the gel at 70 V for approximately 30 minutes (or until the indicator dye migrates 70% through the gel).
2.  Remove the gel and visualize using a UV gel imager.
3.  Confirm a target band at \~300–350 bp and confirm that the NTC shows no amplification band.
4.  Capture and record an annotated gel image.

#### Downstream QC, Normalization, Pooling, and Sequencing Preparation

1.  Purify pooled PCR products using Mag-Bind TotalPure NGS according to the manufacturer’s protocol.
2.  Quantify clean PCR products individually using the Qubit dsDNA HS Assay Kit according to manufacturer instructions.
3.  Calculate sample dilutions and normalize all samples to 4.0 nM concentration using standard calculation templates.
4.  Pool 5.0 µL from each normalized 4.0 nM sample into a single 1.5 mL microcentrifuge tube.
5.  Quantify the final pooled library in triplicate using the Qubit dsDNA HS Assay Kit.
6.  Prepare a thoroughly mixed aliquot of the pooled library for sequencing, along with 10 µL of custom sequencing primers at 100 µM concentration as detailed below:

| Sequencing Primer Role | Field Descriptions / Structure | Sequence (5’ -\> 3’) |
|------------------------|------------------------|------------------------|
| Read 1 Sequencing Primer | Forward Pad + Linker + 515F | `TATGGTAATT GT GTGYCAGCMGCCGCGGTAA` |
| Read 2 Sequencing Primer | Reverse Pad + Linker + 806R | `AGTCAGCCAG CC GGACTACNVGGGTWTCTAAT` |
| Index Sequencing Primer | Illumina Index Oligo | `AATGATACGGCGACCACCGAGATCTACACGCT` |

### Basic Troubleshooting Guide

Weak Amplification / Off-Target Bands

-   If bands are faint or absent on low-biomass samples, note that low-biomass samples may naturally yield faint bands; verify product presence using high-sensitivity capillary electrophoresis (e.g., Bioanalyzer or TapeStation). Ensure master mix and DNA are thoroughly mixed prior to aliquoting.

Contamination

-   If contamination bands appear in the NTC well, re-run PCR ensuring full sterilization of work hood, pipettes, and consumables under UV light for 20 minutes. Use fresh aliquots of PCR-grade water, master mix, and barcoded primer stocks.

PCR Evaporation / Low Post-PCR Volume

-   Ensure PCR plate seals are firmly pressed across all wells. Spin down plates in a plate centrifuge prior to thermocycling to eliminate air bubbles and collect full reaction volumes.

## REFERENCES

-   Earth Microbiome Project 16S Protocol: <http://press.igsb.anl.gov/earthmicrobiome/protocols-and-standards/16s/>
-   Caporaso JG, Lauber CL, Walters WA, Berg-Lyons D, Lozupone CA, Turnbaugh PJ, Fierer N, Knight R. (2011) Global patterns of 16S rRNA diversity at a depth of millions of sequences per sample. *PNAS*, 108(suppl 1), 4516-4522.

## APPENDIX A: DATASHEETS

Not applicable.
