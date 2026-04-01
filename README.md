# 🔍 AI-Based Digital Evidence Extraction System

## 📌 Overview

This project presents a **proof-of-concept AI-based digital evidence extraction system** designed for cybercrime and digital forensic investigations.

The system demonstrates how investigators can analyze **digital text and image data (tweets, chats, memes, etc.)** to identify harmful, abusive, or suspicious content.

⚠️ **Important Note:**
Currently, the system operates on benchmark datasets (e.g., cyberbullying tweets) to validate the AI pipeline. In a real-world forensic scenario, the system is intended to analyze **data from a specific suspect’s profile (e.g., exported chats, posts, or messages)**.

---

## 🚀 Features

* 📄 **Text Processing Pipeline**
  Extracts, cleans, and processes textual data from various sources.

* 🖼️ **OCR-Based Image Analysis**
  Uses OCR techniques to extract text from images and scanned documents.

* 🧠 **AI-Based Classification**
  Applies machine learning/NLP techniques to classify and analyze extracted data.

* 🔍 **Forensic Analysis Module**
  Identifies patterns, keywords, and suspicious content for investigation.

* 📊 **Integrated Workflow**
  Combines multiple pipelines into a single end-to-end system.

---

## 🏗️ Project Structure

```
├── notebook1_text_pipeline.ipynb     # Text extraction and preprocessing
├── notebook2_ocr_pipeline.ipynb      # OCR-based image processing
├── notebook3_forensic_app.ipynb      # Main forensic analysis application
├── data/                             # Input datasets (if any)
├── outputs/                          # Generated results
└── README.md                         # Project documentation
```

---

## ⚙️ Technologies Used

* Python
* Natural Language Processing (NLP)
* OCR (Tesseract / EasyOCR)
* Machine Learning
* Jupyter Notebook

---

## 🧪 How It Works

### Current Prototype Workflow

1. **Input Dataset**
   Pre-collected datasets (e.g., tweets, memes) are used for testing.

2. **Text/Image Extraction**

   * Direct text processing OR
   * OCR extraction from images

3. **Preprocessing**
   Cleaning, tokenization, and normalization.

4. **Analysis & Classification**
   AI models detect toxicity, sentiment, and risk levels.

5. **Output**
   Generates overall statistics and risk distribution.

---

### Intended Real-World Workflow

1. Investigator uploads **suspect-specific data** (chat exports, tweets, etc.)
2. System processes only that individual's data
3. AI models analyze harmful content and extract entities
4. Output is a **forensic report linked to that suspect**, including:

   * Number of harmful messages
   * Severity classification
   * Extracted names/entities

---

## 📥 Installation

```bash
git clone https://github.com/smruthisreshta/digital-evidence-extraction.git
cd digital-evidence-extraction
pip install -r requirements.txt
```

---

## ▶️ Usage

1. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

2. Run notebooks in order:

   * `notebook1_text_pipeline.ipynb`
   * `notebook2_ocr_pipeline.ipynb`
   * `notebook3_forensic_app.ipynb`

---

## 📌 Applications

* Cybercrime Investigation
* Digital Forensics
* Social Media Monitoring
* Online Safety Analysis
* Law Enforcement Support

---

## ⚠️ Limitations (Current Version)

* No suspect-specific data input (works on bulk datasets)
* No direct linkage between suspect and victim
* Uses pre-collected datasets instead of real case data
* No integration with platforms like WhatsApp or Instagram

---

## 🔮 Future Enhancements

* Add **case management module** (suspect-based analysis)
* Support for **chat export formats** (WhatsApp, Instagram, etc.)
* Real-time social media monitoring
* Cloud deployment (AWS / Azure)
* Integration of advanced NLP models (e.g., BERT)
* Victim–suspect relationship detection using NER
* Interactive dashboards for visualization

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

---

## 📜 License

This project is for academic and research purposes.

---

## 👩‍💻 Author

**Smruthi**

---

⭐ If you like this project, consider giving it a star on GitHub!
