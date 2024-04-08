## Using DotPlot3D

After identifying sequences and regions of interest, the plotting is complete using the DotPlot3D tool. Using varying colour options, similarities are shown between sequence 1/sequence 2, sequence 2/sequence 3, sequence 1/sequence 3, and all three sequences. At each plane, there is a different plot of similarities. The following table summarises how dot colour is determined:
Table 1: How colour corresponds to similarity in DotPlot3D

<img src="/3D analysis/images/table1.png">

Similarly, another feature is varying point size based on the presence of transitions and transversions. The current working version will identify these mutations based on the first sequence, and whether there is deviation in both sequence 2 and 3. The following table shows the type of change and whether there is a site of prominent mutation:

<img src="/3D analysis/images/table2.png">

Keeping these attributes in mind, the final 3D plot can be shown in Figure 1. This is an example of a randomly generated sequence of length 20, and shows how the plot can interpret similarities differently than the original method.

<img src="/3D analysis/images/exampleplot.png">
