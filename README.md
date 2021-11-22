# Week of 7/12: Read Bismark User Guide, Trim Galore's RRBS Guide, "DNA methylation of intragenic CpG islands" by Jeziorska, 2017.
# Week of 7/19: Read Thadeous's "Same Difference," 2018, "Enhanced Reduced Representation Bisulfite Sequencing," Garrett-Bakelman, 2015.
# Week of 7/26: Began working with Metabase, read user guide, used simple questions to make four graphs based on those in Epilims home.
# Week of 8/9: Used custom questions to replicate questions in Epilims home, used SQL to graph mapping efficiency based on CpG coverage. Used SQL to attempt to graph mapping efficiency based on read length. Found that "sequencing_assays" library in EpiLIMS was inaccessible.
# Week of 8/16: Used custom questions in combination with SQL to graph CpG coverage at 10x against millions of total reads. Discovered issue with "NA" values in total_reads column, hard coded to exclude values. Modified mapping efficiency based on CpG coverage to include only reads between 50 and 150 million.
# Week of 8/30: Normalized CpG coverage at 10x against millions of total reads, representing the number of CpGs per million reads. See graph1
# Week of 9/13: Attempted to exclude values with few data points using count function.
# Week of 9/20: Successfully graphed normalized CpG coverage per million reads using human (hg19 and hg38) genome, selecting for values with count greater than 10. See graph2
# Week of 10/4: Graphed normalized CpG coverage per million reads with mouse (mm9 and mm10) genome, as well as with ERRBS sequencing.
# Week of 10/11: Attempted to use joins to access data in sequencing_assays to complete missing or incomplete entries in errbs_pipeline. Graphed human ERRBS data and overlaid human and mouse graphs.
# Week of 10/18: Successfully used left join to join data in sequencing_assays with errbs_pipeline. Greatly increased the number of values in human category and produced a much smoother graph. See graph3
# Week of 11/1: Graphed CpG coverage with human ERRBS, RRBS, and RRoxBS data. RRoxBS yields consistently higher values at lower numbers of reads. 
# Week of 11/8: Graphed normalized mouse RRBS, mouse RRoxBS, and all WGoxBS. Graphed unnormalized CpG coverage for human RRBS and ERRBS. 
