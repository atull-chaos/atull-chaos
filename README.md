# Alba Tull

**Extremophile Genomics Researcher · Carnegie Mellon University · **

I build open-access genomic databases for organisms that thrive in Earth's most extreme environments — from glacial ice cores and deep subsurface rock to hypersaline lakes and volcanic hot springs. My work focuses on making extremophile sequencing data discoverable, searchable, and ready for metagenomic analysis.

---

### Databases

**[ExtremoDex](https://extremodex.org)** — *The Extremophile Rolodex*
A rolodex-style index of every extremophile organism and metagenome across 18 categories. ~1,994 dex cards, ~1,921 species, ~55,000 sequencing runs aggregated from NCBI SRA and ENA Portal. Each card links to BioProject accessions, sequencing platforms, geographic data, and cross-references to TardiBase and GlaciaBase.

**[TardiBase](https://tardibase.org)** — *The Tardigrade Genomics Knowledgebase*
Deep tardigrade genomics — genomes, stress genes, species taxonomy, and cryptobiosis data. Includes interactive species profiles with habitat, temperature tolerance, and desiccation survival traits. Covers every tardigrade sequencing project deposited in NCBI SRA.

**[GlaciaBase](https://glaciabase.org)** — *Psychrophile & Cryophile Genomics*
Focused database for cold-adapted microorganisms. Catalogs psychrophiles and cryophiles with growth temperature ranges, isolation sources, 16S/WGS sequencing tags, and BioSample counts. Includes a metagenome assembly pipeline for processing cold-environment datasets.

---

### Metagenome Assembly Pipeline

An end-to-end shell pipeline for extremophile metagenome analysis with two branches:

- **WGS branch** — MEGAHIT assembly → MetaBAT2 binning → CheckM2 quality → GTDB-Tk taxonomy
- **16S/amplicon branch** — QIIME2 import → DADA2 denoising → SILVA classification → alpha/beta diversity

Available at [extremodex.org/pipeline.html](https://extremodex.org/pipeline.html)

---

### Current Work

- Rotation student in the **Kaplow Lab** at CMU (computational genomics)
- Collaborating with **Chris Mason** (Weill Cornell) on extremophile genomics and database curation strategy
- Building extraction and analysis tools for NCBI/ENA sequencing data
- Antarctic biocrust DNA extraction and QC workflows

---

### Tech

JavaScript · Python · Node.js · Bash · NCBI Entrez API · ENA Portal API · Biopython · QIIME2 · MEGAHIT · MetaBAT2 · CheckM2 · GTDB-Tk · Netlify

---

*Created and maintained by Alba Tull · 2026*
