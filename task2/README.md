# 🧬 Task 2: Multiple Sequence Alignment (MSA)

## 🎯 Objective
To perform Multiple Sequence Alignment (MSA) on Immunoglobulin protein sequences across multiple species using Clustal Omega, identify conserved amino acid residues/motifs, and interpret structural and functional conservation.

---

## 🛠️ Tools & Databases Used
* **Database:** UniProt / NCBI Protein Database
* **Alignment Tool:** Clustal Omega (EMBL-EBI)
* **Protein Family:** Immunoglobulin Heavy Constant Gamma (IGHG1) across mammalian species

---

## 📋 Step-by-Step Execution
1. **Sequence Retrieval:** Downloaded FASTA sequences of Immunoglobulin Heavy Chain/Gamma from 5 distinct species (*Homo sapiens*, *Mus musculus*, *Rattus norvegicus*, *Oryctolagus cuniculus*, and *Bos taurus*).
2. **MSA Execution:** Submitted the combined FASTA file to Clustal Omega to generate residue-level alignments.
3. **Motif & Conservation Analysis:** Examined alignment output symbols (`*`, `:`, `.`) to locate conserved cysteine residues responsible for characteristic immunoglobulin domain disulfide bonding and structural stability.

---

## 📊 Results & Interpretation
* **High Conservation Zones:** Core beta-sheet frameworks and conserved cysteine residues essential for the immunoglobulin fold showed high identity across species.
* **Variable Regions:** Loop regions showed sequence divergence, reflecting evolutionary adaptations in antibody binding specificities.

---

## 🖼️ Visual Proofs & Screenshots
![MSA Alignment Result](images/msa_alignment_view.png)

---
