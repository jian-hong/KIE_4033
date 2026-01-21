# RM-19: AI-Powered Clinical Guidance System for Rural Primary Care
**KIE4033 Data Analytics | Assignment 2: Technical Report**

## 📌 Project Overview
**RM-19** is an Evidence-Based Clinical Practice Guidance (CPG) system designed to address healthcare accessibility bottlenecks in rural Malaysia. 

By integrating supervised machine learning (**XGBoost**) for symptom-based disease detection and unsupervised clustering (**HDBSCAN + UMAP**) for logistical friction analysis, this project provides a "Virtual Diagnostic" capability to triage high-risk COVID-19 patients in "medical deserts" where physical test kits are unavailable.

---

## 👨‍💻 Author Information
* **Group ID:** RM-01
* **Name:** OO JIAN HONG
* **Matric Number:** 22004678/1
* **Course:** KIE4033 Data Analytics (Semester 1, 2025/2026)

---

## 🛠️ Installation & Setup Guide

Follow these steps to set up the environment and run the analysis on your local machine.

### 1. Clone the Repository
Open your terminal or command prompt, navigate to your Desktop (or preferred folder), and clone the project:

```bash
cd Desktop
git clone <YOUR_REPOSITORY_URL_HERE>
cd <YOUR_PROJECT_FOLDER_NAME>

### 2. Create a Virtual Environment
Create an isolated Python environment to manage dependencies.

Windows / Mac / Linux:

Bash
python -m venv venv
### 3. Activate the Environment
Activate the virtual environment to ensure you are using the isolated Python instance.

Windows (PowerShell):

PowerShell
.\venv\Scripts\Activate.ps1
(Note: If you see a permission error, run Set-ExecutionPolicy Unrestricted -Scope Process first)

Windows (Command Prompt):

DOS
venv\Scripts\activate
Mac / Linux:

Bash
source venv/bin/activate
### 4. Install Dependencies
Install all required libraries (Pandas, NumPy, XGBoost, HDBSCAN, UMAP, Seaborn, etc.) using the requirements file:

Bash
pip install -r requirements.txt
🚀 How to Run the Analysis
Launch Jupyter Notebook In the same terminal where your environment is active, run:

Bash
jupyter notebook
### 5. Open the Main Notebook

The browser will open automatically showing the file directory.

Click on RM_19_Analysis_Notebook.ipynb.

Execute the Code

Once the notebook is open, go to the top menu bar.

Select Cell > Run All.

Alternatively: Click the "Fast Forward" (⏩) icon or "Restart & Run All" to execute the entire pipeline from Data Loading to Hybrid Risk Overlay.

📂 Project Structure
Plaintext
├── Data/
│   └── rm19_dataset_full.csv       # Primary dataset
├── RM_19_Analysis_Notebook.ipynb   # Main analysis code (XGBoost, Clustering, Overlay)
├── requirements.txt                # List of Python dependencies
└── README.md                       # Project documentation
