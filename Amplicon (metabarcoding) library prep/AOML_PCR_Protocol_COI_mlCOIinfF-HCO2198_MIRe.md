

# NOAA/AOML PCR Protocol COI mlCOIinfF / HCO2198 - MIRe

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
| Stephanie Rosales | NOAA/AOML, UM/ CIMAS | <https://orcid.org/0000-0002-2678-9287> | 2026-08-26 |

### Related Protocols

-   This section contains protocols that should be known to users of this protocol.
-   Internal Protocols: Derivative or altered protocols, or other protocols in this workflow.
-   External Protocols: Protocols from manufacturers or other groups.

#### Internal Protocols

| PROTOCOL NAME | LINK | VERSION | RELEASE DATE |
|------------------|------------------|------------------|------------------|
| AOML 'Omics Protocols | <https://github.com/aomlomics/protocols> | not applicable | ongoing |
| NOAA 'Omics Metabarcoding Assays | <https://github.com/NOAA-Omics/noaa-omics-metabarcoding-assays> | not applicable | ongoing |

#### External Protocols

| PROTOCOL NAME | LINK | ISSUER / AUTHOR | ACCESS DATE |
|------------------|------------------|------------------|------------------|
| MBARI-BOG COI Metabarcoding PCR Protocol | <https://github.com/MBARI-BOG/MBARI-BOG-COI-metabarcoding-pcr-protocol/blob/main/MBARI-BOG-COI-metabarcoding-pcr-protocol.md> | MBARI-BOG | 2026-08-11 |
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
| Extraction Blank | A type of negative control to confirm there is no contamination during DNA extractions. Normally an empty filter is extracted and PCR amplified alongside other samples. |
| No Template Control | A type of negative control during PCR to confirm there is no contamination during the PCR process. Normally nuclease-free water is run in place of DNA on a PCR. |

## BACKGROUND

### Summary

This protocol describes steps for performing PCR for [COI](target_gene) marker gene regions using eDNA extracted from marine samples at NOAA's AOML. The PCR protocol includes primary amplification of triplicate 12.5 µL reactions per sample using 12-basepair Golay barcoded reverse primers with Fluidigm CS1 & CS2 adapters.
Secondary PCR, library preparation, and sequencing are completed by Michigan State University's RTSF Genomics Core.
Steps related to preparing samples for sequencing and the Genomics Core's procedure are included.
This protocol closely follows along with the MBARI-BOG COI metabarcoding protocol: <https://github.com/MBARI-BOG/MBARI-BOG-COI-metabarcoding-pcr-protocol/blob/main/MBARI-BOG-COI-metabarcoding-pcr-protocol.md>.

### Method description and rationale

This protocol is used for PCR amplifying a short fragment of the mitochondrial cytochrome c oxidase subunit I (COI) marker gene region of environmental DNA for characterizing metazoan diversity.
Fluidigm adapters CS1 & CS2 are attached to the forward and reverse primers.

### Spatial coverage and environment(s) of relevance

This protocol can be used to amplify the COI marker gene region of any metazoan eDNA sample.

## PERSONNEL REQUIRED

One person with molecular biology experience.

### Safety

This protocol involves chemical, thermal, and electrical hazards.
Standard laboratory PPE should be worn at all times.
Handle ethanol, DNA Decontaminant, and SYBR Safe according to institutional safety procedures and SDS requirements.
Use appropriate heat protection when handling molten agarose and follow manufacturer/institutional procedures for UV or blue-light gel visualization.
Do not handle the electrophoresis chamber while the power supply is energized.

### Training requirements

