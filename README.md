# 🧬 Covid-19 Genomic Analysis Suite

![Platform](https://img.shields.io/badge/Platform-Windows-blue)
![Type](https://img.shields.io/badge/Type-Executable-green)
![Status](https://img.shields.io/badge/Source_Code-Coming_Soon-yellow)

A professional bioinformatics dashboard for analyzing and aligning SARS-CoV-2 genomic sequences. This repository currently hosts the compiled **Windows Executable (.exe)** and necessary datasets, allowing users to run the analysis tool immediately without installing Python or dependencies.

## 🚀 About The Project
This tool implements the **Needleman-Wunsch algorithm** from scratch to perform global sequence alignment between the Wuhan-Hu-1 reference genome and variants like the Bat CoV RaTG13. It is designed for researchers and students to visualize genomic data interactively.

### Key Features
* **3D Visualization:** Interactive 3D surface plot of the alignment scoring matrix.
* **Sequence Alignment:** Global alignment with adjustable gap penalties.
* **Phylogenetics:** Generates Dendrograms to visualize evolutionary relationships.
* **Mutation Tracking:** Automatically detects and graphs mutation frequencies.
* **Export Ready:** One-click export for all analysis graphs and reports.

---

## 📥 How to Run (No Python Required)

Since this is the standalone version, you do **not** need to install Python or any libraries.

1.  **Download the Executable:**
    * Download the file `Covid-19_Genomic Analysis.exe` from this repository.
2.  **Download the Data:**
    * Download the `data/` folder (containing `MN908947.fna` and `coronavirus.fasta`).
3.  **Setup:**
    * **Crucial:** Place `Covid-19_Genomic Analysis.exe` and the `data/` folder in the **same directory** on your computer.
4.  **Run:**
    * Double-click `Covid-19_Genomic Analysis.exe` to launch the application.
    * Click **"Load Datasets"** to begin analysis.

---

## 📂 Repository Structure

* `Covid-19_Genomic Analysis.exe`: The main application (compiled).
* `data/`: Required genomic dataset files.
    * `MN908947.fna`: SARS-CoV-2 Wuhan-Hu-1 (Reference).
    * `coronavirus.fasta`: Bat Coronavirus (Comparison Sample).

---

## 🔜 Upcoming
The full Python source code (`main.py`) and development documentation will be uploaded to this repository shortly. This will allow developers to modify the algorithms and compile the application themselves.

---
*Developed for Numerical Computing Project.*
