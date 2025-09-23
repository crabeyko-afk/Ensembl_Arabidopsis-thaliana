# Ensembl Data for *Arabidopsis thaliana*

## Description
This repository contains genome and gene annotation data for *Arabidopsis thaliana* from Ensembl Plants.  
It demonstrates how to organize, version, and share bioinformatics data using GitHub and GitHub Desktop.  

## Data Sources
- [Ensembl Arabidopsis thaliana Genome](https://plants.ensembl.org/Arabidopsis_thaliana/Info/Index)
- Genome FASTA 
- Gene annotation GFF3

## Usage

### Downloading files
1. Go to Ensembl Plants → *Arabidopsis thaliana*  
   - Genome FASTA file (primary assembly) → place in `/genome/`  
   - Gene annotation GFF3 file → place in `/annotations/`  

### How to update annotation
1. Replace the old file in `/annotations` with the new version  
2. Commit and push changes with **GitHub Desktop** 

### Scripts included
- `example_script.py` (sample script for testing)  

## Version History
- **v1.0**: Initial genome and annotation files  
- **v1.1**: Updated annotation to Ensembl TAIR10.62

## GitHub Desktop Workflow
```bash
# Example workflow for pushing new files:
git add .
git commit -m "Add genome FASTA and annotation GFF3 for Arabidopsis thaliana"
git push origin main
