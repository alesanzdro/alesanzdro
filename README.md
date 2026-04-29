<h1 align="center">Hi there, I'm Alejandro 👋</h1>

<h3 align="center">Bioinformatician &nbsp;·&nbsp; HPC Systems Administrator &nbsp;·&nbsp; Pipeline Engineer</h3>

<p align="center">
  Genomic Epidemiology &amp; Pathogen Surveillance @ <a href="https://www.fisabio.san.gva.es/">FISABIO</a> — Valencia, Spain 🇪🇸
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Bioinformatics-10%2B%20years-1f6feb?style=flat-square" />
  <img src="https://img.shields.io/badge/Focus-Genomic%20Surveillance-2ea043?style=flat-square" />
  <img src="https://img.shields.io/badge/Stack-Nextflow%20%7C%20Snakemake%20%7C%20Docker-da3633?style=flat-square" />
</p>

---

### 🧬 About me

I'm a bioinformatician with **10+ years of experience** in genomic data analysis and Linux/HPC administration. I work at the **EPIMOL group (FISABIO)** on the genomic surveillance program of the Valencian Community, where I split my time between **designing reproducible pipelines**, **keeping shared HPC infrastructure healthy**, and acting as the **technical bridge between the molecular epidemiology team and IT**.

I tend to identify as a problem solver — whether that means recovering a failed system at 11 pm, debugging an obscure pipeline error, or tracking down why a 10 GbE link suddenly stopped behaving. I care about solutions that are **robust, reproducible, and useful for the people who actually have to run them**.

- Currently working on respiratory viruses (**SARS‑CoV‑2, Influenza, RSV**) and antimicrobial resistance in clinical and foodborne pathogens, including ***Candida auris***.
- Previously: **WGS / WES + CNV analysis on FFPE prostate cancer** samples at **CNIO** under a US Department of Defense contract; transcriptomics & miRNA regulatory networks at **I2SysBio**.
- Hands‑on experience with **Nanopore (MinION / PromethION)** and **Illumina (MiSeq / NextSeq)**, plus epigenomics (modified base detection in *Neisseria gonorrhoeae*).
- Day‑job sysadmin for shared HPC servers (storage, GPU basecalling, NFS, Samba, networking, user management).

---

### ⭐ Flagship project — EPILIMS

> **A complete LIMS platform for molecular epidemiology**, designed and built from scratch to scale genomic surveillance across hospitals of the Valencian Community.

EPILIMS is my main ongoing project: a multi-container web application that centralises the full sample lifecycle — from reception and wet-lab tracking, to sequencing runs, to bioinformatic results across viral, bacterial and fungal pipelines.

- **Multi-container architecture** — Django web app, PostgreSQL database, reverse proxy, background workers, and pipeline integration, all orchestrated via Docker.
- **Designed for sensitive clinical data** — role-based access (lab, bioinformatics, hospital read-only), audit trail, and protection of personally identifiable patient information in compliance with GDPR / LOPDGDD.
- **Built around real surveillance workflows** — supports multiple pipelines per sequencing run, hybrid Illumina + Nanopore data, lineage assignment, AMR profiling, and per-hospital dashboards.
- **40+ tables, normalised schema** — patients, samples, wet-lab extractions, sequencing runs, pipeline executions and results, with materialised views for fast hospital-facing reporting.

---

### 🧪 Open-source pipelines

