# Week of 7/12: Read Bismark User Guide, Trim Galore's RRBS Guide, "DNA methylation of intragenic CpG islands" by Jeziorska, 2017.
# Week of 7/19: Read Thadeous's "Same Difference," 2018, "Enhanced Reduced Representation Bisulfite Sequencing," Garrett-Bakelman, 2015.
# Week of 7/26: Began working with Metabase, read user guide, used simple questions to make four graphs based on those in Epilims home.
# Week of 8/9: Used custom questions to replicate questions in Epilims home, used SQL to graph mapping efficiency based on CpG coverage. Used SQL to attempt to graph mapping efficiency based on read length. Found that "sequencing_assays" library in EpiLIMS was inaccessible.
# Week of 8/16: Used custom questions in combination with SQL to graph CpG coverage at 10x against millions of total reads. Discovered issue with "NA" values in total_reads column, hard coded to exclude values. Modified mapping efficiency based on CpG coverage to include only reads between 50 and 150 million.
