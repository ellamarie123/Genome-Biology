This repository includes the bash and python code used in the analysis of paired-end short read sequence data.

Code files:
- mean_coverage_plot_code.ipynb: The python code used to produce the mean coverage histogram.
- Shannon's_index.ipynb: The python code used to compute the microbial diversity of the prokaryotic consortia.
- comman_line_bash_code.txt: The command line bash code used on the Blue Pebble HPC system to analyse the sequence data.

Data files:
- coverage_report.txt: The output of samtools coverage detailing summary statistics for each contig, used as an input file for 'mean_coverage_plot_code.ipynb'.
- filtered_coverage_report.txt: The output of samtools coverage detailing summary statistics for each contig longer than 500bp, used as an input file for 'mean_coverage_plot_code.ipynb',
