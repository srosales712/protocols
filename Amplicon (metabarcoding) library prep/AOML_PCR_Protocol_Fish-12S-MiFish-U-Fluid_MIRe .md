---
methodology_category: omics analysis
project: NOAA Atlantic Oceanographic and Meteorological Laboratory Omics Program;
  https://github.com/aomlomics/protocols; https://zenodo.org/communities/aomlomics
purpose: PCR [OBI:0000415]
analyses: PCR [OBI:0000415]
geographic_location: Atlantic Ocean [GAZ:00000344]
broad_scale_environmental_context: marine biome [ENVO:00000447]
local_environmental_context: marine biome [ENVO:00000447]
environmental_medium: sea water [ENVO:00002149]
target: 12S mitochondrial ribosomal RNA  [NCIT:C128263]
creator: Stephanie Rosales 
materials_required: vortexer [OBI:0400118], PCR instrument [OBI:0000989], agarose
  gel electrophoresis system [OBI:0001134]
skills_required: sterile technique, pipetting skills, standard molecular technique
time_required: 240
personnel_required: 1
language: en
issued: "2026-08-10"
audience: scientists
publisher: NOAA Atlantic Oceanographic and Meteorological Laboratory
hasVersion:
license: CC0 1.0 Universal
maturity level: mature
pcr_0_1: 1
inhibition_check_0_1: 0
inhibition_check: not applicable
thermocycler: Eppendorf Mastercycler Nexus Thermal Cycler
assay_name: "Fish-12S-MiFish-U-Miya"
assay_validation: not provided
targetTaxonomicAssay: Actinopterygii
targetTaxonomicScope: "Also captures non-target: Vertebrates, bacteria"
target_gene: 12S rRNA (SSU mitochondria)
target_subfragment: ""
ampliconSize: "163-185"
pcr_primer_forward: GCCGGTAAAACTCGTGCCAGC
pcr_primer_reverse: CATAGTGGGGTATCTAATCCCAGTTTG
pcr_primer_name_forward: "MiFish-U-F-V2"
pcr_primer_name_reverse: "MiFish-U-R"
pcr_primer_reference_forward: http://dx.doi.org/10.1098/rsos.150088
pcr_primer_reference_reverse: http://dx.doi.org/10.1098/rsos.150088
pcr_primer_vol_forward: 0.5
pcr_primer_vol_reverse: 0.5
pcr_primer_conc_forward: 10
pcr_primer_conc_reverse: 10
pcr_dna_vol: 1
amplificationReactionVolume: 12.5
probeReporter: not applicable
probeQuencher: not applicable
probe_seq: not applicable
probe_ref: not applicable
probe_conc: not applicable
commercial_mm: Platinum™ Hot Start PCR Master Mixes (2X)
custom_mm: PCR reactions were run in 12.5 µL reaction volumes, with 1.0 µL of DNA,
  6.25 µL of Platinum™ Hot Start PCR Master Mixes (2X), 4.25 µL of water, and 0.5 µL of each primer (10 µM).
block_seq: not applicable
block_ref: not applicable
block_taxa: not applicable
pcr_rep: 3
nucl_acid_amp: "https://www.protocols.io/view/environmental-dna-edna-12s-metabarcoding-illumina-kqdg35kqzv25/v"
pcr_cond: initial denaturation:95_15;normal cycling;denaturation:94_0.5;
annealing:60_0.5;elongation:72_1.5;13;normal cycling;denaturation:94_0.5;annealing:60_0.5;
elongation:72_0.75;25;final elongation:72_10;hold:4
annealingTemp:60.0
pcr_cycles: 38
pcr_analysis_software: not provided
pcr_method_additional: not provided
barcoding_pcr_appr: "two-step PCR"
pcr2_thermocycler: not provided
pcr2_amplificationReactionVolume: 15
pcr2_commercial_mm: 2X Dream Taq Master Mix (K1920)
pcr2_custom_mm: not applicable
pcr2_dna_vol: 1
pcr2_cond: initial denaturation:95_3;denaturation:95_0.25;annealing:60_0.5;elongation:72_1.5;final
  elongation:72_3;11
pcr2_annealingTemp: 60
pcr2_cycles: 11
pcr2_analysis_software: not applicable
pcr2_method_additional: not applicable
output:
  html_document:
    df_print: paged
editor_options: 
  markdown: 
    wrap: sentence
---

