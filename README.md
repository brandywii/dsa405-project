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

1. **EPA eCFR (Title 40 & 180.364):** Federal regulations defining maximum allowed glyphosate residue tolerances (ppm) across conventional and GMO agricultural commodities. *(Scraped via eCFR API)* Data can be downloaded as pdf from https://www.ecfr.gov/current/title-40/chapter-I/subchapter-E/part-180/subpart-C/section-180.364
2. **USDA PDP (Pesticide Data Program):** Empirical sampling and laboratory testing data measuring actual pesticide residues on food products. *(Filtered via CSV download)* Data can be retrieved from https://apps.ams.usda.gov/pdp

---

## Requirements & Setup
Install the latest version of Python to your machine \
Install Visual Studio Code (VS Code) \
Install the required Python3 libraries:
1. numpy
2. pandas

## How to Use Project File
*Option 1: Google Colab*
1. Click on **`DSA405_002_FA26_P2_bdwilki2.ipynb`** Google Colab Notebook in the Main branch
2. Select the **`Download`** icon at the top right corner
3. Go to URL https://colab.research.google.com/ and click on **`File`** then **`Upload Notebook`**
4. Once you upload the notebook and open it you want to select **`Run All`** button or **`Ctrl+F9`** to run all cells in notebook

*Option 2: Open in Visual Studio Code code editor*
1. Download Visual Studio Code to your machine at https://code.visualstudio.com/
2. Click on **`DSA405_002_FA26_P2_bdwilki2.ipynb`** Google Collab Notebook in the Main branch and save it locally on your machine
3. Select **`File`** and then select **`Open File or Ctrl+O`**
4. Select file **`DSA405_002_FA26_P2_bdwilki2.ipynb`**
5. Once notebook is open, select **`Run All`** button or **`Ctrl+F9`** to run all cells in notebook
---
