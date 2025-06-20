# EndoV_environment
The data included in this repository demonstrate EndoV sequence distribution based on sequence similarity searching in environmental metagenomes

1. Query protein sequences belonging to members of the EndoV family were obtained from the Supplementary material from Moody, Obexer, Nickl and Lovelock [An enzyme cascade enables production of therapeutic oligonucleotides in a single operation](https://www.science.org/doi/10.1126/science.add5892) Science380,1150-1154(2023).DOI:[10.1126/science.add5892](https://dx.doi.org/10.1126/science.add5892)

2. The terminal hexahistidine tag and linker 'LE' were removed. The trimmed sequences are in at (EndoV_prot_query_seqs.faa)[https://github.com/MSM-group/EndoV_environment/blob/main/EndoV_prot_query_seqs.faa].

3. The sequences were used to search three separate databases on 20.06.2025:
	- National Center for Biotechnology Information proteins from metagenomic projects (env_nr)[https://blast.ncbi.nlm.nih.gov/Blast.cgi]
	- European Bioinformatics Institute [EBI MGnify](https://www.ebi.ac.uk/metagenomics/sequence-search/)
	- EMBL Global Microbial Gene Catalog [(GMGC)](https://gmgc.embl.de/search.cgi)

4. Tables of hits corresponding to sequences which are similar to the EndoV query sequence(s) are displayed here. For each database query, significant hits were obtained. In cases where environmental metadata could be directly linked, the hits corresponded to a wide diversity of habitats including soil, marine, and wastewater. From this analysis, we can infer EndoV-like sequences are widely found, at least in the sequencing data deposited in public databases.
