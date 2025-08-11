# PRODIGY_ML_05
Food Classification using CNN 

# Task 5 — Food-101 Image Classification (Transfer Learning)

**Project:** Food-101 image classification using EfficientNetB0 (transfer learning).

**Dataset:** Food-101 (101 food categories). Loaded via TensorFlow Datasets (TFDS).  
**Local TFDS cache path:** `C:\Users\admin\tensorflow_datasets\food101\2.0.0`

## Quickstart
1. Install: `pip install tensorflow tensorflow-datasets matplotlib seaborn`
2. Run the notebook cells in order. If dataset is cached as above, TFDS will use the local copy.
3. For quick testing, run in `SAMPLE_MODE` (5% sample). Set `SAMPLE_MODE = False` for full dataset.

## Results
- Model: EfficientNetB0 (frozen base) + small classifier head
- Quick-run accuracy (sample): *X%* (replace with your value after training)
- Notes: Increase epochs and unfreeze base_model for better performance

## Files
- `notebook.ipynb` — Jupyter notebook (cell-by-cell)
- `food101_sample_predictions.png`
- `food101_confusion_matrix.png`
- `food101_classification_report.png`

## Next steps
- Unfreeze some EfficientNet layers and fine-tune
- Use data augmentation for robustness
- Deploy as a simple web app (Streamlit / Flask)
