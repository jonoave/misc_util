# misc_util
Personal collection of small tools to manipulate sequence files

# files added
1. filterMinSpecies.py : 
   Checks the number of sequences in fasta file based on an input total and percent threshold.
   E.g if total is 60 and percent is 50, then the fasta file must have >= 30 sequenes or it will not be copied to output folder.

2. format_fasta_online.py:
   Converts a multi-line fasta into a single line fasta (i.e. >name, newLine, sequence). Just uses awk, so no dependencies on
   biopython or perl.
