# Blood Transcriptomics for Precision Medicine

This project applies transcriptomic analysis of human blood and brain metastasis samples to uncover cell-type-specific expression signatures relevant to **inflammation**, **neurodegeneration**, and **digital phenotyping**.
This notebook explores how gene expression can inform **P4 medicine** (Predictive, Preventive, Personalized, and Participatory).

---

## 📂 Data Sources
- **GSE63060** — Normalized blood transcriptomic data
- **GSM5645890** — Brain metastasis single-cell RNA-seq data with cell type annotations
---

## Project Goals
- 🔎 **Visualize and cluster** cell types by gene expression
- 🧬 **Compare inflammation-related and Alzheimer’s genes** across immune and stromal cells
- 🧮 Apply **PCA and KMeans** to define digital phenotypes
- 🧪 Score **inflammatory burden** per cell type
- ⚙️ Enable **gene panel selection** interactively
---
## 📈 Key Analyses

| Method | What It Does |
|--------|---------------|
| 🧼 Data normalization | Ensures comparability across samples |
| 🔁 Gene symbol mapping | Links probe IDs to gene names |
| 🔥 Heatmaps & PCA | Visualize top 20 variable genes |
| 🧠 Alzheimer’s panel | APP, MAPT, APOE, TREM2 etc. |
| 🧬 Inflammation score | IL1B, IL6, TNF, CXCL8 summed |
| 🔍 Clustering | KMeans on PCA of grouped cell types |
---
## Output Preview
---
## 🚀 How to Use

1. Open the [notebook here](notebooks/Blood_Transcriptomics_Analysis.ipynb)
2. Follow markdown explanations step-by-step
3. When prompted, choose genes of interest interactively
4. Review plots and interpretation
---
## 💥 Relevance to Systems Biology

This project reflects principles of **data-driven systems medicine**:
- Integrates data from **bulk and single-cell** studies
- Uses **dimension reduction** + unsupervised clustering
- Builds **quantitative cell-type signatures** for immune/inflammatory profiling
---

## Author

**Zareen Rahman**
---

## 📄 License
MIT License – feel free to use or extend this work.
