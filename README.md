### 🧬 Cancertope: Cancer Neoepitope & Vaccine Design Platform

Welcome to the official repository for Cancertope, a computational platform and database for identifying cancer-specific neoepitopes and designing personalized cancer vaccines and immunotherapies. 🎯

This resource integrates mutational data, immune epitope prediction, and vaccine candidate prioritization into a unified framework.

⸻

🔬 About the Platform

Cancertope is designed to address a key bottleneck in cancer immunotherapy:

➡️ Identifying tumor-specific antigens (neoantigens) that can trigger a targeted immune response.

Traditional experimental methods are:

* Costly
* Time-consuming
* Not scalable

Cancertope solves this using computational pipelines + large-scale mutation data.

It analyzes:

* Somatic mutations
* Cancer-specific protein regions
* Immune epitope potential

…and converts them into actionable vaccine candidates  ￼

⸻

✨ Key Features

Large-Scale Mutation Analysis 📊

* Based on 905 cancer cell lines
* Covers mutation types:
    * Missense
    * Frameshift
    * Insertions / deletions  ￼

Neoepitope Identification 🧬

* Detects peptides unique to cancer cells
* Filters out peptides present in normal human proteome

Multi-Immune Targeting 🎯
Predicts epitopes for:

* CD8+ T cells (CTL epitopes)
* CD4+ T cells (Helper epitopes)
* B-cell epitopes  ￼

Vaccine Candidate Database 💉

* Curated list of potential cancer vaccine targets
* Includes known oncogenic mutations:
    * TP53
    * BRAF
    * EGFR
    * c-KIT  ￼

⸻

🔍 Overview

Cancertope provides:

* Cancer-specific mutations
* Predicted neoepitopes
* Immunogenicity scoring
* Epitope classification (B-cell, T-cell)
* Candidate vaccine targets

It bridges:

Cancer genomics → Immunology → Vaccine design

⸻

⚙️ Pipeline Overview

Step 1: Mutation Extraction

* Identify somatic mutations from cancer datasets

Step 2: Peptide Generation

* Generate overlapping peptide fragments
* Remove redundancy
* Exclude peptides found in normal proteome  ￼

Step 3: Epitope Prediction

CD8+ T-cell epitopes

* ProPred1
* nHLAPred
* CTLPred

CD4+ T-cell epitopes

* ProPred

B-cell epitopes

* LBtope

Step 4: Candidate Selection

* High immunogenic potential
* Cancer-specific
* Non-cross-reactive

⸻

🧪 Data Contents

Each entry includes:

* Mutation details
* Gene/protein name
* Peptide sequence
* Epitope classification
* HLA binding predictions
* Immunogenicity scores

⸻

🌐 Web Server

Access the platform here:
👉 http://crdd.osdd.net/raghava/cancertope/

Features:

* Database browsing
* Epitope prediction tools
* Personalized vaccine module

⸻

🧠 Personalized Immunotherapy Module

Cancertope supports:

🔹 Partially Personalized Mode

* Uses known cancer mutation profiles

🔹 Fully Personalized Mode

* Accepts:
    * Tumor genome
    * Normal genome

➡️ Outputs patient-specific neoepitopes  ￼

⸻

📦 Dataset Access

Mutation dataset available at:

👉 https://figshare.com/articles/CANCERTOPE_MUTATION_DATASET_txt/4176558  ￼

⸻

📊 Key Statistics

Category	Details
Cancer Cell Lines	905
Vaccine Candidates	60
Mutation Types	Missense, Frameshift, Indels
Epitope Types	CD8+, CD4+, B-cell
Target Use	Cancer Immunotherapy

⸻

🎯 Applications

* Cancer vaccine design
* Neoantigen discovery
* Immunotherapy research
* Personalized medicine
* Computational oncology

⸻

⚠️ Limitations

* Predicted epitopes require experimental validation
* HLA binding ≠ guaranteed immune response
* Risk of cross-reactivity must be evaluated  ￼

⸻

🧠 Citation

If you use Cancertope, please cite:

Gupta et al. (2016)
A Platform for Designing Genome-Based Personalized Immunotherapy or Vaccine against Cancer
PLOS ONE
DOI: 10.1371/journal.pone.0166372  ￼

⸻

📧 Contact & Authors

Developed under the Open Source Drug Discovery (OSDD) initiative

Prof. Dr. Gajendra PS Raghava
raghava@iiitd.ac.in

Website: http://www.imtech.res.in/raghava/cancertope/  ￼

⸻

📄 License

Distributed under:
Creative Commons Attribution License (CC BY 4.0)  ￼

⸻

🙏 Acknowledgements

Supported by:

* OSDD Project
* GENESIS (BSC0121)
