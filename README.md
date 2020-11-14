This is a Python program that takes as input a file containing DNA sequences in multi-FASTA format and answer the following questions:
How many records are in the file? 
What are the lengths of the sequences in the file? What is the longest sequence and what is the shortest sequence? Is there more than one longest or shortest sequence? What are their identifiers?
It is also able to identify all ORFs present in each sequence of the FASTA file
(ORF starts with a start codon (ATG), and ends with a stop codon (TAA, TAG or TGA))
It organise all the ORF their nucleotide and protein sequences in a dataframe and find the sequences aligning with a chosen sequence
