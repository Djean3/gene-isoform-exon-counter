# gene-isoform-exon-counter
Unique Exon Analysis
This project analyzes gene structure diversity by summarizing the number of unique exons present across different isoforms for each gene. It uses the Polars library in Python for fast, scalable data aggregation, producing an output suitable for downstream biological interpretation or exploratory genomics work.

The input file contains gene names, isoform names, and exon identifiers. The output is a concise summary file listing each gene, isoform, and the corresponding count of distinct exons.

The purpose of this project is to explore how the structure of genes varies across isoforms by quantifying the number of distinct exons associated with each isoform.
By comparing exon counts within and across genes, researchers can gain insights into alternative splicing patterns and overall transcriptome complexity.

This type of summary is a critical first step in larger bioinformatics pipelines focused on isoform variation analysis, functional annotation, or evolutionary studies.
