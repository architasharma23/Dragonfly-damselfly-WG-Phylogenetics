# Dragonfly-damselfly-WG-Phylogenetics

Title1: Renaming Fastas
Step 1) Make a google sheet with accession numbers and taxa names for each gene (e.g. coi, 16s and 28s). Keep it ordered by Accession Number (A > Z).
Step 2) On your workstation. Make csv files with list of accesion numbers (e.g. coi.csv, 16s.csv, 28s.csv). Keep Accession list odereded (A > Z).
Step 3) Open Batch Enterez https://www.ncbi.nlm.nih.gov/sites/batchentrez. Upload your csv file here. Once results are loaded. Go to Send To > Complete Record > File > Format : Fasta > Sort by : Accession. This makes sure that downloaded Fasta has list of sequences in order A > Z by accession ID.
Step 4) Make Taxon list csv for each gene. This will have 3 columns = Taxon name (Scientific name goes here), GenBank (Accesion number goes here), name (this is the new name that will be given to each sequence). I like to add underscore here (e.g. Anax_ephippiger).
Step 5) Run the r script. Your renamed file be called "renamed_coi-dr-sequence" for example. Upload it in Geneious/MEGA for further alignment steps.
