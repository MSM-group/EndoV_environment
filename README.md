# EndoV_environment
The data included here is a sequence similarity search of EndoV protein sequecnes in environmental metagenomes, with a focus on endonucleases which showed activity for modified oligonucleotide substrates.

1. Query protein sequences belonging to members of the EndoV family were obtained from the Supplementary material from the published article of Moody, E., Obexer, R, Nickl, F., Spiess, R., and Lovelock, S.L. An enzyme cascade enables production of therapeutic oligonucleotides in a single operation. *Science* **380**, 1150-1154 (2023). DOI:[10.1126/science.add5892](https://dx.doi.org/10.1126/science.add5892)

3. The terminal hexahistidine tag and linker 'LE' were removed. The trimmed sequences are available at [EndoV_prot_query_seqs.faa](https://github.com/MSM-group/EndoV_environment/blob/main/EndoV_prot_query_seqs.faa).

4. The sequences were used to search three separate databases on 20.06.2025:
	- National Center for Biotechnology Information non-redundant proteins derived from environmental samples: [env_nr]([https://blast.ncbi.nlm.nih.gov/Blast.cgi](https://blast.ncbi.nlm.nih.gov/Blast.cgi?PROGRAM=blastp&PAGE_TYPE=BlastSearch&LINK_LOC=blasthome)
	- European Bioinformatics Institute - [EBI MGnify](https://www.ebi.ac.uk/metagenomics/sequence-search/)
	- EMBL Global Microbial Gene Catalog - [GMGC](https://gmgc.embl.de)

5. Tables of hits corresponding to sequences which are similar to the EndoV query sequence(s) are saved and deposited here. For each database query, significant hits were obtained. In cases where environmental metadata could be directly linked, the hits corresponded to a wide diversity of habitats including soil, marine, and wastewater. From this analysis, we can infer EndoV-like sequences are widely detected at least in the sequencing data deposited in public databases.
