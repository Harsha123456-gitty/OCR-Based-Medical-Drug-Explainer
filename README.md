# OCR-Based Medical Drug Explainer

Extracts drug names from prescription images with OCR, cleans text, matches to an internal drug list, and generates explanations. [web:45]

## Features
- OpenCV pre-processing for prescriptions. [web:43]
- Transformer OCR (TrOCR) for drug name extraction. [web:43]
- Text cleanup and spell-correction with ByT5. [web:43]
- RapidFuzz matching to an internal drug dataset. [web:43]
- Explanation generation using FLAN-T5. [web:43]

## Pipeline
![Pipeline](assets/WhatsApp-Image-2025-10-12-at-12.43.50_e92258ed.jpg) [web:50]

## Installation
- Python ≥3.10 and git installed. [web:50]
- Clone repo, create venv, and install requirements: [web:50]
