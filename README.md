# Gene Expression Munger

A script for merging TCGA Level 3 RNAseq gene expression data (raw counts), along with the cwl.json files for use on the Seven Bridges Cancer Genomics Cloud.

To test locally, use: `python munger.py -f Gene_Exp_Test/* -c`

For testing the use of an index file: `python munger.py -r Gene_Exp_Test/test.index -c`