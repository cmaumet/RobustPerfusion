RobustPerfusion
===============
Estimate robust perfusion-weighted maps in Arterial Spin Labelling using Huber's M-estimator.


Call:
asl_robust(inputFiles, outputFile, huberParam)
where:
- inputFiles is the path to the repeated pair-substracted ASL volumes as a cell-array
- outputFile is the full path to the output file
- huberParam: is the parameter of Huber's M-estimator (1.5 by default)


Interactive call (with user interaction):
asl_robust()

Dependencies: SPM8 (or later), Matlab