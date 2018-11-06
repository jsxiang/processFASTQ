# processFASTQ

processFASTQ.ipynb is the main jupyter notebook used to process the fastq files from a paired-end MiSeq sequencing run.

Example FASTQ data can be found at figshare <insert link>.
  Barcodes.txt file contains the custom barcode pairs (a pair of barcode sequence per row) needed for demultiplexing
  
Output file at the end of running processFASTQ.ipynb is a .csv file containing unique sequences in the first column, followed by sequence read counts in each of the demultiplexed subsets of the sequences. 
