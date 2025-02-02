# AI-Powered Document Information Extraction and digitalization

A project to extract, digitize, and classify information from documents using OCR and deep learning.

---

## Overview

This project is designed to process experiment test papers by digitizing them, extracting key textual information, and classifying various document sections. By combining Optical Character Recognition (OCR) and advanced deep learning techniques, the system transforms traditional paper-based records into structured, easily searchable digital formats. The primary focus is on automating workflows, reducing manual effort, and enabling quick access to the desired information.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Key Techniques](#key-techniques)
- [Dataset](#dataset)
- [Workflow](#workflow)
- [Setup and Usage](#setup-and-usage)
- [Results](#results)
- [Contributors](#contributors)
- [License](#license)
- [Contact](#contact)

---

## Features ✨

- **Document Digitization:** Convert scanned test papers into high-quality digital images.
- **OCR Processing:** Extract text from scanned images, retaining layout information for accurate segmentation.
- **Text Classification:** Use deep learning to categorize document sections (e.g., headers, questions, instructions).
- **Quality Control Measures:** Employ confidence scores and edge-case handling for robust performance.
- **Data Structuring:** Output classified text into structured formats like JSON or XML.

---

## Key Techniques 🔍

- **Optical Character Recognition (OCR):** Extract raw text and layout metadata from scanned images.
- **Deep Learning for Classification:** Leverage models like CNNs for layout-based classification and transformers for text-based classification.
- **Preprocessing Pipelines:** Noise reduction, deskewing, and contrast enhancement for higher OCR accuracy.
- **Error Handling:** Automatic flagging of low-confidence results for manual review.

---

## Dataset 📂

The project uses a dataset of scanned experiment test papers that includes:

- **Raw Data:** Scanned images and PDFs of test papers.
- **Annotations:** Manually labeled sections (e.g., headers, instructions) for model training.
- **Positional Metadata:** Bounding boxes and layout information to improve classification accuracy.

---

## Workflow 🛠️

1. **Document Collection & Preprocessing:**  
   - Collect scanned test papers and apply preprocessing steps like noise removal and deskewing.
   
2. **OCR Extraction:**  
   - Convert processed images to text while capturing layout details.
   
3. **Deep Learning Classification:**  
   - Train models to segment and classify sections of text based on content and layout features.
   
4. **Validation & Quality Control:**  
   - Use confidence thresholds and manual review to ensure accuracy.
   
5. **Data Structuring & Integration:**  
   - Convert classified text into structured formats (e.g., JSON) and integrate into digital archives.

---

## Setup and Usage ⚙️

### Prerequisites

- Python 3.9+
- Required libraries: pandas, numpy, scikit-learn, tensorflow, torch, matplotlib, opencv-python

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/extract-info-from-documents-digitalization.git
   cd extract-info-from-documents-digitalization
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. (Optional) Set up a conda environment:
   ```bash
   conda env create -f environment.yml
   conda activate extract-info-env
   ```

---

## Results 📊

- **Structured Digital Records:** Experiment test papers are fully digitized and categorized.
- **Improved Retrieval:** Searchable text and well-defined categories enable quick information access.
- **Reduced Manual Workload:** Automation replaces manual data entry and classification tasks.

---

## Contributors 👥

- [Michael Yerdaw]: MDT 
- [Other Contributors]: 

Open for Collaboration! Feel free to contribute to this repository.

---

## License 📜

This project is licensed under the MTY License. See the LICENSE file for details.

---

## Contact 📬

- **Email:** mty_12@outlook.com  
- **LinkedIn:** 
