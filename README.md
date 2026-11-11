# Syed Nurul Hasan, Ph.D.
### Computational Immunologist — Single-Cell Genomics & Immuno-Oncology

Turning multi-omic data into therapeutic insight: 5+ years postdoctoral research across single-cell and spatial genomics, 10 peer-reviewed publications, and 2,000,000+ single cells analyzed across 10+ projects spanning immuno-oncology and cardiovascular immunology.

📧 [nayanchoton1789@gmail.com](mailto:nayanchoton1789@gmail.com) · 🔗 [LinkedIn](https://linkedin.com/in/syed-nurul-hasan-510b6112b) · 🆔 [ORCID 0000-0002-4564-872X](https://orcid.org/0000-0002-4564-872X)

---

## Featured repositories

**Flagship**
- 🧬 [**bioinformatics-portfolio**](https://github.com/syed1789/bioinformatics-portfolio) — variant analysis, scRNA-seq (Seurat + Scanpy), scATAC-seq, spatial transcriptomics, and a checkpoint-blockade biomarker (AUROC 0.86) built from raw GEO data

**Single-cell & multi-omics**
- [scATAC-WNN-multimodal](https://github.com/syed1789/scATAC-WNN-multimodal) — 10x Multiome RNA+ATAC integration via WNN, chromVAR TF motif scoring
- [cite-seq-wnn-trajectory](https://github.com/syed1789/cite-seq-wnn-trajectory) — CITE-seq WNN integration + Monocle3 pseudotime

**Functional genomics & perturbation**
- [crispr-mageck-screen](https://github.com/syed1789/crispr-mageck-screen) — MAGeCK CRISPR screen hit-calling + GO/KEGG enrichment
- [perturb-seq-deep-learning](https://github.com/syed1789/perturb-seq-deep-learning) — PyTorch classifier predicting CRISPRi guide identity from expression (44.0% vs. 30.8% baseline)

**Bulk sequencing pipelines**
- [nf-variant-pipeline](https://github.com/syed1789/nf-variant-pipeline) — Nextflow germline + somatic (Mutect2) variant calling
- [bulk-rnaseq-star-deseq2](https://github.com/syed1789/bulk-rnaseq-star-deseq2) — STAR→DESeq2 Snakemake DAG with SLURM, SQL, Spark, and a verified Airflow DAG
- [bulk-chipseq-pipeline](https://github.com/syed1789/bulk-chipseq-pipeline) — Input-controlled ChIP-seq, 67% biological-replicate concordance
- [bulk-atacseq-pipeline](https://github.com/syed1789/bulk-atacseq-pipeline) — Tn5 shift, fragment-size & TSS-enrichment QC, MACS3 peak calling
- [cutandrun-pipeline](https://github.com/syed1789/cutandrun-pipeline) — bowtie2 + MACS3 peak calling on public CUT&Tag data

## Infrastructure & scale

- **Containers** — Docker/Singularity profiles in [nf-variant-pipeline](https://github.com/syed1789/nf-variant-pipeline/blob/main/nextflow.config); pinned biocontainers per rule in every Snakemake DAG; Dockerfiles in [cite-seq-wnn-trajectory](https://github.com/syed1789/cite-seq-wnn-trajectory), [crispr-mageck-screen](https://github.com/syed1789/crispr-mageck-screen), [perturb-seq-deep-learning](https://github.com/syed1789/perturb-seq-deep-learning) and [spatial-visium-squidpy](https://github.com/syed1789/spatial-visium-squidpy)
- **HPC (SLURM + Apptainer)** — SLURM job scripts and a Docker/Apptainer runtime switch across the pipeline repos, e.g. [bulk-rnaseq-star-deseq2](https://github.com/syed1789/bulk-rnaseq-star-deseq2/blob/main/HPC_AWS.md), [bulk-chipseq-pipeline](https://github.com/syed1789/bulk-chipseq-pipeline/blob/main/HPC_AWS.md), [bulk-atacseq-pipeline](https://github.com/syed1789/bulk-atacseq-pipeline/blob/main/HPC_AWS.md), [cutandrun-pipeline](https://github.com/syed1789/cutandrun-pipeline/blob/main/HPC_AWS.md)
- **AWS (EC2 + S3)** — one-shot launcher scripts that run an analysis on an EC2 instance, sync results to S3 and terminate, e.g. [`aws/launch_ec2.sh`](https://github.com/syed1789/bulk-rnaseq-star-deseq2/blob/main/aws/launch_ec2.sh); Nextflow `awsbatch` profile in [nf-variant-pipeline](https://github.com/syed1789/nf-variant-pipeline)
- **Workflow engines** — Nextflow, Snakemake, Airflow DAG, PySpark

## Spatial transcriptomics

- [**spatial-visium-squidpy**](https://github.com/syed1789/spatial-visium-squidpy) — 10x Visium mouse brain with Scanpy + Squidpy: Leiden clustering, neighborhood enrichment, co-occurrence, Moran's I, ligand-receptor inference; Docker, SLURM and EC2 run scripts

## Core stack

![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Nextflow](https://img.shields.io/badge/Nextflow-24B2E9?style=flat&logo=nextflow&logoColor=white)
![Snakemake](https://img.shields.io/badge/Snakemake-039475?style=flat)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Seurat](https://img.shields.io/badge/Seurat-single--cell-orange?style=flat)
![Scanpy](https://img.shields.io/badge/Scanpy-single--cell-orange?style=flat)

## Selected publications

- Yepuri G, Ramirez LM, et al. **DIAPH1-MFN2 interaction regulates mitochondria-SR/ER contact and modulates ischemic/hypoxic stress.** *Nature Communications*, 2023.
- Hasan SN, Sharma A, et al. **Bcl11b prevents catastrophic autoimmunity by controlling multiple aspects of a regulatory T cell gene expression program.** *Science Advances*, 2019.
- Kim CJ, Lee CG, et al. **The transcription factor Ets1 suppresses T follicular helper type 2 cell differentiation to halt systemic lupus erythematosus.** *Immunity*, 2018.

Full list (10 peer-reviewed papers) on [ORCID](https://orcid.org/0000-0002-4564-872X).
