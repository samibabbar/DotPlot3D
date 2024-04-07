## Using AnalysisTable3D

During the development of DotPlot3D, there was one clear issue for the limits in analysis, determining whether to plot the entire sequence or specific segments. When looking at a randomly generated set of sequences, there is a specified default length of 100 bp and has no issues in generating the plot. However when inputting custom FASTA sequences and determining similarities beyond approximately 1000 bp, the tool becomes difficult to interpret and needs specifications of specific regions. Therefore, AnalysisTable3D acts as a supplementary tool that specifies and identifies regions of interest prior to the plotting tool. 

With identifications of regions that have similarity within the sequence, users are able to easily spot specific ranges using the green highlights, looking further into specific regions. Since the dot plot itself has restrictions on length, AnalysisTable3D is a helpful alternative when starting with analysis.
