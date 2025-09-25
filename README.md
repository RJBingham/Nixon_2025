# Computational Framework to Identify Beta Barrels in Borrelia Plasmid Proteome
Raw data and code associated with Nixon et al 2025 - Borrelia BBJ25 is a plasmid-encoded Omp85-family protein associated with a potential export system 

**list_of_borrelia_proteomes** - two files in tsv format listing all the target proteomes.
**uniprot_component_fasta_files** - a folder with fasta files corresponding to all individual components (plasmids and chromosomes) from the target proteomes. It is not necessary to download this folder, as the R-code will download these directly from Uniprot. 
**code** - a folder containing R-code. Part 1 of this code will allow the user to the download all the individual components contained in uniprot_component_fasta_files. Part 2 of this code will import the results from prediction algorithms (predtmmbb2, PSORTb, SignalP and TMHMM), then filter these results to predict beta barrels.
**results** - a folder containing the results from prediction algorithms (predtmmbb2, PSORTb, SignalP and TMHMM) for all proteins listed in the uniprot_component_fasta_files.
