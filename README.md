# processFASTQ

processFASTQ.ipynb is the main jupyter notebook used to process the fastq files from a paired-end MiSeq sequencing run, including paired-end joining to custom barcode demultiplexing are implemented in the jupyter notebook processFASTQ. Paired-end sequencing reads are joined using default parameters in PEAR. The version of pear that is used is v0.9.10 [May 30, 2016]. Pear can be downloaded from https://sco.h-its.org/exelixis/web/software/pear/

Example FASTQ data can be found at figshare <insert link>.
  Barcodes.txt file contains the custom barcode pairs (a pair of barcode sequence per row) needed for demultiplexing. It is to be modified  by user for specific barcodes used.
  
Output file at the end of running processFASTQ.ipynb is a .csv file containing unique sequences in the first column, followed by sequence read counts in each of the demultiplexed subsets of the sequences. This file can be further analyzed by scripts in the repository https://github.com/jsxiang/Ribozyme-RNA-seq or https://github.com/jsxiang/Ribozyme-FACS-seq.
