# 2PP-Test Artifact

This repository contains a test artifact (TA), also called test structure, designed for two-photon polymerization (also known as Direct Laser Writing (DLW) or Two/Multi-photon lithography (2PA/MPA)).
Test artifacts can be used to compare structures, to check options used by the slicer, check the state of the 2PP machine itself or to get a construction guidelines for a certain combination of power, velocity and settings.

General ideas behind the test artifact:

* optimized for 2PP-DLW
* should be fast and easy to analyse with optical microscopy or scanning electron microscopy without tilt.
* short time to fabricate
* include a reasonable amount of different features
* bulk and small structures on the substrate

## 3D model of Test Artifact:

The model of the test artifact can be downloaded as [.STL-file](https://github.com/BAMresearch/2PP-TestArtifact/blob/main/Test%20artifact.stl) or [.3mf-file](https://github.com/BAMresearch/2PP-TestArtifact/blob/main/Test%20artifact.3mf) from this repository. 

*Please note that the length are defined in Millimeters and have to be scaled according to your usage.*


## Features of the test artifact

<img src="FeatureOverview.png" width="500">


The following features are integrated in the current version of the test artifact.

| Feature Type | Name |Usage |
| :----: | :-------------: |------------- |
| 1  | Outer Ring  |Tilt analysis, Stitching artefacts |
| 2  | Version Indicator  |    |
| 3  | Z spacing  | estimation of free space in Z direction |
| 4  | Rods | reproducability of geometric shapes |
| 5  | Cones  | shutter properties |
| 6  | Immersion indicator  | immersion depth of TA  |
| 7  | Holes  | reproducability of geometric shapes |
| 8  | Thin Walls  | reproducability of geometric shapes  |
| 9  | Staircase Control  | staircase effect in different angles |
| 10  | Gaps  | reproducability of geometric shapes |
| 11  | Test Pad  |  analyse chemical, mechanical or structural properties |


## How to cite?

This work is currently available as preprint here: https://www.preprints.org/manuscript/202210.0259/v1

Please cite this work as:

> Fritzsche, S.; Pauw, B.R.; Weimann, C.; Sturm, H. First of its Kind: A Test Artifact for Direct Laser Writing. Preprints 2022, 2022100259 (doi: 10.20944/preprints202210.0259.v1).


After peer-review this part will be changed.

## Further ideas for optimization:

* independent individual features so they can be fabricated alone
* include a complex structure
