# Community-Invasion
Data analysis of microbial OTU tables to identify microbial invaders

The function files are designed to output numbers of interest, including OTU counts and percent abundance of OTUs in specific categories of samples (pipeline function (OTU count and abundance) and taxa identity of OTUs in specific categories taxa_strong_pipeline and taxa_weak_pipeline.

The iterate files are designed to loop through the function files multiple times. This allows to iterate through many different rarefactions at the same cut-off. Rarefaction cutoffs can be changed in the function file for comparison across different rarefactions. 

The invasion input tables are used to subset the overall OTU table-- these are represent samples from 12 different 'invasion' events, where microbial community inoculum was added to established 'resident' communities.

