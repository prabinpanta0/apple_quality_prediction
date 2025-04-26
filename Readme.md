# Intelligent Prototype Development

![ISMT College Logo](https://www.collegenp.com/uploads/2024/07/ISMT-College-Kathmandu-Logo.png)  
*International School of Management & Technology (ISMT)*  
![University of Sunderland Logo](https://duckduckgo.com/i/c4c04274417f2077.png)  
*University of Sunderland – UK (Affiliated Institution)*

## Overview
This repository contains my final project for **CET313 – Artificial Intelligence** (BSc (Hons) Computer Systems Engineering) at ISMT College, affiliated with the University of Sunderland. The goal was to build an intelligent prototype.

## Contents
- `taining.ipynb` – Jupyter notebook with data download, preprocessing, model training & evaluation.  
- `apple_quality_model.keras` – Saved Keras model.  
- `apple_quality_prediction_results.json` – Sample inference outputs.  
- `apple-quality.zip` & `apple-quality/` – Raw dataset from Kaggle.  
- `LICENSE` – MIT License for this project.  
- `Readme.md` – This overview.

## Dataset
We use the “apple‑quality” dataset from Kaggle (https://www.kaggle.com/nelgiriyewithana/apple-quality). Before running, ensure you have Kaggle API credentials set up:
```bash
kaggle datasets download -d nelgiriyewithana/apple-quality
unzip apple-quality.zip
```

## Requirements
- Python 3.8+  
- `tensorflow`  
- `scikeras`  
- `pandas`, `numpy`

Install with:
```bash
pip install tensorflow scikeras pandas numpy
```

## Usage
1. Open and run `taining.ipynb` end‑to‑end.  
2. Export or load `apple_quality_model.keras` for inference.  
3. Use the JSON results or integrate into your own script.

## Project Structure
```
├── apple-quality/                # unzipped CSV dataset  
│   └── apple_quality.csv  
├── apple-quality.zip             # original download  
├── apple_quality_model.keras     # trained model  
├── apple_quality_prediction_results.json  
├── taining.ipynb  
├── LICENSE  
└── Readme.md
```

## Affiliations
**ISMT College, Butwal**  
- Branch of International School of Management & Technology, Nepal  
- Offers UK‑affiliated programmes—including BSc (Hons) in CSE—via Pearson Edexcel and University of Sunderland.

**University of Sunderland**  
- Public research university in Sunderland, England  
- Established 1901; offers a wide range of undergraduate and postgraduate programmes.  
- Official site: https://www.sunderland.ac.uk

## License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

*— Prabin Panta*

