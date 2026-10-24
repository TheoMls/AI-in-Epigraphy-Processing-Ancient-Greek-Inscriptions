# Ancient Greek Papyri & Epigraphic Inscriptions Analysis

This repository contains tools, data pipelines, and machine learning models for processing, cleaning, and analyzing Ancient Greek papyri and epigraphic inscriptions (ICDAR Competition & NLP Datasets). This project is an assigment for Knowledge Extraction class.

---

## Project Overview

Ancient Greek textual artifacts (papyri, squeezes, epigraphic inscriptions) often suffer from physical damage, missing characters, and noisy digital transcriptions. 

This project provides an end-to-end pipeline to:
* **Preprocess & Clean** raw Jupyter Notebook outputs and JSON structures (removing personal metadata and system logs).
* **Integrate Classical NLP Tools** (e.g., `cltk`, Hugging Face Papyrus datasets) for text normalization and named entity recognition (NER).
* **Prepare Datasets** for Computer Vision (OCR) and Natural Language Processing tasks targeting ancient texts.

---

## Requirements & Setup

### Prerequisites
* Python 3.9+
* Git & Git LFS (if tracking large dataset files)
