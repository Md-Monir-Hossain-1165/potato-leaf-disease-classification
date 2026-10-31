# Potato Leaf Disease Classification

Submission package containing the research paper, supporting project report, and evaluation outputs for an individual potato leaf disease classification project.

## Google Colab Notebook

The training and evaluation work was completed in this notebook:

[Open the Google Colab Notebook](https://colab.research.google.com/drive/1yti2clWmj8L_ELO61yU5_snd0p2WCWmI?usp=sharing#scrollTo=2b55c17e)

## Dataset

This project uses potato leaf images from the [PlantVillage Dataset](https://github.com/spMohanty/PlantVillage-Dataset).

Three classes were considered:
- Potato Early Blight
- Potato Late Blight
- Potato Healthy

The filtered dataset contains 2,152 images.

## Contents

- `01_Paper/` — Final research paper (`paper.pdf`)
- `02_Report/` — Individual project report (`report.pdf`)
- `03_Results/Tables/` — Model comparison and per-model classification reports
- `03_Results/Figures/` — Sample images, confusion matrices, ROC curves, and training evaluation plots
- `04_Archive/Duplicate_CSV_Exports/` — Original duplicate CSV exports retained for reference

## Result Summary

Both models were evaluated using the same held-out test dataset containing 323 images.

| Model | Accuracy | Macro Precision | Macro Recall | Macro F1 |
|---|---:|---:|---:|---:|
| Custom CNN | 94.12% | 90.45% | 93.32% | 91.78% |
| MobileNetV2 | 97.52% | 96.87% | 94.54% | 95.64% |

### AUC Summary

| Model | Early Blight | Late Blight | Healthy |
|---|---:|---:|---:|
| Custom CNN | 1.00 | 0.99 | 1.00 |
| MobileNetV2 | 1.00 | 1.00 | 1.00 |

MobileNetV2 achieved higher overall accuracy, macro precision, macro recall, and macro F1-score than the Custom CNN.

The canonical result tables are available in `03_Results/Tables/`. Numbered CSV copies were confirmed identical to their corresponding canonical files and are retained only in the archive.

## Upload Guidance

Upload the entire project folder to Google Drive to keep the research paper, individual report, and supporting evaluation results together.

For a simpler submission view, start with:

1. `01_Paper/paper.pdf`
2. `02_Report/report.pdf`