# NOAA/AOML PCR Protocol 12S rRNA MiFish-U (Miya et al) - MIRe

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

### Related Protocols

-   This section contains protocols that should be known to users of this protocol.
-   Internal Protocols: Derivative or altered protocols, or other protocols in this workflow.
-   External Protocols: Protcols from manufacturers or other groups.
-   Include the link to each protocol.
-   Include the version number (internal) or access date (external) of the protocol when it was accessed.

#### Internal Protocols

| PROTOCOL NAME | LINK | VERSION | RELEASE DATE |
|------------------|------------------|------------------|------------------|
| AOML 'Omics Protocols | <https://github.com/aomlomics/protocols> | not applicable | ongoing |
| NOAA 'Omics Metabarcoding Assays | <https://github.com/NOAA-Omics/noaa-omics-metabarcoding-assays> | not applicable | ongoing |

#### External Protocols

| PROTOCOL NAME | LINK | ISSUER / AUTHOR | ACCESS DATE |
|------------------|------------------|------------------|------------------|
| Mag-Bind reg Total Pure NGS, Omega Bio-Tek | <https://omegabiotek.com/product/mag-bind-rxnpure-plus/> | Omega Bio-Tek | 2026-08-11 |
| Invitrogen Qubit 1X dsDNA HS Assay Kits User Guide | <https://assets.thermofisher.com/TFS-Assets/LSG/manuals/MAN0017455_Qubit_1X_dsDNA_HS_Assay_Kit_UG.pdf> | ThermoFisher Scientific | 2026-08-11 |

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
| eDNA | environmental DNA |
| NTC | No template control |
| EtOH | Ethanol |

### Glossary

| SPECIALISED TERM | DEFINITION |
|------------------------------------|------------------------------------|
| Extraction Blank | A type of negative control to confirm there is no contamination during DNA extractions. Normally an empty is filter extracted and PCR amplified alongside other samples. |
| No Template Control | A type of negative control during PCR to confirm there is no contamination during the PCR process. Normally nuclease-free water is run in place of DNA on a PCR. |

## BACKGROUND

### Summary

This protocol describes steps for performing PCR for [12S rRNA](target_gene) marker gene regions using eDNA extracted from Sterivex at NOAA's AOML. The PCR protocol only includes a primary PCR step as the secondary PCR, library preparation and sequencing is completed by Michigan State University's RTSF Genomics Core. Steps related to preparing samples for sequencing and the Genomics Core's procedure are included. Some steps (e.g. PCR plate preparation) have been or can be optimized for use with the Opentrons OT2 robot. This protocol closely follows along with the following protocol from MBARI: <https://www.protocols.io/view/environmental-dna-edna-12s-metabarcoding-illumina-kqdg35kqzv25/v2>.

### Method description and rationale

This protocol is used for PCR amplifying the 12S MiFish marker gene regions of environmental DNA. Fluidigm adapters are already present on the primers described in the following protocol. The following PCR conditions are a modified version of the MBARI/CALeDNA protocol and were optimized at NOAA/AOML to reduce off-target amplification and increase target-band intensity

### Spatial coverage and environment(s) of relevance

This protocol can be used to amplify the 12S marker gene region of any eDNA sample.

## PERSONNEL REQUIRED

One person with molecular biology experience.

### Safety

This protocol involves chemical, thermal, and electrical hazards. Standard laboratory PPE should be worn. Handle ethanol and SYBR Safe according to institutional safety procedures and SDS requirements. Use appropriate heat protection when handling molten agarose and follow manufacturer/institutional procedures for UV or blue-light gel visualization. Do not handle the electrophoresis chamber while the power supply is energized.

### Training requirements

Basic molecular biology training is sufficient for this protocol including sterile technique, pipetting small volumes, programming/running [PCR](purpose) thermal cyclers, and running gel electrophoresis.

### Time needed to execute the procedure

Protocol takes about 4 hours ([240](time_required) minutes) including thermal cycler run time.

## EQUIPMENT

