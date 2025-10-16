### Session 1: End-to-End ML Hands-on (Titanic)

This repo contains a Colab-friendly notebook for an end-to-end ML workflow using the Titanic dataset with pandas and scikit-learn.

#### Folder structure
- `data/raw/` — optional local CSVs (`train.csv`, `test.csv`) for offline use
- `notebooks/01_titanic_end_to_end.ipynb` — main workshop notebook

#### Run in Google Colab (recommended)
1. Open the notebook in Colab.
2. Run the first "Install dependencies" cell. No `requirements.txt` needed.
3. Data options:
   - Preferred: update `TRAIN_URL` and `TEST_URL` variables in the Data Access section to public raw URLs (e.g., files hosted in your GitHub) and run the download cell.
   - Fallback: use the Upload helper cell to drag-and-drop `train.csv` and `test.csv`.

#### Run locally (offline)
1. Place `train.csv` and `test.csv` into `data/raw/`.
2. Open the notebook with Jupyter or VS Code.
3. Skip the URL download cell and use the local path option.

#### Notes
- The notebook includes detailed explanations for each step (EDA, preprocessing, modeling, evaluation, export) and learner TODOs.
- A mini-challenge at the end invites learners to engineer `FamilySize` and other features to improve accuracy.

