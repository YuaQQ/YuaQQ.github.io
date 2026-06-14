# Polymerase Chain Reaction (PCR)

- **Purpose**: Amplify a specific target DNA segment *in vitro*
- **Reagents Required**:
    - DNA template
    - Buffer
    - Primers
    - Deoxyribonucleotides (dNTPs)
    - **Taq DNA polymerase** (heat-stable)
- **Process** (Thermal Cycling):
    - **Denaturation**: Heat separates DNA strands (~95°C)
    - **Annealing**: Primers bind to complementary sequences (~50–65°C)
    - **Extension**: Taq polymerase synthesizes new DNA strand (~72°C)
- **Outcome**: Exponential amplification; after *n* cycles, ~2ⁿ copies of target DNA are produced.

## Gel Electrophoresis

- **Purpose**: Separate DNA, RNA, or proteins by size and/or charge
- **Principle**: Charged molecules migrate through a gel matrix under an electric field
    - Smaller molecules move faster and farther
    - DNA is negatively charged → moves from cathode (−) to anode (+)
- **Gel Types**:
    - **Agarose**: For larger DNA fragments (100 bp – 25 kb)
    - **Polyacrylamide**: For smaller DNA fragments or proteins (higher resolution)
- **Visualization**:
    - DNA: Stained with intercalating dyes (e.g., ethidium bromide)
    - **DNA ladder**: Used as a size reference
    - Band intensity correlates with DNA amount

## Southern Blotting

- **Purpose**: Detect specific DNA sequences within a complex mixture
- **Steps**:
    1. **Restriction Digest**: Cut DNA with restriction enzymes
    2. **Gel Electrophoresis**: Separate fragments by size
    3. **Blotting (Capillary Transfer)**: Transfer DNA from gel to a nitrocellulose membrane
    4. **Hybridization**: Incubate membrane with labeled **probe** complementary to target sequence
    5. **Detection**: Visualize bound probe (autoradiography, chemiluminescence, colorimetry)
- **Key Application**: Identify specific genes, RFLP analysis, genetic fingerprinting

## DNA Sequencing

- **Sanger Sequencing (Chain Termination)**:
    - For fragments < 1000 bp
    - Uses **dideoxyribonucleotides (ddNTPs)** that terminate DNA synthesis
    - Each ddNTP is fluorescently tagged; fragments separated by capillary electrophoresis
- **Next-Generation Sequencing (NGS) Types**:
    - **ATAC-seq**: Maps genome-wide chromatin accessibility
    - **ChIP-seq**: Identifies genomic binding sites of specific proteins

## DNA Cloning & Recombinant DNA Technology

- **Purpose**: Insert a gene into a plasmid for amplification in bacteria
- **Key Components**:
    - **Target gene**
    - **Vector (plasmid)**: Contains origin of replication (ori), antibiotic resistance gene (selection marker), and multiple cloning site (MCS)
    - **Restriction Endonucleases (RE)**: Cut DNA at specific sequences, producing sticky ends
    - **DNA Ligase**: Joins DNA fragments
    - **Competent Bacterial Cells**: For transformation
- **Steps**:
    1. **Digestion**: Cut gene and plasmid with same RE
    2. **Ligation**: Join gene and plasmid → recombinant plasmid
    3. **Transformation**: Introduce plasmid into bacteria
    4. **Selection**: Grow on antibiotic-containing media; only transformed bacteria survive
- **Plasmid Features**:
    - **ori**: Origin of replication
    - **Antibiotic resistance gene** (e.g., KanR): Selection marker
    - **lacI**: Repressor gene for inducible expression
    - **Rop gene**: Regulates plasmid copy number
    - **bom site**: Required for conjugation

## DNA Profiling

- **Restriction Fragment Length Polymorphism (RFLP)**:
    - DNA cut with RE, separated by gel electrophoresis
    - Pattern of fragment lengths varies between individuals
- **Short Tandem Repeats (STR)**:
    - PCR amplification of regions with variable numbers of tandem repeats
    - Fragment size differs based on repeat count; analyzed by gel electrophoresis
    - Used in forensics and paternity testing

## Genome Editing: CRISPR-Cas9

- **CRISPR**: Clustered Regularly Interspaced Short Palindromic Repeats
- **Components**:
    - **Guide RNA (gRNA)**: Complementary to target DNA sequence
    - **Cas9 enzyme**: Endonuclease that cuts DNA