Basic molecular biology training is sufficient for this protocol including sterile technique, pipetting small volumes, and programming/running [PCR](purpose) thermal cyclers.

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
| Stir plate |  | any brand | 1 | Used for mixing agarose gel solution |
| 1-L Glass Container | 1 L Glass Container | Generic Brand | 1 | Used for storing 1x TBE buffer |
| Gel Tray & Box | Gel Electrophoresis Box and Tray | Generic Brand | 1 | Can be substituted with generic |
| Gel Combs | Gel Electrophoresis Combs | Generic Brand | 2 | Can be substituted with generic |
| **Consumable equipment** |  |  |  |  |
| 5mL tube for master mix |  |  | 1 | Size depends on total master-mix volume |
| Platinum™ Hot Start PCR Master Mixes (2X) | ThermoScientific | 3.6 | (mL) |  |
| 96-well PCR Plate |  |  | 2 |  |
| Forward Primer - mlCOIinfF | mlCOIinfF Fluidigm CS1 | IDT | 288 | (ul (10uM)) Primer diluted from 100uM stocks to 10uM |
| Reverse Primer - HCO2198 | HCO2198 Fluidigm CS2 | IDT | 288 | (ul (10uM)) Primer diluted from 100uM stocks to 10uM |
| Gloves | Nitrile Gloves, Exam Grade, Powder-free | ULINE | 1 | (box) Can be substituted with generic |
| Kim Wipes | KimWipe Delicate Task Wipers | KimTech | 1 | (box) Can be substituted with generic |
| PCR Plate Seal | Silverseal, Aluminum, Traditional Adhesive | USA Scientific | 2 |  |
| 1000µL Filter Tips | OT-2 Filter Tips, 1000µL | Opentrons | 1 | (box) Can be substituted with generic |
| 200µL Filter Tips | OT-2 Filter Tips, 200µL | Opentrons | 2 | (boxes) Can be substituted with generic |
| 10 µL Filter tips | TipOne Pipette Tips, 10 µL | TipOne | 2 | (boxes) Can be substituted with generic |
| Parafilm | Parafilm M Lab Film | Generic | 1 | (roll) Can substitute with generic brand |
| **Chemicals** |  |  |  |  |
| Bleach / RNase AWAY | Surface Decontaminant / Bleach Solution | ThermoFisher / Any | 1 | (bottle) Used to sterilize lab surfaces and equipment |
| EtOH | Ethanol | Generic Brand | 1 | (wash bottle) Must be molecular grade ethanol |
| DI water | Deionized water | Generic | 900 | (mL) |
| Molecular water | Invitrogen RT-PCR Grade Water | Fisher Scientific | 3.0 | (mL) |
| TBE Buffer (10x) | TBE Buffer 10X Solution, Molecular Biology Grade, UltraPure | Thermo Scientific | 100 | (mL) |
| Agarose | Agarose LE, Molecular Biology Grade, UltraPure | Thermo Scientific | 4 | (g) |
| SYBR Safe | SYBR Safe DNA Gel Stain | Invitrogen | 20 | (uL) Light sensitive - do not expose to light |
| Gel stain loading dye | DNA Gel Loading Dye (6x) | Thermo Scientific | 100 | (ul per plate) |
| 100bp DNA Ladder | Generuler 100 bp DNA Ladder | Thermo Scientific | 6 | (ul per lane on gel) |
| (OPTIONAL) Clean-Up Protocol |  |  |  |  |
| Omega Beads | Mag-Bind reg Total Pure NGS | Omega | 1 | (kit) |
| 96-well magnetic plate | MagDTR 96-Well Magnetic Separator | Edge Biosystems Inc | 1 | Can be substituted with other brand |
| (OPTIONAL) Qubit |  |  |  |  |
| Qubit Reagents | Qubit dsDNA Quantification Assay Kit | Invitrogen | 1 | (kit) |
| Clear Qubit Assay tubes | 0.5 mL thin-walled, polypropylene tubes | Invitrogen | 98 | Must be correct tubes to allow for fluorometer to read concentration |

-   Description: E.g., "filter".
-   Product Name and Model: Provide the official name of the product.
-   Manufacturer: Provide the name of the manufacturer of the product.
-   Quantity: Provide quantities necessary for one application of the standard operating procedure (e.g., number of filters).
-   Remark: For example, some of the consumable may need to be sterilized, some commercial solution may need to be diluted or shielded from light during the operating procedure.

## STANDARD OPERATING PROCEDURE

### Protocol

#### Preparation

1.  Map out order of samples on 96-well PCR plate.
    Make sure to leave a space for a no template control (NTC) run in singleton for each PCR plate.

