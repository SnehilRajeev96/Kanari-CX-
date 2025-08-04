# Digital CX Maturity Sentiment Analysis

A Python‐based demonstration of  sector‐by‐sector Customer Experience (CX) maturity heatmap via sentiment analysis.  
This repo simulates expert interviews across three UAE sectors (Banking, Healthcare, Retail) at five CX stages, runs sentiment analysis on the transcripts, and produces a color‐coded heatmap matching the original “Digital Maturity by Sector/Stage” chart.

---

## 📝 Table of Contents

1. [Project Overview](#project-overview)  
2. [Features](#features)  
3. [Requirements](#requirements)  
4. [Installation](#installation)  


---

## 🎯 Project Overview

Many organizations track CX maturity across multiple stages and industries. This repo shows how you can:

- **Simulate** qualitative expert interviews  
- **Merge** responses by sector & stage  
- **Compute** sentiment polarity (with TextBlob)  
- **Map** polarity to maturity bands (`Low` → `High`)  
- **Visualize** results as an annotated heatmap  

---

## ⚙️ Features

- Structured transcript simulation (6 experts × 5 stages)  
- Automated sentiment analysis & threshold mapping  
- Pivoted DataFrame to align with your sector/stage matrix  
- Seaborn heatmap with custom annotation  

---

## 🛠️ Requirements

- Python 3.7+  
- [TextBlob](https://textblob.readthedocs.io/en/dev/)  
- pandas  
- matplotlib  
- seaborn  

You can install dependencies via:

```bash
pip install -r requirements.txt
