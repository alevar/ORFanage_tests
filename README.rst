This repository contains all experiments conducted for the ORFanage software. The notebooks should be sufficient to reproduce all results. 
The notebooks are written in Python 3.6 and use the following packages.

numpy
pandas
seaborn
scipy
matplotlib
upsetplot

The following notebooks are provided:

- align.ipynb - Performs alignment of default and re-annotated GENCODE ORFs to the MANE reference ORFs using EMBOSS STRETCHER. Contains comparison of ILPI and PI metrics.
- definitions.py - Common functions re-used in the notebooks. Each notebook imports this file.
- GeneMarkS-T.gencode.ipynb - Evaluation of GeneMarkS-T on the GENCODE annotation.
- GeneMarkS-T.refseq.ipynb - Evaluation of GeneMarkS-T on the RefSeq annotation.
- longest.mane.ipynb - Computes the number of MANE ORFs that are not the longest in their respective transcript.
- misc.ipynb - Number of transcript and number of unique ORFs per gene in different datasets.
- observations.ipynb - Various summaries. Pie charts of RefSeq and GENCODE canonical vs alternative ORFs and non-coding transcripts. Visualization of the experiment testing impact of reference completeness on the accuracy of results.
- run_arabidopsis.ipynb - Performs analysis of ORFanage on the A. thaliana reference annotation.
- run_celegans.ipynb - Performs analysis of ORFanage on the C. elegans reference annotation.
- run_gencode.ipynb - Contains all experiments and analysis of ORFanage using the GENCODE annotation.
- run_gtex.ipynb - contains evaluation of novel ORFs found in the brain tissue of the GTEx project.
- run_refseq.ipynb - Contains all experiments and analysis of ORFanage using the RefSeq annotation.
- transdecoder.gencode.ipynb - Evaluation of TransDecoder on the GENCODE annotation.
- transdecoder.refseq.ipynb - Evaluation of TransDecoder on the RefSeq annotation.
