# mtbmasker

**mtbmasker** is a Python command-line tool designed to generate isolate-specific conservative genome masks for *Mycobacterium tuberculosis* (MTB) genomes. This is particularly useful for downstream variant calling and phylogenomic analyses by masking problematic genomic regions (e.g., PE/PPE genes, IS elements, and other repetitive loci).

---

## ✨ Features

- Generates genome masks per isolate using BLASTn alignment against predefined repetitive genes.
- Supports custom isolate genome files and gene query sets.
- Automatically formats coordinates to BED, sorts, and merges overlapping masked regions.
- Outputs high-quality, isolate-specific `.bed` files for genome masking.

---

## 🧬 Use case

This tool was originally developed for comparative genomics and transmission studies of *Mycobacterium tuberculosis* complex (MTBC) isolates, including *M. africanum*. It ensures that inter-lineage diversity is respected during masking.

---

## 🔧 Installation

### From GitHub (development version):

```bash
pip install git+https://github.com/EtienneNtumba/mtbmasker.git
