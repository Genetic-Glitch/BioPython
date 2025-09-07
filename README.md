# BioPython
For BioPython-based analysis projects


# 🧬 Pairwise Protein Alignment: RBP4 in Human vs. Rat

This repository contains a Google Colab notebook that performs **pairwise alignment** of the **RBP4 protein sequences** from **human and rat**, using Biopython. It includes scoring comparisons using different substitution matrices and visualizations to interpret evolutionary conservation.

---

## 📌 Features

- Load and align protein sequences using Biopython's `PairwiseAligner`
- Compare alignment scores using:
  - BLOSUM62
  - PAM250
- Generate heatmaps of substitution scores
- Interpret matrix behavior and conservation patterns

---

## 📊 Visualizations

- Heatmaps comparing BLOSUM62 and PAM250
- Highlighted conserved regions (e.g., W↔W)
- Diagonal contrast analysis between matrices

---

## 🧠 Interpretation Summary

- **BLOSUM62** favors identical matches and is ideal for closely related sequences.
- **PAM250** allows more substitution flexibility, suitable for distant evolutionary comparisons.
- **W↔W** (Tryptophan) is highly conserved and scored highest in both matrices.
- Diagonal brightness in BLOSUM62 indicates strong conservation; PAM250 is more permissive.

---

## 🛠 Tools Used

- Biopython
- Matplotlib
- NumPy
- Google Colab

---

## 🚀 How to Run

1. Open the notebook in Google Colab
2. Load the required FASTA files provided in the data
3. Run each cell sequentially
4. View alignment results and heatmaps

---

## 📁 Files Included

- `pairwise_alignment_rbp4.ipynb` – Main notebook
- `images/` – Folder for heatmap outputs
- `requirements.txt` – Python dependencies
- `data/` - Folder for FASTA files

---

## 📜 License

This project is open-source under the MIT License.

---

## 🙌 Acknowledgments

Thanks to Biopython and the open-source community for enabling powerful bioinformatics tools in Python.

---

