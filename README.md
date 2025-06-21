# ECG Dummy Data

This repository contains dummy ECG data for training and testing purposes.

## Data Description

The dataset contains ECG recordings with the following beat classifications:

| Code      | What it really means                            | Typical pathology you can call                    |
| --------- | ----------------------------------------------- | ------------------------------------------------- |
| **N (0)** | Normal beat (includes LBBB, RBBB, atrial paced) | Baseline rhythm assessment.                       |
| **S (1)** | Supra-ventricular ectopic beat (PAC, aberrant)  | Atrial ectopy / SVT tendency.                     |
| **V (2)** | Premature ventricular contraction (PVC)         | Ventricular ectopy, possible cardiomyopathy risk. |
| **F (3)** | Fusion beat (normal + PVC collide)              | High PVC burden; can flag VT risk.                |

## Files

- dummy_data/F.csv: Fusion beat data
- dummy_data/N.csv: Normal beat data
- dummy_data/S.csv: Supra-ventricular ectopic beat data
- dummy_data/V.csv: Premature ventricular contraction data

