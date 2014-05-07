fq_utils
========

This is a bundle of scripts designed to manipulate fastq and fastq files.

* fq_fakeqv
* fq_split
* fq_translate
* randseq
 

And useful scripts from other devs:
* genbankdownload.py

### fq_fakeqv
This tool allows you to transform a fasta file into fastq by generating simulated quality values. You can also include gaussian noise into the quality value.


### fq_split
This tool splits a single genome fasta file into ordered read with overlap. 

### fq_translate
This script can translate the quality values from illumina 1.5 to illumina 1.8, and vice-versa.

### randseq
This tool samples random reads from a single genome fasta file (similar to fq_split, but random).


### Genbankdownload.py
This program downloads the genome file corresponding to a Genbank ID and displays it in the correct format.