For 96-well Plate:

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
|---------------|---------------|---------------|---------------|---------------|
| **Durable equipment** |  |  |  |  |
| 100-1000 µL Pipette | Eppendorf Research Plus Adjustable-Volume Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| 10-100 µL Pipette | Eppendorf Research Plus Adjustable-Volume Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| 0.1-2.5 µL Pipette | Eppendorf Research Plus Adjustable-Volume Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| 10-100 µL 8-Channel Pipette | Eppendorf Research Plus 8 Channel Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| 0.5-10 µL 8-Channel Pipette | Eppendorf Research Plus 8 Channel Pipette | Eppendorf | 1 | Can be substituted with any accurate pipette |
| Thermal cycler | Mastercycler Nexus Thermal Cycler | Eppendorf | 1 | Can be substituted with generic |
| Microwave | Generic Microwave | Generic Brand | 1 |  |
| Flask | 500 mL Flask | Generic Brand | 1 | Used for mixing agarose gel solution |
| Thermometer |  | any brand | 1 | Used for monitoring agarose temperature |
| Stir bars |  | any brand | 1 | Used for mixing agarose gel solution |
| Stir plate |  | any brand | 1 | Used for ∂mixing agarose gel solution |
| 1-L Glass Container | 1 L Glass Container | Generic Brand | 1 | Used for storing 1x TBE buffer |
| Gel Tray & Box | Gel Electrophoresis Box and Tray | Generic Brand | 1 | Can be substituted with generic |
| Gel Combs | Gel Electrophoresis Combs | Generic Brand | 2 | Can be substituted with generic |
| **Consumable equipment** |  |  |  |  |
| 5mL tube for master mix (this size depends on the total master-mix volume) |  |  |  |  |
| Platinum™ Hot Start PCR Master Mixes (2X) | ThermoFisher | 0.6 | (mL) |  |
| 96-well PCR Plate |  |  |  |  |
| Forward Primer - 12S MiFish F | 12S MiFish_U F Fluidigm V2 | IDT | 105 | (ul (10uM)) Primer must be diluted from 100uM stocks to 10uM |
| Reverse Primer - 12S MiFish R | 12S MiFish_U R Fluidigm | IDT | 105 | (ul (10uM)) Primer must be diluted from 100uM stocks to 10uM |
| Gloves | Nitrile Gloves, Exam Grade, Powder-free | ULINE | 1 | (box) Can be substituted with generic |
| Kim Wipes | KimWipe Delicate Task Wipers | KimTech | 1 | (box) Can be substituted with generic |
| 96-well PCR Plate |  |  |  |  |
| PCR Plate Seal | Silverseal, Aluminum, Traditional Adhesive | USA Scientific |  |  |
| 10 µL Filter tips | TipOne Pipette Tips, 10 µL | TipOne | 2 | (boxes) Can be substituted with generic |
| Parafilm | Parafilm M Lab Film | Generic | 1 | (roll) Can substitute with generic brand |
| **Chemicals** |  |  |  |  |
| Bleach | DNA Decontaminant | any | 1 | (bottle) Used to sterilize lab surfaces and equipment |
| EtOH | Ethanol | Generic Brand | 1 | (wash bottle) Must be molecular grade ethanol |
| DI water | Deionized water | Generic | 900 | (mL) |
| Molecular water | Invitrogen RT-PCR Grade Water | Fisher Scientific | 1 | (mL) |
| TBE Buffer (10x) | TBE Buffer 10X Solution, Molecular Biology Grade, UltraPure | Thermo Scientific | 100 | (mL) |
| Agarose | Agarose LE, Molecular Biology Grade, UltraPure | Thermo Scientific | 4 | (g) |
| SYBR Safe | SYBR Safe DNA Gel Stain | Invitrogen | 20 | (uL) Light sensitive - do not expose to light |
| Gel stain loading dye | DNA Gel Loading Dye (6x) | Thermo Scientific | 100 | (ul per plate) |
| 100bp DNA Ladder | Generuler 100 bp DNA Ladder | Thermo Scientific | 5 | (ul per lane on gel) |
| (OPTIONAL) Clean-Up Protocol |  |  |  |  |
| Omega Beads | Mag-Bind reg Total Pure NGS | Omega | 1 | (kit) |
| 96-well magnetic plate | MagDTR 96-Well Magnetic Separator | Edge Biosystems Inc | 1 | Can be substituted with other brand |
| (OPTIONAL) Qubit |  |  |  |  |
| Qubit Reagents | Qubit dsDNA Quantification Assay Kit | Invitrogen | 1 | (kit) |
| Clear Qubit Assay tubes | 0.5 mL thin-walled, polypropylene tubes | Invitrogen | 98 | Must be correct tubes to allow for fluorometer to read concentration |

## STANDARD OPERATING PROCEDURE

