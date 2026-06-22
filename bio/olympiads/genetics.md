# Genetics & Evolution

# Genetics - Non-Mendelian Inheritance

## Core Concepts

- **Characters**: Observable physical features (e.g., flower color, seed shape).
- **Traits**: Specific forms of a character (e.g., purple flowers, wrinkled seeds).
- **Inherited Traits**: Traits passed from parents to offspring.
- **Heredity**: The transmission of traits from parents to offspring.
- **Genetics**: The study of heredity.
- **Gene**: A segment of DNA that controls a character.
- **Allele**: Different versions of the same gene controlling a trait.
- **Dominant Allele**: An allele that expresses its trait when paired with a different allele.
- **Recessive Allele**: An allele whose trait is masked when paired with a different allele.
- **Locus (Loci)**: The specific location of a gene on a chromosome.
- **Homologous Chromosomes**: Paired chromosomes, one from each parent, carrying the same genes at the same loci.
- **Genotype**: The genetic makeup of an organism (e.g., allele combinations).
- **Phenotype**: The observable physical appearance of an organism.
- **Homozygous**: Having two identical alleles for a gene.
- **Heterozygous**: Having two different alleles for a gene.

## Mendelian Genetics

### Law of Segregation (Mendel's First Law)

- During gamete formation (meiosis), alleles for each trait separate so that each gamete carries only one allele for each gene.
- This occurs because homologous chromosomes separate during meiosis.
- Illustrated by monohybrid crosses (e.g., purple vs. white flowers in peas).

### Law of Independent Assortment (Mendel's Second Law)

- Genes for different traits assort independently during gamete formation.
- This holds true for genes on different chromosomes or far apart on the same chromosome.
- Illustrated by dihybrid crosses (e.g., seed shape and color in peas yielding a 9:3:3:1 ratio).

## Non-Mendelian Inheritance

### Polygenic Inheritance

- A single character is influenced by multiple genes (multiple loci).
- Traits are usually quantitative (measured, not just observed).
- Examples: human skin color, height, grain yield.
- Trait distribution often follows a normal (bell) curve.
- Phenotype results from the additive effect of alleles at multiple loci.
- Formula: Probability follows binomial distribution: `P(x) = (n choose x) * p^x * (1-p)^(n-x)`.

### Pleiotropy

- A single gene affects multiple phenotypic traits.
- Examples: Marfan syndrome (affects height, fingers, eyes, heart), Porphyria variegata (affects abdomen, muscles, vision).

### Lethality (Special Case of Pleiotropy)

