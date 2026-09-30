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
2. **USDA PDP (Pesticide Data Program):** Empirical sampling and laboratory testing data measuring actual pesticide residues on food products. *(Filtered via CSV download)*

---

## Requirements & Setup
Install the latest version of Python to your machine \n
**Install the required Python3 libraries:**
1. numpy
2. pandas
