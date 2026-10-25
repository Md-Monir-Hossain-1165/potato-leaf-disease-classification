# Potato Leaf Disease Classification

Submission package containing the paper, supporting report, and evaluation outputs for a potato leaf disease classification project.

## Google Colab notebook

The training and evaluation work was completed in this notebook: [Open the Google Colab notebook](https://colab.research.google.com/drive/1yti2clWmj8L_ELO61yU5_snd0p2WCWmI?usp=sharing#scrollTo=2b55c17e).

## Dataset

This project uses the potato leaf images from the [PlantVillage Dataset](https://github.com/spMohanty/PlantVillage-Dataset). The project uses three classes: early blight, late blight, and healthy potato leaves.

## Contents

- `01_Paper/` — final paper (`paper.pdf`)
- `02_Report/` — project report (`report.pdf`)
- `03_Results/Tables/` — model comparison and per-model classification reports
- `03_Results/Figures/` — sample images and evaluation plots, grouped by model
- `04_Archive/Duplicate_CSV_Exports/` — original duplicate CSV exports retained for reference

## Result summary

| Model | Accuracy | Macro F1 |
|---|---:|---:|
| Custom CNN | 96.28% | 94.19% |
| MobileNetV2 | 96.90% | 93.14% |

The canonical result tables are in `03_Results/Tables/`. Numbered CSV copies were confirmed identical to their corresponding canonical files and are retained only in the archive.

## Upload guidance

Upload this entire folder to Drive so that the paper, report, and supporting results remain together. For a simpler submission view, start with `01_Paper/paper.pdf` and `02_Report/report.pdf`.