- **Mechanism**: gRNA guides Cas9 to specific genomic site → creates double-strand break (DSB)
- **DNA Repair Pathways**:
    - **Non-Homologous End Joining (NHEJ)**: Error-prone; leads to insertions/deletions (indels) → **gene knockout**
    - **Homology-Directed Repair (HDR)**: Uses donor template for precise **gene knock-in** or modification
- **CRISPR Variants**:
    - **CRISPRi (Interference)**: Uses deactivated Cas9 fused to repressor to silence gene expression (knockdown)
    - **CRISPRa (Activation)**: Uses deactivated Cas9 fused to activator to enhance gene expression

## Plant Genetic Engineering: Agrobacterium tumefaciens

- **Ti Plasmid**: Natural vector from *Agrobacterium*
- **Process**: Recombinant Ti plasmid (with gene of interest) introduced into plant cells → T-DNA integrates into plant genome
- **Application**: Create transgenic plants with new traits (e.g., pest resistance)

## Gene Expression Analysis

- **Northern Blot**:
    - Detects specific mRNA by gel electrophoresis + hybridization with labeled probe
    - Requires relatively large amount of RNA
- **Quantitative PCR (qPCR / Real-Time PCR)**:
    - Quantifies mRNA levels by measuring amplification in real time
    - **Ct (Threshold Cycle)**: Cycle at which fluorescence crosses threshold; lower Ct = higher expression
    - Steps: RNA → cDNA (reverse transcription) → PCR with fluorescent probes
- **RNA Sequencing (RNA-seq)**:
    - High-throughput sequencing of entire transcriptome
- **In Situ Hybridization**:
    - Uses labeled probes to localize specific mRNA within intact tissue/organism
- **DNA Microarray**:
    - Measures expression of thousands of genes simultaneously
    - Steps: Isolate mRNA → convert to fluorescently labeled cDNA → hybridize to microarray chip → scan fluorescence

## Protein Detection: Western Blot

- **Purpose**: Detect and quantify specific proteins
- **Steps**:
    1. **Cell Lysis**: Release proteins
    2. **Protein Quantification**: Bradford assay
    3. **SDS-PAGE**: Separate denatured proteins by size
    4. **Electroblotting**: Transfer proteins to nitrocellulose membrane
    5. **Blocking**: Incubate with nonspecific protein (e.g., BSA) to prevent nonspecific antibody binding
    6. **Primary Antibody Incubation**: Binds target protein
    7. **Secondary Antibody Incubation**: Binds primary antibody; conjugated to enzyme (e.g., HRP) or fluorophore
    8. **Detection**: Add substrate → chemiluminescent/colorimetric signal
- **Controls Needed**: Loading control (e.g., actin), positive/negative controls

## ELISA (Enzyme-Linked Immunosorbent Assay)

- **Purpose**: Detect and quantify specific proteins/antibodies in liquid samples
- **Common Types**:
    - **Direct ELISA**: Antigen immobilized; detected directly with labeled antibody
    - **Indirect ELISA**: Antigen immobilized; detected with primary antibody + labeled secondary antibody (higher sensitivity)
    - **Sandwich ELISA**: Capture antibody immobilized; binds antigen; detected with labeled detection antibody
- **Detection**: Enzymatic reaction produces color change; absorbance measured

## RNA Interference (RNAi)

- **Purpose**: Silence gene expression post-transcriptionally
- **Mechanism**: Synthetic double-stranded RNA (siRNA) or endogenous microRNA (miRNA) triggers degradation or translational inhibition of complementary mRNA
- **Perfect complementarity** → mRNA degradation
- **Imperfect complementarity** → blocks translation

## Comparison of Blotting Techniques

| Technique | Target Molecule | Gel Type | Transfer Method | Probe | Detection |
| --- | --- | --- | --- | --- | --- |
| **Southern Blot** | DNA (ds) | Agarose | Capillary | DNA (labeled) | Autoradiography / Chemiluminescence |
| **Northern Blot** | mRNA (ss) | Formaldehyde-agarose | Capillary | cDNA/cRNA (labeled) | Autoradiography / Chemiluminescence |
| **Western Blot** | Protein | Polyacrylamide | Electric (electroblotting) | Primary antibody → Secondary antibody | Chemiluminescence / Colorimetric |

Practice Questions (with biochemistry)