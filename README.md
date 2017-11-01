# Coevol_Conform_Migrat
MATLAB code for Zusai &amp; Lu "Poralization and segregation" paper.

1. Extract the zip file.
2. Run SingleSim1608.m for a one-shot simulation, as in Section 3.1 in the paper. It will load "FigJpegPrintNoLeg.m" to plot figures. It may take long time and huge memory to draw a figure like Fig 1-a,b in the paper, since the figure consists of as many independent points as the product of # periods and # agents (without any aggregation).
3. Run MonteCarloIndefEnd1608 for a Monte Calro simulation with changing the value of one parameter, as in Section 3.2 in the paper. It will load "FigJpegPrint.m" to plot figures.