### Protocol

#### Preparation

1.  Map out order of samples on 96-well PCR plate. Make sure to leave a space for a no template control (NTC) for each PCR plate.

2.  Label master mix tube, PCR plates, and any other consumables.

3.  Dilute primers from 100 µM to 10 µM if not already at 10uM. Using the dilution equation:

    (C1)(V1)=(C2)(V2)

4.  Place PCR consumables and molecular-grade water under UV sterilization for 15 minutes.

5.  Set up PCR under hood by wiping off all surfaces, pipettes, and racks with DNA-Away/Bleach and UV sterilizing for 20 mins.

#### PCR

1.  Remove PCR reagents from - 20 °C and allow reagents to thaw on ice or at room temperature.
2.  Remove PCR primers from - 20 °C to thaw out in 4 °C and keep cool during the entire process to avoid primer degradation.
3.  Very\*\* gently vortex primers.
4.  Keep reagents cool or on ice during the duration of the protocol.

5.Make PCR master mix:

-   6.25 µL [Platinum™ Hot Start PCR Master Mixes (2X)](commercial_mm)

-   4.25 µL molecular water

-   0.5 µL Fwd primer (10 μM; 0.4 μM final) - [12S MiFish_U F Fluidigm V2](pcr_primer_name_forward)

-   0.5 µL Rev primer (10 μM; 0.4 μM final) - [12S MiFish_U R Fluidigm](pcr_primer_name_reverse)

-   Add 1 µL of sample DNA (or molecular water for NTC) to respective triplicate wells for a total reaction volume of [12.5](amplificationReactionVolume) µL per well. Pipette up and down or vortex to fully distribute DNA into master mix.

6.  Seal plate with PCR plate seal or strip caps.

| PCR Primer Name | Direction | Sequence (5’ -\> 3’) | Sequence (5’ -\> 3’) with Fluidigm Adapters | Fluidigm Adapter |
|---------------|---------------|---------------|---------------|---------------|
| 12S MiFish F V2 | forward | [GCCGGTAAAACTCGTGCCAGC](pcr_primer_forward) | ACACTGACGACATGGTTCTACA xxx [GCCGGTAAAACTCGTGCCAGC](pcr_primer_forward) | CS1-TS-F |
| 12S MiFish R | reverse | [CATAGTGGGGTATCTAATCCCAGTTTG](pcr_primer_reverse) | TACGGTAGCAGAGACTTGGTCT xxx [CATAGTGGGGTATCTAATCCCAGTTTG](pcr_primer_reverse) | CS2-TS-R |

7.  Load plate onto thermal cycler and select "12s MBARI-PLAT" program to run the following steps:

| PCR step             | Temperature | Duration | Repetition |
|----------------------|-------------|----------|------------|
| Initial Denaturation | 95°C        | 15min    | 1x         |
| Normal Cycling       |             |          |            |
| Denaturation         | 94°C        | 30s      | 13x        |
| Annealing            | 60.0°C      | 30s      | 13x        |
| Extension            | 72°C        | 90s      | 13x        |
| Normal Cycling       |             |          |            |
| Denaturation         | 94°C        | 30s      | 25x        |
| Annealing            | 60°C        | 30s      | 25x        |
| Extension            | 72°C        | 45s      | 25x        |
| Final Extension      | 72°C        | 10min    | 1x         |
| Hold                 | 4°C         | ∞        |            |

#### Quality Control and PCR Clean-Up

### 2% Agarose Gel Electrophoresis

**Purpose:** Following PCR amplification, pool the triplicate PCR products for each sample and run the products on a 2% agarose gel to confirm the presence and approximate size of the target amplicon.

#### A. Prepare the PCR samples

1.  **Pool the triplicate PCR products for each sample.** Combine equal volumes of the three PCR replicates from the same sample into a single tube. Mix gently and briefly centrifuge.

#### B. Prepare 1× TBE buffer

1.  In a 1L glass container, prepare **1 L of 1× TBE** by adding **100 mL of 10× TBE stock** to **900 mL DI water**. Mix thoroughly.

#### C. Prepare the 2% agarose gel for a **5.5 × 5.5-inch gel tray**:

1.  Weigh **4 g agarose** using a laboratory scale and add to a microwave safe flask.

2.  Add **200 mL of 1× TBE** to the flask

3.  Microwave the agarose/TBE mixture for **1 minute**.

