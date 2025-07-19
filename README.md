# Automated-Underwriting-Platform


This project is a Google Colab-based prototype of an AI-powered underwriting platform. It automates property risk assessment using document analysis, computer vision, and multimodal AI. It was designed to evaluate property conditions for insurance underwriting decisions.

---

##  Project Description

The platform performs the following key tasks:
- Extracts key fields from property appraisal reports (PDFs)
- Analyzes images of property to detect damage conditions
- Uses a multimodal transformer (CLIP) to compare text descriptions with images
- Applies underwriting rules based on extracted information and visual findings
- Outputs an automated decision: Approved / Rejected / High Risk

---

##  Features

| Feature                   | Description |
|--------------------------|-------------|
|  Document Analysis     | Uses `pdfplumber` to extract text from PDF reports |
|  Structured Extraction | Extracts address, year built, and damage mentions using regex |
|  Image Analysis        | Uses `OpenCV` and `CLIP` for visual assessment |
|  Multimodal AI         | CLIP compares textual damage descriptions vs uploaded images |
|  Risk Assessment       | Rule-based logic to calculate risk levels |
|  Underwriting Decision | Final judgment based on rules and risk score |
|  Final Report Output   | Markdown summary including all extracted info and decision |

---

##  Tech Stack

- Python (Google Colab)
- `pdfplumber`, `pytesseract`
- `OpenCV`, `Pillow`
- HuggingFace `transformers` (CLIP model)
- `re` for regex-based NLP

---

##  Evaluation Criteria Covered

| Criteria                | Status |
|-------------------------|--------|
| Document Analysis       |  Done |
| Risk Assessment         |  Done |
| Guideline Compliance    |  Done |
| Multimodal Processing   |  Done |

---

##  Output Sample
Underwriting Summary Report

Address: 123 Elm Street

Year Built: 1980

Image Analysis Result: cracks on the wall

Risk Level: High Risk

Decision: ❌ Rejected

## Developed by: Sreeram Venkata Phani Kiranmai  

