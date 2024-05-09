# fMRI-Analysis-on-Flanker-Task-Using-SPM12

This repository contains code for the fMRI 1st level Analysis on Flanker Dataset Using SPM12 on Subject-09. Key components are:

- Flanker Task
- Preprocessing: Realignment, Slice Time Correction, Co-registration, Segmentation, Normalization, Smoothing.
- 1st level analysis (Checking the Increase in bold signal when the subkect was shown an incongurent task)
- Using P value statistic to ensure confidence of not obtaining False Positive

## Requirements

- Matlab
- SPM12 Package
- Matlab Machine Learning Toolbox
- Flanker Task Dataset

## Installation

 **SPM12**
   - Follow the instructions in the [SP12 Package](https://www.fil.ion.ucl.ac.uk/spm/software/download/) to install SPM12.

  **Flanker Task**
  - Obtained from [Openfmri.org](https://openfmri.org/s3-browser/?prefix=ds000001/ds000001_R1.0.0).

## Usage

1. Launch Matlab.
  
2. Navigate to the SUB-09 files:
```
cd ds102/sub-09
```
3. Open SPM12:
```
SPM FMRI
```

## Team Members
1. Sohaib Nasir
2. Nauman Asif