- **Recessive-Lethal Allele**: Causes death in homozygous recessive individuals (e.g., some dwarfism in mice).
- **Dominant-Lethal Allele**: Causes death even in heterozygotes (e.g., Huntington's disease).

### Epistasis

- One gene affects the expression of another gene at a different locus.
- The epistatic gene masks or alters the effect of the other gene.
- Examples:
    - *Drosophila* eye color: `white` gene mutation is epistatic to `cinnabar`.
    - Sweet pea flower color: Two genes interact (9 purple : 7 white ratio in F2).
    - Summer squash color: Gene interaction leads to 12:3:1 or 9:6:1 ratios.
    - Mouse coat color: 9:3:4 ratio.
- Common modified phenotypic ratios: 9:7, 9:3:4, 12:3:1, 9:6:1, 15:1, 13:3.

### Linkage Analysis

- Genes located close together on the same chromosome tend to be inherited together.
- **Recombination Frequency (RF)**: Percentage of recombinant offspring in a cross. `RF = (Number of Recombinants / Total Progeny) * 100`.
- **Genetic Map Distance**: Measured in map units (centiMorgans, cM). 1 cM = 1% recombination frequency.
- **Linkage Group**: A group of genes on the same chromosome that are linked (RF < 50%).
- Crossing over during meiosis can separate linked genes, producing recombinant phenotypes.
- Double or multiple crossovers can lead to underestimation of genetic distances.

### Tetrad Analysis (in Fungi like Yeast and Neurospora)

- Allows direct observation of all four products of a single meiosis.
- **Parental Ditype (PD)**: All spores have parental allele combinations.
- **Nonparental Ditype (NPD)**: All spores have recombinant allele combinations.
- **Tetratype (T)**: Contains both parental and recombinant spores.
- **For Unlinked Genes**: PD ≈ NPD.
- **For Linked Genes**: PD >> NPD.
- **Recombination Frequency (from tetrads)**: `RF = [NPD + (1/2)T] / Total Tetrads * 100`.
- **Ordered Tetrads** (e.g., Neurospora): Allow mapping of genes relative to the centromere based on segregation patterns (MI vs. MII).

### Genomic Imprinting

- Epigenetic process where genes are selectively silenced based on parental origin.
- Example: Mouse Igf2 gene. Only the paternal allele is expressed. Offspring phenotype depends on which parent contributed the functional allele.
- Human Examples:
    - **Prader-Willi Syndrome (PWS)**: Caused by deletion or silencing of paternal genes on chromosome 15q11-q13.
    - **Angelman Syndrome (AS)**: Caused by deletion or silencing of maternal genes on the same region.

### Organellar (Cytoplasmic) Inheritance

- Inheritance of genes located in mitochondrial (mtDNA) or chloroplast (cpDNA) genomes.
- **Maternal Inheritance**: Most common in animals and plants; organelles inherited only from the mother.
- **Biparental Inheritance**: Occurs in some species like budding yeast.
- **Heteroplasmy**: Cell contains organelles with different genotypes.
- **Homoplasmy**: Cell contains organelles with only one genotype.
- Examples: Leaf color in Mirabilis jalapa (chloroplast inheritance), human mitochondrial diseases.

### Maternal Effect

- The phenotype of the offspring is determined by the genotype of the mother, not its own genotype.
- Maternal gene products (mRNA, proteins) deposited in the egg influence early development.
- Examples:
    - Dorsal-ventral axis formation in *Drosophila* (dorsal gene).
    - Anterior-posterior axis formation in *Drosophila* (bicoid, nanos, hunchback, caudal genes).
    - Shell coiling direction in snails (*Lymnaea peregra*).

## Sex Chromosomes & Inactivation

- Humans: XX = female, XY = male. The Y chromosome determines maleness.
- **X-Inactivation (Lyon Hypothesis)**: In female somatic cells, one X chromosome is randomly inactivated early in development, forming a Barr body.
- **Mechanism**: Controlled by the X-inactivation center (Xic) and the Xist gene (produces a long non-coding RNA that coats and silences the X chromosome).
- Results in mosaicism for X-linked traits in females (e.g., tortoiseshell cats).

## Chromosomal Aberrations

- **Deletion**: Loss of a chromosome segment (e.g., cri du chat syndrome, terminal deletion on chr5).
- **Duplication**: Presence of an extra copy of a segment (e.g., gene families like globin genes).
- **Inversion**: A segment is reversed. Paracentric (no centromere involved) or Pericentric (centromere included).
- **Translocation**: Movement of a segment to a non-homologous chromosome.
    - **Reciprocal Translocation**: Exchange of segments.
    - **Robertsonian Translocation**: Fusion of long arms of two acrocentric chromosomes (e.g., origin of human chr 2).

## Population Genetics

- **Population**: Smallest unit of evolution; a group of interbreeding individuals.
- **Gene Pool**: All alleles present in a population.
- **Allele Frequency**: Proportion of a specific allele in the gene pool.
- **Hardy-Weinberg Equilibrium**: A theoretical state where allele and genotype frequencies remain constant from generation to generation.
    - Conditions: No mutation, no gene flow, infinite population size, random mating, no natural selection.
    - Equations: For two alleles (p, q): `p + q = 1` and `p² + 2pq + q² = 1`.

### Evolutionary Forces

- **Natural Selection**: Differential survival and reproduction based on trait differences.
- **Genetic Drift**: Random changes in allele frequencies, especially in small populations.
- **Gene Flow**: Movement of alleles between populations via migration.
- **Mutation**: Ultimate source of new genetic variation.

### Modes of Natural Selection

- **Stabilizing Selection**: Favors intermediate phenotypes (reduces variation).
- **Directional Selection**: Favors one extreme phenotype.
- **Disruptive Selection**: Favors both extreme phenotypes over intermediates.
- **Sexual Selection**: Selection for mating success (intrasexual competition or intersexual choice).
- **Balancing Selection**: Maintains genetic variation.
    - **Heterozygote Advantage**: Heterozygotes have higher fitness (e.g., sickle cell trait in malaria zones).
    - **Frequency-Dependent Selection**: Fitness depends on a phenotype's frequency.
        - **Negative**: Rare phenotypes have an advantage.
        - **Positive**: Common phenotypes have an advantage (e.g., Batesian mimicry).

## Important Genetic Disorders

- **Autosomal Dominant**: Huntington's disease, Achondroplasia.
- **Autosomal Recessive**: Tay-Sachs disease.
- **X-linked Dominant**: Fragile X syndrome.
- **X-linked Recessive**: Duchenne Muscular Dystrophy (DMD).

## Key Example Questions (USABO)

- Polygenic inheritance & number of genes (Harry's plant height).
- Epistasis (Periwinkle flower color, Sky bison whistle response).
- Linkage & Recombination Frequency (Octopus traits, Gene order mapping).
- Genomic Imprinting (Prader-Willi/Angelman diagnosis).
- Organellar Inheritance (Pedigree analysis for mitochondrial disease).
- Maternal Effect (Snail shell coiling).
- X-inactivation (Carrier of X-chromosome duplication).
- Chromosomal Aberrations (Diagnosis via FISH).
- Population Genetics & Selection (Hardy-Weinberg, fitness calculations, selection types).

Practice Questions (Genetics)

Practice Questions (Evolution)