4.  Carefully remove the flask and swirl gently. Continue heating in **15–30 second intervals** until the agarose is completely dissolved and the solution is mostly clear.

    **CAUTION:** The solution can become extremely hot and may suddenly boil over. Watch the flask carefully while microwaving. Wear appropriate heat-resistant gloves when handling the flask.

5.  Allow the agarose solution to cool to approximately **60–65°C**. Place the flask on a stir plate with a stir bar and stir gently while cooling.

6.  While the agarose is cooling, set up the **5.5 × 5.5-inch gel tray** in the electrophoresis chamber. Make sure the tray is oriented correctly and the seals are secure before pouring the gel.

7.  Insert **well combs** into the gel tray and make sure chamber is leveled.

8.  Once the agarose has cooled to approximately 60°C, add 20 µL of 10,000× SYBR Safe DNA Gel Stain to the 200 mL agarose solution (1:10,000 final dilution). Gently swirl to mix, avoiding bubbles.

9.  Immediately close the SYBR Safe container and store it in the dark because SYBR Safe is light sensitive.

10. Carefully pour the agarose solution into the gel tray.

11. If bubbles are present, carefully remove them using a clean pipette tip.

12. Allow the gel to solidify for approximately **30–45 minutes**.

#### D. Prepare samples for loading

1.  While the gel is solidifying, prepare the samples for loading.

2.  Cut large strips of parafilm or use labeled 8-strip tubes to prepare the samples.

3.  Add **1 µL blue loading dye** to each sample position/tube.

4.  Add **5 µL of the pooled PCR product** to the loading dye.

5.  Mix by pipetting up and down **2–3 times**. Avoid creating bubbles.

#### E. Set up the electrophoresis

1.  Once the gel has completely solidified, carefully remove the combs.

2.  Place the gel into the electrophoresis chamber.

3.  Add enough **1× TBE buffer** to completely submerge the gel with approximately **1 cm of buffer above the gel**.

4.  Orient the gel so that the **wells are closest to the negative (black) electrode**. DNA will migrate through the gel toward the **positive (red) electrode**.

#### F. Load the gel

1.  Carefully load **5 µL of each prepared PCR sample** into the designated wells.

2.  When loading, place the pipette tip just inside the well and slowly dispense the sample. Avoid puncturing the well or allowing the sample to float out.

3.  Record the position of every sample on the gel-loading diagram.

4.  Load **5 µL of an appropriate DNA ladder** into a designated well. Record its position.

**Example:**

| Well | Sample     |
|------|------------|
| 1    | DNA ladder |
| 2    | Sample 1   |
| 3    | Sample 2   |
| 4    | Sample 3   |
| 5    | Sample 4   |
| …    | …          |

#### G. Run the gel

1.  Place the lid securely on the electrophoresis chamber.

2.  Confirm that the electrodes are connected correctly and that the chamber is closed before turning on the power supply.

3.  Run the gel at **100 V for approximately 40–50 minutes**, or until the loading dye has migrated an appropriate distance through the gel.

4.  **Do not open or handle the electrophoresis chamber while the power supply is running.** Turn off and disconnect the power supply before removing the gel.

#### H. Visualize the PCR products

1.  Carefully remove the gel from the electrophoresis chamber.

2.  Place the gel on the gel imaging/reader system.

3.  Visualize and photograph the gel using the appropriate imaging settings.

4.  Confirm whether a **distinct band is present at the expected amplicon size**.

5.  Record the results for each sample, including:

-   Presence/absence of the expected band

-   Approximate band size

-   Band intensity

-   Presence of additional nonspecific bands

-   Presence of primer-dimer or very small products

6.  Save the gel image using a file name that clearly identifies the experiment, date, primer set, and samples.

#### Quantification

Run Qubit on final PCR Products 1. Follow manufacturer protocol for running Qubit: <https://tools.thermofisher.com/content/sfs/manuals/Qubit_dsDNA_HS_Assay_UG.pdf>.

(OPTIONAL) Run Second 2% Agarose Gel on Purified PCR Products 1. Follow along with previous gel instructions.

#### Sequencing Preparation

1.  After PCR QC, transfer 10 µL of the pooled PCR product to the corresponding well of a new 96-well plate.
    -   Reserve at least one well empty for Michigan State's sequencing negative control. MSU adds its own negative control.
