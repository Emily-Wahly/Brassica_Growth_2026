Code for FastQC analysis:
fastqc /workdir/erw98/Brassica_Growth_2026/data/*.fastq.gz     --threads 5     -o /workdir/erw98/Brassica_Growth_2026/analysis/00_FastQC/fastqc_reports/
multiqc fastqc_reports/ -o multiqc_results/
