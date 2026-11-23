# dsa405-project: Glyphosate residue in fast food inputs

**Author:** Brandy Wilkinson  
**Course:** DSA 405 (Fall 2026)  
**Repository:** `brandywii/dsa405-project`

---

## Project Overview & Research Question

Health-conscious consumers currently cannot easily access or compare pesticide surveillance data against federal regulatory tolerances. 

This project addresses this transparency gap by investigating:
> **Which primary raw fast-food ingredients contain the highest frequencies and concentrations of glyphosate, and how do those levels compare to EPA Maximum Residue Limits (MRLs)?**

By cross-referencing federal regulatory tolerances with empirical pesticide surveillance records, this project provides transparent, data-backed insights into consumer exposure to glyphosate when dining out.

---

## Data Sources

1. **EPA eCFR (Title 40 & 180.364):** Federal regulations defining maximum allowed glyphosate residue tolerances (ppm) across conventional and GMO agricultural commodities. *(Scraped via eCFR API)* 
2. **USDA PDP (Pesticide Data Program):** Empirical sampling and laboratory testing data measuring actual pesticide residues on food products. *(Filtered via CSV download)* Data can be retrieved from https://apps.ams.usda.gov/pdp

---

## Requirements & Setup
Install the latest version of Python to your machine \
Install Visual Studio Code (VS Code) \
Install the required Python3 libraries:
1. numpy
2. pandas
3. matplotlib.pyplot

---

## How to Use Project Files

All required datasets are loaded automatically when running the notebooks. No manual data downloads, path edits, or API keys are required.

### Option 1: Google Colab
1. Open the [dsa405-project](https://github.com/brandywii/dsa405-project/tree/main) repository (`main` branch).
2. Click on **`01_extraction_and_verification.ipynb`** and select the **`Download raw file`** icon in the top-right corner. Repeat for **`02_analysis_and_figures.ipynb`**.
3. Go to [Google Colab](https://colab.research.google.com/), click **`File`** $\rightarrow$ **`Upload notebook`**, and upload both files.
4. Open **`01_extraction_and_verification.ipynb`** first and select **`Runtime`** $\rightarrow$ **`Run all`** (or **`Ctrl+F9`**) to automatically load the raw PDP CSV, fetch the eCFR tolerances via REST API, run all 5 `assert` checks, and generate the merged dataset.
5. Open **`02_analysis_and_figures.ipynb`** and select **`Runtime`** $\rightarrow$ **`Run all`** (or **`Ctrl+F9`**) to reproduce all summary statistics and figures.

### Option 2: Visual Studio Code (Local)
1. Download and install [Visual Studio Code](https://code.visualstudio.com/) (with the Python and Jupyter extensions enabled).
2. Clone the repository or download **`01_extraction_and_verification.ipynb`** and **`02_analysis_and_figures.ipynb`** from the `main` branch to your machine.
3. In VS Code, select **`File`** $\rightarrow$ **`Open File...`** (or **`Ctrl+O`**) and open **`01_extraction_and_verification.ipynb`**.
4. Select the **`Run All`** button at the top of the notebook editor to execute all cells.
5. Repeat Steps 3–4 for **`02_analysis_and_figures.ipynb`**.

---