2.  Label master mix tube, PCR plates, and any other consumables.

3.  Dilute primers from 100 µM to 5 µM if not already at 5 µM using the dilution equation:

    (C1)(V1) = (C2)(V2)

4.  Place PCR consumables and molecular-grade water under UV sterilization for 15 minutes.

5.  Set up PCR under hood by wiping off all surfaces, pipettes, and racks with DNA-Away/Bleach and UV sterilizing for 20 mins.

#### PCR

1.  Remove PCR reagents from -20 °C and allow reagents to thaw on ice or at room temperature.
2.  Remove PCR primers from -20 °C to thaw out at 4 °C and keep cool during the entire process to avoid primer degradation.
3.  Very gently vortex primers.
4.  Keep reagents cool or on ice during the duration of the protocol.
5.  Make PCR master mix (per single 12.5 µL reaction):
    -   6.25 µL Platinum™ Hot Start PCR Master Mixes (2X)
    -   4.25 µL molecular water
    -   0.5 µL Fwd primer (5 µM stock) - mlCOIinfF
    -   0.5 µL Rev primer (5 µM stock) - HCO2198
    -   Add 1 µL of sample DNA extract template (or molecular water for NTC) to respective wells for a total reaction volume of 12.5µL per well. Pipette up and down or vortex to fully distribute DNA into master mix.
6.  Seal plate with PCR plate seal or strip caps.

| PCR Primer Name | Direction | Sequence (5’ -\> 3’) | Sequence (5’ -\> 3’) with Fluidigm Adapters | Fluidigm Adapter |
|---------------|---------------|---------------|---------------|---------------|
| mlCOIinfF | forward | ACACTGACGACATGGTTCTACAHCO2198 | ACACTGACGACATGGTTCTACAGGWACWGGWTGAACWGTWTAYCCYCC | CS1-TS-F |
| HCO2198 | reverse | TACGGTAGCAGAGACTTGGTCT | TACGGTAGCAGAGACTTGGTCTTAAACTTCAGGGTGACCAAAAAATCA | CS2-TS-R |

7.  Load plate onto thermal cycler (using normal ramp speed) and select program to run the following steps:

| PCR step             | Temperature             | Duration | Repetition |
|----------------------|-------------------------|----------|------------|
| Initial Denaturation | 95°C                    | 10min    | 1x         |
| Touchdown Cycling    |                         |          |            |
| Denaturation         | 94°C                    | 10s      | 16x        |
| Annealing            | 62.0°C (-1°C per cycle) | 30s      | 16x        |
| Extension            | 68°C                    | 60s      | 16x        |
| Normal Cycling       |                         |          |            |
| Denaturation         | 94°C                    | 10s      | 25x        |
| Annealing            | 46°C                    | 30s      | 25x        |
| Extension            | 68°C                    | 60s      | 25x        |
| Final Extension      | 72°C                    | 10min    | 1x         |
| Hold                 | 4°C                     | ∞        |            |

#### Quality Control and PCR Clean-Up

### 2% Agarose Gel Electrophoresis

**Purpose:** Following PCR amplification, run PCR products on a 2% agarose gel to confirm the presence and approximate size of the target amplicon (\~313 bp).

#### A. Prepare the PCR samples

1.  Mix PCR product gently and centrifuge briefly prior to loading.

#### B. Prepare 1× TBE buffer

1.  In a 1L glass container, prepare **1 L of 1× TBE** by adding **100 mL of 10× TBE stock** to **900 mL DI water**. Mix thoroughly.

#### C. Prepare the 2% agarose gel for a **5.5 × 5.5-inch gel tray**:

1.  Weigh **4 g agarose** using a laboratory scale and add to a microwave safe flask.

2.  Add **200 mL of 1× TBE** to the flask.

3.  Microwave the agarose/TBE mixture for **1 minute**.

4.  Carefully remove the flask and swirl gently.
    Continue heating in **15–30 second intervals** until the agarose is completely dissolved and the solution is mostly clear.

    **CAUTION:** The solution can become extremely hot and may suddenly boil over.
    Watch the flask carefully while microwaving.
    Wear appropriate heat-resistant gloves when handling the flask.

