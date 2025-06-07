# 🧪 Bulk RNA-seq Analysis of Neutrophils Exposed to High NaCl

This repository contains selected code and visualizations from a bulk RNA-seq project analyzing the transcriptional response of human neutrophils exposed to hypertonic NaCl conditions.

⚠️ Full datasets and code are **not shared at this time** due to ongoing manuscript submission.

---

## 🧬 Project Summary

- **Model**: Human neutrophils stimulated with high extracellular NaCl
- **Goal**: Identify transcriptional changes and uncover NaCl-induced immune programs
- **Tools**: DESeq2, fgsea, EnhancedVolcano, ggplot2, pheatmap

---

## 🧪 Analysis Overview

- Differential expression analysis using **DESeq2**
- Derivation of NaCl-responsive gene signatures
- Functional enrichment via **GSEA (fgseaMultilevel)** using curated KEGG pathways
- Visualization of DEGs and enriched biological processes

---

## 📊 Example Output

### Volcano Plot
*(DEGs in NaCl-stimulated neutrophils vs. control)*  
![Volcano Plot](figures/volcano_plot_NaCl.png)

---

### GSEA Barplot
*(Top 30 enriched KEGG pathways sorted by Normalized Enrichment Score)*  
![GSEA Plot](figures/na.vs.control.GSEA.BAR.PLOT.png)

---

## 📁 Repository Structure

- `/code`: Partial scripts used for analysis and plotting  
- `/figures`: Final visualizations (non-reproducible for now)  
- `/results`: (Optional) Summary tables of top DEGs  
- `/data`: Not included due to confidentiality

---

## 📫 Contact

Feel free to reach out via [LinkedIn](https://www.linkedin.com/in/ignaciomazzitelli) if you're interested in the methodology, the dataset, or future collaborations.

[![ORCID](https://img.shields.io/badge/ORCID-0000--0001--9351--5799-a6ce39?logo=orcid&style=flat-square)](https://orcid.org/0000-0001-9351-5799)

---

🧪 *“Bridging biology and artificial intelligence through curiosity, critical thinking, and code.”*