| Pipeline | Stack | Description |
|---|---|---|
| [**epitaxmag**](https://github.com/alesanzdro/epitaxmag) | Nextflow DSL2 · Nanopore | Modular environmental metagenomics pipeline: multi-tool taxonomic profiling, MAG recovery, virulence screening and AMR linkage. |
| [**epicandi**](https://github.com/alesanzdro/epicandi) | Snakemake · Illumina + ONT | WGS surveillance pipeline for *Candida auris* (assembly, polishing, annotation, AMR mutations, alternative genetic code). |
| [**epibac**](https://github.com/EpiMol/epibac) | Snakemake · Python | Bacterial genomic analysis pipeline: assembly, MLST, virulence and antimicrobial resistance characterisation. |
| [**DGSPefsa**](https://github.com/alesanzdro/DGSPefsa) | Python · Bash | Foodborne pathogen surveillance — supporting routine reporting in collaboration with public-health authorities. |

---

### 🧰 Tech stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

**Workflow & pipelines**

![Nextflow](https://img.shields.io/badge/Nextflow-0DB7ED?style=for-the-badge&logo=nextflow&logoColor=white)
![Snakemake](https://img.shields.io/badge/Snakemake-039475?style=for-the-badge&logo=snakemake&logoColor=white)
![nf-core](https://img.shields.io/badge/nf--core-24B064?style=for-the-badge&logo=nextflow&logoColor=white)

**Web & data**

![Django](https://img.shields.io/badge/Django%205-092E20?style=for-the-badge&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)

**AI & LLM — providers and models**

![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI%20%2F%20GPT-412991?style=for-the-badge&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![DeepSeek](https://img.shields.io/badge/DeepSeek-4D6BFE?style=for-the-badge&logo=deepseek&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![Hugging%20Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Llama](https://img.shields.io/badge/Llama%20%2F%20Qwen%20%2F%20Mistral-0467DF?style=for-the-badge&logo=meta&logoColor=white)

**Agentic development & ML**

![Claude%20Code](https://img.shields.io/badge/Claude%20Code-1F1F1F?style=for-the-badge&logo=anthropic&logoColor=D97757)
![MCP](https://img.shields.io/badge/MCP-Model%20Context%20Protocol-6E40C9?style=for-the-badge&logo=anthropic&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-000000?style=for-the-badge&logo=cursor&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)

**Containers, environments & HPC**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Singularity](https://img.shields.io/badge/Singularity-1A237E?style=for-the-badge&logo=linuxfoundation&logoColor=white)
![Conda](https://img.shields.io/badge/Conda%2FMamba-44A833?style=for-the-badge&logo=anaconda&logoColor=white)
![SLURM](https://img.shields.io/badge/SLURM-FFA500?style=for-the-badge&logo=linux&logoColor=black)
![Lmod](https://img.shields.io/badge/Lmod-555?style=for-the-badge&logo=gnu&logoColor=white)

**Infrastructure & ops**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub%20Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![NFS](https://img.shields.io/badge/NFS%20%2F%20Samba-EE0000?style=for-the-badge&logo=files&logoColor=white)

---

### 🧠 Areas of expertise

- **Sequencing** — end‑to‑end Nanopore (MinION / PromethION) and Illumina (MiSeq / NextSeq) workflows, including duplex basecalling and modified base calling
- **Variant analysis** — germline, somatic and CNV calling, including challenging FFPE samples
- **Pathogen genomics** — viral lineage assignment, AMR, MLST, phylogenetics, outbreak investigation
- **Epigenomics** — methylation calling and modified base detection
- **Pipeline engineering** — Nextflow DSL2 & Snakemake, parallelization strategies, reproducible environments
- **Full-stack development** — Django / FastAPI web apps with PostgreSQL backends, deployed in Docker
- **AI-assisted engineering** — daily multi-provider LLM workflow (Claude, ChatGPT/OpenAI, Gemini, DeepSeek) and self-hosted open-weight models via **Ollama** (Llama, Qwen, Mistral, DeepSeek-Coder, Gemma). Hands-on **prompt engineering**, agentic coding with **Claude Code** and **Cursor**, custom **MCP servers** and integrations, and LLM-powered automation for pipeline scaffolding, code review and internal tooling. Comfortable embedding deep-learning components (neural basecallers, ML-based variant callers) into production bioinformatics pipelines.
- **HPC sysadmin** — SLURM, Lmod, conda/mamba, Docker / Singularity, NFS, Samba, RAID storage, networking
- **Troubleshooting** — pipelines, systems, networks, the occasional human

---

### 📊 GitHub stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=alesanzdro&show_icons=true&hide_border=true&theme=tokyonight&include_all_commits=true" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=alesanzdro&layout=compact&hide_border=true&theme=tokyonight&langs_count=8" />
</p>

<p align="center">
  <!-- Streak stats. If herokuapp ever stops working, swap the host for one of these mirrors:
       - https://streak-stats.demolab.com/
       - https://github-readme-streak-stats-eight.vercel.app/
  -->
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=alesanzdro&theme=tokyonight&hide_border=true" />
</p>

---

### 📫 Get in touch

<p>
  <a href="https://github.com/alesanzdro"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/sanzcarbonell/?locale=es_ES"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <!-- Add or remove badges as you like -->
  <!-- <a href="https://orcid.org/0000-0000-0000-0000"><img src="https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white" /></a> -->
  <!-- <a href="mailto:you@fisabio.es"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a> -->
</p>

---

<p align="center">
  <i>"Everything you do should be done with passion."</i>
</p>
