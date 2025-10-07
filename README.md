# Mining Over 170,000 Uncultured Phage Genomes Reveals Novel Endolysins Active Against Multidrug-Resistant *Streptococcus pyogenes*

This repository provides supporting materials for the manuscript:

> **"Mining Over 170,000 Uncultured Phage Genomes Reveals Novel Endolysins Active Against Multidrug-Resistant *Streptococcus pyogenes*"**

---

## 📘 Repository Overview

This repository contains the commands used to identify and characterize **phage-encoded lytic proteins** — specifically **endolysins** and **holins** — from a large dataset of uncultured gut phage genomes.  

---

## 📂 Repository Contents

### 1. `commands.txt`
This text file contains all commands used for:
- Identifying endolysin and holin candidates  
- Characterizing these proteins using domain annotation, sequence similarity search, and signal peptide prediction.
- Predicting associated phage host
- Predicting phage life style

---

### 2. `identified_lytic_proteins.xlsx`
This Excel file contains detailed annotations of all identified endolysin and holin sequences, along with associated metadata.

#### Columns include:
| Column | Description |
|--------|-------------|
| **PHROG ID** | Protein family identifier from the PHROG database |
| **hmmscan E-value** | E-value of the best HMMER match |
| **hmmscan bit score** | Bit score from HMMER alignment |
| **Predicted Host Genus** | Host genus predicted using iPHoP |
| **Gram Stain of Predicted Genus** | Gram classification (positive/negative) of predicted host |
| **Predicted Phage Life Cycle** | Temperate, virulent or chronic |
| **Protein Sequence Length** | Number of amino acids |
| **Potential Endolysin Enzymatically Active Domain(s)** | Identified catalytic domains with description |
| **Potential Endolysin Cell Wall-Binding Domain(s)** | Identified CBDs with description |
| **Potential Holin Domain(s)** | Identified holin domains |
| **Endolysin Type** | Categorization of endolysin |
| **Holin Class** | Predicted holin class (I, II, or III) |
| **Amino Acid Sequence** | Full-length protein sequence |
| **Nucleotide Sequence** | Corresponding nucleotide sequence |
| **Domain Arrangement Present in InterPro (yes/no)** | Indicates if the domain combination exists in InterPro |
| **Domain Arrangement Represented By** | Representative accession if applicable |
| **Signal Peptide Prediction** | Predicted signal peptide if applicable |
| **Cleavage Site** | Predicted cleavage position if applicable |
| **BLASTp vs nr Best Hit Accession** | Accession of top BLASTp hit in NCBI nr database |
| **BLASTp vs nr Best Hit % Identity** | Percent identity to the best BLASTp hit |

---

## 📄 Citation

If you use or adapt the data or commands from this repository, please cite:

> Elbehery, A.H.A, *et al.* (2025). **Mining Over 170,000 Uncultured Phage Genomes Reveals Novel Endolysins Active Against Multidrug-Resistant *Streptococcus pyogenes*.**

(Full citation details will be updated upon publication.)
