# CS703 Final Submission

**Project:** Sentiment Analysis of Amazon Product Reviews Using NLP  
**Student:** Nawaz Shareef Mohammed

---

# Project Structure

On a Windows machine, create the following directory:

```text
C:\CS703\
```

Place the following files directly inside the folder:

```text
C:\CS703\
│── CS703_Final_Combined_Project_Revised.ipynb
│── Reviews.csv
│── README.md
└── requirements.txt
```

> **Important:** Do **not** rename `Reviews.csv`. The notebook expects the dataset at:

```text
C:\CS703\Reviews.csv
```

---

# Installation

Open **Command Prompt** and install the required Python packages:

```bash
py -m pip install -r C:\CS703\requirements.txt
```

### Optional: Install the spaCy Language Model

```bash
py -m spacy download en_core_web_sm
```

> **Note:** The spaCy language model is optional. If it is unavailable, the notebook automatically uses a deterministic fallback and continues without requiring any downloads.

---

# Running the Project

1. Launch **Jupyter Notebook** or **JupyterLab**.
2. Open:

```text
C:\CS703\CS703_Final_Combined_Project_Revised.ipynb
```

3. Select:

```
Kernel → Restart Kernel and Run All Cells
```

4. Allow the preprocessing (50,000-review normalization) and model training cells to complete.
5. Verify that the notebook finishes without any red traceback errors.

---

# Generated Files

Running the notebook will automatically generate:

```text
C:\CS703\
│── phase3_final_dataset.csv
│
├── outputs\
│
└── model_artifacts\
```

---

# Dataset

Include **Reviews.csv** with the notebook submission so the assessor does **not** need any additional account, login, or credentials.

For dataset provenance, see the Stanford SNAP project:

https://snap.stanford.edu/data/web-FineFoods.html

---

# Important Notes

- The Stanford SNAP dataset is distributed in a different raw format. This project requires the provided **Reviews.csv** file.
- All notebook paths are configured to use:

```text
C:\CS703\
```

Do **not** move the dataset to another location such as:

- Downloads
- Desktop
- Colab
- Kaggle
- `data/`

- Every major visualization in the notebook is followed by an explanation discussing:
  - Business implications
  - Model selection
  - Deployment considerations
  - Monitoring recommendations

---

# Requirements

- Python 3.x
- Jupyter Notebook or JupyterLab
- Packages listed in `requirements.txt`

---

# Submission Checklist

- `CS703_Final_Combined_Project_Revised.ipynb`
- `Reviews.csv`
- `requirements.txt`
- `README.md`

All files should be placed directly inside:

```text
C:\CS703\
```
