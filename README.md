# WasteWise AI

AI-Powered Household Waste Segregation & Sustainability Assistant

## Overview
WasteWise AI is a web-based AI decision-support prototype for household waste segregation. Users enter a natural-language description of a waste item, and the system predicts its waste category and provides practical disposal or recovery guidance.

## AI Method
- Natural Language Processing (NLP)
- TF-IDF feature extraction
- Logistic Regression multi-class classification
- Curated household-waste dataset
- Streamlit interface

## Supported Categories
Plastic, glass, paper, organic waste, e-waste, hazardous waste, metal, textiles, and other.

## Technology Stack
Python, Streamlit, scikit-learn, Pandas, Joblib, TF-IDF, Logistic Regression.

## Sustainability Alignment
Primary: SDG 12 — Responsible Consumption and Production.
Secondary: SDG 11 — Sustainable Cities and Communities; SDG 13 — Climate Action.

## Prototype Workflow
User description → TF-IDF features → Logistic Regression classifier → predicted category → disposal/recovery guidance.

## Important Limitation
This is an educational prototype trained on a small curated dataset. Its internal 5-fold cross-validation accuracy was 0.443 ± 0.057 and should not be interpreted as real-world performance.

## Future Scope
Image-based waste recognition, multilingual Indian-language support, larger locally validated datasets, and location-aware municipal collection guidance.

## Project Deliverables
The repository contains the project documentation and submission material. The presentation deck and prototype demonstration PDF are also available in the ChatGPT project package provided alongside this repository.
