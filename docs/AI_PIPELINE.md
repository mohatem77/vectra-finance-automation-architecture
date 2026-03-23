# AI Processing Pipeline

## Overview

The AI pipeline is responsible for extracting and structuring invoice data.

---

## Pipeline Stages

### 1. Document Ingestion
- PDF upload
- Email ingestion
- API input

---

### 2. Preprocessing
- Image enhancement
- Noise reduction

---

### 3. OCR Processing
- Text extraction from document

---

### 4. Data Extraction
- Invoice number
- Supplier name
- Date
- Amount
- VAT
- Line items

---

### 5. Confidence Scoring
Each extracted field is assigned a confidence level

---

### 6. Output Structuring

Example:

```json
{
  "invoice_number": "INV-001",
  "amount": 2500
}
