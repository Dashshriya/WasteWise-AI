# WasteWise AI — Submission Content

## Title
WasteWise AI – AI-Powered Household Waste Segregation & Sustainability Assistant

## Problem Statement
Household waste is often mixed at the source because people are uncertain about how different or unfamiliar items should be segregated. When recyclable, organic, electronic and hazardous materials are mixed together, recycling and recovery become more difficult, while inappropriate disposal of e-waste and hazardous materials can create environmental risks. There is a need for a simple and accessible solution that can help individuals identify the appropriate waste category before disposal. WasteWise AI addresses this challenge by using natural-language processing and machine learning to classify waste items from short descriptions and provide practical disposal or recovery guidance. The project aims to encourage responsible consumption and better source-level waste segregation while demonstrating how AI can support everyday sustainability decisions.

## Solution
WasteWise AI is a web-based AI decision-support prototype for household waste segregation. Users enter a natural-language description such as “banana peel”, “empty shampoo bottle”, “old mobile phone” or “used battery”. The system processes the text using TF-IDF feature extraction and uses a Logistic Regression multi-class classifier to predict the appropriate waste category. The prototype supports categories including plastic, glass, paper, organic waste, e-waste, hazardous waste, metal and textiles. After classification, the application provides a recommended disposal or recovery action along with the model confidence and top predictions.

## Target Users
Households, students, schools and colleges, environmentally conscious individuals, residential communities, and organizations promoting responsible waste segregation.

## Impact
WasteWise AI aims to improve awareness and decision-making at the point where waste is generated. By helping users distinguish between recyclable, organic, e-waste and hazardous materials, the solution can support better source segregation and reduce contamination of recyclable waste streams.

## Technologies
Python, Streamlit, scikit-learn, TF-IDF, Logistic Regression, Pandas, Joblib, Natural Language Processing (NLP).