5.  Allow the agarose solution to cool to approximately **60–65°C**.
    Place the flask on a stir plate with a stir bar and stir gently while cooling.

6.  While the agarose is cooling, set up the **5.5 × 5.5-inch gel tray** in the electrophoresis chamber.
    Make sure the tray is oriented correctly and the seals are secure before pouring the gel.

7.  Insert **well combs** (20 wells per comb, 2 combs for a total of 40 wells) into the gel tray and make sure chamber is leveled.

8.  Once the agarose has cooled to approximately 60°C, add 20 µL of 10,000× SYBR Safe DNA Gel Stain to the 200 mL agarose solution (1:10,000 final dilution).
    Gently swirl to mix, avoiding bubbles.

9.  Immediately close the SYBR Safe container and store it in the dark because SYBR Safe is light sensitive.

10. Carefully pour the agarose solution into the gel tray.

11. If bubbles are present, carefully remove them using a clean pipette tip.

12. Allow the gel to solidify for approximately **30–45 minutes**.

#### D. Prepare samples for loading

1.  While the gel is solidifying, prepare the samples for loading.

2.  Cut large strips of parafilm or use labeled 8-strip tubes to prepare the samples.

3.  Add **1 µL blue loading dye** to each sample position/tube.

4.  Add **5 µL of the PCR product** to the loading dye.

5.  Mix by pipetting up and down **2–3 times**.
    Avoid creating bubbles.

#### E. Set up the electrophoresis

1.  Once the gel has completely solidified, carefully remove the combs.

2.  Place the gel into the electrophoresis chamber.

3.  Add enough **1× TBE buffer** to completely submerge the gel with approximately **1 cm of buffer above the gel**.

4.  Orient the gel so that the **wells are closest to the negative (black) electrode**.
    DNA will migrate through the gel toward the **positive (red) electrode**.

#### F. Load the gel

1.  Carefully load **5 µL of each prepared PCR sample** into the designated wells.

2.  When loading, place the pipette tip just inside the well and slowly dispense the sample.
    Avoid puncturing the well or allowing the sample to float out.

3.  Record the position of every sample on the gel-loading diagram.

4.  Load **5 µL or 6 µL of an appropriate DNA ladder** into a designated well.
    Record its position.

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

1.  Run Qubit on final PCR Products (optional).
    Follow manufacturer protocol for running Qubit: <https://tools.thermofisher.com/content/sfs/manuals/Qubit_dsDNA_HS_Assay_UG.pdf>.

2.  (OPTIONAL) Run Second 2% Agarose Gel on Purified PCR Products.
    Follow along with previous gel instructions.

#### Sequencing Preparation

1.  After PCR QC, transfer 10 µL of the PCR product to the corresponding well of a new 96-well plate.
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

#### Sequencing Submission and Facility Protocol

