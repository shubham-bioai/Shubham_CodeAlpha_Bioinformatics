# 🧬 Task 1: DNA/Protein Sequence Analysis

## 🎯 Objective
Retrieve a protein sequence from NCBI, perform a BLAST search to find homologous sequences, and document similarity, identity, alignment scores, and E-values.

---

## 🛠️ Execution Summary
* **Protein Selected:** Human Hemoglobin Subunit Beta (HBB)
* **Accession ID:** `NP_000509.1`
* **Query Length:** 147 amino acids
* **BLAST Program:** NCBI `blastp`
* **BLAST Request ID (RID):** `E6M2XSDZ014`

---

## 📊 Summary of Top Results

| Target Description | Organism | Query Cover | E-value | Percent Identity | Accession |
| :--- | :--- | :---: | :---: | :---: | :---: |
| **Hb Monza protein** | *Homo sapiens* | 100% | 2e-97 | 86.47% | `XEF57200.1` |
| **beta-globin** | *Homo sapiens* | 100% | 2e-93 | 93.20% | `AAA35597.1` |
| **hemoglobin subunit beta-like** | *Canis lupus familiaris* (Dog) | 100% | 1e-92 | 89.80% | `NP_001257812.1` |
| **hemoglobin subunit beta-like** | *Ailuropoda melanoleuca* (Panda) | 100% | 1e-92 | 89.80% | `NP_001291812.1` |
| **hemoglobin subunit beta** | *Rhynchonycteris naso* (Bat) | 100% | 2e-91 | 89.12% | `KAM8815943.1` |

---

## 🖼️ Proof & Screenshots

### 1. NCBI BLAST Search Summary
![BLAST Search Summary](images/blast_search_summary.png)

### 2. Significant Alignments Table
![BLAST Alignment Table](images/blast_results_table.png)

---

