DNA Sequence Analysis

A bioinformatics project focused on analyzing DNA sequence length and nucleotide composition using Python.

Overview

This project analyzes a collection of 87 DNA sequences to explore basic sequence characteristics and nucleotide composition.

The analysis was performed in Python using Biopython, pandas, and Matplotlib. The workflow includes reading FASTA data, processing aligned sequences, calculating sequence-level statistics, and generating visualizations.

Objectives

* Analyze DNA sequence lengths
* Calculate GC and AT content
* Determine A, T, G, and C nucleotide composition
* Explore variation across sequences using descriptive statistics
* Create clear visualizations of the results
* Practice a reproducible bioinformatics workflow

Methods

The analysis followed these main steps:

1. FASTA sequences were loaded using Biopython.
2. Alignment gaps were removed before sequence-level calculations.
3. Sequence length was calculated for each sequence.
4. GC and AT content were calculated.
5. A, T, G, and C nucleotide counts were determined.
6. Descriptive statistics were calculated using pandas.
7. Results were exported as CSV files.
8. The findings were visualized using Matplotlib.

Results

The analysis was performed on 87 DNA sequences.

Sequence Length

* Mean: 1437.95 bp
* Median: 1451 bp
* Standard deviation: 46.61 bp
* Minimum: 1285 bp
* Maximum: 1529 bp
* Range: 244 bp

GC Content

* Mean: 55.91%
* Median: 55.91%
* Minimum: 54.76%
* Maximum: 57.78%
* Lowest GC: gb|DQ341427.1 (54.76%)
* Highest GC: ref|NR_137420.1 (57.78%)

The relatively narrow GC content range indicates that the analyzed sequences have broadly similar nucleotide composition.

Nucleotide Composition

A, T, G, and C nucleotide counts were calculated across all 87 sequences. The overall nucleotide composition was visualized to compare the four nucleotide types across the dataset.

Visualizations

The project includes five final visualizations:

* Sequence length across the dataset
* GC content across DNA sequences
* AT content across DNA sequences
* Overall nucleotide composition
* GC content across sequences sorted by GC percentage

The figures are available in the figures directory.

Repository Structure

DNA-Sequence-Analysis/
│
├── data/
│   ├── 16SRNA_Deino_87seq.aln
│   ├── sequence_analysis_results.csv
│   ├── nucleotide_composition.csv
│   └── analysis_summary.csv
│
├── figures/
│   ├── sequence_length.png
│   ├── gc_content.png
│   ├── at_content.png
│   ├── nucleotide_composition.png
│   └── gc_content_distribution.png
│
├── DNA_Sequence_Analyzer.ipynb
└── README.md

Future Improvements

Possible extensions of this project include:

* Comparing multiple sequence datasets
* Adding additional sequence quality metrics
* Performing more advanced statistical analysis
* Exploring sequence similarity and evolutionary relationships

Author

Duru Menek

High school student interested in bioinformatics, computational biology, and data analysis.

This project was developed as an independent learning project to apply programming and data analysis techniques to biological sequence data.
