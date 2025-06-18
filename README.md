# NER-system-using-CRF-

# HinglishNER-CRF

A lightweight Named Entity Recognition (NER) system built for code-mixed Hinglish text using Conditional Random Fields (CRF). This project demonstrates how to curate a small dataset, extract linguistic features, train a sequence labeling model, and evaluate its performance.

---

##  Features

- Built for **Hinglish** (Hindi in Roman script)
- Supports entity types:
  - `PER` (Person)
  - `LOC` (Location)
  - `ORG` (Organization)
- CRF-based sequence model using `sklearn-crfsuite`
- Token-level tagging in standard IOB format