1.  Submit secondary amplification to **Michigan State University’s Research Technology Support Facility (RTSF)**.

    -   Prepare the submission form and email it to [gtsf\@msu.edu](mailto:gtsf@msu.edu) and upload it to [Sequence_submisson](https://drive.google.com/open?id=1dx2EngdEjOJDt1GcsYZ6lUKz-xl-aP5e)

    -   Pre-register your samples at  <https://msu.claritylims.com/lablink/login>

    -   Ship samples overnight with an excess of dry ice (Note: dry ice is not available on campus and needs to be purchased outside of campus) on a Monday, Tuesday, or Wednesday to: 

        -   Shari Tjugum-Holland

        -   612 Wilson Road, S-18 D

        -   East Lansing, MI 48824 

2.  More information can be found at this [link](https://rtsf.natsci.msu.edu/genomics/sample-drop-off-shipping.aspx#:~:text=frost%2Dfree%20freezer).

Information on sequencing is provided by Michigan State University's Genomics Core Facility:

The Genomics Core performs a secondary PCR using dual-indexed, Illumina compatible primers which target the Fluidigm CS1/CS2 oligomers at the ends of the primary PCR products.
Amplicons are batch normalized using the Invitrogen SequalPrep DNA Normalization plates and the recovered product is pooled.
The pool is QC'd and quantified using a combination of Qubit dsDNA HS and Agilent 4200 TapeStation HS DNA1000 assays.

The amplicon pool often has two target peaks (plus a likely primer dimer peak) in which the smaller of the two, a eukaryotic derived amplicon is the focus.
This peak is isolated using the Sage Science BluePippin instrument.
The pool is QC’d and quantified using a combination of Qubit dsDNA HS, Agilent 4200 TapeStation HS DNA1000 and Invitrogen Collibri Library Quantification qPCR assays.

Each pool is loaded onto one (1) Illumina MiSeq v2 Standard flow cell.
Sequencing is carried out in a 2x250bp paired end format using a MiSeq v2 500 cycle reagent cartridge.
Custom sequencing and index primers complementary to the Fluidigm CS1 and CS2 oligomers are added to appropriate wells of the reagent cartridge.
Base calling is done by Illumina Real Time Analysis (RTA) v1.18.54 and output of RTA is demultiplexed and converted to FastQ format with Illumina Bcl2fastq v2.20.0.
A summary of the run output is provided by MSU and basic QC information about sequence data is provided by the accompanying FastQC reports.
For information regarding interpretation of these reports, please see the FastQC Tutorial and FAQ from [MSU's website](https://rtsf.natsci.msu.edu/genomics/technical-documents/fastqc-tutorial-and-faq.aspx).

Data is downloaded using an account on the Genomics FTP server.
See the [Genomics FAQ](https://rtsf.natsci.msu.edu/genomics/data-retrieval.aspx) for general instructions.
Sequence data typically remains available on the FTP server for 60 days.
It is the responsibility of the researcher to download and store data long term.
The RTSF Genomics Core only guarantees retention of sequence data for one year from the date of availability.

### Basic troubleshooting guide

Low Volume Post-PCR

-   If using strip-caps, ensure they are tightly fitting on wells. Any gap in the lid will allow for some volume to evaporate during the PCR process on the thermal cycler. If using PCR plate seals, spin down the plate after taking it off the thermal cycler to ensure all condensation is drawn back into the well.

Contamination

-   If there are contamination bands appearing on the gel, run another PCR ensuring full sterilization of work spaces and equipment under the hood and use new vials of Platinum™ Hot Start PCR Master Mixes (2X) and molecular water. If diluted primers are contaminated, use freshly-made aliquot of primers.

Weak Amplification / Off-Target Bands

-   If there are weak amplification bands on the gel, ensure the master mix and template DNA are fully mixed prior to aliquoting. You can also increase the primer concentration, add Bovine Serum Albumin (BSA) to the master mix to relieve inhibition, or optimize thermal cycler settings (such as increasing the total number of cycles or adjusting the annealing temperature).

PCR Evaporation / Low Post-PCR Volume

-   If reaction volumes are noticeably low or uneven after thermocycling, inspect plate sealing and tube closures. Ensure strip caps fit tightly across all wells, or use a high-temp adhesive PCR plate seal and firmly press down edges. Always spin down the plate in a centrifuge immediately after removing it from the thermal cycler to pull any condensed liquid back into the reaction volume.

## REFERENCES

-   Leray M, Yang JY, Meyer CP, Mills SC, Agudelo N, Ranwez V, Boehm JT, Machida RJ. (2013) A new versatile primer set targeting a short fragment of the mitochondrial COI region for metabarcoding metazoan diversity: application for characterizing coral reef fish gut contents. *Frontiers in Zoology*, 10(1), 1-4. <https://doi.org/10.1186/1742-9994-10-34>
-   Folmer O, Black M, Hoeh W, Lutz R, Vrijenhoek R (1994) DNA primers for amplification of mitochondrial cytochrome c oxidase subunit I from diverse metazoan invertebrates. *Molecular Marine Biology and Biotechnology*, 3, 294–299. <http://dx.doi.org/10.1007/978-1-4615-2381-9_24>

## APPENDIX A: DATASHEETS

Not applicable.
