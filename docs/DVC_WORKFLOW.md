# DVC Workflow for Dataset Versioning

## 1. Introduction

DVC (Data Version Control) is a tool used to manage and version large datasets and machine learning artifacts. Git is mainly used to track source code and small metadata files, while DVC tracks the actual data files.

In this experiment, DVC is integrated with Git to maintain different versions of the Iris dataset and reproduce previous dataset versions when required.

## 2. DVC Initialization

DVC was initialized inside the Git repository using:

```bash
dvc init
