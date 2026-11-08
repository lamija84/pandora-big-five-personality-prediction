# PANDORA personality prediction experiments

This repository accompanies the revised study on Big Five personality prediction from Reddit text. The files are separated by purpose so that earlier exploratory runs are not mistaken for the final evaluation.

## Files

- `PANDORA_Final_Organized_Notebook.ipynb`: the main record of the revised author-level experiments, including four regression models, held-out evaluation, uncertainty checks, frozen SBERT, XGBoost vocabulary-size sensitivity, and comment-count ablation. Python code is preserved; saved execution outputs have been cleared before public release to reduce the risk of exposing dataset records or author identifiers.
- `PANDORA_Results_Summary.ipynb`: a read-only, immediately visible collection of key recorded result tables. No model training is needed to view it. Each section identifies the source analysis in the main notebook.

## Data and reproduction

The main notebook expects the original PANDORA data and saved intermediate files under `/content/drive/MyDrive/PANDORA_Original/`. These datasets and artifacts are not distributed here. Access to PANDORA must comply with the dataset authors' terms; do not publish raw author comments or identifiers without permission.

The main notebook retains its original execution order and code, including cells that expect artifacts from earlier runs. It is an experimental record rather than a verified clean-runtime, one-click reproduction script. The summary notebook is for inspecting results, not generating them. Later Colab environment versions are not necessarily the versions used for every earlier run.

The paper provides the interpretation of the results. In particular, supplementary ablation numbers should not be conflated with the primary cross-validation-selected model comparison.

## Public release note

This repository omits the historical exploratory notebook and all original datasets. The main notebook is not verified as a clean-runtime, end-to-end reproduction pipeline. Inspect any new outputs before committing them.