2.  Seal plate, label with ID and place in freezer till day of shipping.
3.  Fill out Illumina Sample Submission form with sample information and 96-well plate format.
    -   Can be found online at: [LIMS Project Submission](https://rtsf.natsci.msu.edu/genomics/lims-project-submission.aspx)
4.  Login to [LabLink](https://msu.claritylims.com/lablink/login) and create a project for the sequencing run.
5.  Upload project and run information, sample submission form and gel images (annotated) to the project.
6.  Prepare plates for shipping by obtaining dry ice (5-10lbs depending on quantity of plates), a styrofoam cooler and fitted cardboard box.
7.  Place 1-2 inches of dry ice on bottom of styrofoam cooler followed by sequencing plates then the remainder of dry ice.
8.  Place lid on cooler (do not tape shut) and place cooler into cardboard box.
9.  Tape the cardboard box shut and attach a shipping label.

#### Sequencing Facility Protocol

Information on sequencing is provided by Michigan State University's Genomics Core Facility:

The Genomics Core performs a secondary PCR using dual-indexed, Illumina compatible primers which target the Fluidigm CS1/CS2 oligomers at the ends of the primary PCR products. Amplicons are batch normalized using the Invitrogen SequalPrep DNA Normalization plates and the recovered product is pooled. The pool is QC'd and quantified using a combination of Qubit dsDNA HS and Agilent 4200 TapeStation HS DNA1000 assays.

The amplicon pool often has two target peaks (plus a likely primer dimer peak) in which the smaller of the two, a eukaryotic derived amplicon is the focus. This peak is isolated using the Sage Science BluePippin instrument. The pool is QC’d and quantified using a combination of Qubit dsDNA HS, Agilent 4200 TapeStation HS DNA1000 and Invitrogen Collibri Library Quantification qPCR assays.

Each pool is loaded onto one (1) Illumina MiSeq v2 Standard flow cell. Sequencing is carried out in a 2x250bp paired end format using a MiSeq v2 500 cycle reagent cartridge. Custom sequencing and index primers complementary to the Fluidigm CS1 and CS2 oligomers are added to appropriate wells of the reagent cartridge. Base calling is done by Illumina Real Time Analysis (RTA) v1.18.54 and output of RTA is demultiplexed and converted to FastQ format with Illumina Bcl2fastq v2.20.0. A summary of the run output is provided by MSU and basic QC information about sequence data is provided by the accompanying FastQC reports. For information regarding interpretation of these reports, please see the FastQC Tutorial and FAQ from [MSU's website](https://rtsf.natsci.msu.edu/genomics/technical-documents/fastqc-tutorial-and-faq.aspx).

Data is downloaded using an account on the Genomics FTP server. See the [Genomics FAQ](https://rtsf.natsci.msu.edu/genomics/data-retrieval.aspx) for general instructions. Sequence data typically remains available on the FTP server for 60 days. It is the responsibility of the researcher to download and store data long term. The RTSF Genomics Core only guarantees retention of sequence data for one year from the date of availability.

### Basic troubleshooting guide

Low Volume Post-PCR

-   If using strip-caps, ensure they are tightly fitting on wells. Any gap in the lid will allow for some volume to evaporate during the PCR process on the thermal cycler. If using PCR plate seals, spin down the plate after taking it off the thermal cycler to ensure all condensation is drawn back into the well.

Contamination

-   If there are contamination bands appearing on the gel, run another PCR ensuring full sterilization of work spaces and equipment under the hood and use new vials of Platinum Hot Start PCR Master Mix and molecular water. If diluted primers are contaminated, use freshly-made aliquot of primers.

Weak Amplification / Off-Target Bands

-   If there are weak amplification bands on the gel, ensure the master mix and template DNA are fully mixed prior to aliquoting. You can also increase the primer concentration, add Bovine Serum Albumin (BSA) to the master mix to relieve inhibition, or optimize thermal cycler settings (such as increasing the total number of cycles or adjusting the annealing temperature).

PCR Evaporation / Low Post-PCR Volume

-   If reaction volumes are noticeably low or uneven after thermocycling, inspect plate sealing and tube closures. Ensure strip caps fit tightly across all wells, or use a high-temp adhesive PCR plate seal and firmly press down edges. Always spin down the plate in a centrifuge immediately after removing it from the thermal cycler to pull any condensed liquid back into the reaction volume.

## REFERENCES

Not applicable.

## APPENDIX A: DATASHEETS

Not applicable.
