# Fragment_Recruitment_Plotter
This is a script which generates a fragment recruitment plot. 

# ASSUMPTIONS: It is assumed that the file format will be in the SAM or PSL 
# format, with the extensions limited to .sam or .psl. It is assumed that there
# will be three input samples each run. To run just one or two samples, input
# the same sample multiple times. It is assumed that the input samples will
# have been aligned to the same Reference Genome, as the Ref. Genome name
# printed in the plotter will only display the ref genome from the last input
# sample. Due to the small scope of this project, it is assumed that .sam files
# were aligned via Bowtie2 and .psl files were aligned via FR-HIT. 

# The aligned reads have been named with a specific protocol as follows: 
# abau_4e.sam, aodo_is.psl, etc. If this format is followed, this program parses
# the input names to generate the legend labels and the graph reference genome
# name. If this format is not followed, the graph will still be generated,
# however, the aforementioned labels will revert to 'unknown' in the generated graphic. 

# Only the 10 reference genomes pertinent to this project are automatically
# parsed and displayed as their full scientific name. 

